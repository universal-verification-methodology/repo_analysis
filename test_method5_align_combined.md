# Test Method 5: Align Attribute + Combined Approaches

This method tests the `align` attribute (which GFM explicitly supports) combined with other techniques.

## Verification IP (VIP) & Testbenches

### Test A: Using `align` attribute (GFM-supported)

<table>
<thead>
<tr>
<th align="left">Repository</th>
<th align="left">Description</th>
<th align="center">Language</th>
<th align="center">Stats</th>
<th align="left">Documentation</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left" valign="top"><a href="https://github.com/universal-verification-methodology/apb-uart-uvm-env">apb-uart-uvm-env</a></td>
<td align="left" valign="top">UVM environment for APB based UART (RX-FreeRunning)</td>
<td align="center" valign="top">SystemVerilog</td>
<td align="center" valign="top"><img src="https://img.shields.io/github/stars/Lampro-Mellon/apb-uart-uvm-env?style=flat-square&color=yellow&labelColor=gray" alt="GitHub stars"> <img src="https://img.shields.io/github/forks/Lampro-Mellon/apb-uart-uvm-env?style=flat-square&color=green&labelColor=gray" alt="GitHub forks"> <img src="https://img.shields.io/github/last-commit/Lampro-Mellon/apb-uart-uvm-env?style=flat-square&color=blue&labelColor=gray&label=last%20commit" alt="Last Commit"></td>
<td align="left" valign="top"><a href="./docs/apb-uart-uvm-env.md">📄</a></td>
</tr>
<tr>
<td align="left" valign="top"><a href="https://github.com/universal-verification-methodology/ethernet_10ge_mac_SV_UVM_tb">ethernet_10ge_mac_SV_UVM_tb</a></td>
<td align="left" valign="top">SystemVerilog-based UVM testbench for an Ethernet 10GE MAC core</td>
<td align="center" valign="top">Verilog</td>
<td align="center" valign="top"><img src="https://img.shields.io/github/stars/andres-mancera/ethernet_10ge_mac_SV_UVM_tb?style=flat-square&color=yellow&labelColor=gray" alt="GitHub stars"> <img src="https://img.shields.io/github/forks/andres-mancera/ethernet_10ge_mac_SV_UVM_tb?style=flat-square&color=green&labelColor=gray" alt="GitHub forks"> <img src="https://img.shields.io/github/last-commit/andres-mancera/ethernet_10ge_mac_SV_UVM_tb?style=flat-square&color=blue&labelColor=gray&label=last%20commit" alt="Last Commit"></td>
<td align="left" valign="top">-</td>
</tr>
<tr>
<td align="left" valign="top"><a href="https://github.com/universal-verification-methodology/Synchronous-FIFO-UVM-TB">Synchronous-FIFO-UVM-TB</a></td>
<td align="left" valign="top">UVM Testbench for synchronus fifo</td>
<td align="center" valign="top">SystemVerilog</td>
<td align="center" valign="top"><img src="https://img.shields.io/github/stars/Anjali-287/Synchronous-FIFO-UVM-TB?style=flat-square&color=yellow&labelColor=gray" alt="GitHub stars"> <img src="https://img.shields.io/github/forks/Anjali-287/Synchronous-FIFO-UVM-TB?style=flat-square&color=green&labelColor=gray" alt="GitHub forks"> <img src="https://img.shields.io/github/last-commit/Anjali-287/Synchronous-FIFO-UVM-TB?style=flat-square&color=blue&labelColor=gray&label=last%20commit" alt="Last Commit"></td>
<td align="left" valign="top">-</td>
</tr>
</tbody>
</table>

---

### Test B: Colgroup + Width attribute + Align

<table>
<colgroup>
<col width="120" align="left">
<col width="350" align="left">
<col width="100" align="center">
<col width="180" align="center">
<col align="left">
</colgroup>
<thead>
<tr>
<th>Repository</th>
<th>Description</th>
<th>Language</th>
<th>Stats</th>
<th>Documentation</th>
</tr>
</thead>
<tbody>
<tr>
<td valign="top"><a href="https://github.com/universal-verification-methodology/apb-uart-uvm-env">apb-uart-uvm-env</a></td>
<td valign="top">UVM environment for APB based UART (RX-FreeRunning)</td>
<td valign="top">SystemVerilog</td>
<td valign="top"><img src="https://img.shields.io/github/stars/Lampro-Mellon/apb-uart-uvm-env?style=flat-square&color=yellow&labelColor=gray" alt="GitHub stars"> <img src="https://img.shields.io/github/forks/Lampro-Mellon/apb-uart-uvm-env?style=flat-square&color=green&labelColor=gray" alt="GitHub forks"> <img src="https://img.shields.io/github/last-commit/Lampro-Mellon/apb-uart-uvm-env?style=flat-square&color=blue&labelColor=gray&label=last%20commit" alt="Last Commit"></td>
<td valign="top"><a href="./docs/apb-uart-uvm-env.md">📄</a></td>
</tr>
<tr>
<td valign="top"><a href="https://github.com/universal-verification-methodology/ethernet_10ge_mac_SV_UVM_tb">ethernet_10ge_mac_SV_UVM_tb</a></td>
<td valign="top">SystemVerilog-based UVM testbench for an Ethernet 10GE MAC core</td>
<td valign="top">Verilog</td>
<td valign="top"><img src="https://img.shields.io/github/stars/andres-mancera/ethernet_10ge_mac_SV_UVM_tb?style=flat-square&color=yellow&labelColor=gray" alt="GitHub stars"> <img src="https://img.shields.io/github/forks/andres-mancera/ethernet_10ge_mac_SV_UVM_tb?style=flat-square&color=green&labelColor=gray" alt="GitHub forks"> <img src="https://img.shields.io/github/last-commit/andres-mancera/ethernet_10ge_mac_SV_UVM_tb?style=flat-square&color=blue&labelColor=gray&label=last%20commit" alt="Last Commit"></td>
<td valign="top">-</td>
</tr>
<tr>
<td valign="top"><a href="https://github.com/universal-verification-methodology/Synchronous-FIFO-UVM-TB">Synchronous-FIFO-UVM-TB</a></td>
<td valign="top">UVM Testbench for synchronus fifo</td>
<td valign="top">SystemVerilog</td>
<td valign="top"><img src="https://img.shields.io/github/stars/Anjali-287/Synchronous-FIFO-UVM-TB?style=flat-square&color=yellow&labelColor=gray" alt="GitHub stars"> <img src="https://img.shields.io/github/forks/Anjali-287/Synchronous-FIFO-UVM-TB?style=flat-square&color=green&labelColor=gray" alt="GitHub forks"> <img src="https://img.shields.io/github/last-commit/Anjali-287/Synchronous-FIFO-UVM-TB?style=flat-square&color=blue&labelColor=gray&label=last%20commit" alt="Last Commit"></td>
<td valign="top">-</td>
</tr>
</tbody>
</table>

---

### Test C: Minimal clean HTML table (no styling)

<table>
<tr>
<th>Repository</th>
<th>Description</th>
<th>Language</th>
<th>Stats</th>
<th>Documentation</th>
</tr>
<tr>
<td><a href="https://github.com/universal-verification-methodology/apb-uart-uvm-env">apb-uart-uvm-env</a></td>
<td>UVM environment for APB based UART (RX-FreeRunning)</td>
<td>SystemVerilog</td>
<td><img src="https://img.shields.io/github/stars/Lampro-Mellon/apb-uart-uvm-env?style=flat-square&color=yellow&labelColor=gray" alt="GitHub stars"> <img src="https://img.shields.io/github/forks/Lampro-Mellon/apb-uart-uvm-env?style=flat-square&color=green&labelColor=gray" alt="GitHub forks"> <img src="https://img.shields.io/github/last-commit/Lampro-Mellon/apb-uart-uvm-env?style=flat-square&color=blue&labelColor=gray&label=last%20commit" alt="Last Commit"></td>
<td><a href="./docs/apb-uart-uvm-env.md">📄</a></td>
</tr>
<tr>
<td><a href="https://github.com/universal-verification-methodology/ethernet_10ge_mac_SV_UVM_tb">ethernet_10ge_mac_SV_UVM_tb</a></td>
<td>SystemVerilog-based UVM testbench for an Ethernet 10GE MAC core</td>
<td>Verilog</td>
<td><img src="https://img.shields.io/github/stars/andres-mancera/ethernet_10ge_mac_SV_UVM_tb?style=flat-square&color=yellow&labelColor=gray" alt="GitHub stars"> <img src="https://img.shields.io/github/forks/andres-mancera/ethernet_10ge_mac_SV_UVM_tb?style=flat-square&color=green&labelColor=gray" alt="GitHub forks"> <img src="https://img.shields.io/github/last-commit/andres-mancera/ethernet_10ge_mac_SV_UVM_tb?style=flat-square&color=blue&labelColor=gray&label=last%20commit" alt="Last Commit"></td>
<td>-</td>
</tr>
<tr>
<td><a href="https://github.com/universal-verification-methodology/Synchronous-FIFO-UVM-TB">Synchronous-FIFO-UVM-TB</a></td>
<td>UVM Testbench for synchronus fifo</td>
<td>SystemVerilog</td>
<td><img src="https://img.shields.io/github/stars/Anjali-287/Synchronous-FIFO-UVM-TB?style=flat-square&color=yellow&labelColor=gray" alt="GitHub stars"> <img src="https://img.shields.io/github/forks/Anjali-287/Synchronous-FIFO-UVM-TB?style=flat-square&color=green&labelColor=gray" alt="GitHub forks"> <img src="https://img.shields.io/github/last-commit/Anjali-287/Synchronous-FIFO-UVM-TB?style=flat-square&color=blue&labelColor=gray&label=last%20commit" alt="Last Commit"></td>
<td>-</td>
</tr>
<tr>
<td><a href="https://github.com/universal-verification-methodology/AMBA_APB_SRAM">AMBA_APB_SRAM</a></td>
<td>AMBA v.3 APB v.1 Specification Complaint Slave SRAM Core design and testbench</td>
<td>SystemVerilog</td>
<td><img src="https://img.shields.io/github/stars/courageheart/AMBA_APB_SRAM?style=flat-square&color=yellow&labelColor=gray" alt="GitHub stars"> <img src="https://img.shields.io/github/forks/courageheart/AMBA_APB_SRAM?style=flat-square&color=green&labelColor=gray" alt="GitHub forks"> <img src="https://img.shields.io/github/last-commit/courageheart/AMBA_APB_SRAM?style=flat-square&color=blue&labelColor=gray&label=last%20commit" alt="Last Commit"></td>
<td>-</td>
</tr>
<tr>
<td><a href="https://github.com/universal-verification-methodology/UVM-APB_RAL">UVM-APB_RAL</a></td>
<td>Example of the use of UVM Register Abstraction Layer in a verification of a simple APB DUT</td>
<td>SystemVerilog</td>
<td><img src="https://img.shields.io/github/stars/JoseIuri/UVM-APB_RAL?style=flat-square&color=yellow&labelColor=gray" alt="GitHub stars"> <img src="https://img.shields.io/github/forks/JoseIuri/UVM-APB_RAL?style=flat-square&color=green&labelColor=gray" alt="GitHub forks"> <img src="https://img.shields.io/github/last-commit/JoseIuri/UVM-APB_RAL?style=flat-square&color=blue&labelColor=gray&label=last%20commit" alt="Last Commit"></td>
<td>-</td>
</tr>
</table>

---

### Test D: Stacked badges (vertical layout)

<table>
<tr>
<th>Repository</th>
<th>Description</th>
<th>Language</th>
<th>Stats</th>
<th>Docs</th>
</tr>
<tr>
<td><a href="https://github.com/universal-verification-methodology/apb-uart-uvm-env">apb-uart-uvm-env</a></td>
<td>UVM environment for APB based UART (RX-FreeRunning)</td>
<td>SystemVerilog</td>
<td>
<img src="https://img.shields.io/github/stars/Lampro-Mellon/apb-uart-uvm-env?style=flat-square&color=yellow&labelColor=gray" alt="GitHub stars"><br>
<img src="https://img.shields.io/github/forks/Lampro-Mellon/apb-uart-uvm-env?style=flat-square&color=green&labelColor=gray" alt="GitHub forks"><br>
<img src="https://img.shields.io/github/last-commit/Lampro-Mellon/apb-uart-uvm-env?style=flat-square&color=blue&labelColor=gray&label=last%20commit" alt="Last Commit">
</td>
<td><a href="./docs/apb-uart-uvm-env.md">📄</a></td>
</tr>
<tr>
<td><a href="https://github.com/universal-verification-methodology/ethernet_10ge_mac_SV_UVM_tb">ethernet_10ge_mac_SV_UVM_tb</a></td>
<td>SystemVerilog-based UVM testbench for an Ethernet 10GE MAC core</td>
<td>Verilog</td>
<td>
<img src="https://img.shields.io/github/stars/andres-mancera/ethernet_10ge_mac_SV_UVM_tb?style=flat-square&color=yellow&labelColor=gray" alt="GitHub stars"><br>
<img src="https://img.shields.io/github/forks/andres-mancera/ethernet_10ge_mac_SV_UVM_tb?style=flat-square&color=green&labelColor=gray" alt="GitHub forks"><br>
<img src="https://img.shields.io/github/last-commit/andres-mancera/ethernet_10ge_mac_SV_UVM_tb?style=flat-square&color=blue&labelColor=gray&label=last%20commit" alt="Last Commit">
</td>
<td>-</td>
</tr>
<tr>
<td><a href="https://github.com/universal-verification-methodology/Synchronous-FIFO-UVM-TB">Synchronous-FIFO-UVM-TB</a></td>
<td>UVM Testbench for synchronus fifo</td>
<td>SystemVerilog</td>
<td>
<img src="https://img.shields.io/github/stars/Anjali-287/Synchronous-FIFO-UVM-TB?style=flat-square&color=yellow&labelColor=gray" alt="GitHub stars"><br>
<img src="https://img.shields.io/github/forks/Anjali-287/Synchronous-FIFO-UVM-TB?style=flat-square&color=green&labelColor=gray" alt="GitHub forks"><br>
<img src="https://img.shields.io/github/last-commit/Anjali-287/Synchronous-FIFO-UVM-TB?style=flat-square&color=blue&labelColor=gray&label=last%20commit" alt="Last Commit">
</td>
<td>-</td>
</tr>
<tr>
<td><a href="https://github.com/universal-verification-methodology/AMBA_APB_SRAM">AMBA_APB_SRAM</a></td>
<td>AMBA v.3 APB v.1 Specification Complaint Slave SRAM Core design and testbench</td>
<td>SystemVerilog</td>
<td>
<img src="https://img.shields.io/github/stars/courageheart/AMBA_APB_SRAM?style=flat-square&color=yellow&labelColor=gray" alt="GitHub stars"><br>
<img src="https://img.shields.io/github/forks/courageheart/AMBA_APB_SRAM?style=flat-square&color=green&labelColor=gray" alt="GitHub forks"><br>
<img src="https://img.shields.io/github/last-commit/courageheart/AMBA_APB_SRAM?style=flat-square&color=blue&labelColor=gray&label=last%20commit" alt="Last Commit">
</td>
<td>-</td>
</tr>
<tr>
<td><a href="https://github.com/universal-verification-methodology/UVM-APB_RAL">UVM-APB_RAL</a></td>
<td>Example of the use of UVM Register Abstraction Layer in a verification of a simple APB DUT</td>
<td>SystemVerilog</td>
<td>
<img src="https://img.shields.io/github/stars/JoseIuri/UVM-APB_RAL?style=flat-square&color=yellow&labelColor=gray" alt="GitHub stars"><br>
<img src="https://img.shields.io/github/forks/JoseIuri/UVM-APB_RAL?style=flat-square&color=green&labelColor=gray" alt="GitHub forks"><br>
<img src="https://img.shields.io/github/last-commit/JoseIuri/UVM-APB_RAL?style=flat-square&color=blue&labelColor=gray&label=last%20commit" alt="Last Commit">
</td>
<td>-</td>
</tr>
</table>
