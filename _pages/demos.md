---
permalink: /demos/
title: "Demos"
author_profile: true
classes: wide
---

Live interactive demos from our research on trustworthy AI systems.

<div class="demo-grid">

<div class="demo-card" data-aos="fade-up">
  <h3>GuardNet <span class="demo-tag">Live</span></h3>
  <p>
    A pre-inference graph-attention defense that detects both jailbreak and prompt-leakage adversarial
    prompts <em>before</em> they reach the target LLM. GuardNet constructs hybrid token graphs
    integrating sequential, syntactic, and attention-derived relations, then applies Graph Neural
    Networks for prompt-level detection and token-level localization — with no access to model weights.
  </p>
  <a class="demo-btn" href="https://javad-forough.github.io/GuardNet/" target="_blank" rel="noopener">Launch GuardNet Demo ↗</a>
</div>

<div class="demo-card" data-aos="fade-up" data-aos-delay="100">
  <h3>DynaNoise <span class="demo-tag">Live</span></h3>
  <p>
    An adaptive inference-time defense against membership inference attacks. DynaNoise modulates
    injected noise based on per-query sensitivity estimated via Shannon entropy, preserving model
    utility while substantially reducing attack success rates — outperforming static defenses like
    DP-SGD and MemGuard across CIFAR-10, ImageNet-10, and SST-2.
  </p>
  <a class="demo-btn" href="https://javad-forough.github.io/DynaNoise-Demo/" target="_blank" rel="noopener">Launch DynaNoise Demo ↗</a>
</div>

</div>
