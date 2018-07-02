![][1]

VC VIP USB SystemVerilog/UVM QuickStart
=======================================

Debug
-----

------------------------------------------------------------------------

**[Basic Example]**: [Basic Example Architecture] | [Interfaces] |
[Instantiate VIP] | [Configure VIP] | [Sequences] | <span
class="style1">[Objections]</span> |<span class="style1"> [Tests] |
[Start and End Simulation] </span>| Debug | [Additional Examples] |
[Advanced Topics]

**[Intermediate Example]**

------------------------------------------------------------------------

This section describes the following debug features supported by VIP:

Protocol Analyzer
-----------------

USB VIP supports the Verdi Protocol Analyzer. The Protocol Analyzer is
an interactive graphical application which provides the
protocol-oriented analysis and debugging capabilities.

Using Native Protocol Analyzer for Debugging
--------------------------------------------

This feature enables you to invoke Protocol Analyzer from Verdi GUI. You
can synchronize the Verdi wave window, smart log and the source code
with the Protocol Analyzer transaction view. Protocol Analyzer can be
enabled in an interactive and post-processing mode. The new features
available in Native Protocol Analyzer includes layer based grouping of
the transactions, Quick filter, Call stack, horizontal zoom, and reverse
debug with the interactive support.

### Prerequisites

Protocol Analyzer uses transaction-level dump database. You can use the
following settings to dump the transaction database:

#### Compile Time Options:

-   `-lca  `
-   `-kdb // dumps the work.lib++ data for source coding view  `
-   `+define+SVT_FSDB_ENABLE // enables FSDB dumping  `
-   `-debug_access  `

For more information on how to set the FSDB dumping libraries, see
Appendix B section in Linking Novas Files with Simulators and Enabling

  [1]: synopsys_color.gif
  [Basic Example]: index_basic.html
  [Basic Example Architecture]: architecture.html
  [Interfaces]: interfaces.html
  [Instantiate VIP]: instantiate.html
  [Configure VIP]: configure.html
  [Sequences]: sequences.html
  [Objections]: objections.html
  [Tests]: tests.html
  [Start and End Simulation]: simulation.html
  [Additional Examples]: additional_egs.html
  [Advanced Topics]: advanced.html
  [Intermediate Example]: ../../../tb_usb_svt_uvm_intermediate_sys/doc/tb_usb_svt_uvm_intermediate_sys/index_intermediate.html