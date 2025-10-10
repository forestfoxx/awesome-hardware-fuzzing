# Awesome hardware fuzzing
A curated list of research and repositories on the novel technique of hardware fuzzing. For various reasons, most of existing works target RISC-V, with some exceptions. 

[The Emergence of Hardware Fuzzing: A Critical Review of its Significance](https://arxiv.org/html/2403.12812v1)

[State of Hardware Fuzzing: Current Methods and the Potential of Machine Learning and Large Language Models](https://www.isqed.org/English/Proceedings/pdf/4C-2-176.pdf)

[The Fuzz Odyssey: A Survey on Hardware Fuzzing Frameworks for Hardware Design Verification](https://dl.acm.org/doi/fullHtml/10.1145/3649476.3658697)

[Fuzzing Hardware Like Software](https://www.usenix.org/system/files/sec22-trippel.pdf) | [source code](https://github.com/googleinterns/hw-fuzzing)
		
[MileSan: Detecting Exploitable Microarchitectural Leakage via Differential Hardware-Software Taint Tracking](https://comsec.ethz.ch/research/hardware-design-security/milesan-detecting-exploitable-microarchitectural-leakage-via-differential-hardware-software-taint-tracking/) | [source code](https://github.com/comsec-group/milesan-meta)					

DiveFuzz: Enhancing CPU Fuzzing via Diverse Instruction Construction | [source code](https://github.com/In2Sec/DiveFuzz)

[Encarsia: Evaluating CPU Fuzzers via Automatic Bug Injection](https://comsec.ethz.ch/research/hardware-design-security/encarsia/) | [source code](https://github.com/comsec-group/encarsia)

[Cascade: CPU Fuzzing via Intricate Program Generation](https://github.com/comsec-group/cascade-artifacts) | [source code](https://github.com/comsec-group/cascade-artifacts)

[FeedbackFuzz: Fuzzing Processors via Intricate Program Generation with Feedback Engine](https://ieeexplore.ieee.org/document/10889404)

[Phantom Trails: Practical Pre-Silicon Discovery of Transient Data Leaks](https://download.vusec.net/papers/phantom-trails_sec25.pdf) | [source code](https://github.com/vusec/phantom-trails) and [artifacts](https://zenodo.org/records/14726711) and [this repo](https://github.com/vusec/hw-fuzzing-libafl) and [PoCs](https://github.com/vusec/riscv-transient-attacks)

[Lost and Found in Speculation: Hybrid Speculative Vulnerability Detection](https://arxiv.org/pdf/2410.22555) | Note: hardware fuzzing + IFT (Specure, not yet opensource)

[SpecDoctor: Differential Fuzz Testing to Find Transient Execution Vulnerabilities](https://jaewonhur.github.io/files/jwhur-specdoctor.pdf) | [source code](https://github.com/vusec/specdoctor)

[Revizor: Testing Black-box CPUs against Speculation Contracts](https://arxiv.org/abs/2105.06872) | [source code](https://github.com/microsoft/sca-fuzzer)

[Hide and Seek with Spectres: Efﬁcient discovery of speculative information leaks with random testing](https://arxiv.org/pdf/2301.07642) | [source code](https://github.com/microsoft/sca-fuzzer)

[Speculation at Fault: Modeling and Testing Microarchitectural Leakage of CPU Exceptions](https://www.usenix.org/conference/usenixsecurity23/presentation/hofmann) | [source code](https://github.com/microsoft/sca-fuzzer) and [artifact](https://github.com/vusec/SpeculationAtFault-AE)

[Testing side-channel security of cryptographic implementations against future microarchitectures](https://arxiv.org/pdf/2402.00641) | [source code](https://github.com/hw-sw-contracts/leakage-model-testing)
      
[SpecFuzz: Bringing Spectre-type vulnerabilities to the surface](https://arxiv.org/abs/1905.10311) | [source code](https://github.com/OleksiiOleksenko/SpecFuzz)

[Blacksmith: Scalable Rowhammering in the Frequency Domain](https://comsec.ethz.ch/wp-content/files/blacksmith_sp22.pdf) | [source code](https://github.com/comsec-group/blacksmith)

[ZenHammer: Rowhammer Attacks on AMD Zen-based Platforms](https://comsec.ethz.ch/research/dram/zenhammer/) | [source code](https://github.com/comsec-group/zenhammer)

[Posthammer](https://comsec.ethz.ch/research/dram/posthammer/) | [source code](https://github.com/comsec-group/posthammer/tree/main/native-fuzzer)

[RISC-H: Rowhammer Attacks on RISC-V](https://comsec-files.ethz.ch/papers/risc-h_dramsec24.pdf)

[TEESec: Pre-Silicon Vulnerability Discovery for Trusted Execution Environments](https://moeinghaniyoun.github.io/files/TEESec.pdf) | [source code](https://github.com/MoeinGhaniyoun/TEESec)

[INTROSPECTRE: A Pre-Silicon Framework for Discovery and Analysis of Transient Execution Vulnerabilities](https://radu.teodorescu.us/assets/pdf/introspectre_isca2021.pdf)

[SPEECHMINER: A Framework for Investigating and Measuring Speculative Execution Vulnerabilities](https://www.ndss-symposium.org/ndss-paper/speechminer-a-framework-for-investigating-and-measuring-speculative-execution-vulnerabilities/) | [source code](https://github.com/teecert/SpeechMiner)

[Rubicon: Precise Microarchitectural Attacks with Page-Granular Massaging](https://comsec.ethz.ch/research/dram/rubicon/) | [source code](https://github.com/comsec-group/rubicon) and [Rubicon-enhanced Blacksmith Rowhammer fuzzer](https://github.com/rubicon-artifacts/rubicon-blacksmith/tree/main)

[TRRespass: Exploiting the Many Sides of Target Row Refresh](https://download.vusec.net/papers/trrespass_sp20.pdf) | [source code](https://github.com/vusec/trrespass) and [modified TRRespass](https://github.com/hyichang0510/Trrespass-modified-) and [another fork](https://github.com/pjattke/trrespass-fork) and [another inspired work](https://github.com/mojomojo52/multibank_hammer) and [Sledgehammer paper](https://www.usenix.org/system/files/sec24summer-prepub-482-kang.pdf)

[RISCVuzz: Discovering Architectural CPU Vulnerabilities via Differential Hardware Fuzzing](https://ghostwriteattack.com/) | [source code for GhostWrite PoC](https://github.com/cispa/GhostWrite)

[SIGFuzz: A Framework for Discovering Microarchitectural Timing Side Channels](https://seclab.bu.edu/papers/SIGFuzz-date2023.pdf) | [source code](https://github.com/bu-icsg/SIGFuzz)

[WhisperFuzz: White-Box Fuzzing for Detecting and Locating Timing Vulnerabilities in Processors](https://arxiv.org/pdf/2402.03704) | [artifacts](https://zenodo.org/records/14166394)

[SurgeFuzz: Surge-Aware Directed Fuzzing for CPU Designs](https://www.rsg.ci.i.u-tokyo.ac.jp/members/shioya/pdfs/Sugiyama-ICCAD'23.pdf) | [source code](https://github.com/shioya-lab-public/surgefuzz)

[GenFuzz: GPU-accelerated Hardware Fuzzing using Genetic Algorithm with Multiple Inputs](https://tsung-wei-huang.github.io/papers/2023-dac.pdf) | [source code](https://github.com/dian-lun-lin/GenFuzz)

[ProcessorFuzz: Guiding Processor Fuzzing using Control and Status Registers](https://ieeexplore.ieee.org/document/10133714) | [source code](https://github.com/bu-icsg/ProcessorFuzz)

[DIFUZZ RTL: Differential Fuzz Testing to Find CPU Bugs](https://jaewonhur.github.io/files/jwhur-difuzzrtl.pdf) | [source code](https://github.com/compsec-snu/difuzz-rtl)

[MorFuzz: Fuzzing Processor via Runtime Instruction Morphing Enhanced Synchronizable Co-simulation](https://www.usenix.org/system/files/sec23fall-prepub-7-xu-jinyan.pdf) | [source code](https://github.com/sycuricon/MorFuzz)

[DejaVuzz: Disclosing Transient Execution Bugs with Dynamic Swappable Memory and Differential Information Flow Tracking assisted Processor Fuzzing](https://www.arxiv.org/pdf/2504.20934) | [source code](https://github.com/sycuricon/DejaVuzz)
                
[Medusa: Microarchitectural Data Leakage via Automated Attack Synthesis](https://www.usenix.org/conference/usenixsecurity20/presentation/moghimi-medusa) | [source code](https://github.com/flowyroll/medusa)                

[Effective Processor Verification with Logic Fuzzer Enhanced Co-simulation](https://masc.soe.ucsc.edu/docs/micro21.pdf) | [source code for dromajo](https://github.com/chipsalliance/dromajo)

[NoCFuzzer: Automating NoC Veriﬁcation in UVM](https://jyhuang91.github.io/papers/tcad2025-nocfuzzer.pdf) | [source code](https://github.com/magicYang1573/NoC-UVM-Testbench)

[VerilogReader: LLM-Aided Hardware Test Generation](https://arxiv.org/pdf/2406.04373) | [source code](https://github.com/magicYang1573/llm-hardware-test-generation)

[Bridging the Gap between Hardware Fuzzing and Industrial Verification](https://arxiv.org/pdf/2506.00461) | [source code](https://github.com/magicYang1573/fast-hw-fuzz)

Pre-Silicon Hardware Fuzzing Toolkit | [source code](https://github.com/IntelLabs/PreSiFuzz)

[Sandsifter: the x86 processor fuzzer](https://www.blackhat.com/docs/us-17/thursday/us-17-Domas-Breaking-The-x86-ISA.pdf) | [source code](https://github.com/xoreaxeaxeax/sandsifter), [python3 port](https://github.com/jakiki6/sandsifter), [test runs repo](https://github.com/rigred/sandsifter-tests), [fork with some fixes](https://github.com/rigred/sandsifter), [Black Hat talk](https://www.youtube.com/watch?v=KrksBdWcZgQ)

Work inspired by sandsifter: [vmsifter](https://github.com/intel/vmsifter), [sandsifterOS](https://github.com/MikeHorn-git/sandsifterOS), [baresifter](https://github.com/blitz/baresifter)

[Uncovering Hidden Instructions in Armv8-A Implementations](https://rakeshk.folk.ntnu.no/pubs/armshaker_HASP20.pdf) | [source code for Armshaker](https://github.com/frestr/armshaker)

[Osiris: Automated Discovery of Microarchitectural Side Channels](https://www.usenix.org/system/files/sec21-weber.pdf) | [source code](https://github.com/cispa/osiris)

[Microarchitectural Leakage Templates and Their Application to Cache-Based Side Channels](https://hnemati.github.io/paper/ccs22-leakagetemplates.pdf) | [source code for Plumber](https://github.com/scy-phy/plumber/)

[ABSynthe: Automatic Blackbox Side-channel Synthesis on Commodity Microarchitectures](https://comsec.ethz.ch/wp-content/files/absynthe_ndss20.pdf) | [source code](https://github.com/vusec/absynthe)                

[TikTag: Breaking ARM's Memory Tagging Extension with Speculative Execution](https://arxiv.org/abs/2406.08719) | [source code](https://github.com/compsec-snu/tiktag)

[SiliFuzz: Fuzzing CPUs by proxy](https://storage.googleapis.com/gweb-research2023-media/pubtools/6405.pdf) | [source code](https://github.com/google/silifuzz), [Reptar CPU vulnerability](https://bughunters.google.com/blog/5997221712101376/the-reptar-cpu-vulnerability)

[PathFuzz: Broadening Fuzzing Horizons with Footprint Memory for CPUs](https://dl.acm.org/doi/10.1145/3649329.3655911) | [source code](https://github.com/OpenXiangShan/xfuzz)

[Functional Verification for Agile Processor Development: A Case for Workflow Integration](https://github.com/OpenXiangShan/XiangShan-doc/raw/main/publications/jcst2023-workflow-integration.pdf) | [source code](https://github.com/openxiangshan/difftest)

[SSFuzz: Generating syntactic and semantic seeds for RISC-V Processors](https://dl.acm.org/doi/abs/10.1145/3649476.3658712) | [source code](https://github.com/ipasslab/SSFuzz) (not yet opensource?)

[Symbolic Simulation Enhanced Coverage-Directed Fuzz Testing of RTL Design](https://ieeexplore.ieee.org/document/9401267) | [slides](https://confcats-event-sessions.s3.amazonaws.com/iscas21/slides/1259.pdf)

[Grammar-based fuzz testing for microprocessor RTL design](https://dl.acm.org/doi/10.1016/j.vlsi.2022.05.001)

[UISFuzz: An Efficient Fuzzing Method for CPU Undocumented Instruction Searching](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8863327)

[Hot Fuzz: Assisting verification by fuzz testing microelectronic hardware](https://ieeexplore.ieee.org/document/10192176)

[HyperFuzzing for SoC Security Validation](https://ieeexplore.ieee.org/document/9256500) | [source code](https://github.com/skmuduli92/HyperFuzzer)

[Beyond Random Inputs: A Novel ML-Based Hardware Fuzzing](https://ieeexplore.ieee.org/abstract/document/10546625)

[RLFuzz: Accelerating Hardware Fuzzing with Deep Reinforcement Learning](https://www.bibsonomy.org/bibtex/2229ab60e60c1b371f6a6ac51f3e368af/raphael.goetz) | also see [HYDRANOS project](https://hydranos.eu/)

[TaintFuzzer: SoC Security Verification using Taint Inference-enabled Fuzzing](https://ieeexplore.ieee.org/document/10323726)

[SoCFuzzer: SoC Vulnerability Detection using Cost Function enabled Fuzz Testing](https://ieeexplore.ieee.org/document/10137024)

[Detection of Hardware Trojans in SystemC HLS Designs via Coverage-guided Fuzzing](https://agra.informatik.uni-bremen.de/doc/konf/2019DATE_Detection_of_Hardware_Trojans_in_SystemC_HLS_Designs_via_Coverage-guided_Fuzzing.pdf)

[MABFuzz: Multi-Armed Bandit Algorithms for Fuzzing Processors](https://ieeexplore.ieee.org/abstract/document/10546726)

[DirectFuzz: Automated Test Generation for RTL Designs using Directed Graybox Fuzzing](https://ieeexplore.ieee.org/document/9586289)

[RFUZZ: Coverage-Directed Fuzz Testing of RTL on FPGAs](https://people.eecs.berkeley.edu/~ksen/papers/rfuzz.pdf) | [source code](https://github.com/ekiwi/rfuzz)

[TheHuzz: Instruction Fuzzing of Processors Using Golden-Reference Models for Finding Software-Exploitable Vulnerabilities](https://www.usenix.org/system/files/sec22-kande.pdf)

[HyPFuzz: Formal-Assisted Processor Fuzzing](https://www.usenix.org/system/files/usenixsecurity23-chen-chen.pdf)

[RTLFUZZLAB: Building A Modular Open-Source Hardware Fuzzing Framework](https://woset-workshop.github.io/WOSET2021.html#article-10) | [source code](https://github.com/ekiwi/rtl-fuzz-lab)

[PSOFuzz: Fuzzing Processors with Particle Swarm Optimization](https://ieeexplore.ieee.org/abstract/document/10323913)

[FormalFuzzer: Formal Verification Assisted Fuzz Testing for SoC Vulnerability Detection](https://ieeexplore.ieee.org/document/10473911)

[Efficient Cross-Level Processor Verification using Coverage-guided Fuzzing](https://ics.jku.at/files/2022GLSVLSI_Crosslevel-Processor-Verification-using-CGF.pdf)

[Fuzzing Hardware: Faith or Reality?](https://ieeexplore.ieee.org/document/9642252)

[HScheduler: An execution history-based seed scheduling strategy for hardware fuzzing](https://www.sciencedirect.com/science/article/abs/pii/S0167404825001671)

[FuzzWiz - Fuzzing Framework for Efficient Hardware Coverage](https://arxiv.org/pdf/2410.17732) 
                     
[GenHuzz: An Efficient Generative Hardware Fuzzer](https://www.usenix.org/conference/usenixsecurity25/presentation/wu-lichao) | [source code](https://zenodo.org/records/14727632)

[HFL: Hardware Fuzzing Loop with Reinforcement Learning](https://ieeexplore.ieee.org/document/10993080) | [source code TBD?](https://github.com/wu-lichao/Chat-Chip)

[Accelerating Hardware Verification with Graph Models](https://arxiv.org/pdf/2412.13374) | Note: unrelated to the same-name GraphFuzz [here](https://github.com/hgarrereyn/GraphFuzz) and [here](https://arxiv.org/pdf/2502.15160)

[Fuzzerfly Effect: Hardware Fuzzing for Memory Safety](https://ieeexplore.ieee.org/document/10462151)

[Trusting the Trust Anchor: Towards Detecting Cross-Layer Vulnerabilities with Hardware Fuzzing](https://dl.acm.org/doi/pdf/10.1145/3489517.3530638)

[PCBleed: Fuzzing for CPU Bugs Through Use of Performance Counters](https://dspace.mit.edu/bitstream/handle/1721.1/156944/muradyan-mnatalie-meng-eecs-2024-thesis.pdf?sequence=1)

[Time and Order: Towards Automatically Identifying Side-Channel Vulnerabilities in Enclave Binaries](https://www.usenix.org/system/files/raid2019-wang-wubing.pdf) | [source code for ANABLEPS](https://github.com/OSUSecLab/ANABLEPS)

[JustSTART: How to Find an RSA Authentication Bypass on Xilinx UltraScale(+) with Fuzzing](https://arxiv.org/pdf/2402.09845) | [source code](https://github.com/emsec/confuzz)

[SPINALFUZZ: Coverage-Guided Fuzzing for SpinalHDL Designs](https://ics.jku.at/files/2022ETS_SpinalFuzz.pdf) | [source code](https://github.com/ics-jku/spinalfuzz)

[Core Fuzzing - A Versatile Platform for Security Verification](https://alenkruth.com/media/paper/techcon23-corefuzzing-initial.pdf)

[Veriﬁcation of Chisel Hardware Designs with ChiselVerify](https://kevinlaeufer.com/pdfs/chiselverify_and_chiseltest_formal_micpro.pdf) | [source code](https://github.com/chiselverify/chiselverify)

[Towards Functional Coverage-Driven Fuzzing for Chisel Designs](https://woset-workshop.github.io/PDFs/2021/a08.pdf) | [source code](https://github.com/chiselverify/chiselverify)

[Exploring Coverage Metrics in Hardware Fuzzing: A Comprehensive Analysis](https://dl.acm.org/doi/10.1145/3649476.3660386)

[Uniﬁed HW/SW Coverage: A Novel Metric to Boost Coverage-guided Fuzzing for Virtual Prototype based HW/SW Co-Veriﬁcation](https://hets.dfki.de/doc/konf/FDL2022_nbruns.pdf) | [source code for RISC-V virtual prototype](https://github.com/agra-uni-bremen/riscv-vp)

[Directed Test Generation for Hardware Validation: A Survey](https://www.cise.ufl.edu/research/cad/Publications/csur23.pdf)

[Accelerating Coverage Directed Test Generation for Functional Verification: A Neural Network-based Framework](https://dl.acm.org/doi/10.1145/3194554.3194561)

[Verismith: Verilog hardware synthesis tool fuzzer](https://github.com/ymherklotz/verismith)

[Bottom-Up Generation of Verilog Designs for Testing EDA Tools](https://arxiv.org/pdf/2504.06295) | [source for ChiGen Verilog fuzzer with type inference and gradual code injection](https://github.com/lac-dcc/chimera)

[Pfuzz: go module for fuzzing Verilog simulators and synthesizers](https://github.com/toby-bro/pfuzz)

[Lost in Translation: Enabling Confused Deputy Attacks on EDA Software with TransFuzz](https://comsec.ethz.ch/research/hardware-design-security/mirtl/) | [source code](https://github.com/comsec-group/mirtl)

[cpufuzz is a dumb, simple and portable CPU fuzzer](https://github.com/a0rtega/cpufuzz)

[CrossFire: Fuzzing macOS Cross-XPU Memory on Apple Silicon](https://dl.acm.org/doi/10.1145/3658644.3690376) | [source code](https://github.com/ZJU-SEC/CrossFire)

[Fuzzing on a ChipWhisperer-Nano](https://github.com/x41sec/ChipFuzz)

[ChipFuzzer: Towards Fuzzing Matter-based IoT Devices for Vulnerability Detection](https://link.springer.com/chapter/10.1007/978-3-031-94455-0_2) | [source code](https://github.com/OCyberLab/ChipFuzzer)

[Evaluation of Hardware Fuzzing](https://www.esat.kuleuven.be/cosic/thesis/2026/hw_fuzzing_evaluation.pdf) thesis proposal

[Genesys-Pro: Innovations in Test Program Generation for Functional Processor Veriﬁcation](https://uobdv.github.io/Design-Verification/Supplementary/GenesysPro.pdf) old paper

[EMFuzz: Use Electromagnetic Fuzzing for Automated Attack Surface Assessment of Actuators](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11121353)
      
Other methodologies (honestly they deserve their own separate list because it's often not directly related to fuzzing but since I found them while researching fuzzing approaches I include them here for comparison sake and for my own convenience)

[Graph Neural Network based Hardware Trojan Detection at Intermediate Representative for SoC Platforms](https://dl.acm.org/doi/pdf/10.1145/3526241.3530827)

[TIUP : Effective Processor Verification with Tautology-Induced Universal Properties](https://dl.acm.org/doi/10.1109/ASP-DAC58780.2024.10473912) | [source code](https://github.com/CrazybinaryLi/TPV)

[Isadora: Auromated information-flow property generation for hardware security verification](https://kastner.ucsd.edu/wp-content/uploads/2022/11/admin/jcen2022-isadora.pdf) 

[Isadora: Automated Information Flow Property Generation for Hardware Designs](https://cd-public.github.io/papers/2021/ASHES2021.pdf) | [source code](https://github.com/cd-public/Isadora)

[CellIFT: Leveraging Cells for Scalable and Precise Dynamic Information Flow Tracking in RTL](https://comsec.ethz.ch/research/hardware-design-security/cellift/) | [source code](https://github.com/comsec-group/cellift-meta)

[A Pre-Silicon Approach to Discovering Microarchitectural Vulnerabilities in Security Critical Applications](https://radu.teodorescu.us/assets/pdf/barber_cal2022.pdf)

[HardFails: Insights into Software-Exploitable Hardware Bugs](https://www.usenix.org/system/files/sec19-dessouky.pdf)

[CheckMate: Automated Synthesis of Hardware Exploits and Security Litmus Tests](https://www-cs.stanford.edu/people/trippel/pubs/ctrippel_MICRO51.pdf) | [source code](https://github.com/ctrippel/checkmate)

[AutoSVA: Democratizing Formal Veriﬁcation of RTL Module Interactions](https://arxiv.org/pdf/2104.04003) | [source code](https://github.com/PrincetonUniversity/AutoSVA)

[A Survey on Assertion-based Hardware Verification](https://par.nsf.gov/servlets/purl/10353227) 

[Synthesizing Hardware-Software Leakage Contracts for RISC-V Open-Source Processors](https://arxiv.org/pdf/2401.09383) | [source code](https://github.com/gdnmhr/contractgen) and [artifact](https://zenodo.org/records/10491534)

[A Symbolic Approach to Detecting Hardware Trojans Triggered by Don’t Care Transitions](https://dl.acm.org/doi/10.1145/3558392) | [source code](https://github.com/sysrel/HWDCT)

[Specification and Verification of Side-channel Security for Open-source Processors via Leakage Contracts](https://gideonmohr.de/upload/2023-ccs-paper.pdf) | [source code](https://github.com/zilongwang123/LeaVe)

[SHarPen: SoC Security Verification by Hardware Penetration Test](https://ieeexplore.ieee.org/document/10044868)

[Hardware Support to Improve Fuzzing Performance and Precision](https://gts3.org/assets/papers/2021/ding:snap.pdf) | [source code](https://github.com/sslab-gatech/SNAP)

[A Methodology for Testing CPU Emulators](https://dl.acm.org/doi/10.1145/2522920.2522922) | [source code](https://github.com/sevenseasofbri/EmuFuzz)

[End-to-End Automated Exploit Generation for Validating the Security of Processor Designs](https://www.cs.unc.edu/~rzhang/files/MICRO2018.pdf) | [source code](https://github.com/rzhang2285/Coppelia)

[RTL-ConTest: Concolic Testing on RTL for Detecting Security Vulnerabilities](https://ieeexplore.ieee.org/document/9380345) | [source code](https://github.com/UTD-TIES-LAB/RTL-Contest)

[RTL Verification for Secure Speculation Using Contract Shadow Logic](https://arxiv.org/pdf/2407.12232) | [source code](https://github.com/qinhant/ShadowLogicArtifact)

[Side-Channel Aware Fuzzing](https://arxiv.org/pdf/1908.05012)

mchammer - synthesizing hardware machine check exceptions for processor exploitation and privilege escalation | [toolkit includes machine check synthesis kernel module and Northbridge MCE fuzzer](https://github.com/xoreaxeaxeax/mchammer)
