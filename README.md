# EDA-Collection
This is a collection of electronic design automation surveys, courses, and open source tools.

## Table of contents
 - [Books and Surveys]
 - [Courses and Tutorials]
 - [Workshops on Open Source EDA]
 - [Open Source Tools (code available)]
 - [Open Access Tools (binary only)]

## Books and Surveys
### Overview
 - ICCAD 2015 Session 3D [From EDA to DA: Can We Evolve Beyond Our E-Roots?](https://www.mpassociates.com/events/proceedings.aspx?id=196--3-D)
 - DAC-2015 [DA Perspective Challenge](https://vlsicad.ucsd.edu/DAPerspectiveChallenge/competing-proposals.html)
 - CCC Visioning Activity 2014 [Extreme Scale Design Automation](https://cra.org/ccc/visioning/visioning-activities/2014-activities/extreme-scale-design-automation/)
 - 2018 [Opportunities for Machine Learning in IC Physical Design](https://vlsicad.ucsd.edu/NEWS18/2018_CASS_ML_Kahng-v5-ACTUAL.pdf)
### Synthesis
 - 2003 [Synthesis and Optimization of Digital Circuits](https://si2.epfl.ch/~demichel/publications/mcgraw/)
 - 2018 [Logic Synthesis for Established and Emerging Computing](https://ieeexplore.ieee.org/abstract/document/8478240)
### Placement
 - 2015 [Progress and Challenges in VLSI Placement Research](http://doi.org/10.1109/jproc.2015.2478963)
### Routing

## Courses and Tutorials
 - Rob A. Rutenbar, [VLSI CAD Part I: Logic](https://www.coursera.org/learn/vlsi-cad-logic) and [VLSI CAD Part II: Layout](https://www.coursera.org/learn/vlsi-cad-layout)
 - Sung Kyu Lim, [ECE6133: Physical Design Automation of VLSI Systems](http://limsk.ece.gatech.edu/course/ece6133/)
 - David Z. Pan, [EE 382V: VLSI Physical Design Automation](http://users.ece.utexas.edu/~dpan/EE382V_PDA/)
 - Sanjit A. Seshia, [EECS 219C: Formal Methods: Specification, Verification, and Synthesis](https://people.eecs.berkeley.edu/~sseshia/219c/)
 - Chung-Kuan Cheng, [CSE245: Computer Aided Circuit Simulation and Verification](https://cseweb.ucsd.edu/classes/wi15/cse245-a/)
 - Gogul Ilango's notes [ASIC Design](https://gogul09.github.io/asic-design)

## Workshops on Open Source EDA
- DAC Birds of a Feather: Open Source Academic EDA Software
  - [DAC 2019 BOF](https://github.com/The-OpenROAD-Project/Birds-of-a-Feather-Open-Source-Academic-EDA-Software/wiki/DAC-2019-Birds-of-a-Feather:-Open-Source-Academic-EDA-Software), June 5, 2019; Las Vegas, NV, USA.
- OSDA: Workshop on Open Source Design Automation
  - [OSDA 2019](https://osda.gitlab.io/), co-located with DATE, March 29, 2019; Florence, Italy.
- WOSET: Workshop on Open-Source EDA Technology
  - [WOSET 2018](https://woset-workshop.github.io/), co-located with ICCAD, Nov 8, 2018; San Diego, CA, USA.
- [ORConf: The open source digital design conferece](https://orconf.org/)
  - ORConfs: [2018](https://orconf.org/2018/) | [2017](https://orconf.org/2017/) | [2016](https://orconf.org/2016/) | [2015](https://orconf.org/2015/) | [2014](https://orconf.org/2014/) | [2013](https://orconf.org/2013/) | [2012](https://orconf.org/2012/)

## Open Source Tools (code available)
### ASIC Flow
 - [qflow](http://opencircuitdesign.com/qflow/) (Dr. R. Timothy Edwards)
   - *A Digital Flow using Open Source EDA Tools.*
 - [VSDFLOW](https://github.com/kunalg123/vsdflow) (VLSI System Design)
   - *An automated RTL-to-GDS flow for programmers, hobbyists, and small-scale entrepreneurs.*
 - [OpenRoad](https://theopenroadproject.org/) (UCSD)
   - *Aim to develop open-source tools that achieve autonomous, 24-hour layout implementation.*
 - [Ophidian](https://github.com/eclufsc/ophidian) (UFSC)
   - *An open-source library for physical design research and teaching.*
 - [Rsyn](https://github.com/RsynTeam/rsyn-x) (FURG)
   - *An Extensible Physical Synthesis Framework.*
 - [gEDA](http://www.geda-project.org/)
   - *Working on a full GPL'd suite and toolkit of Electronic Design Automation tools.*

### FPGA Flow
 - [VTR](https://github.com/verilog-to-routing/vtr-verilog-to-routing) (Toronto)
   - *An **CAD flow** tool for FPGA including ODIN-II, ABC, VPR place, and VPR route.*
 - [RapidWright](https://github.com/Xilinx/RapidWright.git) (Xilinx)
   - *Provide Vivado Interface for users to build customized FPGA implementations.*
   - Similar projects: [Torc](https://github.com/torc-isi/torc), [RapidSmith](http://rapidsmith.sourceforge.net/), and [RapidSmith2](https://github.com/byuccl/RapidSmith2)
 - [IceStorm](http://www.clifford.at/icestorm/) (Clifford Wolf)
   - *Aims at reverse engineering and documenting the bitstream format of Lattice iCE40 FPGAs and providing simple tools for analyzing and creating bitstream files.*
   - A working fully open source flow with *Yosys* and *Arachne-pnr*.
 - [FPGA CAD Framework](https://github.com/EliasVansteenkiste/FPGA-CAD-Framework) (Ghent Univ.)
   - *A Java framework focused on rapid prototyping of new CAD algorithms for FPGA compilation.*
 - [Rebit](https://code.google.com/archive/p/rebit/)
   - *A low level configuration analysis and for the debugging and validation of the bitstream files of architectures that exploit dynamic partial reconfiguration on Xilinx FPGAs.*
 - [Sdaccel-chisel-integration](https://github.com/necst/sdaccel_chisel_integration)
   - *A wrapper in Chisel for using RTL kernels into SDAccel 2017.1.*
 - [hCODE](https://github.com/hCODE-FPGA/hCODE/tree/master/lib) (Kumamoto Univ.)
   - *A tool to simplify the creation, sharing, and software integration of FPGA hardware accelerators.*
 - [Automata to Routing](https://github.com/jackwadden/Automata-to-Routing) (U.Va.)
   - *An open-source toolchain to design and evaluate island style spatial automata processing architectures.*
 - [DATuner](https://github.com/cornell-zhang/datuner) (Cornell, PKU)
   - *A parallel bandit-based approach for autotuning FPGA compilation.*

### High-level Synthesis
 - [LegUp](http://legup.eecg.utoronto.ca/) (Toronto)
   - *A **high-level synthesis** tool to improve C to Verilog synthesis without building an infrastructure from scratch.*
 - [GAUT](http://www.gaut.fr/) (Université Bretagne Sud)
   - *A high-level synthesis tool from algorithm to hardware architecture.*
 - [PandA](https://panda.dei.polimi.it/) (Politecnico di Milano)
   - *A usable framework that will enable the research of new ideas in the HW-SW Co-Design field.*
 - [FCUDA](https://github.com/adsc-hls/fcuda) (ADSC High Level Synthesis Team)
   - *A source-to-source transformation framework that takes CUDA kernels with FCUDA annotation pragmas as input and produces a synthesizable C code.*

### DSL and IR
 - [HeteroCL](https://github.com/cornell-zhang/heterocl) (Cornell, UCLA)
   - *A Multi-Paradigm Programming Infrastructure for Software-Defined Reconfigurable Computing.*
 - [Chisel](https://chisel.eecs.berkeley.edu/) (Berkeley)
   - *A hardware construction language that supports advanced hardware design using highly parameterized generators and layered domain-specific hardware languages.*
 - [FIRRTL](https://github.com/freechipsproject/firrtl) (Berkeley)
   - *An intermediate representation (IR) for digital circuits designed as a platform for writing circuit-level transformations.*
 - [BAG: Berkeley Analog Generator](https://github.com/ucb-art/BAG_framework) (Berkeley)
   - *A Python-based circuit design platform that aims to automate analog circuit design, but at the same time give the user full visibility and control over every step in the design flow.*

### Logic Synthesis
 - [ABC](https://github.com/berkeley-abc/abc) (Berkeley)
   - *A sequential logic synthesis and formal verification tool.*
 - [LLDHL](https://github.com/errordeveloper/llhdl)
   - *A logic synthesis and manipulation infrastructure for FPGAs.*
 - [Yosys](https://github.com/YosysHQ/yosys) (Clifford Wolf)
   - *A framework for Verilog RTL synthesis,* used by qflow and OpenROAD

### Placement
 - [DREAMPlace](https://github.com/limbo018/DREAMPlace) (UT Austin)
   - *A GPU-accelerated analytical placement tool.*
 - OpenROAD [RePlAce](https://github.com/abk-openroad/RePlAce) (UCSD)
   - *A global placement tool with advancing solution quality and routability validation.*
 - [RippleFPGA](https://github.com/cuhk-eda/ripple-fpga) (CUHK)
   - *A simultaneous pack-and-place algorithm for FPGA.*
 - [arachne-pnr](https://github.com/YosysHQ/arachne-pnr)
   - *A place and route tool for FPGAs.*
 - [nextpnr](https://github.com/YosysHQ/nextpnr)
   - *A vendor neutral, timing driven, FOSS FPGA place and route tool.*
 - qflow [Graywolf](https://github.com/rubund/graywolf)
   - *A placement tool in VLSI design and used together with qflow.*

### Routing
 - qflow [Qrouter](http://opencircuitdesign.com/qrouter/)
   - *A detailed router based on the standard Lee maze router algorithm.*
 - [Dr. CU](https://github.com/cuhk-eda/dr-cu) (CUHK)
   - *VLSI detailed routing tool.*
 - [FGR](http://vlsicad.eecs.umich.edu/BK/FGR/) (UMich)
   - *A global router based on Lagrange Multipliers and won the 1st place in ISPD 2007 contest.*
 - [BoxRouter](https://www.cerc.utexas.edu/utda/download/BoxRouter.htm) (UT Austin)
   - *A global router for ultimate routability and won the 2nd place in ISPD 2007 contest.*
 - [NTHU-Route](http://www.cs.nthu.edu.tw/~tcwang/nthuroute/) (NTHU)
   - *A fast and stable global router and won the 1st place in ISPD 2008 contest.*
 - [FastRoute](http://home.engineering.iastate.edu/~cnchu/FastRoute.html) (Iowa State)
   - *A global routing tool for VLSI back-end design.*
 - [FLUTE](http://home.eng.iastate.edu/~cnchu/flute.html) (Iowa State)
   - *A very fast and accurate technique for rectilinear Steiner minimal tree (RSMT) construction.*
 - [SALT](https://github.com/chengengjie/salt) (CUHK)
   - *A tool for generating VLSI routing topology.*

### Logic Simulation
 - [Verilator](https://www.veripool.org/wiki/verilator)
   - *A fast free Verilog/SystemVerilog simulator.*
 - [GHDL](https://github.com/ghdl/ghdl)
   - *An open-source simulator for the VHDL language.*
 - [FreeHDL](http://freehdl.seul.org/)
   - *A free, open source, GPL'ed VHDL simulator for Linux.*
 - [TkGate](https://github.com/bnoordhuis/tkgate)
   - *A digital circuit editor and simulator with a Tcl/Tk-based interface.*

### Timing Analysis
 - [OpenTimer](https://github.com/OpenTimer/OpenTimer) (UIUC)
   - *A High-Performance Timing Analysis Tool for VLSI Systems.*
 - OpenROAD [OpenSTA](https://github.com/abk-openroad/OpenSTA)
   - *A gate level static timing verifier.*

### Circuit Analysis
 - [ngspice](http://ngspice.sourceforge.net/)
   - *Open source spice simulator.*
 - [SPICE](http://bwrcs.eecs.berkeley.edu/Classes/IcBook/SPICE/) (Berkeley)
   - *A general-purpose circuit simulation program for nonlinear dc, nonlinear transient, and linear ac analyses.*
 - [mixedsim](https://github.com/Isotel/mixedsim) (Isotel)
   - *Mixed signal simulation with Verilog.*
 - [Gnucap: GNU Circuit Analysis Package](http://gnucap.org/dokuwiki/doku.php?id=gnucap:start)
   - *A modern "post-spice" analog and mixed signal circuit simulator.*
 - [Qucs: Quite Universal Circuit Simulator](https://github.com/Qucs/qucs/)
   - *Setup a circuit with a graphical user interface (GUI) and simulate the large-signal, small-signal and noise behaviour of the circuit.*
 - [Xyce](https://xyce.sandia.gov/) (Sandia NL)
   - *An open source, SPICE-compatible, high-performance analog circuit simulator, capable of solving extremely large circuit problems by supporting large-scale parallel computing platforms.*

### Physical Analysis
 - [FreeCAD](https://www.freecadweb.org/)
   - *An open-source parametric 3D modeler made primarily to design real-life objects of any size.*
 - [Fast Field Solvers](https://www.fastfieldsolvers.com/) (FastFieldSolvers)
   - *The "SPICE" of the ElectroMagnetic world.*
   - E.M. Workbench, FasterCap, FastCap2, FastHenry2, FastModel

## Verification
 - [Netgen](http://opencircuitdesign.com/netgen/)
   - *A circuit netlist comparison (LVS) and netlist conversion tool.*
 - [SymbiYosys](https://github.com/YosysHQ/SymbiYosys) (Clifford Wolf)
   - *Front-end for Yosys-based formal verification flows.*

### Layout
 - [Magic](http://opencircuitdesign.com/magic/)
   - *A VLSI layout editor, extraction, and DRC tool.*
 - [KLayout](https://www.klayout.de/build.html)
   - *A high performance layout viewer and editor.*
 - [OpenMPL](https://github.com/limbo018/OpenMPL)
   - *An open source layout decomposition tool.*

### PDK and IP
 - [FreePDK](https://www.eda.ncsu.edu/wiki/FreePDK) (NC State)
   - *An open-source, Open-Access-based PDK for the 45nm technology node and the Predictive Technology Model.*
 - POSH [OpenFPGA](https://github.com/LNIS-Projects/OpenFPGA) (UofU)
   - *A **FPGA IP generator** using XML-based architecture description including three parts: FPGA-Verilog, FPGA-SPICE, FPGA-Bitstream.*
 - [OpenRAM](https://github.com/mguthaus/OpenRAM) (UCSC)
   - *An open-source memory compiler for VLSI circuits.*
 - [LibreCores](https://www.librecores.org/)
   - *A digital hardware design community for creating and distributing IP cores in the open source spirit.*
 - [OpenCores](https://opencores.org/)
   - *The reference community for Free and Open Source gateware IP cores.*

### Parsers
 - HDL (Verilog, VHDL, etc.)
   - [Icarus Verilog](https://github.com/steveicarus/iverilog), a Verilog simulation and synthesis tool compiling source code written in Verilog (IEEE-1364) into some target format
   - [verilog-parser](https://github.com/ben-marshall/verilog-parser), a parser for the IEEE 1364-2001 verilog standard
   - [pyverilog](https://pypi.org/project/pyverilog), a hardware design processing toolkit for Verilog HDL including verilog parser, dataflow analyzer, control-flow analyzer and code generator
   - [hdlparse](https://kevinpt.github.io/hdlparse/), a simple package implementing a rudimentary parser for VHDL and Verilog
 - LEF/DEF
   - Si2 [LEF/DEF Toolkit](https://projects.si2.org/openeda.si2.org/projects/lefdef/)
   - RazKarapetyan's [LEF/DEF parser](https://github.com/RazKarapetyan/LEF-DEF-parser)
   - Tri Minh Cao's [LEF parser](https://github.com/trimcao/lef-parser)
 - Liberty
   - Mirror of Synopsys's [Liberty parser library](https://github.com/eclufsc/libertyParser)
 - SDC
   - Synopsys TAP-in [SDC parser](https://www.synopsys.com/community/interoperability-programs/tap-in.html)
   - dalance's [SDC parser](https://github.com/dalance/sdc-parser)

## Open Access Tools (binary only)
### ASIC Flow
 - [DATC Robust Design Flow](https://github.com/jinwookjungs/datc_robust_design_flow) (IEEE CEDA)
 - [VLSI CAD Bookshelf 2](http://vlsicad.eecs.umich.edu/BK/)

### FPGA Flow

### High-level Synthesis
 - [FuseSoC](https://github.com/olofk/fusesoc/blob/master/doc/fusesoc.adoc)
   - *A package manager and a set of build tools for HDL code.*

### Placement
 - [ePlace](http://vlsi-cuda.ucsd.edu/~ljw/ePlace/index.html) (UCSD)
   - *An electrostatics based placer using Nesterov's method.*
 - [NTUplace](http://eda.ee.ntu.edu.tw/w04/download/ntuplace.php) (NTU)
   - *A ratio partitioning based placer for large-scale mixed-size designs.*
 - [FastPlace](http://vlsicad.eecs.umich.edu/BK/Slots/cache/www.public.iastate.edu/~nataraj/FastPlace.html) (Iowa State)
   - *An Analytical Placer for Large-scale VLSI Circuits.*
 - [mPL6](http://cadlab.cs.ucla.edu/cpmo/) (UCLA)
   - *Constrained placement by multilevel optimization.*
 - [Dragon](http://vlsicad.eecs.umich.edu/BK/Slots/cache/er.cs.ucla.edu/Dragon/) (UCLA)
   - *A fast, effective standard-cell placement tool for both variable-die and fixed-die ASIC design.*
 - [Capo](http://vlsicad.eecs.umich.edu/BK/PDtools/Capo/) (UMich)
   - *A fast and high-quality routability-driven placer for standard-cell ASICs.*

### Parsers
 - Liberty
   - [Liberty::Parser](https://metacpan.org/pod/Liberty::Parser), a Perl wrapper for Synopsys's Open Liberty Project

