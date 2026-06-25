---
layout: page
title: FedChain
description: Proof-of-stake blockchain for secure federated learning.
importance: 3
---

FedChain is my bachelor's thesis project on blockchain-based federated learning. It investigates limitations in prior approaches and implements a proof-of-stake protocol designed to remain resilient to malicious model updates.

The system uses bidirectional gRPC for peer-to-peer communication, asymmetric cryptography for message integrity, and PyTorch for federated model training.

<p>
  <a href="{{ '/assets/pdf/FedChain_Thesis.pdf' | relative_url }}"><strong>Read the thesis</strong></a>
  ·
  <a href="https://github.com/ale18V/FedChain"><strong>View the code</strong></a>
</p>

<object
  data="{{ '/assets/pdf/FedChain_Thesis.pdf' | relative_url }}"
  type="application/pdf"
  width="100%"
  height="760"
  aria-label="FedChain bachelor thesis"
>
  <p>Your browser cannot display the PDF inline. <a href="{{ '/assets/pdf/FedChain_Thesis.pdf' | relative_url }}">Download the thesis.</a></p>
</object>
