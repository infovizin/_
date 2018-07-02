![](synopsys_color.gif)

VC Verification IP for Ethernet
===============================

UVM Quickstart
==============

VIP Installation Tips
---------------------

------------------------------------------------------------------------

**[Basic Example](index_basic.md)**: [[Architecture](architecture.md) \|
]{.style1}[Interfaces](interfaces.md) \| [Instantiate
VIP](instantiate.md) \| [Configure VIP](configure.md) \|
[Sequences](sequences.md) \| [Objections](objections.md) \|
[Tests](tests.md) \| [[Start Simulation](start_simulation.md)]{.style1}[
\| [End Simulation](end_simulation.md) \| [Debug](debug.md) \|
[Verification Planner](verification_planner.md) \| [VIP Installation
Tips](vip_installation_tips.md) \| [Installation
Examples](installation_eg.md) \| [Advanced
Topics](advanced.md)]{.style1}

[**Intermediate
Example:**](../../../tb_ethernet_svt_uvm_intermediate_sys/doc/tb_ethernet_svt_uvm_intermediate_sys/index_intermediate.md)
Architecture \| Interfaces \| Instantiate VIP \| Configure VIP \|
Sequences \| Exceptions \| Functional Coverage \| Callbacks \|
Objections \| Scoreboard \| Tests \| Start Simulation \| End Simulation
\| Debug \| Verfication Planner [\| VIP Installation Tips \|]{.style1}
Installation Examples \| Advanced Topics

[[**Advanced Example**:]{.style3}]{.style2} Not Available

------------------------------------------------------------------------

This section describes compile-time and runtime options.

Compile-Time and Runtime Options
--------------------------------

[Every Synopsys example has ASCII files containing compile-time and
runtime options. ]{style="font-family:Arial, Helvetica, sans-serif; "}

[ ]{style="font-family:Arial, Helvetica, sans-serif; "}

[The examples for the Ethernet VIP are at the following
location:]{style="font-family:Arial, Helvetica, sans-serif; "}

[\$DESIGNWARE\_HOME/vip/svt/ethernet\_svt/latest/examples/sverilog/\<test\_name\>]{style="font-family:Courier; font-size:10.0pt; "}

[ ]{style="font-family:Arial, Helvetica, sans-serif; "}

[For
example:]{style="font-family:Arial, Helvetica, sans-serif; "}[ ]{style="font-family:Courier; font-size:10.0pt; "}

[\$DESIGNWARE\_HOME/vip/svt/ethernet\_svt/latest/examples/sverilog/tb\_ethernet\_svt\_uvm\_basic\_sys]{style="font-family:Courier; font-size:10.0pt; "}

[ ]{style="font-family:Arial, Helvetica, sans-serif; "}

[The files contain the following
options:]{style="font-family:Arial, Helvetica, sans-serif; "}

[For compile-time
options:]{style="font-family:Arial, Helvetica, sans-serif; "}
[sim\_build\_options (also,
vcs\_build\_options)]{style="font-family:Courier; font-size:10.0pt; "}

[For runtime
options:]{style="font-family:Arial, Helvetica, sans-serif; "}
[sim\_run\_options (also,
vcs\_run\_options)]{style="font-family:Courier; font-size:10.0pt; "}

[ ]{style="font-family:Arial, Helvetica, sans-serif; "}

[These files contain both optional and required switches.
]{style="font-family:Arial, Helvetica, sans-serif; "}[For the Ethernet
VIP, the following are the contents of each file, listing\
optional and required
switches:]{style="font-family:Arial, Helvetica, sans-serif; "}

[ ]{style="font-family:Courier; font-size:10.0pt; "}

[sim\_build\_options]{style="font-family:Courier; font-size:10.0pt; "}

[ ]{style="font-family:Courier; font-size:10.0pt; "}

[Required:
+define+UVM\_PACKER\_MAX\_BYTES=1500000]{style="font-family:Courier; font-size:10.0pt; "}

[Required:
+define+UVM\_DISABLE\_AUTO\_ITEM\_RECORDING]{style="font-family:Courier; font-size:10.0pt; "}

[Required:
+define+SVT\_ETHERNET]{style="font-family:Courier; font-size:10.0pt; "}

[Required:
+define+SYNOPSYS\_SV]{style="font-family:Courier; font-size:10.0pt; "}

[Optional:
+define+SVT\_ETHERNET\_ANALYSIS\_PORT\_PKT\_HDR\_DATA\_SPLIT]{style="font-family:Courier; font-size:10.0pt; "}

[Optional:
+define+SVT\_ETHERNET\_TX\_TRANSACTION]{style="font-family:Courier; font-size:10.0pt; "}

[ ]{style="font-family:Courier; font-size:10.0pt; "}

[vcs\_build\_options(VCS-specific):]{style="font-family:Courier; font-size:10.0pt; "}

[Required:
-timescale=1ps/1fs]{style="font-family:Courier; font-size:10.0pt; "}

[ ]{style="font-family:Courier; font-size:10.0pt; "}

[sim\_run\_options]{style="font-family:Courier; font-size:10.0pt; "}

[Required:
+UVM\_TESTNAME=\$scenario]{style="font-family:Courier; font-size:10.0pt; "}

[where, ]{style="font-family:Arial, Helvetica, sans-serif; "}[scenario
]{style="line-height:115%; font-family:Courier; font-size:10.0pt; "}[is
the UVM testname you pass to a
simulator.]{style="font-family:Arial, Helvetica, sans-serif; "}

[Optional: +UVM\_VERBOSITY=UVM\_HIGH (// Debug
verbosity)]{style="font-family:Courier; font-size:10.0pt; "}

 

Related Information
-------------------

-   [Class Definition Order in
    SystemVerilog](https://solvnet.synopsys.com/retrieve/019032.md)

------------------------------------------------------------------------

[[SolvNet](https://solvnet.synopsys.com) \|
[Support](https://solvnet.synopsys.com/EnterACall) \| [Running
Examples](running_egs.md) \|
[Accellera](http://www.accellera.org/home)]{style="background-color: rgb(255, 255, 255);"}

------------------------------------------------------------------------

© 2018 Synopsys, Inc. All Rights Reserved.
