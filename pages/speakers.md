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

<div id="speaker4" style="display: flex; flex-direction: column;">

<h3> Automating Clinical Trial Regulatory Documents with Agentic AI: Generation and Evaluation of SAPs, CSRs, and LoTs
</h3>

<h4> Sheraz Khan, Pfizer </h4>

<p>
<img class="imgfloat" src="../docs/Khan.jpg"/>

Dr. Sheraz Khan is a Senior Director and AQDS Group Lead at Pfizer, where he spearheads AI-driven innovation to optimize clinical trial processes. With over two decades of experience bridging computational science, drug development, and digital health, his work focuses on data-driven decision-making, process automation, and regulatory corpus generation. Prior to Pfizer, Dr. Khan served on the faculty at Harvard Medical School and led digital biomarker analysis for Biogen. A recognized thought leader, he holds a PhD in Computational and Applied Mathematics from École Polytechnique, France, two digital health patents, and has published over 75 high-impact papers.

</p>


<h4>Abstract</h4>

Automating clinical regulatory documents like SAPs, CSRs, and LoTs offers a massive opportunity to accelerate drug development. This talk explores deploying Agentic AI workflows to autonomously synthesize and draft these highly structured documents while adhering to strict regulatory guidelines. Additionally, the session introduces a domain-specific evaluation framework designed to score AI-generated outputs for accuracy, traceability, and compliance, ensuring they meet the rigorous quality control standards of clinical trials.

</div>

----

<div id="speaker5" style="display: flex; flex-direction: column;">

<h3> BEAM: Bayesian Hybrid Design With Adaptive Sample Size Through Multisource Exchangeability Modeling
</h3>

<h4> Meizi Liu, Takeda</h4>

<p>
<img class="imgfloat" src="../docs/Liu.jpg"/>

Meizi Liu is a Senior Manager in Statistics at Takeda, with experience across oncology, autoimmune, and neurodegenerative indications. She leads statistical strategies and supports key decision-making for different stages of clinical development programs. Her expertise includes Bayesian methods, adaptive trial designs, and dose optimization. She earned her Ph.D. in Biostatistics from the University of Chicago, where her dissertation focused on practical and advanced dose-finding designs. She has co-authored multiple publications in peer-reviewed journals on topics including dose optimization, Bayesian dynamic borrowing, and Bayesian adaptive designs in clinical trials.


</p>


<h4>Abstract</h4>

Randomized controlled trials (RCTs) remain the gold standard for evaluating treatment efficacy, but they often face practical challenges, including high cost, long timelines, and difficulties in enrolling and retaining patients in control arms. Hybrid trial designs that incorporate external data, such as historical controls and real-world evidence, offer a promising approach to improve efficiency while maintaining rigor.
In this talk, we introduce the Bayesian Hybrid Design with Adaptive Sample Size through Multisource Exchangeability Modeling (BEAM). The BEAM framework leverages a modified multisource exchangeability model to dynamically borrow information from multiple external data sources, while adaptively adjusting sample size throughout the trial. This approach allows for efficient use of available data while accounting for potential heterogeneity between current and historical sources.
We present key design concepts, operating characteristics based on simulation studies, and practical considerations for implementation. Results demonstrate that BEAM can effectively control type I error, reduce bias, and maintain statistical power compared to traditional and alternative adaptive designs. A case study in ankylosing spondylitis is used to illustrate the application and potential impact of the proposed approach. 
Overall, BEAM provides a flexible and efficient framework for clinical trial design, with the potential to reduce development time and improve decision-making in drug development.
</div>

----


<div id="speaker6" style="display: flex; flex-direction: column;">

<h3> The FDA's Risk-Based Regulatory Perspective on AI in Drug Development
</h3>

<h4> Hussein Ezzeldin, U.S. Food and Drug Administration</h4>

<p>
<img class="imgfloat" src="../docs/Ezzeldin.jpg"/>
Hussein Ezzeldin: Dr. Ezzeldin is a Senior Public Health Advisor in the Office of Medical Policy at the Center for Drug Evaluation and Research (CDER). He supports various initiatives related to the use of real-world data and evidence, digital health technologies, and artificial intelligence in drug development. Dr. Ezzeldin has extensive experience in postmarket surveillance and has contributed to multiple agency efforts advancing the use of innovative data sources and technologies in regulatory decision-making.
</p>


<h4>Abstract</h4>

The integration of Artificial Intelligence and Machine Learning (AI/ML) into drug and biologics development is accelerating, with the FDA's, center for Drugs (CDER) and center for Biologics (CBER), having now received over 1,000 submissions incorporating AI/ML—a number that has shown a constant increase in recent years. This presentation will provide the FDA's perspective on this transformative shift, sharing data on the landscape of AI/ML submissions and highlighting key trends, including a notable concentration of applications in the clinical development phase.
We will detail the FDA's proactive and collaborative approach to regulation, which is anchored in a risk-based framework tailored to the specific context of use. This talk will explain how the regulatory evaluation of AI/ML is calibrated based on the model's potential influence and the consequence of its output. Furthermore, we will highlight international collaboration initiatives aimed at further advancing good AI/ML practices in drug development. Finally, we will emphasize the critical importance of early sponsor engagement with the FDA to successfully navigate this evolving landscape, encouraging innovation while upholding the fundamental evidentiary standards for ensuring safety and efficacy.
</div>

----

<div id="speaker7" style="display: flex; flex-direction: column;">

<h3> Development of the recent FDA CDER/CBER Bayesian draft guidance
</h3>

<h4> James Travis, U.S. Food and Drug Administration</h4>

<p>	
<img class="imgfloat" src="../docs/Travis.jpg"/>
James Travis is a master mathematical statistician in the Division of Biometrics II in the US FDA Center for Drug Evaluation and Research. He is the technical lead for the pediatric and maternal health scientists and has been supporting pediatric drug development since joining the Pediatric Review Committee in 2017. He has worked extensively on applications in the complex and innovative trial design program and led the development of the FDA draft guidance “Use of Bayesian Methodology in Clinical Trials of Drug and Biological Products”.
</p>


<h4>Abstract</h4>
Bayesian methods have seen increasing usage through the complex innovative trial design program and more generally in pediatric and rare disease trials and to ease their implementation and feasibility, FDA committed to publishing a draft guidance to support their use under the sixth reauthorization of the Prescription Drug User Fee Act (PDUFA). This draft guidance, “Use of Bayesian Methodology in Clinical Trials of Drug and Biological Products,” was published in January 2026. The draft guidance discusses many issues related to the use of Bayesian methods including success criteria, operating characteristics, prior distributions and expectations for documenting and reporting Bayesian analyses. 
In this presentation I will review some of the key considerations in this draft guidance and discuss some of the case examples that motivated the considerations.

</div>




