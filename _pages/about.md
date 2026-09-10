---
layout: home
permalink: /
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<section class="home-hero">
  <div class="home-hero__copy">
    <p class="eyebrow">Machine learning · Memory · NeuroAI</p>
    <h1>I study memory across artificial and biological systems.</h1>
    <p class="home-hero__lead">
      I am a PhD candidate at the <a href="https://www.mpi-sws.org/">Max Planck Institute for Software Systems (MPI-SWS)</a> and <a href="https://www.uni-saarland.de/">Saarland University</a>, advised by <a href="https://mtoneva.com/">Mariya Toneva</a> and <a href="https://ivaleram.github.io/">Isabel Valera</a>. My research asks how intelligent systems encode experience in context, reinstate that context during remembering, and control how past experience shapes ongoing computation. I use artificial models as experimentally tractable systems for studying these mechanisms and connect them to questions from human memory and neuroscience.
    </p>
    <p class="home-hero__meta">
      Member of the RTG <a href="https://www.neuroexplicit.org/">Neuroexplicit Models of Language, Vision, and Action</a> · Saarbrücken, Germany
    </p>
    <div class="home-actions">
      <a class="button button--primary" href="/research/">Research</a>
      <a class="button" href="/publications/">Publications</a>
      <a class="button button--quiet" href="/background/">Background</a>
      <a class="button button--quiet" href="{{ base_path }}/cv/">CV</a>
    </div>
  </div>
  <div class="home-hero__portrait" aria-label="Portrait of Mathis Pink">
    <img src="/images/profile.jpg" alt="Mathis Pink">
  </div>
</section>

<section class="home-section home-section--intro">
  <div class="section-heading">
    <p class="eyebrow">Research</p>
    <h2>Memory as a computational problem</h2>
  </div>
  <div class="section-copy">
    <p>
      I treat episodic memory as a computational problem centered on three operations: representing experience in context, reinstating relevant context during retrieval, and controlling how memory enters ongoing computation. These questions can be studied through behavior, internal representations, causal mechanisms, and formal principles, creating a common language for comparison across artificial and biological systems.
    </p>
  </div>
</section>

<section class="research-grid" aria-label="Research themes">
  <article class="research-card">
    <h3>Episodic memory</h3>
    <p>How do intelligent systems bind events to temporal and situational context, and which representations preserve the contextualized structure of an experience?</p>
    <a href="/research/#episodic-memory">Read more →</a>
  </article>
  <article class="research-card">
    <h3>Mechanisms of remembering</h3>
    <p>How is contextual information represented and reinstated during remembering? I combine behavioral experiments, mechanistic analysis, and theory to identify concrete computations.</p>
    <a href="/research/#mechanisms">Read more →</a>
  </article>
  <article class="research-card">
    <h3>Memory and cognitive control</h3>
    <p>How do intelligent systems decide when to retrieve, preserve, consolidate, or reinstate information as part of ongoing computation?</p>
    <a href="/research/#cognitive-control">Read more →</a>
  </article>
</section>

<section class="home-section home-section--work">
  <div class="section-heading">
    <p class="eyebrow">Selected publications</p>
    <h2>Recent work</h2>
  </div>
  <div class="section-copy section-copy--link">
    <a href="/publications/">All publications →</a>
  </div>
</section>

<div class="featured-work">
  <article class="featured-paper featured-paper--primary">
    <div class="featured-paper__meta"><span>ICML 2026</span><span>Mechanistic memory</span></div>
    <h3><a href="https://arxiv.org/abs/2607.22575">Temporal Context Reinstatement Drives Episodic-Like Order Memory in Long-Context Language Models</a></h3>
    <p>Long-context LLMs reproduce a human temporal-distance effect, represent time along a one-dimensional code, and use a specific attention head to reinstate temporal context during retrieval.</p>
    <div class="paper-links">
      <a href="https://arxiv.org/abs/2607.22575">Paper</a>
      <a href="https://openreview.net/forum?id=sycSMgogxM">OpenReview</a>
      <a href="https://github.com/mathispink/temporal-context-reinstatement">Code</a>
    </div>
  </article>

  <article class="featured-paper">
    <div class="featured-paper__meta"><span>2024</span><span>Human &amp; model memory</span></div>
    <h3><a href="https://arxiv.org/abs/2410.08133">Assessing Episodic Memory in LLMs with Sequence Order Recall Tasks</a></h3>
    <p>Introduces SORT and Book-SORT, adapting a human temporal-order memory paradigm to LLMs and validating the naturalistic task in a human experiment.</p>
    <div class="paper-links"><a href="https://arxiv.org/abs/2410.08133">Paper</a></div>
  </article>

  <article class="featured-paper">
    <div class="featured-paper__meta"><span>2025</span><span>Research agenda</span></div>
    <h3><a href="https://arxiv.org/abs/2502.06975">Position: Episodic Memory is the Missing Piece for Long-Term LLM Agents</a></h3>
    <p>Develops a framework for episodic memory in long-term agents around single-shot, contextualized, continuously learned experience.</p>
    <div class="paper-links"><a href="https://arxiv.org/abs/2502.06975">Paper</a></div>
  </article>
</div>

<section class="questions-block">
  <div>
    <p class="eyebrow">Research questions</p>
    <h2>Current directions</h2>
  </div>
  <div class="questions-block__grid">
    <p>How is contextual information represented so that an earlier event can be recovered as part of a specific episode?</p>
    <p>Which representational and computational principles recur across artificial and biological memory?</p>
    <p>How does cognitive control determine when past experience should be retrieved, consolidated, or reinterpreted?</p>
  </div>
</section>

<section class="home-section home-section--background">
  <div class="section-heading">
    <p class="eyebrow">Background</p>
    <h2>From active vision to memory</h2>
  </div>
  <div class="section-copy">
    <p>
      Before my PhD, I studied Cognitive Science at Osnabrück University and worked with <a href="https://www.kietzmannlab.org/">Tim Kietzmann</a> and <a href="https://www.ewi-psy.fu-berlin.de/en/psychologie/arbeitsbereiche/neural_dyn_of_vis_cog/Cognitive-Computational-Neuroscience/Adrien-Doerig/index.html">Adrien Doerig</a> on active foveated vision at the intersection of machine learning and computational neuroscience, using reinforcement learning to model where an agent chooses to look. Earlier, I studied Philosophy and Economics at the University of Bremen.
    </p>
    <p>
      That training shapes how I approach memory: start from cognitively meaningful phenomena, formulate them as computational problems, and connect behavior to internal representation, mechanism, and control.
    </p>
    <p><a href="/background/">Full background →</a></p>
  </div>
</section>

<section class="news-block">
  <div class="section-heading">
    <p class="eyebrow">Updates</p>
    <h2>Recent</h2>
  </div>
  <div class="news-list">
    <div class="news-item"><time>2026</time><p>Work on temporal context reinstatement accepted at ICML 2026.</p></div>
    <div class="news-item"><time>2026</time><p>Work on competing literal and figurative representations in LLMs published as a long paper at EACL 2026.</p></div>
    <div class="news-item"><time>2025</time><p>Teaching assistant at the CAJAL Neuroscience &amp; AI summer school in Lisbon.</p></div>
  </div>
</section>
