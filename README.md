# awesome-hardware-fuzzing
A curated list of research and repositories on the novel technique of hardware fuzzing. For various reasons, most of existing works target RISC-V, with a few exceptions. 

[The Emergence of Hardware Fuzzing: A Critical Review of its Significance](https://arxiv.org/html/2403.12812v1)

[The Fuzz Odyssey: A Survey on Hardware Fuzzing Frameworks for Hardware Design Verification](https://dl.acm.org/doi/fullHtml/10.1145/3649476.3658697)

[Fuzzing Hardware Like Software](https://www.usenix.org/system/files/sec22-trippel.pdf) | [source code](https://github.com/googleinterns/hw-fuzzing)
						
[Encarsia: Evaluating CPU Fuzzers via Automatic Bug Injection](https://comsec.ethz.ch/research/hardware-design-security/encarsia/) | [source code](https://github.com/comsec-group/encarsia)

[Cascade: CPU Fuzzing via Intricate Program Generation](https://github.com/comsec-group/cascade-artifacts) | [source code](https://github.com/comsec-group/cascade-artifacts)

[Phantom Trails: Practical Pre-Silicon Discovery of Transient Data Leaks](https://download.vusec.net/papers/phantom-trails_sec25.pdf) | [source code](https://github.com/vusec/phantom-trails) and [artifacts](https://zenodo.org/records/14726711) and [this repo](https://github.com/vusec/hw-fuzzing-libafl)

[Lost and Found in Speculation: Hybrid Speculative Vulnerability Detection](https://arxiv.org/pdf/2410.22555) | Note: hardware fuzzing + IFT (Specure, not yet opensource)

[SpecDoctor: Differential Fuzz Testing to Find Transient Execution Vulnerabilities](https://jaewonhur.github.io/files/jwhur-specdoctor.pdf) | [source code](https://github.com/vusec/specdoctor)

[Revizor: Testing Black-box CPUs against Speculation Contracts](https://arxiv.org/abs/2105.06872) | [source code](https://github.com/microsoft/sca-fuzzer)
      
[SpecFuzz: Bringing Spectre-type vulnerabilities to the surface](https://arxiv.org/abs/1905.10311) | [source code](https://github.com/OleksiiOleksenko/SpecFuzz)

[Blacksmith: Scalable Rowhammering in the Frequency Domain](https://comsec.ethz.ch/wp-content/files/blacksmith_sp22.pdf) | [source code](https://github.com/comsec-group/blacksmith)

[ZenHammer: Rowhammer Attacks on AMD Zen-based Platforms](https://comsec.ethz.ch/research/dram/zenhammer/) | [source code](https://github.com/comsec-group/zenhammer)

[Posthammer](https://comsec.ethz.ch/research/dram/posthammer/) | [source code](https://github.com/comsec-group/posthammer/tree/main/native-fuzzer)

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

Pre-Silicon Hardware Fuzzing Toolkit | [source code](https://github.com/IntelLabs/PreSiFuzz)

[Sandsifter: the x86 processor fuzzer](https://www.blackhat.com/docs/us-17/thursday/us-17-Domas-Breaking-The-x86-ISA.pdf) | [source code](https://github.com/xoreaxeaxeax/sandsifter) [python3 port](https://github.com/jakiki6/sandsifter) [test runs repo](https://github.com/rigred/sandsifter-tests) [fork with some fixes](https://github.com/rigred/sandsifter) [Black Hat talk](https://www.youtube.com/watch?v=KrksBdWcZgQ)

Work inspired by sandsifter: [vmsifter](https://github.com/intel/vmsifter), [sandsifterOS](https://github.com/MikeHorn-git/sandsifterOS), [baresifter](https://github.com/blitz/baresifter)

[Uncovering Hidden Instructions in Armv8-A Implementations](https://rakeshk.folk.ntnu.no/pubs/armshaker_HASP20.pdf) | [source code for Armshaker](https://github.com/frestr/armshaker)

[TikTag: Breaking ARM's Memory Tagging Extension with Speculative Execution](https://arxiv.org/abs/2406.08719) | [source code](https://github.com/compsec-snu/tiktag)

[SiliFuzz: Fuzzing CPUs by proxy](https://storage.googleapis.com/gweb-research2023-media/pubtools/6405.pdf) | [source code](https://github.com/google/silifuzz) [Reptar CPU vulnerability](https://bughunters.google.com/blog/5997221712101376/the-reptar-cpu-vulnerability)

[PathFuzz: Broadening Fuzzing Horizons with Footprint Memory for CPUs](https://dl.acm.org/doi/10.1145/3649329.3655911) | [source code](https://github.com/OpenXiangShan/xfuzz)

[SSFuzz: Generating syntactic and semantic seeds for RISC-V Processors](https://dl.acm.org/doi/abs/10.1145/3649476.3658712) | [source code](https://github.com/ipasslab/SSFuzz) (not yet opensource?)

[Hot Fuzz: Assisting verification by fuzz testing microelectronic hardware](https://ieeexplore.ieee.org/document/10192176)

[HyperFuzzing for SoC Security Validation](https://ieeexplore.ieee.org/document/9256500) | [source code](https://github.com/skmuduli92/HyperFuzzer)

[Beyond Random Inputs: A Novel ML-Based Hardware Fuzzing](https://ieeexplore.ieee.org/abstract/document/10546625)

[RLFuzz: Accelerating Hardware Fuzzing with Deep Reinforcement Learning](https://www.bibsonomy.org/bibtex/2229ab60e60c1b371f6a6ac51f3e368af/raphael.goetz) | also see [HYDRANOS project](https://hydranos.eu/)

[TaintFuzzer: SoC Security Verification using Taint Inference-enabled Fuzzing](https://ieeexplore.ieee.org/document/10323726)

[SoCFuzzer: SoC Vulnerability Detection using Cost Function enabled Fuzz Testing](https://ieeexplore.ieee.org/document/10137024)

[Detection of Hardware Trojans in SystemC HLS Designs via Coverage-guided Fuzzing](https://agra.informatik.uni-bremen.de/doc/konf/2019DATE_Detection_of_Hardware_Trojans_in_SystemC_HLS_Designs_via_Coverage-guided_Fuzzing.pdf)

[MABFuzz: Multi-Armed Bandit Algorithms for Fuzzing Processors](https://ieeexplore.ieee.org/abstract/document/10546726)

[DirectFuzz: Automated Test Generation for RTL Designs using Directed Graybox Fuzzing](https://ieeexplore.ieee.org/document/9586289)

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

[Accelerating Hardware Verification with Graph Models](https://arxiv.org/pdf/2412.13374) | Note: unrelated to the same-name GraphFuzz[here](https://github.com/hgarrereyn/GraphFuzz) and [here](https://arxiv.org/pdf/2502.15160)

[Fuzzerfly Effect: Hardware Fuzzing for Memory Safety](https://ieeexplore.ieee.org/document/10462151)

[Trusting the Trust Anchor: Towards Detecting Cross-Layer Vulnerabilities with Hardware Fuzzing](https://dl.acm.org/doi/pdf/10.1145/3489517.3530638)

[JustSTART: How to Find an RSA Authentication Bypass on Xilinx UltraScale(+) with Fuzzing](https://arxiv.org/pdf/2402.09845) | [source code](https://github.com/emsec/confuzz)

[SPINALFUZZ: Coverage-Guided Fuzzing for SpinalHDL Designs](https://ics.jku.at/files/2022ETS_SpinalFuzz.pdf) | [source code](https://github.com/ics-jku/spinalfuzz)

[Veriﬁcation of Chisel Hardware Designs with ChiselVerify](https://kevinlaeufer.com/pdfs/chiselverify_and_chiseltest_formal_micpro.pdf) | [source code](https://github.com/chiselverify/chiselverify)

[Towards Functional Coverage-Driven Fuzzing for Chisel Designs](https://woset-workshop.github.io/PDFs/2021/a08.pdf) | [source code](https://github.com/chiselverify/chiselverify)

[Exploring Coverage Metrics in Hardware Fuzzing: A Comprehensive Analysis](https://dl.acm.org/doi/10.1145/3649476.3660386)

[Uniﬁed HW/SW Coverage: A Novel Metric to Boost Coverage-guided Fuzzing for Virtual Prototype based HW/SW Co-Veriﬁcation](https://hets.dfki.de/doc/konf/FDL2022_nbruns.pdf) | [source code for RISC-V virtual prototype](https://github.com/agra-uni-bremen/riscv-vp)

[Verismith: Verilog hardware synthesis tool fuzzer](https://github.com/ymherklotz/verismith)

Other methodologies (honestly they deserve their own separate list because it's not related to fuzzing but since I found them while researching fuzzing approaches I include them here for comparison sake and for my own convenience)

[Graph Neural Network based Hardware Trojan Detection at Intermediate Representative for SoC Platforms](https://dl.acm.org/doi/pdf/10.1145/3526241.3530827)

[TIUP : Effective Processor Verification with Tautology-Induced Universal Properties](https://dl.acm.org/doi/10.1109/ASP-DAC58780.2024.10473912) | [source code](https://github.com/CrazybinaryLi/TPV)

[Isadora: Auromated information-flow property generation for hardware security verification](https://kastner.ucsd.edu/wp-content/uploads/2022/11/admin/jcen2022-isadora.pdf) 

[Isadora: Automated Information Flow Property Generation for Hardware Designs](https://cd-public.github.io/papers/2021/ASHES2021.pdf) | [source code](https://github.com/cd-public/Isadora)

[CellIFT: Leveraging Cells for Scalable and Precise Dynamic Information Flow Tracking in RTL](https://comsec.ethz.ch/research/hardware-design-security/cellift/) | [source code](https://github.com/comsec-group/cellift-meta)

[ABSynthe: Automatic Blackbox Side-channel Synthesis on Commodity Microarchitectures](https://comsec.ethz.ch/wp-content/files/absynthe_ndss20.pdf) | [source code](https://github.com/vusec/absynthe)
   
[Osiris: Automated Discovery of Microarchitectural Side Channels](https://www.usenix.org/system/files/sec21-weber.pdf) | [source code](https://github.com/cispa/osiris)

                  
