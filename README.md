# Universal Verification Methodology (UVM) Repository Index

## Overview

This repository serves as an index and documentation hub for repositories maintained by the [Universal Verification Methodology Community](https://github.com/universal-verification-methodology/) on GitHub. The organization hosts a diverse collection of UVM-related projects, tools, examples, and educational resources for hardware verification engineers.

## Purpose

This index provides:
- **Centralized Repository Listing**: Quick access to all UVM-related repositories
- **Detailed Documentation**: In-depth analysis and documentation for each repository (see example below)
- **Learning Resources**: Structured information to help understand and utilize each project
- **Quick Reference**: Easy navigation to find specific tools, VIPs, or examples

## Documentation Format

Each repository can have a detailed markdown documentation file (e.g., `apb-uart-uvm-env.md`) that includes:
- Overview and purpose
- Features and capabilities
- Usage instructions
- Implementation details (components, architecture, etc.)
- Verification techniques
- Notes and best practices

**Example**: See [`apb-uart-uvm-env.md`](./apb-uart-uvm-env.md) for a comprehensive documentation example.

## Repository Index

### UVM Frameworks & Libraries

| Repository | Description | Language | Status | Documentation |
|------------|-------------|----------|--------|---------------|
| [uvm-python](https://github.com/universal-verification-methodology/uvm-python) | UVM 1.2 port to Python | Python | Active | - |
| [pyuvm](https://github.com/universal-verification-methodology/pyuvm) | The UVM written in Python | Python | Active | - |
| [cocotb](https://github.com/universal-verification-methodology/cocotb) | Python-based chip (RTL) verification | Python | Active | - |

### Verification IP (VIP) & Testbenches

| Repository | Description | Language | Status | Documentation |
|------------|-------------|----------|--------|---------------|
| [apb-uart-uvm-env](https://github.com/universal-verification-methodology/apb-uart-uvm-env) | UVM environment for APB based UART (RX-FreeRunning) | SystemVerilog | Active | [📄](./apb-uart-uvm-env.md) |

### Register Model & Code Generation Tools

| Repository | Description | Language | Status | Documentation |
|------------|-------------|----------|--------|---------------|
| [rggen](https://github.com/universal-verification-methodology/rggen) | Code generation tool for control and status registers | Ruby | Active | - |
| [PeakRDL](https://github.com/universal-verification-methodology/PeakRDL) | Control and status register code generator toolchain | Python | Active | - |
| [PeakRDL-uvm](https://github.com/universal-verification-methodology/PeakRDL-uvm) | Generate UVM register model from compiled SystemRDL input | Python | Active | - |

### Hardware Verification Projects

| Repository | Description | Language | Status | Documentation |
|------------|-------------|----------|--------|---------------|
| [core-v-verif](https://github.com/universal-verification-methodology/core-v-verif) | Functional verification project for the CORE-V family of RISC-V cores | Assembly, SystemVerilog | Active | - |

### Hardware Tools & Utilities

| Repository | Description | Language | Status | Documentation |
|------------|-------------|----------|--------|---------------|
| [hwt](https://github.com/universal-verification-methodology/hwt) | VHDL/Verilog/SystemC code generator, simulator API written in python/c++ | Python, C++ | Active | - |

### Organization & Infrastructure

| Repository | Description | Language | Status | Documentation |
|------------|-------------|----------|--------|---------------|
| [repo_analysis](https://github.com/universal-verification-methodology/repo_analysis) | Repository analysis and indexing | - | Active | - |
| [.github](https://github.com/universal-verification-methodology/.github) | GitHub organization configuration and templates | Shell | Active | - |

## Repository Categories

### 🎓 Educational & Learning Resources
Repositories focused on teaching UVM concepts and providing examples:
- Example testbenches and verification environments
- Tutorial projects
- Best practice demonstrations

### 🛠️ Tools & Utilities
Development tools and utilities for UVM workflows:
- Code generators
- Register model generators
- Simulator integrations
- Workflow automation

### 📦 Verification IP (VIP)
Ready-to-use verification IP for common protocols:
- AXI, AHB, APB protocol VIPs
- UART, SPI, I2C interface VIPs
- Custom protocol implementations

### 🏗️ Frameworks & Libraries
Core frameworks and libraries for UVM development:
- UVM implementations in various languages
- Base classes and utilities
- Verification methodologies

### 🔬 Research & Advanced Projects
Advanced verification projects and research implementations:
- RISC-V core verification
- Complex system verification
- Novel verification techniques

## Contributing

To add documentation for a repository:

1. Create a markdown file following the format of [`apb-uart-uvm-env.md`](./apb-uart-uvm-env.md)
2. Include comprehensive details about:
   - Overview and purpose
   - Features and capabilities
   - Usage instructions
   - Architecture and components
   - Verification techniques
3. Update this README.md to include the repository in the appropriate category
4. Add a link to the documentation file in the "Documentation" column

## Quick Links

- **Organization**: [universal-verification-methodology](https://github.com/universal-verification-methodology/)
- **Example Documentation**: [apb-uart-uvm-env.md](./apb-uart-uvm-env.md)
- **UVM Standard**: [Accellera UVM](https://www.accellera.org/downloads/standards/uvm)
- **SystemVerilog Standard**: [IEEE 1800](https://ieeexplore.ieee.org/document/8299595)

## Statistics

- **Total Repositories**: 73+ (as of latest update)
- **Primary Languages**: SystemVerilog, Python, Verilog, VHDL, Perl
- **Documented Repositories**: 1 (apb-uart-uvm-env)

## Notes

- This index is actively maintained and updated as new repositories are added to the organization
- Documentation files follow a consistent format for easy navigation and understanding
- For questions or contributions, please open an issue or submit a pull request
- Repository status (Active/Archived) is based on recent commit activity

---

**Last Updated**: January 2026

**Maintained by**: Universal Verification Methodology Community
