---
title: "WATERFALL: Workflow for Adaptive Training with Evolutionary Reward Formulation and Automated Learning Loops"
collection: publications
permalink: /publication/2026-WATERFALL
excerpt: ''
date: 2026-12-07
venue: 'NeurIPS'
paperurl: 'TBD'
citation: 'Eleftherios Triantafyllidis, Filippos Christianos, Zhibin Li, and Bernd Bickel. WATERFALL: Workflow for Adaptive Training with Evolutionary Reward Formulation and Automated Learning Loops. In Advances in Neural Information Processing Systems (NeurIPS), 2026.'
---

Accepted and to be featured in NeurIPS 2026 in Australia, Sydney, December 2026.

<b>**Paper Abstract**</b>

Reward design remains a central bottleneck in reinforcement learning (RL), particularly in sparse-reward, long-horizon and partially observable settings requiring dependency chaining, memory, and deceptive affordance disambiguation. While recent foundation-model approaches reduce manual reward engineering, most assume goal-conditioning, task descriptions, expert demonstrations, or ground-truth metrics. These assumptions are particularly problematic in partially observable environments, where task-relevant objectives, affordances, and dynamics must be discovered through interaction rather than disclosed a priori. We formalise this problem setting by introducing WATERFALL, an iterative population-based workflow for automated reward discovery under the strict observability constraints inherent in POMDP environments, without relying on semantic task descriptors, pre-disclosed environment dynamics, goal conditioning, or ground-truth metrics. WATERFALL achieves this by first (i) synthesising diverse programmatic reward candidates via persona-conditioned generation, thereafter (ii) evaluating candidate behaviour from raw visual rollouts utilising a Swiss-system evolutionary tournament judged by vision-language models to identify elites, and finally (iii) leveraging longitudinal assessment histories to iteratively mutate, escalate, or prune candidates. We evaluate WATERFALL across fully observable and reveal-gated partially observable environments ranging from discrete to continuous, comparing against sparse-reward RL, intrinsic-motivation and foundation-model reward-synthesis baselines. Our results indicate that WATERFALL discovers and refines reward programs without access to privileged information, outperforming baselines that retain their native information advantages, most clearly in the POMDP regime. Extensive ablations also substantiate that visual evidence, tournament-based selection, and iterative refinement are jointly important. Enforcing this contract is what separates autonomous reward discovery from benchmark-privileged reward shaping.