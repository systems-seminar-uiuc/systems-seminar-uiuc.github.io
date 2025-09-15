# Transparently Enhancing Applications through Operating System Architectures and Mechanisms


## Abstract

Operating systems are the foundational software that all modern applications rely on, bridging applications and hardware. As both applications and hardware have rapidly evolved over the past decades, it has become imperative for operating systems to identify and support new demands without breaking existing applications. My research focuses on the progressive evolution of operating systems to achieve high performance, stronger reliability, and better customization, with an emphasis on new architectures and mechanisms.

In this talk, I will present our work on evolving operating system architectures for high performance, where we build a filesystem, uFS, as a semi-microkernel filesystem running in userspace for performance while coexisting with commodity OSes. I will then introduce Ananke, a new recovery mechanism that enables transparent runtime recovery from filesystem failures, providing stronger reliability guarantees. Finally, I will present our recent work, Midas, which introduces a systematic tunability management framework that enables dynamic runtime tuning of previously untunable logic – without kernel modification or application disruption – while supporting rich customization semantics.


## Speaker bio

Jing Liu is a Senior Researcher at Microsoft Research Asia. She received her Ph.D. in 2024 from the University of Wisconsin–Madison, advised by Prof. Andrea Arpaci-Dusseau and Prof. Remzi Arpaci-Dusseau. Jing’s research focuses on evolving operating systems, as well as file and storage systems, to meet modern demands. She has received the Erik Riedel Best Paper Award at FAST 2025 and a Meta PhD Research Fellowship in 2022.

