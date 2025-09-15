# LiquidCache: Efficient Pushdown Caching for Cloud-Native Data Analytics

## Abstract

We present LiquidCache, a novel pushdown-based disaggregated
caching system that evaluates filters on cache servers before trans-
mitting data to compute nodes. Our key observation is that data
decoding, not filter evaluation, is the primary bottleneck in exist-
ing systems. To address this challenge, we transcode Parquet data
into a lightweight “Liquid” format optimized for caching and fil-
ter evaluation. This format is co-designed with filter evaluation
semantics to enable selective decoding, late filter materialization,
and encoding-aware filter evaluation, delivering low decoding costs
while preserving high compression ratios. The “Liquid” format ex-
ists exclusively in the cache, allowing easy adoption without break-
ing ecosystem compatibility. Through integration with Apache
DataFusion and evaluation with ClickBench and TPC-H, we demon-
strate that LiquidCache reduces cache CPU time by up to 10× with-
out increasing memory footprint, and reduces network traffic by
two orders of magnitudes compared to non-pushdown systems.

## Bio

Xiangpeng Hao (https://xiangpeng.systems/) is a fifth-year PhD student
at UW-Madison advised by Andrea Arpaci-Dusseau and Remzi H. Arpaci-Dusseau.
His research focuses on LiquidCache (https://github.com/XiangpengHao/liquid-cache), a
distributed caching system for cloud-native analytical workloads.
LiquidCache has been actively tested in production by organizations such as 
Pydantic, OpenObserve, and AWS internal systems.
He has also self-raised research funding from InfluxData, SpiralDB, and Bauplan to support his PhD work.
