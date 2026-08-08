# Ultra-Low-Latency LLM Inference on Wafer-Scale Accelerators 

## Abstract:

Wafer-scale accelerators offer hundreds of thousands of cores, large on-chip memory, and high-bandwidth interconnects, yet most LLM inference systems are still designed around GPU-centric assumptions about memory, communication, and parallel execution. This talk presents WaferLLM, an LLM inference system built for wafer-scale architectures. WaferLLM introduces wafer-scale prefill and decode parallelism, on-chip KV-cache management, and two high-performance kernels, MeshGEMM and MeshGEMV, for mapping LLM computation onto the wafer-scale fabric. On a Cerebras WSE-2 system, WaferLLM achieves 2,700 tokens per second for a single user — sub-millisecond per-token latency. I will also discuss our ongoing work toward making wafer-scale LLM serving even lower-latency, more cost-efficient, and easier to deploy for interactive reasoning and test-time compute.

## Bio:

Luo Mai is an Associate Professor at the University of Edinburgh. His research interests include computer systems, machine learning, and data management. At Edinburgh, he leads the Large-Scale Machine Learning Systems Group and co-directs the UK EPSRC Centre for Doctoral Training in Machine Learning Systems. He also leads key projects in the UK ARIA Scaling AI Compute programme, focusing on enabling next-generation AI infrastructure. He previously worked at Imperial College London and Microsoft Research, and received his PhD from Imperial College London with support from a Google Doctoral Fellowship.
