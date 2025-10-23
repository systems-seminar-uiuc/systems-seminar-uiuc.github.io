# METIS: Fast Quality-Aware RAG Systems with Configuration Adaptation (SOSP'25)

## Abstract

RAG (Retrieval Augmented Generation) allows LLMs (large language models) to generate better responses with external knowledge, but using more external knowledge causes higher response delay. Prior work focuses either on reducing the response delay (e.g., better scheduling of RAG queries) or on maximizing quality (e.g., tuning the RAG workflow), but they fall short in systematically balancing the tradeoff between the delay and quality of RAG responses. To balance both quality and response delay, this paper presents METIS, the first RAG system that jointly schedules queries and adapts the key RAG configurations of each query, such as the number of retrieved text chunks and synthesis methods. Using four popular RAG-QA datasets, we show that compared to the state-of-the-art RAG optimization schemes, METIS reduces the generation latency by 1.64 – 2.54× without sacrificing generation quality.

## Short Bio

Siddhant is a third-year PhD student in Computer Science at the University of Chicago, advised by Junchen Jiang and Nick Feamster. His research interests lie in efficient serving systems for Large Language Models, focusing on Compound-AI systems like RAG and also machine learning methods for performance improvement in systems and networks.
