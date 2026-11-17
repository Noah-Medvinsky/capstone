---
title: Capstone
permalink: /
---

<span class="eyebrow">CSS 497 Capstone · Autumn 2026</span>

# Motif Models vs. DNA Language Models for Predicting Transcription Factor Binding

<p class="lead">Proteins called transcription factors switch genes on and off by binding to short DNA "words" called motifs. My capstone reproduces part of Tang et al. (2025) and tests whether a pretrained DNA language model, HyenaDNA, predicts where these proteins bind better than a classical motif scan (PWM) and a simple convolutional neural network.</p>

<div class="stats">
  <div class="stat"><b>10</b><span>transcription factors</span></div>
  <div class="stat"><b>3</b><span>methods compared</span></div>
  <div class="stat"><b>60</b><span>model training runs</span></div>
  <div class="stat"><b>59</b><span>automated tests</span></div>
</div>

## Explore the portfolio

<ul class="card-grid">
  <li><a class="card" href="{{ '/users-perspective/' | relative_url }}">
    <h3>User’s Perspective</h3>
    <p>What the project is, the problem it answers, and what you get from it.</p>
    <span class="go">Read →</span></a></li>
  <li><a class="card" href="{{ '/developers-perspective/' | relative_url }}">
    <h3>Developer’s Perspective</h3>
    <p>How the project was built, theme by theme, from the data to the error analysis.</p>
    <span class="go">Read →</span></a></li>
  <li><a class="card" href="{{ '/my-perspective/' | relative_url }}">
    <h3>My Perspective</h3>
    <p>What this capstone taught me about myself as a researcher and developer.</p>
    <span class="go">Read →</span></a></li>
  <li><a class="card" href="{{ '/annotated-bibliography/' | relative_url }}">
    <h3>Annotated Bibliography</h3>
    <p>The papers, databases, and tools I learned from, grouped by theme.</p>
    <span class="go">Read →</span></a></li>
</ul>

<figure>
  <img src="{{ '/assets/img/pwm-vs-cnn.png' | relative_url }}"
       alt="Dot plot of test AUROC for 10 transcription factors. For every factor, the one-hot CNN scores higher than the PWM motif scan. The gap is small for ATF2 and CTCF, which have strong motifs, and large for BACH1, where the PWM scores below random guessing.">
  <figcaption>The convolutional neural network beats the motif scan on all 10 transcription factors. The gap is smallest for factors with a strong, specific motif, such as CTCF and ATF2.</figcaption>
</figure>
