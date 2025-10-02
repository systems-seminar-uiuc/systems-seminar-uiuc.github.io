### Abstract

Mechanism level analysis raises the abstraction unit of analysis from a single statement to a cohesive control code structure that implements a reusable policy, such as a task re-execution loop (e.g., retry), access control workflow (e.g., throttling), or a more generic state-machine logic. At this granularity, incorrect behavior is rarely attributed to a single line of code. Instead it emerges from the aggregate evolution of the overall implementation of the mechanism, along with its state, decision rules, and possible execution limits on control and data paths.

In this talk, I'll walk you through several widely-used control mechanisms -- retry, task cancellation, and throttling logic -- highlight common bug patterns, and discuss techniques to find them. Currently, I'm working on techniques to find bugs in throttling mechanisms and actively seeking PhD, MSc, and BSc students to collaborate with. While the project timeline is flexible, I aim to submit this work to a top-tier Systems conference in the first half of 2026 (e.g., SOSP, EuroSys, ASPLOS).

### About me

I'm a postdoc in the SysNet group hosted by Prof. Tianyin Xu. I recently obtained my PhD at UChicago advised by Prof. Shan Lu. My research focuses on systems relability and performance analysis, with an emphasis on building (AI-guided) analysis tools to find correctness/performance bugs in modern software systems. I'm planning to apply for tenure-track faculty positions in 1-2 years, so I'm more than happy to work side-by-side, mentor, and collaborate with students.
