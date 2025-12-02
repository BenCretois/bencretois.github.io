---
title: "ROaR"
description: "Creating models that can generalise to other classes with not much annotations"
category: "Machine learning"
date: 2024-01-01
status: "present"
tags: ["AI", "machine learning", "transfer learning", "acoustic monitoring", "sound recognition"]
website: "https://www.sintef.no/en/projects/2025/roar-robust-acoustic-recognition/"
weight: 2
---

## Did you hear that? What was that?

The questions posed above immediately activate our minds, prompting quick answers like "It's just a car on the road" or "That must be a rare bird." Most of the time, we don't even consciously ask or think about what we heard. We instinctively recognize the sound - whether it's a car, a bird, or something else.

Artificial intelligence (AI) is also capable of recognizing sounds automatically, but teaching this skill to AI is often not feasible. Collecting enough data to train AI systems to identify every relevant sound source in every possible context is often prohibitively expensive. Unlike humans, who can grasp the general concept of a sound after just a few examples, AI requires vast amounts of data and repeated training to identify each sound properly. **ROaR aims to close this gap and lower the costs of implementing AI-powered sound recognition** across a wide range of applications.

## 🎵 Sound contains information, and information has value

This opens up numerous potential applications where sound monitoring is critical. For instance, environmental noise monitoring is a crucial first step in noise control, which we desperately need because, in Western Europe alone, noise pollution costs over a million healthy life years (DALYs) each year. Sound monitoring can also be used to track nature and biodiversity, helping us evaluate whether our restoration efforts are having the desired impact or guiding us to where further efforts will have the most impact.

At the heart of sound monitoring is the ability to recognize sound sources. This is something we, as humans, start learning early - before we're even born. The good news is, we can teach machines to do the same. With the right data, AI can become highly proficient at recognizing sounds. The best part? These systems can operate continuously, even in hazardous environments.

## 🔄 Transfer learning

However, while large language models (LLMs) are transforming how we work with text, and computer vision models excel at interpreting images, AI still struggles with sound. Transfer learning - one of the key techniques in machine learning that enables a model trained on one task to be adapted to another - doesn't perform as well with audio. Audio classification models often fail to generalize across different contexts. Simply put: **Change of application? Start training from scratch.**

## 🎯 Create a service that enables easy development of sound monitoring systems

This means audio classification technology is too expensive for most. It requires too much manual labour for each new application. This is where **RoAR** comes in: **Robust Acoustic Recognition**. Rather than developing a new sound classification system for each individual application, ROaR aims to create a service that enables the easy development of sound monitoring systems with minimal manual effort.

How do we get the most out of each and every labelled datapoint? We'll explore everything from:
- **Audio representation**: What do we feed our models?
- **Data augmentation**: How do we teach AI about sound propagation?
- **Distributions/clustering**: Which clips sound similar, and which don't?
- **Active learning**: Which samples will provide the most useful new information for my system?

The research will cover a variety of use cases, including both urban noise and biodiversity datasets, to ensure broad applicability.

## Key Innovations

- **Few-shot learning**: Effective sound recognition with minimal training data
- **Cross-domain adaptation**: Models that work across different acoustic environments  
- **Active learning strategies**: Smart data selection for maximum learning efficiency
- **Unified framework**: One platform for diverse acoustic monitoring applications