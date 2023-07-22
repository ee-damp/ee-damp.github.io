---
layout: post
title: Learning to Select a Subset of Training Examples to Generalize Efficient Model Training
subtitle: Eeshaan Jain
cover-img: assets/img/Cover_study.jpg
thumbnail-img: ""
share-img: ""
readtime: true
tags: [Academic, BTP, Blog]
---

### Basic Information

- **Project Title**: Learning to Select a Subset of Training Examples to Generalize Efficient Model Training
- **Name**: Eeshaan Jain
- **Project**: BTP
- **Semester(s)**: 8
- **Guide**: Abir De

### Abstract


Existing subset selection methods for efficient learning predominantly employ
discrete combinatorial and model-specific approaches which lack generalizability.
For an unseen architecture, one cannot use the subset chosen for a different model.
To tackle this problem, we propose SUBSELNET, a trainable subset selection
framework, that generalizes across architectures. Here, we first introduce an
attention-based neural gadget that leverages the graph structure of architectures and
acts as a surrogate to trained deep neural networks for quick model prediction. Then,
we use these predictions to build subset samplers. This naturally provides us two
variants of SUBSELNET. The first variant is transductive (called as Transductive10 SUBSELNET) which computes the subset separately for each model by solving
a small optimization problem. Such an optimization is still super fast, thanks to
the replacement of explicit model training by the model approximator. The second
variant is inductive (called as Inductive-SUBSELNET) which computes the subset
using a trained subset selector, without any optimization. Our experiments show
that our model outperforms several methods across several real datasets.
### Any courses you completed relevant to the project


Introduction to ML Course + CS769 + CS768
### Describe your experience on the project


What was your motivation for choosing this project and/or this guide?
Over the summer of my 2nd year and 5th semester, I took and read a lot of stuff on graphs, ML, and optimization - which led me to be enthusiastic about an intersection of these. Only a few professors in the institute work in these, and Prof. Abir De is one of those. The project topic came from a drawback we saw in many of the methods being published, and we worked to improve it.

What was the type of work, e.g.-theoretical, coding-heavy?
The initial phase was slightly theoretical, though the overall project was very coding-heavy and empirical.

What was the workload?
This project started before my 8th semester when I did my BTP, but the workload was high (a few hours per day consistently).

Any publication/possibility of a publication based on the work done as a part of the project?
The work has been submitted to a top-tier conference.

Will you be working on any extension to the project?
Some works can arise as future directions of the project; however, I will not be working on these.

### Describe your experience with the guide


How involved was the guide?
The guide was involved in the project and guided me through regular meetings.

Frequency and structure of meetings?
The meetings with the professor were regular but spontaneous (whenever something didn't work or there was an update). However, the BTP was also done with Google, so there were seldom meetings with them.

How approachable was the guide for questions/doubts?
Very approachable and cleared all doubts instantly.

What was the evaluation like?
Since the project was targeted toward a paper and I worked immensely on it, there was no separate evaluation. The BTP report and presentation were given to Prof. Jayakrishnan Nair from the EE Department, and he asked some questions regarding methodology. 
### Any advice for anyone considering a project under the same guide? Any other professors working in similar fields?


Any advice for anyone considering a project under the same guide?
I want to point out that since the project might target a project a publication, the workload might be intense at times (such as working extremely long hours continuously for weeks) but rewarding.

Are any other professors working in similar fields?
The C-MInDS website will give a good overview of the professors' research fields. However, as far as I know (which might be an incomplete list): Prof Ganesh and Prof. Soumen from CSE work in similar fields.