# Compiler, Language and Runtime Teams

A listing of compiler, language and runtime teams for people looking for jobs in this area. My motivation for curating this is in [this blog post](https://www.mgaudet.ca/technical/2019/12/10/compiler-jobs).

### Scope

- Teams that work on language implementations, compilers for languages, language runtimes, static analysis, etc. This includes things like:
  - Database query compilers
  - HDL & Synthesis Compilers
    
  I want to err on the side of openness! The field is broad, and I don't want to be too close-minded here.
- I generally want evidence that a company has hired at some point in the past or will in the future (which excludes some boutique firms & early stage startups).


### Contributing

[**Please contribute:**](https://github.com/mgaudet/CompilerJobs/pulls) Pass on projects, teams, companies I've missed. 

**Feel free to spruce up the description of the work for teams you know about! Many of these are simply stubs**

I generally link to a company's Careers/Job's page rather than linking to specific jobs -- these links have a longer lifespan than just the straight up link to a job. 

### Annotations: 

* 📤: Remote Work Supported

    At the time the icon was added, the company offered remote work. 

* 🧑‍🎓: Internships offered

    These companies are known to have offered internships or co-ops in compiler, languages and runtimes. 

* 🗺 : Location

    Derived from job postings or other knowledge, this is where the team works. Definitely not comprehensive! **Please, help me update this too!** 

# Companies (<i id="count"></i>)

## [Access Softek Toolchains](https://www.softek-toolchains.com/careers) 📤

* LLVM Toolchain Development 

## [AdaCore](https://www.adacore.com/company/careers) 📤 🧑‍🎓

🗺 _New York (US), Paris & Grenoble & Toulouse & Vannes (France), Bristol (UK), Tallinn (Estonia)_

* Ada runtimes and front-ends ([GNAT](https://github.com/gcc-mirror/gcc/tree/master/gcc/ada), [libadalang](https://github.com/AdaCore/libadalang)).
* Back-ends to said front-ends ([GCC](https://gcc.gnu.org/), [LLVM](https://github.com/AdaCore/gnat-llvm), [Infer](https://github.com/facebook/infer), [Why3](https://github.com/AdaCore/spark2014)...).
* Various custom languages (e.g. [langkit](https://github.com/AdaCore/langkit), [gprbuild](https://github.com/AdaCore/gprbuild), [recordflux](https://github.com/Componolit/RecordFlux)...).

## [Aicas](https://www.aicas.com/cms/en/careers)

🗺  _Karlsruhe, Germany_

* Real-time JVM

## [Amazon](https://www.amazon.jobs)

* [Corretto](https://aws.amazon.com/corretto/)
* [Inferentia](https://aws.amazon.com/machine-learning/inferentia/)
* [Rust](https://aws.amazon.com/blogs/opensource/how-our-aws-rust-team-will-contribute-to-rusts-future-successes/)

## [Ambarella](https://www.ambarella.com/)
🗺 _Santa Clara, CA, Taiwan_

* Computer vision AI hardware compiler

## [AMD](https://jobs.amd.com/) 📤 (most teams)

 * [AOCC](https://developer.amd.com/amd-aocc/)
 * [ROCm](https://rocmdocs.amd.com/en/latest/)
 * Two LLVM teams: work on the AMDGPU backend for graphics and compute 

## [Ampere Computing](https://amperecomputing.com/apply/)

* Work on OpenJDK

## [Anaconda](https://www.anaconda.com/careers)

* [Pyston](https://www.anaconda.com/blog/pyston-team-joins-anaconda): General-purpose Python JIT originally developed at Dropbox

## [Anyon Systems](https://anyonsys.com/)
🗺 _Toronto / Markham, Canada_

* Quantum Compiler Development
* MLIR/LLVM

## [Apple](https://www.apple.com/jobs/) 🧑‍🎓 
🗺 _Cupertino, CA, London, UK, Israel_

* Clang and LLVM
* Swift
* GPU Compiler
* JSC (JavaScript interpreter created as part of WebKit)
* Static Analysis tooling

## [Arm](https://www.arm.com/company/careers)
🗺  _Cambridge, Manchester, UK_

* GCC
* LLVM work to support Arm32 (embedded), and to support Scalable Vector Extension (SVE)
* LLVM-based downstream GPU compiler for Mali GPUs
* ML compiler

## [Ascenium](https://www.ascenium.com/careers)
🗺 _Campbell, CA_, _Stavanger and Oslo, Norway_

* LLVM and Hardware codesign.

## [Astral](https://astral.sh/) 📤

* [Ruff](https://astral.sh/ruff), a linter and autoformatter for Python code written in Rust.

## [Autodesk](https://www.autodesk.com/careers/overview) 📤
🗺 _Quebec, Ontario_

* JIT Compiler for [Bifrost for Maya](https://newpossible.autodesk.com/bifrost) (LLVM?)


## [Azul](https://www.azul.com/careers-at-azul-systems/) 📤

* Java Virtual Machine
* Falcon JIT compiler (LLVM)

## [Bodo](https://angel.co/company/bodoai) 📤

🗺 _Pittsburgh, PA_ 

* Python, LLVM 

## [Broad Institute](https://broadinstitute.wd1.myworkdayjobs.com/broad_institute)

🗺 _Cambridge, MA_

* Building the [Hail](https://hail.is/) project for genomics, including a custom language and compiler. 

## [Brookhaven National Laboratory](https://jobs.bnl.gov/)

🗺 _Upton, New York_ 

Work on the Programming Models and Compilers (PMC) group of the Computational Science Initiative. 

## [ByteDance](https://jobs.bytedance.com)

🗺 _Mountain View, California_ 

* Performance analysis and optimization

## [Canonical](https://canonical.com/careers/) 📤

* Building and improving Rust Compiler & toolchain for Ubuntu

## [Category Labs](https://www.category.xyz/) 📤
🗺 _New York City_ 

* Accelerating blockchain 

## [Celestial AI](https://www.celestial.ai/careers)
🗺 _Santa Clara, CA, Hyderabad, India, Toronto, Canada_

* Compiler Backend for the Celestial AI Machine Learning accelerator architecture

## [Cerebras](https://cerebras.net/careers/)
🗺 _Los Altos, CA, San Diego, CA or Toronto, Canada_

* LLVM and more

## [Cisco](https://www.cisco.com/c/en/us/about/careers.html) 
🗺 _Belgrade, Serbia_ 

* Work on CISCO Silicon One™ compiler

## [Cloudflare](https://www.cloudflare.com/careers/)

* Cloudflare Workers: V8 (WebAssembly, Javascript, deployed at the edge)

## [Codasip](https://codasip.com/company/careers/) 🧑‍🎓📤 (Europe/US)
🗺 _Brno/Prague, Czech Republic, Munich, Germany, and Bristol, UK_ 

* CHERI extension for LLVM (RISC-V)
* LLVM engineers, to support the RISC-V vector processing unit

## [Codeplay](https://www.codeplay.com/company/careers/)

* Clang, LLVM, LLDB

## [Cognitect](https://www.cognitect.com/careers.html)

* Clojure and ClojureScript

## [Coherent Logix](https://www.coherentlogix.com/careers/)📤
🗺 _Austin, TX_

* Building an LLVM based C compiler for Coherent Logix's multicore chip.

## [Columbia University - Data Science Institute](https://apply.interfolio.com/91828)
🗺 _New York City_

* Building languages for probabilistic programming and causal reasoning.
* Static/Dynamic analyses and code transformation.
* Julia oriented.

## [Compiler Tool Chain Consulting Services](https://compiler-toolchain-for.me/careers) 📤

* Custom LLVM-based compiler toolchains for clients

## [Crowdstrike](https://www.crowdstrike.com/careers/) 📤
🗺 _US, Canada_

* The Sensor and Language Tooling (SaLT) team works on a DSL to script Falcon's threat detection sensor

## [d-Matrix](https://www.d-matrix.ai/careers)
🗺 _Santa Clara, California _

* Deep Neural Network hardware, with associated compiler (LLVM+MLIR) 


## [DashBit](https://dashbit.co/)

* Elixir

## [DataChemist](https://www.datachemist.com/company/our-team)

* WOQL Compiler

## [DeepX](https://deepx.career.greetinghr.com/ko/career)
🗺 _Seongnam, South Korea_

* Deep Learning Compiler for NPU hardware

## [Deno](https://jobs.ashbyhq.com/Deno) 📤
* JavaScript runtime and tools written in Rust

## [Distributive](https://distributive.network) 📤
🗺  Kingston, ON (Canada)

* Distributed Computing on Web Stack - scheduling, WASM toolchains, etc.
* PythonMonkey, deep embedding of SpiderMonkey (JS engine) into Python VM

## [Dfinity](https://dfinity.org/careers/)
🗺  _San Fransisco CA, Palo Alto CA, Zurich Switzerland_

* Motoko programming language and system for blockchain smartcontracts.

## [Digital Mars](https://digitalmars.com/)

* C/C++ compilers
* D compiler

## [Dropbox](https://www.dropbox.com/jobs) 

* Python
* [MyPy](http://mypy-lang.org/about.html)

## [Dyalog](https://www.dyalog.com/careers.htm)

* Dyalog APL

## [Edgecortix](https://www.edgecortix.com/)
🗺  _Tokyo, Japan_

* Machine learning hardware compilers

## [Efficient Computer](https://www.efficient.computer/about#careers)
🗺  _San Jose, CA_ or _Pittsburgh, PA_

* Develop compilers for a energy-efficient programmable processor

## [Embecosm](https://www.embecosm.com/about/careers/)
🗺 _Southampton, UK,  Nürnberg, Germany_ 

* Open Source toolchain development, with a primary focus on GCC, LLVM and Verilator.


## [emmtrix Technologies](https://www.emmtrix.com/company/jobs) 🧑‍🎓
🗺  _Karlsruhe, Germany_

* Source-to-source compilers
* Static analysis (LLVM)
* Parallelizing transformations

## [EnCharge AI](https://www.enchargeai.com/careers)
🗺 _U.S., Canada, Germany, Norway_

* Graph compilers for AI/ML workloads.

## [Enso](https://www.ycombinator.com/companies/enso)

* Compiler for visual programming language, JIT based on Graal/Truffle.

## [Epic Games](https://www.epicgames.com/site/en-US/careers)

* DSL compiler and toolchain for game development

## [Esperanto Technologies](https://www.esperanto.ai/careers/)
🗺 _Mountain View, California, Austin, Texas Portland, Oregon, Barcelona, Spain_

*  LLVM and GLOW compiler teams for RISC-V AI acceleration. 

## [Espressif](https://www.espressif.com/en/join-us/job-search) 📤
🗺  _Brno, Czechia_

* GNU GCC, GDB, Binutils development for Xtensa and other architectures.

## [Ericsson](https://www.ericsson.com/en/careers)

* Erlang

## [F5](https://www.f5.com/company/careers) 
🗺  _San Jose, Seattle_ 

* Compilers for Security work 

## [Fabric Cryptography](https://www.fabriccryptography.com) 📤

* LLVM-based compiler for custom cryptographic hardware

## [Fastly](https://www.fastly.com/about/careers)

* [Lucet](https://www.fastly.com/blog/announcing-lucet-fastly-native-webassembly-compiler-runtime), a WebAssembly compiler and runtime for edge computation.  
* [Cranelift](https://github.com/bytecodealliance/cranelift) 
* [VCL](https://developer.fastly.com/reference/vcl/)

## [Flow Computing](https://flow-computing.com/company/) 📤 (preferably Europe)
🗺 _Oulu, Finland_

* LLVM (mostly back-end)

## [Fluence Labs](https://fluence.network/join.html) 📤

* Aquamarine, a distributed choreography language & platform

## [Flux Computing](https://www.fluxcomputing.com/careers)
🗺 _London, UK,_

* Machine learning compiler for optical TPU hardware

## [Fuel Labs](https://jobs.lever.co/fuellabs) 📤

* Building [Sway](https://github.com/FuelLabs/sway), a smart-contract programming language

## [Furiosa](https://furiosa.ai/jobs)
🗺 _Seoul, South Korea_

* AI Accelarator

## [FutureWei Technologies](https://www.futurewei.com/index.php/careers)

* Rust compiler work.

## [Galois](https://galois.com/careers/) 
🗺 _Arlington, VA_ 

* Programming language design and implementation for building trustworthy computing. 

## [GitHub](https://github.com/about/careers) 📤

* [CodeQL](https://securitylab.github.com/tools/codeql/), a query language for writing custom static analysis rules

## [Google](https://careers.google.com/) 📤
🗺 _Mountain View, CA, Seattle, WA, and London, UK_

Innumerable projects, but off the top of my head: 

* [Go](https://golang.org/)
* LLVM contributions
* [V8](https://v8.dev/)
* [Dart](https://dart.dev/)
* [MLIR](https://www.tensorflow.org/mlir)

## [GrammaTech](https://www.grammatech.com/careers) 📤 (US only)
🗺 _Ithaca, NY_

* [CodeSonar](https://www.grammatech.com/products/source-code-analysis), a static analysis tool
* [CodeSentry](https://www.grammatech.com/codesentry-sca), a binary analysis tool

## [Graphcore](https://www.graphcore.ai/jobs)
🗺 _Bristol, Cambridge, UK_

* Machine learning hardware compiler (LLVM)

## [Greenhills](https://www.ghs.com/jobs.html)

* Certified C/C++ for Embedded

## [Grit](https://about.grit.io/) 

* Compilers for [GritQL](https://docs.grit.io/language/overview)

## [Groq](https://groq.com/careers/)
🗺 _Portland, Mountain View, Toronto_ 

* Machine Learning Hardware compilers

## [Guardsquare](https://www.guardsquare.com/careers)
🗺 _Leuven, Belgium / Munich, Germany_

* ProGuard
* LLVM-based software protection and hardening
* Android application protection and hardening
* Mobile application security testing

## [Horizon Quantum Computing](https://horizonquantum.applytojob.com/) 
🗺 _Singapore_

* Quantum computing compiler

## [HPE](https://careers.hpe.com/jobs) 📤🧑‍🎓

* [Chapel](https://chapel-lang.org/)
* Cray Programming Environment, a suite of Fortran, C and C++ compilers
* LLVM contributions

## [Huawei](https://www.huawei.com/ch-en/about-huawei/careers) 

* Research and Development work in compilers and runtime systems.
* LLVM
* Rust

## [IBM](https://www.ibm.com/employment/) 🧑‍🎓
🗺 _Markham, Ontario, Canada_ 

* Eclipse [OMR](https://github.com/eclipse/omr) & [OpenJ9](https://github.com/eclipse/openj9)
* [XLC](https://www.ibm.com/us-en/marketplace/ibm-c-and-c-plus-plus-compiler-family)
* [XL Fortran](https://www.ibm.com/us-en/marketplace/xl-fortran-linux-compiler-power)
* [IBM Cobol](https://www.ibm.com/us-en/marketplace/ibm-cobol) 

As well as some other IBM internal compilers, and LLVM projects.

## [Imagination Technologies](https://www.imaginationtech.com/careers/vacancies/)
🗺 _Cambridge, Manchester, Bristol, Kings Langley, UK, Poland_

* PowerVR GPU compiler (middle-end is LLVM-based, but back-end is not)

## [Immunant](https://immunant.com/jobs/) 📤

* Builds [the C2Rust translator](https://github.com/immunant/c2rust)

## [Inria](https://www.inria.fr/en/)
🗺 _Multiple locations, France_

* OCaml, Coq

## [Intel](https://www.intel.com/content/www/us/en/jobs/jobs-at-intel.html) 📤 (few teams at Intel Labs)

* [Intel C++ Compiler](https://software.intel.com/en-us/c-compilers)
* [Intel FPGA OpenCL compiler](https://www.intel.ca/content/www/ca/en/software/programmable/sdk-for-opencl/overview.html)
* [Intel Labs](https://www.intel.com/content/www/us/en/research/overview.html) with ML Compiler and MLIR work
* LLVM contributions (mostly X86 backend)

## [Igalia](https://www.igalia.com/jobs/) 📤🧑‍🎓
🗺 _A Coruña, Galicia, Spain / Worldwide_

* Consultancy which is heavily involved in free and open source software, and the web platform. Known in compilers circles for work on scripting engines (SpiderMonkey, V8, JSC), as well as LLVM and Guile.

## [Jane Street](https://www.janestreet.com/join-jane-street/apply/) 🧑‍🎓
🗺 _New York, London_

Jane Street has work on it's primary for of OCaml, called [OxCaml](http://oxcaml.org), as well as other roles throughout the organization that involve smaller-scale compiler work.

* A [post about OCaml work at JS](https://blog.janestreet.com/work-on-the-ocaml-compiler-at-jane-street/)
* A [Programming langauge engineer](https://www.janestreet.com/join-jane-street/position/4275921002/) role focused on OxCaml.
* A [Language and Runtime Engineer](https://www.janestreet.com/join-jane-street/position/6378838002/) role that's aimed at an in-house language system backed by a graph-structured compute engine.
* [Tools & Compilers Researcher Internship](https://www.janestreet.com/join-jane-street/position/5869205002/)
* A [prefaculty](https://www.janestreet.com/join-jane-street/programs-and-events/visiting-researcher-prefaculty/) position aimed at people who want to spend a year in industry before going off to an academic PL faculty position.

Other internal language-oriented projects include work on a [Haxl](https://hackage.haskell.org/package/haxl)-like system in OCaml, work on compilation pipelines to Javascript and Wasm for OCaml, and a SQL variant with several custom execution engines.

## [Jetbrains](https://www.jetbrains.com/careers/apply/)

🗺 _Munich & Berlin Germany, Prague Czech Republic, Amsterdam Netherlands, Cyprus, Serbia, Armenia (other locations for non-compiler jobs)_

* Kotlin

## [JITX](https://www.jitx.com/careers) 📤
🗺 _SF Bay Area, CA_

* DSL to generate circuit board designs

## [Jsoftware](https://www.jsoftware.com/#/contact)

* J programming language

## [Julia Computing](https://juliacomputing.com/communication/jobs) 📤🧑‍🎓
🗺 _Boston, MA_ 

* Development of [Julia](https://julialang.org/)

## [Klara](https://klarasystems.com/careers/) 📤

* LLVM for ARM on FreeBSD

## [Kx Systems](https://kx.com/about/careers/)

* K programming language

## [Lemurian Labs](https://www.lemurianlabs.com/) 

* AI Portability

## [Lightmatter](https://lightmatter.co/people/join-us/)

* Machine learning hardware compilers

## [Linaro](https://www.linaro.org/careers)

* LLVM work supporting the Arm architecture

## [Lokad](https://www.lokad.com/jobs-senior-compilation-engineer)
🗺 _Paris, France_

* DSL compiler for [supply chain optimisation](http://blog.lokad.com/journal/2016/9/26/will-compilation-save-supply-chains)

## [lowRISC](https://lowrisc.org/jobs/)
🗺 _Cambridge, UK_

* Non-profit with LLVM RISC-V work

## [Lynx Tool](https://lynxtool.com/careers)

* Compiler for a visual programming language.

## [MathWorks](https://www.mathworks.com/company/jobs/opportunities.html?source=19210&s_eid=Rci_19210)
🗺 _Natick, MA, USA_

* [MATLAB](https://www.mathworks.com/products/matlab.html)
* [Simulink](https://www.mathworks.com/products/simulink.html)
* [HDL Coder](https://www.mathworks.com/products/hdl-coder.html) 
* [LLVM](https://llvm.org/devmtg/2014-10/Slides/Cheng-InteractiveModeling.pdf)
* [JIT](https://www.mathworks.com/company/jobs/opportunities/9537-senior-software-engineer-jit-compiler?source=19210&s_eid=Rci_19210)

## [Matter Labs](https://matter-labs.io) 📤

* LLVM-based compiler for executing Ethereum smart contracts

## [Marvell](https://www.marvell.com/company/careers/)

* GCC contributions

## [Meta](https://www.metacareers.com)

A variety of projects, a limited subset of which I know about below. 

* [PyTorch](https://pytorch.org/)
* [HHVM](https://hhvm.com/)
* [Python (Cinder)](https://github.com/facebookincubator/cinder)
* LLVM contributions (MLIR, LLDB, ThinLTO, BOLT etc.)

## [MCST](http://www.mcst.ru/vakansis)
🗺  _Moscow, Russia_

* [LCC](http://www.mcst.ru/lcc) optimizing compiler for MCST's chips
* Binary translator from x86 to own Elbrus ISA

## [MediaTek](https://careers.mediatek.com/)
🗺 _Woburn, MA, USA_

* Compiler development for MediaTek chips

## [Micron](https://www.micron.com/careers)

* Deep Learning Compiler

## [Microchip](https://careers.microchip.com/)

* Compiler development for Microchip's chips. 

## [Microdoc](https://www.microdoc.com/career/) 📤
🗺 _Berlin, Munich, Stuttgart, Germany_

We develop custom GraalVM and Java runtime environments and virtual machines for use in embedded systems:
  * [GraalVM](https://www.graalvm.org/) Enterprise and Community runtime environments.
  * Java SE, OpenJDK and J9 runtime environments.
  * Target operating systems include QNX, Linux, Android, Windows CE, OSE.
  * Target processor architectures include ARM 64-bits and 32-bits, Intel x86 32-bits, AMD x86_64, MIPS, PowerPC.
  * Implementing custom features inside the JVM or standard library.

## [Microsoft](https://careers.microsoft.com/)

* MSVC
* C#, F#
* [Checked C](https://github.com/Microsoft/checkedc) 
* TypeScript
* JVM
* Rust Compiler
* [Python](https://github.com/faster-cpython)

## [Microsoft Research](https://www.microsoft.com/en-us/research/careers/)

* Koka, Lean, F* (F-star)
* probably other things too.

## [Modular](https://www.modular.com/company/careers) 📤 (US/Canada)

* AI Graph Compiler: MLIR

## [Mozilla](https://careers.mozilla.org/listings/) 📤 🧑‍🎓 

* [SpiderMonkey development](https://spidermonkey.dev)

## [Mutual Knowledge Systems (MuKn)](https://mukn.io/) 📤

*  Building [Glow](https://glow-lang.org), a language for DApps

## [Mythic](https://www.mythic-ai.com/join/)
🗺 _SF Bay Area, CA_

* Machine learning hardware compilers

## [Nethermind](https://boards.eu.greenhouse.io/nethermind/jobs/4034249101) 📤 🧑‍🎓 

* Get to contribute to a compiler for a target language with a novel memory model
* Opportunity to work on tooling support

## [NextSilicon](https://www.nextsilicon.com/careers)
🗺 _Israel, Zurich_

* MLIR work for specialised HPC hardware

## [=nil.foundation;](https://nil.foundation/careers/jobs) 

* Ethereum L2 

## [Nintendo](https://careers.nintendo.com/job-openings/)
🗺 _Redmond, WA_ 

* Compiler engineering

## [Nomic Foundation](https://nomic.foundation/) 📤 

* Compiler Engineering (Rust) - Slang
* Ethereum Development Runtime (Rust) - EDR

## [NVIDIA](https://www.nvidia.com/en-us/about-nvidia/careers/) 📤 (some teams)

* LLVM middle-end/back-end contributions
* Front-end work on nvcc to support CUDA
* Flang
* ML Compiler

## [NXP](https://www.nxp.com/company/about-nxp/careers:CAREERS)

* LLVM

## [OCamlPRO](https://ocamlpro.com/) 🧑‍🎓
🗺 _Paris, France_

* Toolchains for OCaml, COBOL and Rust

* Positions for industry oriented doctoral theses and internships

## [Octasic](http://www.octasic.com/careers/#openings)
🗺 _Montreal, QC, Canada_ 

* Compilers for Octasic’s multi-core digital signal processors (LLVM) 

## [OctoML](https://octoml.ai/company/careers/) 📤

* [Apache TVM](https://tvm.apache.org/)

## [Omni Design](https://www.omnidesigntech.com/about/careers/)
🗺 _Multiple locations, USA_

* Circuit compilers for semiconductors, such as memory compilers, register file and SRAM generation, and software driven circuit topology creation.

## [OpenAI](https://openai.com/careers/)
🗺 _San Fransisco_

* [Triton](https://github.com/openai/triton), a language and compiler for writing highly efficient custom Deep-Learning primitives

## [OpenText](https://careers.opentext.com/)
🗺 _Richmond Hill, ON, CA Waterloo, ON, CA Ottawa, ON, CA Mississauga, ON, CA_

* Application Security static analysis (OpenText Fortify)

## [Oracle](https://www.oracle.com/corporate/careers/) 

* OpenJDK, including the hotspot compiler

🗺 _Zurich_, _Linz_, _California_, _Prague_, _Brno_, _Lviv_, _Casablanca_, _Belgrade_, _Remote_ (📤)

* [GraalVM](https://www.graalvm.org/) (also [internships](https://www.graalvm.org/community/internship/))

## [Oso](https://www.osohq.com/company/jobs) 📤

🗺 *New York, US / Remote (US/Europe)*

* [Polar](https://docs.osohq.com/learn/polar-foundations.html): a logic programming language for
  expressing authorization logic and policies.

## [Oven](https://oven.sh)
🗺 San Francisco, 📤 Remote

* [Bun](https://bun.sh): a JavaScript runtime with a native bundler, transpiler, task runner, and npm client built-in.
    * Written in Zig

## [Partisa](https://partisia.com/careers/)
🗺 _Aarhus, Denmark_ 

* Creating a language for multi-party computation. 

## [Pensando](https://recruiterflow.com/Pensando-Systems/jobs)
🗺 _Milpitas, CA_

* P4 compiler targetting the Capri processor (LLVM)

## [Persimmons](https://apply.workable.com/persimmons-ai/)
🗺 _San Jose, CA_

* Compiler for Persimmons' proprietary ML accelerator hardware.

## [PGI](https://www.pgroup.com/about/jobs.htm) 
🗺 _Portland_

* PGI's compilers 
* [Flang](https://github.com/flang-compiler/flang), a Fortran frontend for LLVM

## [Praetorian](https://www.praetorian.com/company/careers/) 📤
🗺 _US_

* [Chariot Source Code](https://www.praetorian.com/chariot/source-code/), a static analysis tool that exists as part of the Chariot platform

## [Prophecy.io](https://angel.co/company/prophecy-io/jobs)
🗺 _San Fransisco_

* Scala + Spark engineering (Query optimizer)

## [Quadric](https://quadric.io/#join-the-team)
🗺 _Burlingame, CA_

 * LLVM development for Quadric platform

## [Qualcomm](https://www.qualcomm.com/company/careers) 📤 (some teams)

* LLVM (Hexagon, AArch64, and RISC-V teams)
* GCC
* GPU Compiler
* ML Compiler

## [Quantinuum](https://www.quantinuum.com/company/careers) 
🗺 _Multiple locations, UK/US/Japan_

* Quantum compiler

## [Quarkslab](https://www.quarkslab.com/careers-jobs/) 
🗺 _Paris, France_ (remote available within France)
* A security product built on LLVM

## [R2C](https://r2c.dev/) 📤
🗺 _San Fransisco, CA_

* Program analysis tools

## [Radix Labs](https://www.radix.bio/careers) 📤

* DSL for optimising biotech procedures and executing them in a physical biology lab

## [Raincode Labs](https://www.raincodelabs.com/careers/)

* A variety of compiler/language engineering projects, providing modernization and cost reduction.

## [Rebellions](https://rebellions.ai/career/)
🗺 _Seongnam, South Korea_

* Compiler stack to accelerate deep learning models on NPU products.

## [Red Hat](https://www.redhat.com/en/jobs)

* GCC 
* JVM (OpenJDK)
* LLVM

## [Rigetti Computing](https://www.rigetti.com/careers) 📤

* Quantum Computing Compiler (LLVM + Rust)

## [Rivos](https://www.rivosinc.com/)
🗺 _Mountain View CA, Austin TX, Portland OR, Fort Collins CO, and Cambridge, UK_ 

* LLVM contribution for RISC-V 

## [Roblox](https://corp.roblox.com/careers/)
🗺 _San Mateo, CA_

* Embedded scripting languages for the Roblox game engine, for example [Luau](https://luau-lang.org/)

## [Runtime Verification](https://runtimeverification.com/careers/) 📤

* K Framework 

## [Sambanova](https://sambanova.ai/careers/)

* Deep Learning Compiler (MLIR)
* Place & Route (PNR)

## [Samsung](https://www.samsung.com/us/careers/)
🗺 _San Jose_

* JIT Compiler for Samsung GPU (OpenGL-ES, OpenCL) 

## [SAP](https://jobs.sap.com/) 

* ABAP
* JVM
* Node.js

## [Scala Center - EPFL](https://scala.epfl.ch/)

* Non-profit with Scala compiler work (JVM, Scala.js, Scala native), editor integration and tooling

## [SCI Semiconductor](https://www.scisemi.com/careers/) 📤

* LLVM Support for [CHERIoT](https://cheriot.org/) 

## [SEGGER](https://www.segger.com/about-us/job-offers/) 📤

* [Clang-based compiler specialised for embedded development](https://blog.segger.com/the-segger-compiler/)

## [Semantic Designs](http://www.semdesigns.com/Careers/)
🗺 _Austin, TX_

* [DMS](http://www.semdesigns.com/Products/DMS/index.html), a suite of program transformation tools for large scale software systems
* [PARLANSE](http://www.semdesigns.com/Products/Parlanse/index.html), a parallel programming language

## [SEMRON](https://semron.ai/)
🗺 _Dresden, GER_

- LLVM, MLIR

## [ShiftLeft](https://www.shiftleft.io/) 📤

* Compiler technology used for application security.

## [Shopify](https://www.shopify.com/careers) 📤

* Ruby
* Static analysis and typing
* Interpreters, garbage collectors
* JVM, Truffle, Graal

## [Shorebird](https://shorebird.dev/jobs/) 📤

* Dart VM and compiler

## [Siemens](https://new.siemens.com/global/en/company/jobs.html)
🗺 _A number of locations_

A number of Compiler/PL projects: 

* HDL Compilers
* DSL Compilers
* Industrial Automation Compilation


## [SiFive](https://www.sifive.com/jobs) 
🗺 _San Mateo, California, Hsinchu Taiwan_

* LLVM, MLIR

## [Silexica](https://www.silexica.com/careers/)
🗺 _Cologne_

* Heterogenous architecture development

## [SiMa.ai](https://sima.ai/careers/) 🧑‍🎓
🗺  _San Jose, CA_

* Machine Learning accelerator compiler
* Hardware software co-design 

## [SiPerl](https://careers.sipearl.com/en#jobs) 🧑‍🎓
🗺  _Multiple locations, Europe_

* LLVM-based compiler

## [Snowflake](https://careers.snowflake.com) 
🗺 _ Bellevue, WA, & San Mateo, CA_ 

* Database query compiler 

## [Snyk](https://snyk.io/careers/all-jobs/)
🗺 _Bucharest, Romania_

* [Snyk Code](https://snyk.io/product/snyk-code/), a static analysis tool that exists as part of the Snyk platform

## [Solana](https://jobs.solana.com/)

* Solang, a compiler for Solidity that targets WebAssembly and BPF

## [Sonatype](https://www.sonatype.com/company/careers) 📤
🗺 _US, Canada, Colombia_

* [Sonatype Lift](https://www.sonatype.com/products/sonatype-lift), a code quality analysis platform

## [Sony](https://www.sonyjobs.com/find-a-job.html)
🗺 _Bangalore, India, UK_

* LLVM Compiler Development

## [Splunk](https://www.splunk.com/en_us/careers.html) (acquired by Cisco) 📤
🗺 _Seattle, WA + multiple locations_

* Query language / compiler development

## [STMicroelectronics](https://www.st.com/content/st_com/en/about/careers/careers.html) 
🗺 _Grenoble, France_

* Support for STMicroelectronic products
* Clang, LLVM

## [Stripe](https://stripe.com/jobs)

* [Sorbet type checker for Ruby](https://github.com/sorbet/sorbet)
* [LLVM-based AOT compiler for Ruby](https://twitter.com/penelope_zone/status/1410652824422260738?s=20)

## [Styra](https://www.styra.com/careers) 📤
🗺 _US, Canada, Europe_

* Makers of [Open Policy Agent](https://www.openpolicyagent.org/)
  and the datalog-derived logic programming language Rego.
* Interpreters, compiler (e.g. compiling Rego to Wasm), and applications of static analysis.

## [Synopsys](https://www.synopsys.com/company/synopsys-careers.html)

* Makers of Coverity
* LLVM work on the ARC backend
* LLDB
* Neural Network Compiler 

## [Synthetic Minds](https://www.workatastartup.com/jobs/44386) 📤

* Working on Program Synthesis 

## [Tachyum](https://www.tachyum.com/jobs/)

* Compiler toolchain development for a new architecture that supports binary translation. 

## [Tarides](https://tarides.com/careers/) 📤
🗺 _Paris, France, Cambridge, UK, Chennai, India_

* OCaml compiler

## [Tenstorrent](https://tenstorrent.com/careers/) 📤 (some positions)
🗺 _Toronto, ON_

* Machine learning hardware compilers
* RISC-V LLVM toolchain/compiler work

## [Terapines](https://www.terapines.com/post/1965/)
🗺 _Wuhan, China_

* AI compiler development based on LLVM/MLIR
* Mojo language development
* RISC-V compiler toolchain development
* CIRCT compiler development
* ClangIR development

## [TetraMem](https://www.tetramem.com/)
🗺 _SF Bay Area_

* Machine learning hardware compilers, LLVM

## [The Browser Company](https://thebrowser.company/careers) 📤 (US/Canada)
🗺 _New York, US_

* Swift compiler work

## [Theobroma Systems](https://careers.theobroma-systems.com/jobs/)
🗺 _Vienna_

* Compiler support for ARM SoC

## [TI](https://careers.ti.com/) 

* LLVM 
* TI specific compiler toolchains

## [TikTok](https://careers.tiktok.com/)
🗺 _Mountain View, CA_

* Compilers for mobile platforms

## [Trail of Bits](https://www.trailofbits.com/careers) 📤 🧑‍🎓

Security firm that does [compiler engineering and research](https://www.trailofbits.com/services/research-and-development)

## [TrustInSoft](https://trust-in-soft.com/trustinsoft-careers/)
🗺 _San Francisco, Paris_

* [TrustInSoft Analyzer](https://trust-in-soft.com/product-c-and-c-source-code-analyzer/), a source code verification tool for C and C++

## [Unity](https://careers.unity.com/)

* .NET
* Mono
* IL2CPP, a compiler to convert .NET IL to C++

## [UPMEM](https://www.upmem.com)
🗺 _Grenoble, France_

Building a processing-in-memory product. 

* LLVM-based compiler

## [Vector](https://jobs.vector.com/global/our-jobs)

* Static analysis and abstract program interpretation for software hardening

## [Veeva Systems](https://careers.veeva.com/) [📤](https://careers.veeva.com/work-anywhere/) 
🗺 _Pleasanton, Columbus, Boston, Kansas City, New York City, Raleigh, and Toronto_ 

* Work on Language and Runtime system 

## [Ventana](https://jobs.jobvite.com/ventanamicro/)

* RISC-V Architecture
* GCC
* LLVM
* Performance Analysis

## [Vercel](https://vercel.com/careers?department=Engineering)
🗺 United States

Static analysis framework for JavaScript applications

## [Veridise](https://veridise.com/careers/) 📤

Automated analysis of blockchain programs, built atop LLVM

## [Vypercore](https://www.vypercore.com/team) 
🗺 _Bristol / Cambridge_

Toolchain development for RISC-V core with novel hardware memory allocation management technology. 

## [Wasmer](https://www.workatastartup.com/jobs/15822)

* WebAssembly runtime (LLVM)

## [Waymo](https://waymo.com/careers/)
🗺 _Mountain View, CA_

* Machine learning hardware compiler

## [Well-Typed](https://www.well-typed.com/) 📤

* Glasgow Haskell Compiler (GHC)

## [Weta Digital](https://careers.wetafx.co.nz/)
🗺 _Wellington, NZ_ 

* Shader Language development 
* LLVM 

## [WhatsApp](https://www.whatsapp.com/join)

* Erlang

## [Wibu-Systems](https://jobs.wibu.com/de?id=d7d9f1) 🧑‍🎓
🗺  _Karlsruhe, Germany_

* compiler development and security research with LLVM, .NET CIL, Python and more

## [WindRiver](https://www.windriver.com/careers/)

* Compilers for VxWorks

## [Wolfram Research](https://www.wolfram.com/company/careers/)
🗺 _Linköping, Sweden_

* Wolfram language, WolframAlpha, Mathematica
* Modelica

## [Workday](https://www.workday.com/en-us/company/careers/overview.html)
🗺 _Pleasanton, CA_

* Compiler, runtime and IDE for Workday's proprietary programming languages, XpressO and YP

## [Woven Planet](https://woven.toyota/en/careers/)
🗺 _Tokyo, Japan_

* Static analysis and developer tools for vehicle software.

## [Xilinx](https://careers.xilinx.com/)
🗺 _Cologne, Germany_

* Compiler for FPGA Systems 

## [Xanadu](https://www.xanadu.ai/careers/)
🗺 _Toronto, Canada_

* Compilation stack for quantum computing and hybrid computation
* LLVM, MLIR, QIR 

## [YoYo Games](https://www.yoyogames.com/en/jobs) 📤
🗺 _Dundee, Scotland_

* LLVM
* GML (GameMaker Language) compiler
* JavaScript compiler
* Integrated Development Environment targeting desktop, web, mobile and games console environments

## [Yosys HQ](https://www.yosyshq.com/jobs) 📤
🗺 _Multiple locations, Earth_

* Open source FPGA and ASIC logic synthesis and hardware formal verification with model checking
* MLIR, CIRCT

## [Zoox](https://zoox.com/careers/)
🗺 _Foster City, CA_

* Program analysis tools for verifying firmware
