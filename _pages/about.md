---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I earned a Bachelor of Engineering in Data Science and Big Data Technology from East China Normal University (ECNU) in Shanghai, China. My research interests include **AI Infrastructure**, **ML/LLM Systems**, and **Data-Centric AI**.

From September 2024 to September 2025, I worked as an Undergraduate Research Assistant in the Decision Intelligence Lab at ECNU under the supervision of Prof. Yang Shu. My research focused on visual modeling for time-series forecasting and led to three co-authored papers that explore time series beyond conventional sequence-based approaches.

My citation record is available on <a href='{{ site.author.googlescholar }}'>Google Scholar</a> (<strong><span id='total_cit'>loading...</span></strong> citations).

{% comment %}
# 🔥 News
{% endcomment %}

# 📝 Publications

1. Mingyang Y<sup>&ast;</sup>, <strong>Xiahui G<sup>&ast;</sup></strong>, Peng C, et al. (2025). **Towards Measuring and Modeling Geometric Structures in Time Series Forecasting via Image Modality.** *ACM Multimedia 2025*.<br>
   Introduces a geometric-structure view of time-series forecasting, with an image-based metric for evaluating shape similarity and a plug-and-play loss for structure-aware training.

2. Mingyang Y, Peng C, **Xiahui G**, et al. (2026). **Vision-Enhanced Time Series Forecasting by Decomposed Feature Extraction and Composed Reconstruction.** *ICASSP 2026*.<br>
   Recasts time-series forecasting as image reconstruction, combining decomposed temporal features with the input sequence's shape prior to reconstruct future sequences in the visual domain.

3. Mingyang Y, Chenwei Y, Yanlei S, Zhenkai L, Peng C, and **Xiahui G**. (2026). **TCT-Loss: Shape-Aware Time-Series Forecasting with a Zero-Shot Time-Column Transformer Autoencoder.** *ICASSP 2026*.<br>
   Builds a transferable shape-aware loss around a Time-Column Transformer autoencoder, supervising forecasts by comparing decoded time-series images across datasets and horizons.

4. Mingyang Y, Yukun W, Zhaoting C, Junwei H, and **Xiahui G**. (2026). **Triad: A Unified Sparse-Attention Offloading System for Long-Context LLM Inference.** Submitted to *NeurIPS 2026*.<br>
   Enables high-throughput CPU-offloaded sparse attention by jointly optimizing which KV rows to retrieve, how they are fetched, and how KV storage is balanced across CPU and GPU.

5. Yicheng B, **Xiahui G**, Xuhong W, and Xin T. (2026). **SPARED: Reasoning-Based AI-Generated Image Detection via Adversarially Edited Data.** Submitted to *AAAI 2027*.<br>
   Trains a reasoning-based AI-generated-image detector in an attacker-defender loop, where an adaptive image editor generates paired hard negatives to overcome static-data and provenance shortcuts.

6. Junwei H<sup>&ast;</sup>, <strong>Xiahui G<sup>&ast;</sup></strong>, and Mingyang Y. (2026). **ComMark: Synchronization-Aware Local Slot Communication for Robust Multi-Bit Audio Watermarking.** Submitted to *AAAI 2027*.<br>
   Reframes robust multi-bit audio watermarking as synchronization-aware local communication, distributing payload across overlapping spectrogram slots while identifying STFT magnitude as the dominant recoverable carrier.

<sup>&ast;</sup> Equal contribution.

# 🔬 Research Experience

- ***09/2024 – 09/2025*** — **Undergraduate Research Assistant**, Decision Intelligence Lab, East China Normal University
  - Conducted research under Prof. Yang Shu on visual modeling for time-series forecasting, co-authoring three papers that explore time series beyond conventional sequence-based approaches.

# 🎖 Honors and Awards

- ***2024*** — Special Class Scholarship (Rank 2%)
- ***2024*** — COMAP's Mathematical Contest in Modeling (MCM), Meritorious Winner (Top 7%)
- ***2023*** — First Class Scholarship (Rank 5%)
- ***2023*** — China Undergraduate Mathematical Contest in Modeling, Second Prize

<span class='anchor' id='educations'></span>

# 📖 Education

- ***09/2022 – 07/2026*** — **East China Normal University**, Shanghai, China<br>
  Bachelor of Engineering in Data Science and Big Data Technology
  - **Academic standing:** GPA 3.78/4.0; Major GPA 3.90/4.0; WAM 91/100; Top 10%
  - **Relevant coursework:** Deep Learning (99), Artificial Intelligence (97), Statistical Methods and Machine Learning (A), Computer Vision (95), Computer Systems (97), Distributed Systems (95)

{% comment %}
# 💬 Invited Talks
{% endcomment %}

<span class='anchor' id='internships'></span>

# 💻 Selected Engineering Experience

- ***04/2026 – Present*** — **Full-Stack Engineer Intern**, M77, Shanghai, China
  - Built an internal AI platform for employee training, discussion, design-case retrieval, and 3D-rendering-based quotation, with reusable LLM skills and similarity-based result reuse to reduce redundant model calls.

- ***05/2024 – 04/2025*** — **Core Team Member**, Multi-Agent System in Power-Sector Cost Management
  - Built a RAG-based multi-agent approval system over nearly one million historical documents, combining domain rules, structured extraction, dense retrieval, and reranking for automated cost review.

# ⚙️ Skills

- **Programming:** Python, C/C++, Java
- **Framework:** PyTorch
- **Tools:** Linux, Git, Docker, LaTeX
- **Languages:** Chinese (Native), English (IELTS 6.5)
