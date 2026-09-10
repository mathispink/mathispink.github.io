---
layout: single
title: "Research"
permalink: /research/
author_profile: false
---

<div class="research-lead">
  <p class="eyebrow">Overview</p>
  <p class="research-lead__text">I study computational principles of contextual memory across artificial and biological systems.</p>
  <p>My research asks how intelligent systems represent experience in context, reinstate contextual information during remembering, and control how memory shapes ongoing computation. My work connects machine learning, cognitive science, and computational neuroscience. Artificial models make these processes experimentally accessible at the level of behavior, internal representation, and causal mechanism. Human behavior and neuroscience provide complementary constraints on the computations that support memory. I use cross-system comparison to identify principles of contextual memory that can be formalized and tested across systems.</p>
</div>

## Episodic memory {#episodic-memory}

An episode preserves an event together with the context that gives it a place in experience: when it happened, what surrounded it, and which event it belonged to. This structure supports source memory, temporal and spatial reasoning, and later reinterpretation.

I ask which forms of contextual binding are required for episodic memory, how they can be operationalized in artificial systems, and which properties are shared with human memory. This gives a concrete route from cognitive concepts to computational models and measurable behavior.

One line of work introduced **Sequence Order Recall Tasks (SORT)**, adapting a temporal-order paradigm from cognitive psychology to long-context language models. Book-SORT extends the paradigm to naturalistic long-term memory and includes a human experiment that validates the task as a measure of temporal context memory.

<div class="research-links">
  <a href="https://arxiv.org/abs/2410.08133">SORT paper</a>
  <a href="https://arxiv.org/abs/2502.06975">Episodic-memory position paper</a>
</div>

## Mechanisms of remembering {#mechanisms}

To explain how a system remembers, I study the internal representations and computations that produce memory behavior. Behavioral comparison establishes which effects and phenomena are shared across systems; mechanistic analysis asks how relevant information is organized internally and which computations causally support memory retrieval.

In recent work, we found that long-context LLMs reproduce a characteristic human temporal-distance effect on episodic-like order judgments. Mechanistic analyses identified a one-dimensional representation of temporal position and a dedicated attention head that reinstates temporal context during retrieval. Causal interventions on this localized mechanism alter temporal memory behavior.

The broader aim is to identify computational motifs such as context representations and reinstatement that can be defined at a common level of analysis and compared across artificial and human memory.

<div class="research-links">
  <a href="https://arxiv.org/abs/2607.22575">ICML 2026 paper</a>
  <a href="https://github.com/mathispink/temporal-context-reinstatement">Code &amp; data</a>
</div>

## Memory and cognitive control {#cognitive-control}

Intelligent memory depends on control over how past information enters current computation. A longer-term direction concerns **internal actions**: learned operations through which a system controls what information becomes active. A model might learn when to retrieve an episode, when to consolidate experience into persistent knowledge, when to preserve source-provenance, or when to reinstate an earlier internal state.

This perspective raises questions about trade-offs between episodic specificity and compression, conditions under which consolidated knowledge is sufficient, situations where provenance matters, and mechanisms that determine when earlier context should become active again.

## Comparing artificial and biological memory {#brains}

Artificial and biological systems offer different views of history-dependent computation. I am particularly interested in naturalistic paradigms—stories, repeated experiences, and longer timescales—where similar inputs can produce different internal states because of what a system has previously experienced.

Precise comparison can be made at several levels: behavior, representational organization, dynamics, and mechanism. These levels can agree or diverge, and the pattern of correspondence can reveal which organizational principles recur across implementations. I believe there is still a large untapped potential to learn from neural recordings and their alignment with model activations. Studying how both systems differ in how they utilize contextual memory can offer insights to improve models and identify general principles.

## Earlier work {#trajectory}

Before working on memory, I studied **active foveated vision** during my M.Sc. in Cognitive Science at Osnabrück University, at the intersection of machine learning and computational neuroscience. A reinforcement-learning policy within a model controlled where the same model looked next in natural scenes.

Across these projects, my approach has been to start from a cognitively meaningful phenomenon, formulate it as a computational problem, and connect observable behavior to internal representations, mechanisms, and optimization.
