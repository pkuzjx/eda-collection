# EDA-Surveys-and-Courses
This is a collection of traditional electronic design automation surveys, courses, open source tools and books.

## Table of contents
 - [Surveys]
 - [Courses]
 - [Open Source Tools (Part I:Code available)]
 - [Open Source Tools (Part II:Binary only)]
 - [Books]

## Surveys
### Synthesis
 - [Optimization of Digital Circuits]()
### Placement
 - [Progess and Challenges in VLSI Placement Research]()
### Routing

## Courses
 - [VLSI CAD Part I: Logic](https://zh.coursera.org/learn/vlsi-cad-logic)
 - [VLSI CAD Part II: Layout](https://zh.coursera.org/learn/vlsi-cad-layout)

## Open Source Tools (Part I:Code available)
### ASIC Flow
 - [OpenRoad](https://theopenroadproject.org/)(UCSD)
   - *Aim to develop open-source tools that achieve autonomous, 24-hour layout implementation.*
 - [Rsyn](https://github.com/RsynTeam/rsyn-x)(FURG)
   - *An Extensible Physical Synthesis Framework.*
 - [Qflow](http://opencircuitdesign.com/qflow/)()
   - *A Digital Flow using Open Source EDA Tools.*
 - [Automata to Routing](https://github.com/jackwadden/Automata-to-Routing)(University of Virginia)
   - *An open-source toolchain to design and evaluate island style spatial automata processing architectures.*

### FPGA Flow
 - [VTR](https://github.com/verilog-to-routing/vtr-verilog-to-routing)(Toronto)
   - *An **CAD flow** tool for FPGA including ODIN-II, abc, vpr-place, vpr-route.*
 - [OpenFPGA](https://github.com/LNIS-Projects/OpenFPGA)(Utah, POSH projects)
   - *A **FPGA IP generator** using XML-based architecture description including three parts: FPGA-Verilog, FPGA-SPICE, FPGA-Bitstream.*
 - [RapidWright](https://github.com/Xilinx/RapidWright.git)(Xilinx)
   - *Provide Vivado Interface for users to build customized FPGA implementations.*
 - [FPGA CAD Framework](https://github.com/EliasVansteenkiste/FPGA-CAD-Framework) ()
   - *A Java framework focused on rapid prototyping of new CAD algorithms for FPGA compilation.*
 - [Rebit](https://code.google.com/archive/p/rebit/)
   - *A low level configuration analysis and for the debugging and validation of the bitstream files of architectures that exploit dynamic partial reconfiguration on Xilinx FPGAs.*
 - [Sdaccel-chisel-integration](https://github.com/necst/sdaccel_chisel_integration)
   - *A wrapper in Chisel for using RTL kernels into SDAccel 2017.1.*
 - [hCODE](https://github.com/hCODE-FPGA/hCODE/tree/master/lib) (Kumamoto University)
   - *A tool to simplify the creation, sharing, and software integration of FPGA hardware accelerators.*
 - [IceStorm](http://www.clifford.at/icestorm/)
   - *Aims at reverse engineering and documenting the bitstream format of Lattice iCE40 FPGAs and providing simple tools for analyzing and creating bitstream files.*
 - [Torc](https://github.com/torc-isi/torc)

### High-level Synthesis
 - [LegUp](http://legup.eecg.utoronto.ca/)(Toronto)
   - *A **high-level synthesis** tool to improve C to Verilog synthesis without building an infrastructure from scratch.*
 - [GAUT](http://www.gaut.fr/) (Université Bretagne Sud)
   - *A high-level synthesis tool from algorithm to hardware architecture.*
 - [FCUDA](https://github.com/adsc-hls/fcuda) (ADSC High Level Synthesis Team)
   - *A source-to-source transformation framework that takes CUDA kernels with FCUDA annotation pragmas as input and produces a synthesizable C code.*

### DSL and IR
 - [HeteroCL](https://github.com/cornell-zhang/heterocl) (Cornell)
   - *A Multi-Paradigm Programming Infrastructure for Software-Defined Reconfigurable Computing.*
 - [FIRRTL](https://github.com/freechipsproject/firrtl) (Berkeley)
   - *An intermediate representation (IR) for digital circuits designed as a platform for writing circuit-level transformations.*


### Logic Synthesis
 - [ABC](https://github.com/berkeley-abc/abc) (Berkeley)
   - *A sequential logic synthesis and formal verification tool.*
 - [LLDHL](https://github.com/errordeveloper/llhdl)
   - *A logic synthesis and manipulation infrastructure for FPGAs.*
 - [Yosys](https://github.com/YosysHQ/yosys)
   - *A framework for Verilog RTL synthesis.*
 - [Icarus Verilog](https://github.com/steveicarus/iverilog)
   - *A Verilog simulation and synthesis tool compiling source code written in Verilog (IEEE-1364) into some target format.*

### Placement
 - [RePlAce](https://github.com/abk-openroad/RePlAce) (UCSD)
   - *A global placement tool with advancing solution quality and routability validation.*
 - [arachne-pnr](https://github.com/YosysHQ/arachne-pnr) (MIT)
   - *A place and route tool for FPGAs.*
 - [Graywolf](https://github.com/rubund/graywolf) (Yale University)
   - *A placement tool in VLSI design and used together with qflow.*
 - [DREAMPlace](https://github.com/limbo018/DREAMPlace) (UT Austin)
   - *A GPU-accelerated analytical placement tool.*

### Route
 - [Qrouter](http://opencircuitdesign.com/qrouter/)
   - *A detailed router based on the standard Lee maze router algorithm.*
 - [FGR](http://vlsicad.eecs.umich.edu/BK/FGR/) (UMich)
   - *A global router based on Lagrange Multipliers and won the 1st place in ISPD 2007 contest.*
 - [BoxRouter](https://www.cerc.utexas.edu/utda/download/BoxRouter.htm) (UTAustin)
   - *A global router for ultimate routability and won the 2nd place in ISPD 2007 contest.*
 - [NTHU-Route](http://www.cs.nthu.edu.tw/~tcwang/nthuroute/) (NTHU)
   - *A fast and stable global router and won the 1st place in ISPD 2008 contest.*
 - [FastRoute](http://home.engineering.iastate.edu/~cnchu/FastRoute.html) (Iowa State University)
   - *A global routing tool for VLSI back-end design.*
 - [Flute](http://home.eng.iastate.edu/~cnchu/flute.html) (Iowa State University)
   - *A very fast and accurate technique for rectilinear Steiner minimal tree (RSMT) construction.*

### Logic Simulation
 - [Verilator](https://www.veripool.org/wiki/verilator)
   - *A fast free Verilog/SystemVerilog simulator.*
 - [GHDL](https://github.com/ghdl/ghdl)
   - *An open-source simulator for the VHDL language.*

### Timing Analysis
 - [OpenTimer](https://github.com/OpenTimer/OpenTimer) (UIUC)
   - *A High-Performance Timing Analysis Tool for VLSI Systems.*

### Memory Compiler
 - [OpenRAM](https://github.com/mguthaus/OpenRAM) (UCSC)
   - *An open-source memory compiler for VLSI circuits.*


## Open Source Tools (Part II:Binary only)
### ASIC Flow
 - [DATC Robust Design Flow](https://github.com/jinwookjungs/datc_robust_design_flow) (IEEE CEDA)

### FPGA Flow

### High-level Synthesis
 - [FuseSoC](https://github.com/olofk/fusesoc/blob/master/doc/fusesoc.adoc)
   - *A package manager and a set of build tools for HDL code.*

### Placement
 - [FastPlace](http://vlsicad.eecs.umich.edu/BK/Slots/cache/www.public.iastate.edu/~nataraj/FastPlace.html) (Iowa State University)
   - *An Analytical Placer for Large-scale VLSI Circuits.*
 - [NTUplace](http://eda.ee.ntu.edu.tw/w04/download/ntuplace.php) (NTU)
   - *A ratio partitioning based placer for large-scale mixed-size designs.*
 - [ePlace](http://vlsi-cuda.ucsd.edu/~ljw/ePlace/index.html) (UCSD)
   - *An electrostatics based placer using Nesterov's method.*
 - [Dragon](http://vlsicad.eecs.umich.edu/BK/Slots/cache/er.cs.ucla.edu/Dragon/) (UMich)
   - *A fast, effective standard-cell placement tool for both variable-die and fixed-die ASIC design.*
 - [Capo](http://vlsicad.eecs.umich.edu/BK/PDtools/Capo/) (UMich)
   - *A fast and high-quality routability-driven placer for standard-cell ASICs.*

## Books
