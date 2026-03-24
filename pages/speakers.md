---
layout: page-fullwidth
title: "Speakers & Presentations"
header: no
permalink: /speakers/
---

<div id="speaker1" style="display: flex; flex-direction: column;">

<h3>Quantifying Prior Information via Kullback-Leibler Divergence: A New Perspective on Effective Sample Size 
</h3>

<h4>Ming-Hui Chen, University of Connecticut </h4>

<p>
<img class="imgfloat" src="../docs/Chen.jpg"/>

Dr. Ming-Hui Chen is a Board of Trustees Distinguished Professor and Head of Department of Statistics at University of Connecticut (UConn). Dr. Chen's areas of research focus include Bayesian statistics, categorical data, design of clinical trials, MA and NMA, missing data, prostate cancer data, and survival data. He is an Elected Fellow of AAAS, ASA, IMS, and ISBA. He has published over 500 research papers. Currently, he is Co Editor-in-Chief of Statistics and Its Interface, and inaugurated Co Editor-in-Chief of New England Journal of Statistics in Data Science. 
</p>


<h4>Abstract</h4>

The effective sample size (ESS) tells us how much information a prior contributes in Bayesian analysis. Yet, existing definitions often fail when the prior and likelihood disagree. In this talk, I introduce a new way to measure ESS using the reverse Kullback-Leibler divergence between an informative prior and a power posterior. This formulation provides a clear optimization-based interpretation and ensures desirable convexity properties. I’ll show how this framework generalizes classical ESS definitions, discuss its theoretical guarantees, and illustrate its behavior through simple examples and applied case studies. Overall, this approach offers an intuitive way to understand "how much data" a prior effectively adds. This is a joint work with Min Lin and Chenguang Wang.

</div>

----

<div id="speaker2" style="display: flex; flex-direction: column;">

<h3>Closing the Loop in Evidence Synthesis: High-Fidelity IPD Reconstruction from Kaplan-Meier Plots and Robust Inference

</h3>

<h4>Yanxun Xu, Johns Hopkins University</h4>

<p>
<img class="imgfloat" src="../docs/Xu.jpg"/>

Dr. Yanxun Xu is a Professor and the Joseph & Suzanne Jenniches Scholar in the Department of Applied Mathematics and Statistics, the Data Science and AI Institute, and the Sidney Kimmel Comprehensive Cancer Center at Johns Hopkins University. She specializes in the intersection of Bayesian statistics and artificial intelligence, with contributions in reinforcement learning, high-dimensional data analysis, nonparametric statistics, and uncertainty quantification. Her methods have been successfully applied to areas in intelligent healthcare, including work in clinical trial designs, cancer genomics, early disease diagnosis such as predictive models for Alzheimer's disease, and the analysis of electronic health records. Her research is continually funded by the National Science Foundation (NSF), the National Institutes of Health (NIH), and industrial partners.
</p>


<h4>Abstract</h4>

The reconstruction of Individual Patient Data (IPD) from Kaplan-Meier (KM) plots is a cornerstone of evidence synthesis but is historically bottlenecked by manual, error-prone digitization and statistically simplistic assumptions. In this talk, we present a two-part solution that first automates and then rigorously advances this critical process. We first introduce KM-GPT, the first fully automated, AI-powered pipeline for reconstructing IPD directly from KM plots. By integrating advanced image preprocessing, multi-modal reasoning, and iterative algorithms, KM-GPT eliminates manual intervention and provides a scalable, web-accessible tool for high-accuracy data extraction, as validated on synthetic and real-world datasets. Building upon this automation, we then present RESOLVE-IPD, a unified framework that addresses fundamental methodological limitations. RESOLVE-IPD combines high-fidelity graphics extraction with a novel reconstruction algorithm that leverages explicit censoring marks to eliminate systemic bias. Furthermore, for scenarios with limited data, it introduces an optimization-based method to infer missing subgroup survival curves from overall IPD. We will demonstrate the superior accuracy of both systems and illustrate their transformative clinical utility through real-world case studies.

</div>

----

<div id="speaker3" style="display: flex; flex-direction: column;">

<h3>From Hallucination to Trust: Building Knowledge Graphs for Reliable and Explainable AI in Biomedical Discovery</h3>

<h4>Jinfeng Zhang, Insilicom LLC</h4>

<p>
<img class="imgfloat" src="../docs/Zhang.jpg"/>

Dr. Jinfeng Zhang received his Ph.D. in bioinformatics from the University of Illinois at Chicago in 2004 and completed postdoctoral training in Statistics at Harvard University from 2004 to 2007. He joined the Department of Statistics at Florida State University as a faculty member in 2007, where he conducted research at the intersection of machine learning and biology for over 15 years. In summer 2025, Dr. Zhang transitioned full-time to his startup, Insilicom LLC, where he is developing a foundation knowledge graph to power next-generation AI models and applications, and applying it to drug discovery and pharmacovigilance. His research spans biological information extraction, natural language processing, biomedical knowledge graphs, and AI for science, with a consistent focus on building trustworthy, data-driven methods for advancing life sciences. Dr. Zhang and his team have earned international recognition through multiple top awards in biological NLP and AI challenges, including the LitCoin NLP Challenge organized by NIH and NASA (2022), the BioCreative Challenge VIII Knowledge Graph Track (2023), and the BioASQ 13B Biomedical Question Answering Challenge (2025).
</p>


<h4>Abstract</h4>

AI has become a transformative force in biomedical research and drug development. Yet as its influence grows, so does a fundamental challenge: trust. LLMs, while remarkably powerful, can hallucinate, producing fluent but false statements that may mislead researchers and even contaminate the scientific record. As AI-generated content proliferates, the foundations of scientific knowledge itself are at risk unless we develop robust ways to ground AI in verifiable truth.
In this talk, I will present our work on building large-scale biomedical knowledge graphs as the factual backbone for trustworthy AI. Our team developed IKraph, a comprehensive knowledge graph that integrates the full PubMed literature, numerous public databases, and high-throughput genomics datasets. It captures tens of millions of entities and relationships spanning genes, drugs, diseases, and pathways. Beyond its scale, IKraph is designed with explicit links to supporting evidence, enabling transparency, auditability, and reproducibility. The methods behind IKraph have been validated through multiple first-place finishes in international challenges, including applications in biomedical question answering.
I will show how this infrastructure can accelerate biomedical discovery and drug development, including applications in drug repurposing and hypothesis generation. More broadly, I will argue that knowledge graphs are essential to the future of trustworthy AI. By grounding AI systems in structured, evidence-based knowledge, we can build a new generation of tools that are not only intelligent, but also accountable and capable of advancing biomedical discovery with integrity and confidence.

</div>

----



----
