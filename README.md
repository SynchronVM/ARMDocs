# ARMDocs

### Papers
- [Using ARM trustzone to build a trusted language runtime for mobile applications](https://dl.acm.org/doi/pdf/10.1145/2541940.2541949) - Trusted Language Runtime for mobile applications - very close to something that we would like to do (but Cortex-A9 processor, different from our use case of TrustZone-M)
- [Demystifying Arm TrustZone: A Comprehensive Survey](https://dl.acm.org/doi/abs/10.1145/3291047) - An extensive and very useful survey on TrustZone (must read)
- [Understanding the Prevailing Security Vulnerabilities in TrustZone-assisted TEE Systems](https://ieeexplore.ieee.org/abstract/document/9152801) - Why/How do security attacks still exist after TEEs? Looked like a good SoK paper addressing this question (maybe answers the "how" more).

### Videos
- [The ARM University Program, ARM Architecture Fundamentals](https://www.youtube.com/watch?v=7LqPJGnBPMM) - Very good basic introduction to the ARM architecture, assembly, etc.
- [May the Trust be with You: Empowering TrustZone-M with Multiple Trusted Environments](https://www.youtube.com/watch?v=kuMh1MXqJBw) - Introduces TrustZone-M slightly and describes the [uTango](https://arxiv.org/pdf/2102.03625.pdf) TEE on it.
- [Using TrustZone on Cortex-M23 and Cortex-M33](https://www.youtube.com/watch?v=0LpCEwSfA0s) - Shows a demo of the generated assembly and a walkthrough across the secure and non-secure memory regions while executing a sample application. Uses some proprietary tools like Keil.
- [Designing a Trusted Execution environment in Zephyr OS](https://www.youtube.com/watch?v=HZiZz3Rr4sg) - Zephyr's TrustZone maintainer talks about the changes in Zephyr to support TrustZone. Fairly high-level.
- [Zephyr and Trusted Execution Environments](https://www.youtube.com/watch?v=mMnxdZP5_iw) - A user-experience talk on Zephyr's TrustZone APIs. Again no code shown, very high-level talk.
- [Enclaves in OS/runtime](https://www.youtube.com/watch?v=shTEOoySk1I) - Very good introduction (in the context of Intel SGX)

### Official Documentation from ARM
- [Using TrustZone on Armv8-M](https://www.keil.com/appnotes/files/apnt_291.pdf)

### Language Abstractions for Trusted Code
- [Secured Routines: Language-based Construction of Trusted Execution Environments](https://www.usenix.org/conference/atc19/presentation/ghosn) - Contains paper, video, etc. Very relevant work.
- [Enclosure: language-based restriction of untrusted libraries](https://dl.acm.org/doi/abs/10.1145/3445814.3446728) - Uses Intel SGX and more advanced support from Intel, which might not be entirely relevant. But the runtime abstractions are very similar to what we are thinking about.
- [Trust as a Programming Primitive](https://infoscience.epfl.ch/record/289120) - Adrien Ghosn's PhD thesis (author of the two papers above). (Must Read)
- [Uranus: Simple, Efficient SGX Programming and its Applications](https://dl.acm.org/doi/abs/10.1145/3320269.3384763) - Java annotations based abstractions.
- [JE Programming Language](https://prg-grp.github.io/je-lang/) - [Video](https://www.youtube.com/watch?v=6fPYfUjXcGg)
