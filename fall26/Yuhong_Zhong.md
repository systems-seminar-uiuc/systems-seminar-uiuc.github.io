# The Agentic CPU Cloud: From Servers to Rack-Scale Resource Pools

## Abstract

As AI agents increasingly shift work from GPUs to CPU-intensive tool use, CPU capacity is becoming a new bottleneck. This growing CPU demand comes in the form of thousands, or eventually millions, of isolated agent environments. But the cloud was designed for long-running services, not for launching and tearing down sandbox fleets at this scale. We claim that making these workloads economical requires a radical redesign of cloud infrastructure around rack-scale resource pooling rather than fixed server boundaries.

In this talk, we will describe three projects that explore key pieces of this architecture. Skyfall uses CXL to build a shared memory pool across servers, allowing both memory capacity to be provisioned independently of individual machines and us to freely move VMs across servers with virtually no overhead or downtime. Oasis extends this idea to PCIe devices, using the CXL memory fabric as a software datapath for pooling resources such as NICs without requiring expensive PCIe switching hardware. Octopus shows how to scale these ideas beyond small pools, using sparse CXL topologies to connect substantially larger numbers of servers without relying on large CXL switches.

Together, these systems point toward a different kind of cloud built around rack-scale pools of compute, memory, networking, and storage that can be assembled dynamically around each workload. This architecture is particularly well matched to agentic sandboxes, where high density, fast provisioning, and efficient resource sharing directly translate into lower cost and greater scale. If you are trying to run very large numbers of agent sandboxes efficiently, come talk to us.

## Bio

Yuhong Zhong is a fourth-year PhD candidate in Computer Science at Columbia University, advised by Asaf Cidon. His recent research focuses on breaking the CPU bottleneck of AI agents by using CXL to build rack-integrated systems that pool and dynamically compose compute, memory, and I/O resources. His work was recognized with the Best Paper Award at OSDI ’22.
