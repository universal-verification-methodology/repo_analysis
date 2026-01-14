# APB UART UVM Environment

## Overview

The `apb-uart-uvm-env` is a UVM-based testbench designed for verifying the APB UART interface. It includes integrated clock and reset handling, and supports comprehensive testing of UART communication functionalities.

## Features

- **UVM-based Architecture**: Fully compliant with UVM 1.0 standards.
- **Virtual Interfaces**: Utilizes virtual interfaces for signal handling.
- **Comprehensive Agents**: Includes dedicated agents for APB, clock/reset, and UART interfaces.
- **Modular Design**: Supports modular testing with base and specific sequences.
- **Multi-tool Support**: Compatible with VCS and ModelSim simulation tools.

## Usage

To use this testbench:

1. Ensure UVM 1.0 and SystemVerilog 2012 are supported in your environment.
2. Compile the testbench using the provided build commands:
   - `vcs -f filelist.f`
   - `vsim -c testbench`
3. Run the base test:
   - `apbuart_base_test`

## Implementation Details

### Components

#### Interfaces
- **clk_interface**: Virtual interface for clock and reset signals.
- **uart_interface**: Virtual interface for UART communication signals.

#### Agents
- **apb_agent**: Agent for APB interface communication.
  - Components: `apb_driver`, `apb_monitor`, `apb_sequencer`
- **clk_rst_agent**: Agent for clock and reset signal handling.
  - Components: `clk_rst_driver`, `clk_rst_monitor`, `clk_rst_sequencer`
- **uart_agent**: Agent for UART communication.
  - Components: `uart_driver`, `uart_monitor`, `uart_sequencer`

#### Drivers
- **apb_driver**: Driver for APB interface transactions.
- **clk_rst_driver**: Driver for clock and reset signal transactions.
  - Task: `run_sqr_api` - Keeps the sequencer updated by monitoring reset signal transitions.
- **uart_driver**: Driver for UART communication transactions.

#### Monitors
- **apb_monitor**: Monitor for APB interface transactions.
- **clk_rst_monitor**: Monitor for clock and reset signal transactions.
- **uart_monitor**: Monitor for UART communication transactions.

#### Sequencers
- **apb_sequencer**: Sequencer for APB interface transactions.
- **clk_rst_sequencer**: Sequencer for clock and reset signal transactions.
- **uart_sequencer**: Sequencer for UART communication transactions.

#### Sequences
- **config_apbuart**: Sequence for configuring the APB UART interface.
- **transmit_single_beat**: Sequence for transmitting a single data beat.
- **rec_reg_test**: Sequence for receiving register tests.
- **vseq_base**: Base verification sequence.
- **recdrv_test_uart**: Sequence for UART receiver driver tests.
- **fe_test_uart**: Sequence for UART frame error tests.
- **pe_test_uart**: Sequence for UART parity error tests.
- **err_free_test_uart**: Sequence for UART error-free tests.

#### Environment
- **apbuart_env**: Environment containing all agents and components for APB UART testing.
  - Agents: `apb_agent`, `clk_rst_agent`, `uart_agent`

#### Tests
- **apbuart_base_test**: Base test for APB UART interface verification.
  - Environment: `apbuart_env`

## Verification Techniques

This testbench employs the following verification techniques:

- **UVM Agent-based Verification**: Each interface is handled by dedicated agents.
- **Sequence-based Testing**: Sequences are used to define test scenarios.
- **Virtual Interface Usage**: Ensures signal handling is abstracted and flexible.
- **Clock and Reset Handling**: Integrated clock and reset agents ensure proper signal control during testing.

## Notes

- The `clk_rst_driver` contains a task `run_sqr_api` that ensures the sequencer is updated based on reset signal transitions.
- All agents are part of the `apbuart_env` environment.
- The testbench uses virtual interfaces for signal handling.