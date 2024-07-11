---
title: "Feasible Reachable Policy Iteration"
collection: publications
permalink: /publication/2024-05-01-Feasible Reachable Policy Iteration
excerpt: 'The goal-reaching tasks with safety constraints are common control problems in real world, such as intelligent driving and robot manipulation. The difficulty of this kind of problem comes from the exploration termination caused by safety constraints and the sparse rewards caused by goals. The existing safe RL avoids unsafe exploration by restricting the search space to a feasible region, the essence of which is the pruning of the search space. However, there are still many ineffective explorations in the feasible region because of the ignorance of the goals. Our approach considers both safety and goals; the policy space pruning is achieved by a function called feasible reachable function, which describes whether there is a policy to make the agent safely reach the goals in the finite time domain. This function naturally satisfies the self-consistent condition and the risky Bellman equation, which can be solved by the fixed point iteration method. On this basis, we propose feasible reachable policy iteration (FRPI), which is divided into three steps: policy evaluation, region expansion, and policy improvement. In the region expansion step, by using the information of agent to reach the goals, the convergence of the feasible region is accelerated, and simultaneously a smaller feasible reachable region is identified. The experimental results verify the effectiveness of the proposed FR function in both improving the convergence speed of better or comparable performance without sacrificing safety and identifying a smaller policy space with higher sample efficiency.'
date: 2024-05-01
venue: 'The 41st International Conference on Machine Learning (ICML 2024)'
projecturl: 'https://jackqin007.github.io/FRPI/'
slidesurl: 'https://openreview.net/pdf?id=ks8qSwkkuZ'
citation: '@inproceedings{qinfeasible,
title={Feasible Reachable Policy Iteration},
author={Qin, Shentao and Yang, Yujie and Mu, Yao and Li, Jie and Zou, Wenjun and Li, Shengbo Eben and Duan, Jingliang},
booktitle={Forty-first International Conference on Machine Learning},
year={2024},
url={https://openreview.net/pdf?id=ks8qSwkkuZ}
}'
---


The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.