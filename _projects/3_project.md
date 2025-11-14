---
layout: page
title: Energy-efficient Scaled Spintronics for Probabilistic Computing
#description: with background image
img: assets/img/project3_cover.jpg
importance: 1
category: Spintronics
related_publications: false
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project3_1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Image reference: Chowdhury, S. et al. (2023).IEEE J. Explor. Solid-State Comput. Devices Circuits 9, 1–11
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/project3_2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left:  Charge-based p-bits; reference: J. Daniel et al. (2024) Nat. Commun.
    Right: Spin-based p-bits; reference: S. Bunaiyan, S. Datta, and K. Y. Camsari, (Dec. 2023) arXiv: arXiv:2312.01477.
</div>

As conventional transistor scaling slows and modern computing demands—especially in AI and machine learning—continue to rise, new hardware paradigms are needed to overcome the limitations of deterministic, charge-based logic. We explore spintronic devices for probabilistic computing as a fundamentally different direction for energy-efficient computation. Unlike traditional bits, spintronic probabilistic bits (p-bits) leverage the intrinsic fluctuations of low-barrier nanomagnets (LBMs) and their coupling through spin transport in nonmagnetic channels, enabling stochastic switching dynamics that naturally support sampling, inference, and optimization.

These magnetic devices naturally “flip” between states in a random but controllable way, making them ideal for probabilistic computing—a style of computation that embraces randomness to solve complex problems more efficiently. Our work focuses on two complementary types of p-bits.
1. Charge-based p-bits, built using CMOS-like electronics, are used to implement the Ising model, a mathematical framework widely used for optimization and probabilistic inference.
2. Spin-based p-bits, which leverage spin currents and magnetic interactions, can represent continuous states and are used to build systems based on the Heisenberg model, enabling richer, more expressive forms of computation.

This includes studying the collective behavior of coupled LBMs governed by stochastic Landau–Lifshitz–Gilbert dynamics, and experimentally realizing on-chip p-bit cores that demonstrate probabilistic computation.

Through a combination of device physics, spin transport engineering, and system-level integration, this project aims to build a scalable hardware foundation for probabilistic and neuromorphic computing, offering advantages in speed, power efficiency, and functional flexibility compared to conventional CMOS logic.

This research is supported by the U.S. Navy and the National Science Foundation (NSF).


- J. Daniel, Z. Sun, X. Zhang, Y. Tan, N. Dilley, Z. Chen, J. Appenzeller, “Experimental demonstration of an on-chip p-bit core based on stochastic magnetic tunnel junctions and 2D MoS₂ transistors,” Nat. Commun., vol. 15, no. 1, p. 4098, 2024.

- Y. Tan*, R. Tripathi*, J. Appenzeller, Z. Chen, “Nonlocal Detection of Vector Spin Accumulation in Graphene for Probabilistic Computing,” MRS Fall, 2024.



