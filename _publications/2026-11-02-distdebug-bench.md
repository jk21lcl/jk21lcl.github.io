---
title: "DistDebug-Bench: Can LLM Agents Diagnose Bugs in Distributed Systems?"
collection: publications
category: conferences
permalink: /publication/2026-11-02-distdebug-bench
excerpt: 'DistDebug-Bench is a benchmark for code-level diagnosis of real distributed-system bugs, testing whether agents can move from incident evidence to precise root-cause code.'
date: 2026-11-02
venue: 'NeurIPS, Evaluations and Datasets Track'
paperurl: 'https://arxiv.org/abs/2611.03523'
citation: 'Yuxuan Jiang, <b>Chenglin Liu</b>, John Rose, Mason Miller, Ruthesh Thavamani, Juntao Wu, Yinwei Huang, Jiahao Xu, and Peng Huang. (2026). &quot;DistDebug-Bench: Can LLM Agents Diagnose Bugs in Distributed Systems?&quot; In <i>Advances in Neural Information Processing Systems (NeurIPS 2026), Track on Evaluations and Datasets</i>.'
---

LLM agents show strong potential in software engineering tasks such as competitive programming and code synthesis. Existing benchmarks, however, largely focus on small-scale settings such as self-contained Python modules, leaving distributed systems, an essential class of production software, under-examined. We introduce DistDebug-Bench, a benchmark for evaluating agents' ability to diagnose complex-system failures at the code level. It curates 120 high-quality real-world bugs from 11 widely used distributed systems, spanning 5 programming languages and 10 failure patterns. Through an extensive evaluation of state-of-the-art LLMs and agents, we identify substantial gaps between current agents and real-world debugging tasks. A recurring gap is tunnel vision due to a lack of explicit reasoning structure and nondeterminism from inconsistent tool-use scope. The benchmark and evaluator are available at [https://github.com/OrderLab/distdebug-bench](https://github.com/OrderLab/distdebug-bench), with agent traces and a leaderboard at [https://distdebug.com](https://distdebug.com).
