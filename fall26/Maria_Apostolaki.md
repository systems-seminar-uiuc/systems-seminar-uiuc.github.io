# Making Network Knowledge First-Class: A Neurosymbolic Approach to Network Management 

## Abstract

As networks grow in scale and complexity, machine learning is becoming increasingly attractive for automation. Yet learned systems remain difficult to trust: they can fail in unexpected ways, are hard to reason about, and provide few guarantees. At the same time, networks are governed by substantial structure and domain knowledge—from physical constraints and protocol semantics to deployment policies and operational practices.

In this talk, I will argue for formalizing this network knowledge symbolically and making it a first-class component of autonomous network management. Through our work on AI-assisted generation, testing, and control, I will show how symbolic knowledge can complement learning in several ways: constraining generated outputs to feasible behaviors, making stress testing tractable despite enormous input spaces, and selectively guarding learned controllers at runtime without replacing or retraining them.

Together, these results point to a broader neurosymbolic design space for networked systems, in which learning provides adaptability and generalization while symbolic knowledge provides structure, constraints, and guarantees. I will conclude with a central challenge for this agenda: where should this symbolic knowledge come from? Much of the knowledge that governs real networks is implicit, fragmented, or not available in machine-readable form. I will discuss emerging approaches for deriving such knowledge from data, including our own work, as well as the remaining challenges in making this process reliable and scalable.

## Bio

Maria Apostolaki is an Assistant Professor of Electrical and Computer Engineering at Princeton University. Her research spans networking and security, with a focus on combining ML with formal methods for more trustworthy network management. She has received the NSF CAREER, Sloan Research Fellowship, Google Research Scholar Award, IETF/IRTF Applied Networking Research Prizes, and Commendations for Outstanding Teaching. Maria earned her PhD from ETH Zurich and was a postdoctoral researcher at Carnegie Mellon University before joining Princeton.
