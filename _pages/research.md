---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

The intersection of human cognition, technology, and social interaction forms the foundation of my research, spanning three interconnected projects that examine how technology reshapes human experience and decision-making.

My primary research on **data privacy** investigates the evolution of privacy norms in our increasingly digitized world. Through the theoretical framework of contextual integrity, this work examines how individuals navigate data-sharing across diverse digital environments, from social platforms to workplace monitoring systems. The research employs experimental methods and participatory approaches to demonstrate that collective deliberation significantly enhances privacy decision-making processes and informed consent. 

In extension, the **mental privacy** project explores the emerging challenges posed by evolving neurotechnologies. This projects investigates a qualitatively new dimension of privacy concerns: the direct and wide-spread access to mental states through technologies like mobile EEG headsets and other neural interfaces. Through cross-cultural experimental studies and conceptual work, the project contributes to fundamental questions about mental integrity and the boundaries of acceptable neural data collection, informing both theoretical frameworks in neurophilosophy and practical policy development for upcoming neurotechnologies.

The **AI-advisor** project reveals subtle yet profound shifts in human cognition when interacting with artificial intelligence systems. This work uncovers how individuals unconsciously attribute agency and responsibility to AI advisory systems, even when these systems function identically to non-AI alternatives. The findings highlight a fascinating cognitive bias where AI presence alone alters fundamental patterns of responsibility attribution, contributing to our understanding of human-AI relationships.

My theoretical work on **co-perception** challenges traditional individualistic models of sensory processing. This research establishes that perceiving alongside others fundamentally transforms basic perceptual processes and decision-making. The project demonstrates the existence of automatic mechanisms for distinguishing between private and shared perceptual experiences, separate from established concepts of joint attention. These findings have significant implications for understanding social learning dynamics and the development of collaborative technologies.

These interconnected projects contribute to a broader understanding of how technological advancement reshapes human cognition and social interaction. The findings inform the design of human-centered technologies while advancing theoretical frameworks in cognitive science and human-computer interaction.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
