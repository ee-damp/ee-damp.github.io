---
layout: post
title: WSI Classification with Clustering & Fisher Vector Encoding
subtitle: Shounak Das
cover-img: assets/img/Cover_study.jpg
thumbnail-img: ""
tags: [SRE, Blog]
---

### Basic Information

- **Project Title / Domain**: WSI Classification with Clustering & Fisher Vector Encoding
- **Name**: Shounak Das
- **Guide**: Prof. Amit Sethi

### Description of Abstract / Project

Whole Slide Images (WSIs) are high-resolution, gigapixel-sized images that pose significant computational challenges for traditional machine learning models due to their size and heterogeneity. In this project, we developed a scalable and efficient methodology for WSI classification by leveraging patch-based feature extraction, clustering, and Fisher vector encoding.

Initially, the WSIs were divided into fixed-size patches, and deep feature embeddings were extracted from each patch using a pre-trained convolutional neural network (CNN). These patch-level embeddings were then clustered using K-means, where each cluster aggregated semantically similar regions of the WSI. To effectively summarize each cluster, Fisher vector representations were computed by modeling the distribution of patch embeddings in each cluster as a parametric Gaussian mixture model (GMM).

The Fisher vectors from each cluster were concatenated into a high-dimensional feature vector, creating a compact and informative representation of the entire WSI. This feature vector was then used by a classifier to predict the WSI’s diagnostic label. Our approach captured both local and global tissue structures and showed strong performance for large-scale WSI classification, demonstrating superior accuracy and scalability compared to other methods.

### Whom did you work with?

PG students, The prof directly

### Relevant Courses

EE769

### How did you connect with the prof?

I met the professor in the lab one day since I was looking to do a project in machine learning. That led to an RnD project under him, which I really enjoyed, so I continued working with him for my SRE and now my DDP as well.
For finalizing the SRE project, I discussed with his PhD student Ravi (had also worked with him during my RnD)and the professor on how we could do something meaningful based on my RnD work and continue it in some form.

### Expectations from Prof

The professor expects the students to spend a few hours each week in the lab, ideally at least once or twice a week. The more time we can spend, the better. He also encourages regularly discussing progress and doubts with him and the PhD student we’re working under.

I expected guidance on shaping the project direction, and regular feedback on my work. I also looked forward to learning from his experience and research insights throughout the project.

### Logistics of the Project

I met the professor at least once a week for progress updates, as he expects students to stay in regular touch. I was also in frequent contact with the PhD student I was working under.

There was one midterm review (after midsem) with the professor, followed by an end-term evaluation which included a 15-minute presentation with QnA in front of the professor and another external faculty member from EE/CS (like Prof. Kumar Appaiah, Prof. Sharayu Moharir, or Prof. Ajit Rajwade). Along with this, we also had to submit an IEEE-format report detailing the work done during the project.

### Reading Material

I went through a few key papers in detail to understand the core concepts behind WSI classification. These included:
(a) Data Efficient and Weakly Supervised Computational Pathology on Whole Slide Images,
(b) Attention-based Deep Multiple Instance Learning

For the rest, I mostly skimmed through them and directly used their official code from their GitHub repositories to speed up development and focus on building the pipeline efficiently.

### Tools / Simulations / Softwares / Hardwares Used

I worked mostly with Python and used PyTorch for building models. I ran experiments on the lab server to get GPU access. I also used Git for version control and basic Linux commands.

### Outcomes / Deliverables

We were able to develop a scalable approach using patch-based feature extraction, K-means clustering, and Fisher vector encoding to create compact representations of WSIs for classification. The method captured both local and global tissue structures and showed strong performance.

Deliverables:
A 15-minute end-term presentation with Q&A, an IEEE-format report summarizing my work, and the progress made on the project itself in terms of implementation and results.

I was also able to get a publication in ISBI (a medical imaging conference) based on this work, although this wasn’t a hard deliverable expected for the SRE.

### Extension to DDP

Yes, I’m doing my DDP under Prof. Sethi as well, since I really enjoyed working in MEDAL lab during my SRE and RnD project. Although the DDP topic is different from my SRE, continuing in the same lab felt like a natural choice. My current work focuses on applying Vision-Language Models (VLMs) to WSIs, building on my interest in medical imaging and exploring a newer, more impactful research direction.

### Type of Project

implementation-driven

### Connection to DDP

Yes, my SRE helped me get started with my DDP in many ways. It gave me a strong foundation in working with Whole Slide Images (WSIs), understanding the challenges involved, and handling large-scale medical imaging data. I also got hands-on experience with using lab servers, accessing GPUs for training deep learning models, and managing compute resources efficiently. It also helped me get comfortable with the lab environment, the workflow, and collaborating with my professor and PhD student, which made the transition to my DDP much smoother.

### Advice

If you're considering a project under Prof. Sethi, I’d highly recommend it, especially if you're interested in machine learning. He’s very friendly and supportive, and gives you a lot of freedom to explore your own ideas. At the same time, he expects you to be proactive, maintain regular lab presence, and stay in touch with the PhD student you're working under.

That said, make sure to apply or speak to him well in advance, since many students reach out to him for RnD, SRE, and DDP projects and he can only take a limited number of students.

Other EE profs:
Prof. Rajbabu (IP and CV)
Prof. Preeti Rao (Speech and NLP)

Other dept. profs:
Prof. Biplab Banerjee, Prof. Suyash Awate, Prof. Ajit Rajwade
