---
title: "Stochastic Trajectory Optimization for Demonstration Imitation"
collection: publications
permalink: /publication/2024-08-03-paper-arXiv24-stochastic-trajectory-optimization
excerpt: 'In this paper, we introduce Stochastic Trajectory Optimization for Demonstration Imitation (STODI), a trajectory optimization framework for robots to imitate the shape of demonstration trajectories with improved dynamic performance.'
date: 2024-08-03
venue: 'arxiv'
paperurl: 'https://arxiv.org/pdf/2408.03131'
---
Humans often learn new skills by imitating the experts and gradually developing their proficiency. In this work, we introduce Stochastic Trajectory Optimization for Demonstration Imitation (STODI), a trajectory optimization framework for robots to imitate the shape of demonstration trajectories with improved dynamic performance. Consistent with the human learning process, demonstration imitation serves as an initial step, while trajectory optimization aims to enhance robot motion performance. By generating random noise and constructing proper cost functions, the STODI effectively explores and exploits generated noisy trajectories while preserving the demonstration shape characteristics. We employ three metrics to measure the similarity of trajectories in both the time and frequency domains to help with demonstration imitation. Theoretical analysis reveals relationships among these metrics, emphasizing the benefits of frequency-domain analysis for specific tasks. Experiments on a 7-DOF robotic arm in the PyBullet simulator validate the efficacy of the STODI framework, showcasing the improved optimization performance and stability compared to previous methods. The source code can be found at [ming-bot/STODI](https://github.com/ming-bot/STODI).

[Download paper here](http://zitwng.github.io/files/paper_arXiv24_stochastic_trajectory_optimization.pdf)

Recommended citation: Ming, C., Wang, Z., Zhang, B., Duan, X., & He, J. (2024). Stochastic Trajectory Optimization for Demonstration Imitation. arXiv preprint arXiv:2408.03131.
