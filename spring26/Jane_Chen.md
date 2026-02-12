# ML for Systems in the Real World: Challenges Beyond Training the Models

## Abstract:

There has been growing interest in applying machine learning to improve system performance, particularly because of its capability of adapting to heterogeneous and dynamic environments. But making ML effective in real systems requires addressing challenges that go well beyond training a model. In this talk, I will present two pieces of my work that tackle fundamental obstacles in this space.

The first challenge is accurate state representation. The performance of learned controllers depends heavily on the fidelity of their input features. Yet, current network controllers rely on hand-made instantaneous or running-average metrics that provide coarse, delayed, or incomplete views of the true network state. I will describe UNUM, which constructs system-wide state embeddings to enable higher-quality and coordinated policy decisions.

The second challenge is efficient and adaptable deployment. For many system problems, constructing a single large learned model is impractical or unnecessarily costly. I will present Darwin, a neural-aided expert selection system that makes ML-driven policies practical by balancing instance-optimal decisions with generalization and runtime overhead.

## Bio:

Jiayi (Jane) Chen is a fifth-year Ph.D. student in Computer Science at The University of Texas at Austin, advised by Professor Aditya Akella and Professor Sanjay Shakkottai. Her research lies at the intersection of machine learning, networks, and systems, with a focus on applying learning-based techniques to improve the performance of network systems. She is part of the Learning-Directed Operating System (LDOS) expedition. Her work has appeared in SIGCOMM, NSDI, NeurIPS, HotOS.

