---
layout: page
title: BanditDL
description: Communication-efficient neighbor sampling in decentralized learning.
importance: 1
---

Uniformly sampling a small number of peers is a strong baseline for communication-efficient decentralized learning: it reduces message complexity while retaining convergence and robustness guarantees. BanditDL asks whether adaptive neighbor sampling can improve on this baseline under heterogeneous data, without increasing the communication budget.

The project models peer selection as a combinatorial semi-bandit problem and compares uniform sampling with ε-greedy, EXP3, combinatorial UCB, combinatorial Thompson sampling, and discounted variants across several heterogeneous data partitions. The experiments show a personalization-generalization frontier: adaptive samplers can exploit latent structure, but aggressive in-cluster sampling does not always improve global performance.

<p>
  <a href="{{ '/assets/pdf/BanditDL_Report.pdf' | relative_url }}"><strong>Read the report</strong></a>
  ·
  <a href="https://github.com/ale18V/BanditDL"><strong>View the code</strong></a>
</p>

<object
  data="{{ '/assets/pdf/BanditDL_Report.pdf' | relative_url }}"
  type="application/pdf"
  width="100%"
  height="760"
  aria-label="BanditDL report"
>
  <p>Your browser cannot display the PDF inline. <a href="{{ '/assets/pdf/BanditDL_Report.pdf' | relative_url }}">Download the report.</a></p>
</object>
