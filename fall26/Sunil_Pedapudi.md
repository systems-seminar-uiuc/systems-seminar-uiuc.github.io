# Polarities of an agentic data cloud: data, compute, and trust 

## Abstract

Large-scale data systems are shifting from reactive query engines to closed-loop systems of action, where agents perceive streams, reason over petabyte history, and commit distributed transactions. Building an agentic data cloud around these closed loops exposes three pairs of opposing forces that intensify simultaneously:

1. Data abundance and trajectory scarcity: Event streams, multimodal files, and logs accumulate toward zettabyte scale, yet carry low marginal signal per byte. Conversely, verifiable trajectories for reinforcement learning and task-specific evaluations remain scarce because privacy considerations restrict trace reuse and passive logs omit counterfactual actions.

2. Reasoning capability and context-window cost: Frontier LLMs can plan workflows and interpret unstructured inputs, yet funneling tables or streams through context windows is prohibitive in time and cost. Under concurrent agent fan-out, attention over records consumes orders of magnitude more time and HBM bandwidth than columnar or stream operators. Agents must therefore plan rather than scan, synthesizing SQL, dataflows, and sketches for distributed engines while reserving model inference for ambiguous records.

3. Semantic understanding and least-privilege isolation: Verifying join cardinality, temporal windows, consistency, and standard operating procedures in agent-authored queries and transactions requires shared context across schemas, documentation, lineage, and query histories. Simultaneously, table, row, and column policies forbid direct or indirect access beyond a user’s permissions. Shared catalogs, embeddings, summaries, and delegated actions risk leaking restricted facts across those policies, whereas per-user isolation fragments context and blocks precomputation.

These three polarities span data systems, system architecture, programming languages, and security. Open problems include filtering low-signal streams and simulating verifiable RL environments, co-optimizing reasoning with distributed execution, and verifying semantic correctness under least-privilege isolation.

## Bio

Sunil Pedapudi is a Principal Engineer at Google, where he leads the Data Cloud Frontier AI team. His applied research spans automated hill-climbing, high-performance inference, simulation and evaluation, and semantic understanding across large-scale analytical systems. Over the preceding decade, he led architecture and engineering for petascale distributed processing systems, including Google’s Flume and Cloud Dataflow. He studied Computer Science at UC Berkeley.
