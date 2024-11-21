## Paper List

#### Sanctum: Minimal Hardware Extensions for Strong Software Isolation
- **Authors**: Victor Costan, Ilia Lebedev, and Srinivas Devadas
- **Link**: https://www.usenix.org/conference/usenixsecurity16/technical-sessions/presentation/costan

#### A Formal Foundation for Secure Remote Execution of Enclaves
- **Link**: https://dl.acm.org/doi/pdf/10.1145/3133956.3134098
- Formal verification of SGX and Sanctum?

#### Intel SGX Explained
- **Authors**: Victor Costan and Srinivas Devadas
- **Link**: https://eprint.iacr.org/2016/086.pdf
- **Interesting**: Cracked multiple times, for example by SGXSpectra, a speculative execution exploit: https://ieeexplore.ieee.org/document/8806740

#### Keystone: An Open Framework for Architecting Trusted Execution Environments
- **Link**: http://docs.keystone-enclave.org/en/latest/Getting-Started/How-Keystone-Works/Keystone-Basics.html
- **Interesting**: https://keystone-enclave.org/files/keystone-risc-v-summit.pdf
- **Another Link**: https://keystone-enclave.org/2019/07/22/Keystone-Paper.html
- **One More Link**: https://keystone-enclave.org/
- https://n.ethz.ch/~sshivaji/publications/keystone_eurosys20.pdf
- **Experiments on Spectre like side channel attacks**: https://www.sciencedirect.com/science/article/pii/S0045790622007613 (this was not successful, keystone protected against them)

#### Demystifying Arm TrustZone: A Comprehensive Survey
- **Link**: https://www.dpss.inesc-id.pt/~nsantos/papers/pinto_acsur19.pdf

#### Secure and Trusted Execution: Past, Present and Future – A Critical Review in the Context of the Internet of Things and Cyber-Physical Systems
- **Link**: https://core.ac.uk/download/pdf/77298166.pdf

#### Trusted Execution Environment: What It Is, and What It Is Not
- **Link**: https://hal.science/hal-01246364/file/trustcom_2015_tee_what_it_is_what_it_is_not.pdf

#### A survey on the (in)security of Trusted Execution Environments
- **Link**: https://www.sciencedirect.com/science/article/pii/S0167404823000901
- Really interesting because the main focus is the attack and not the structure of the TEE itself

#### IIoTEED: An Enhanced, Trusted Execution Environment for Industrial IoT Edge Devices
- **Link**: https://ieeexplore.ieee.org/document/7839870
- Sounds interesting, sadly i cant get access :/ (even tried fu vpn!)

#### Sancus: Low-cost Trustworthy Extensible Networked Devices with a Zero-software Trusted Computing Base 
- **Link**: https://www.usenix.org/conference/usenixsecurity13/technical-sessions/presentation/noorman

#### Survey on Trusted Execution Environments
- **Link**: https://www.net.in.tum.de/fileadmin/TUM/NET/NET-2022-07-1/NET-2022-07-1_05.pdf

#### Fortress: Securing IoT Peripherals with Trusted Execution Environments
- **Link**: https://arxiv.org/abs/2312.02542v2
- Really recent, only 1 citation.

#### hardware based trusted computing architectures for isolation and attestation
- **Link**: https://ieeexplore.ieee.org/document/7807249
- Nice summary paper

#### A Security Architecture for RISC-V based IoT Devices
- **Link**: https://past.date-conference.com/proceedings-archive/2019/pdf/1077.pdf

#### Secure Boot and Remote Attestation in the Sanctum Processor
- **Link**: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8429295
- Bootloader ohne hardware? Iwi generieren die aus dünner Luft einen "eliptical curve key" zum verifizieren

#### Systematic Literature Review on the Use of Trusted Execution Environments to Protect Cloud/Fog-Based Internet of Things Applications
- **Link**: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9445012
- Exhaustive Literature Review

#### MyTEE: Own the Trusted Execution Environment on Embedded Devices
- **Link**: https://www.ndss-symposium.org/wp-content/uploads/2023/02/ndss2023_s41_paper.pdf
- Really interesting, assumes minimal hardware (only basic TrustZone primitives) and build TEE on that

#### When Oblivious is Not: Attacks against OPAM
- **Link**: https://www.usenix.org/conference/woot20/presentation/roy

#### Komodo: Using verification to disentangle secure-enclave hardware from software
- **Link**: https://www.microsoft.com/en-us/research/wp-content/uploads/2017/10/komodo.pdf

## Not focused

#### Formal Verification of a Trusted Execution Environment-Based Architecture for IoT Applications
- **Link**: https://ieeexplore.ieee.org/abstract/document/9424184
- Cant access

#### Systematic Literature Review on the Use of Trusted Execution Environments to Protect Cloud/Fog-Based Internet of Things Applications
- **Link**: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9445012
- **Reason**: Too broad, is just an overview of mainly arm trustzone and Intel SGX, which i want to cover more in detail anyways

#### Performance Analysis of Scientific Computing Workloads on Trusted Execution Environments
- **Link**: https://arxiv.org/abs/2010.13216
- **Reason**: Sounds very interesting, often performance is not the main focus. However, this is completly in the other direction from IoT. It focuses on high performance computing

## Comments

- Sancus
- Sanctum
- keystone for RISC-V
- 