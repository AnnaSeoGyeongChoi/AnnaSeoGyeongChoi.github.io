---
title: "Research"
hidemeta: true
description: "What Anna is interested in."
---

# Research Interests: AI Ethics and Automatic Speech Recognition

## Overview

My research challenges the foundational assumptions underlying speech technology, demonstrating that what appears technically neutral often perpetuates linguistic injustice. I have established myself as a leading voice in ASR fairness research, publishing at venues including ACM FAccT, Interspeech, ICASSP, and AIES, with $30,000+ in research support. **My work centers on deconstructing harmful technical assumptions while building constructive frameworks for equitable speech technology.**

Through interdisciplinary approaches grounding computer science in philosophy, linguistics, and human-computer interaction, I examine how systematic biases emerge across the ASR pipeline: training data, model architecture, and transcript evaluation.

## Theoretical Contributions

### SpeechSpectrum Framework
I have developed the **SpeechSpectrum framework**, which reconceptualizes ASR output not as a single "correct" transcription but as one point along a continuous spectrum of possible representations. Built on the linguistic concept of the oral-literate continuum, this framework reveals that "accuracy" cannot be defined without reference to user context and intended function, challenging the field's assumption that technical optimization and user needs align.

### Philosophical Framework of Speech Technology Harm
Moving beyond simple error rates, I have formulated three tangible, temporal harms unique to speech technology:
- **Temporal taxation**: The unequal cognitive and time burden of correcting errors
- **Conversational disruption**: The fragmentation of communicative flow  
- **Power asymmetry**: The unequal relationship where the system controls the interaction

This framework demonstrates that systematic misrecognition constitutes a form of disrespect that inflicts compounding injustice on marginalized linguistic communities.

## Research Areas

### Training Data and Representation

In the era of end-to-end speech recognition, training data quality fundamentally determines system performance. However, current ASR datasets exhibit significant representation gaps that perpetuate algorithmic bias.

**Key challenges:**
- **Benchmark limitations**: Standard benchmarks like LibriSpeech rely on read speech from demographically narrow populations, achieving artificially low error rates (3%) that don't reflect real-world performance
- **Underrepresented populations**: Marginalized communities, including speakers with non-native accents, regional dialects, speech impairments, and speakers of understudied languages, lack adequate representation
- **Data collection ethics**: Critical questions around linguistic norms, socioeconomic factors, transcription conventions, and collection methodologies require systematic examination

My work emphasizes the importance of transparent dataset documentation and awareness of representational limitations in ASR training corpora.

### Model Architecture and Linguistic Knowledge

While end-to-end models dominate current ASR research, their black-box nature presents significant challenges for ethical AI development. I advocate for incorporating explicit linguistic knowledge to address data scarcity for underrepresented speech varieties.

**Research focus:**
- **Pronunciation modeling**: Leveraging linguistic expertise and rule-based approaches to supplement limited training data for minority language varieties
- **Fine-tuning with linguistic constraints**: Incorporating phonetic rules, G2P mappings, and grammatical knowledge alongside data-driven approaches
- **Hybrid methodologies**: Combining the interpretability of traditional systems (e.g., Kaldi) with the performance benefits of modern architectures

This approach challenges the prevalent "more data solves everything" paradigm, particularly for communities that cannot achieve equal representation in training corpora.

### Transcript Evaluation and Application Context

Current ASR evaluation practices rely heavily on Word Error Rate (WER), which inadequately captures system performance across diverse use cases and populations.

**Research directions:**
- **Context-aware evaluation**: Developing metrics that account for application-specific requirements (clinical documentation vs. voice assistants vs. call centers)
- **Stylistic adaptation**: Investigating how transcript formatting should vary based on intended use (punctuation, fillers, disfluencies, timing information)
- **Hallucination analysis**: Examining how model uncertainty manifests as fabricated content, particularly in challenging acoustic conditions

### Clinical Speech Technology and Vulnerable Populations

My research with clinical populations reveals systematic performance disparities and novel harms in ASR systems. Through empirical studies with d/Deaf and hard-of-hearing speakers, people with aphasia, and other speech-affecting conditions, I demonstrate that standard evaluation practices mask important disparities and create false impressions of universal capability.

**Key contributions:**
- **Community-driven auditing methodology**: Pioneering approaches where affected communities' preferences—not system defaults—define evaluation "ground truth"
- **Infrastructure instability analysis**: Revealing how basic technical choices (feature extraction tools, transcription formats) introduce systematic variations that undermine claims of system reliability
- **Hallucination identification**: Documenting instances where ASR systems fabricate speech content never produced by speakers, particularly in challenging acoustic conditions

**Clinical applications**: In medical settings, I investigate how transcript formatting requirements vary dramatically—from capturing diagnostic disfluencies and timing information to preserving medical terminology accuracy across different clinical specialties.

## Research Impact and Vision

### Methodological Innovation
My work bridges computer science and humanities scholarship, bringing philosophical rigor to technical problems while developing actionable solutions for real-world deployment. I have created frameworks now being adopted by both academic and industry researchers, challenging the field's reliance on single-output paradigms and aggregate performance metrics.

### Policy and Industry Impact
Through systematic auditing of commercial ASR systems and development of practical evaluation tools, my research directly informs industry procurement decisions and regulatory frameworks. Current projects will generate policy recommendations for responsible AI deployment in healthcare and government contexts.

### Interdisciplinary Leadership
By grounding technical work in philosophy, linguistics, and human-computer interaction, I am fostering unified approaches to ASR fairness across disparate research communities. My vision is to embed justice in fundamental conceptual frameworks rather than treating fairness as a post-hoc optimization problem.

## Current and Future Research Directions

### ClinSpeech: Clinical ASR Evaluation Ecosystem
I am leading development of the first holistic benchmark for evaluating ASR fairness across clinical populations. This open-source ecosystem will establish systematic, cross-condition, and intersectional evaluation standards, introducing novel metrics that capture clinically relevant dimensions including preservation of medical terminology and handling of diagnostically significant disfluencies.

### Economic Quantification of Linguistic Harm
Building on my theoretical work on temporal taxation, I am developing comprehensive methodologies for quantifying the economic costs of ASR bias. This research will establish "linguistic equity indices" measuring productivity losses, hiring discrimination, and remote work accessibility impacts, creating business cases for investing in fair models.

### High-Stakes Deployment Analysis
I am investigating ASR deployment in legal and carceral contexts, examining how these technologies amplify power asymmetries in life-altering decisions. Using public parole hearing data, this research applies established sociotechnical auditing methods to analyze ASR's role in mediating justice system outcomes, generating policy recommendations for responsible AI deployment in government contexts.

### Participatory Data Ethics
I am developing enhanced ethics frameworks that challenge extractive data collection paradigms, reframing the process as data stewardship with meaningful community involvement in research design and decision-making. This work includes practical tools for engaging vulnerable populations in speech research through principles of participatory design.

---

*Through systematic interrogation of technical assumptions, interdisciplinary collaboration, and development of practical tools, my research program aims to create speech technologies designed not merely for technical accuracy, but for social justice -- empowering users and respecting the rich diversity of human language. I welcome collaborations and discussions on advancing equitable speech technology.*