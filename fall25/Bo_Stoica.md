### Abstract

Mechanism level code analysis raises the abstraction unit of investigation from a single statement to a cohesive control code structure that implements a reusable policy, such as a task re-execution loop (e.g., retry), access control workflow (e.g., throttling), or a more generic state-machine logic. At this granularity, incorrect behavior is rarely attributed to a few lines of code. Instead it emerges from the aggregate evolution of the overall implementation of the mechanism itself, along with its state, decision rules, and possible execution limits on control and data paths.

In this talk, I'll walk you through several control mechanisms that are widely used in large-scale systems -- retry, task cancellation, and throttling logic -- highlight common bug patterns, and discuss techniques to find some of them. I'll also talk about one of my ongoing research projects -- finding bugs in throttling functionality -- for which I'm actively seeking PhD, MSc, and BSc students to collaborate with. While the project timeline is flexible, I aim to submit this work to a top-tier Systems conference in the first half of 2026 (e.g., SOSP, EuroSys, ASPLOS). If you'd like to learn more, feel free to reach out via email ( bastoica@illinois.edu ).

### About me

I'm a postdoc in the SysNet group hosted by Prof. Tianyin Xu. I recently graduated with a PhD from UChicago where I was advised by Prof. Shan Lu. My research focuses on systems reliability and performance analysis, with an emphasis on building (AI-guided) analysis tools to find correctness & performance bugs in modern software systems. I'm planning to apply for tenure-track faculty positions by 2027, so I'm incredibly excited to work side-by-side, mentor, and collaborate with students.
