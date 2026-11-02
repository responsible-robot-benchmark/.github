# ResponsibleRobotBench

**Benchmarking risk-aware task-level decision making for robotic manipulation with large multimodal models.**

[Project website](https://responsible-robot-benchmark.github.io/) · [Open-source code](https://github.com/responsible-robot-benchmark/ResponsibleRobotBench) · [Paper and appendix](https://responsible-robot-benchmark.github.io/downloads/manuscript.pdf)

**Benchmark design.** We introduce ResponsibleRobotBench, a benchmark of 23 manipulation task configurations spanning conditionally safe tasks, hazard-free controls, and inherently unsafe goals. Task goals and safety conditions are specified and checked separately, with task variants varying hazard presence and grasping requirements.

**Empirical analysis.** We evaluate five LMMs through episode-level analyses linking hazard predictions, mitigation choices, action prerequisites, and outcomes. The results reveal failures after correct hazard recognition, divergence between terminal safety and safe completion, and differences between assistance availability and recovery after actual help requests.

**Open-source implementation.** We release the benchmark implementation, a modular LMM planning system supporting skill, pose, and robot-API code interfaces with 12 input configurations, and tools for collecting motion-planner demonstrations.

- **Use the benchmark:** [installation](https://github.com/responsible-robot-benchmark/ResponsibleRobotBench/blob/main/docs/installation.md), [data collection](https://github.com/responsible-robot-benchmark/ResponsibleRobotBench/blob/main/docs/dataset.md), and [evaluation](https://github.com/responsible-robot-benchmark/ResponsibleRobotBench/blob/main/docs/evaluation.md).
- **Explore the demonstrations:** [simulation task gallery](https://responsible-robot-benchmark.github.io/#simulation) and [Franka / UR5e experiments](https://responsible-robot-benchmark.github.io/#real-robot).
- **Read the study:** [full paper with supplementary material](https://responsible-robot-benchmark.github.io/downloads/manuscript.pdf).

Lei Zhang, Ju Dong, Kaixin Bai, Minheng Ni, Yu Fu, Zoltán-Csaba Márton, Zhaopeng Chen, and Jianwei Zhang.
