---
layout: page
title: Call For Papers
permalink: /Calls/
nav_order: 2
---

Transfer learning from large pre-trained language models (PLM) has become the de-facto method for a wide range of natural language processing tasks. Current transfer learning methods, combined with PLMs, have seen outstanding successes in transferring knowledge to new tasks, domains, and even languages. However, existing methods (including fine-tuning, in-context learning, parameter-efficient tuning, and semi-parametric models with knowledge augmentation) still lack consistently good performance across different tasks and domains, varying sizes of data resources, and diverse textual inputs. 

This workshop aims to invite researchers from different backgrounds to share their latest work in efficient and robust transfer learning methods, discuss challenges and risks of transfer learning models when deployed in the wild, understand positive and negative transfer, and also debate over future directions. We welcome submissions on several topics but not limited to:

- **Robust transfer learning for various NLP applications**. PLMs are usually trained with (masked) language modeling as the learning objective on generic large corpora, which is different from the downstream task objective and data distribution. This discrepancy between the pre-training stage and the adaptation stage can pose significant challenges to the robust deployment in real-world applications. We encourage submissions that bridge the gap between pre-training and transfer learning for robust generalization to new domains, tasks and languages.

- **Data-efficient and compute-efficient transfer learning**. As researchers scale up the size of PLMs, this enables the scaling power in language understanding while bringing great challenges — using these large PLMs are becoming increasingly expensive (computationally and fiscally). We welcome methods that use PLMs in a data-efficient and compute-efficient way, including few-shot learning and parameter/inference-efficient transfer learning.

- **Characterization of positive and negative transfer**. A current weakness of transfer learning is the limited understanding of when transfer from a source task/domain/language will lead to performance improvements in another, or predicting how positive or negative the effect of transfer will be. Although negative transfer is a known issue in transfer learning, multitask learning, multilingual training, continual learning, and domain adaptation, the causes remain unclear. As research efforts scale up to address an ever expanding set of domains, tasks, and languages, understanding positive and negative transfer becomes increasingly valuable.

- **Benchmarks and evaluations on transfer learning**.  Most standard NLP benchmarks and evaluations are English-centric or only consider the setting where training and test data are i.i.d. and static. Recent years have witnessed more diverse evaluation protocols, such as settings with distribution shift and multilingual benchmarks. We are interested in evaluation setups that take into account real-world distribution shifts, e.g. users with different cultural backgrounds and streams of dynamically-changing data.

## Important Dates

* **Sep 22nd AoE:** OpenReview submission deadline
* **Oct 14th AoE :** Acceptance notifications
* **Nov 3rd AoE:** Camera-ready submission deadline
* **December 3rd:** In-person workshop

## Submission Guidelines

**Submission URL**: [https://openreview.net/group?id=NeurIPS.cc/2022/Workshop/TL4NLP](https://openreview.net/group?id=NeurIPS.cc/2022/Workshop/TL4NLP)

**Format**: All submissions must be in PDF format. We have provided a modified `.sty` file [here](neurips_2022.sty) to be used with the official NeurIPS template found on the [NeurIPS website](https://neurips.cc/Conferences/2022/PaperInformation/StyleFiles). All submissions should have **at least 4 pages and at most 8 pages** of content, including all figures and tables; unlimited pages are allowed for reference and supplementary materials. One additional content page is allowed for the camera-ready version.

**Archival vs. Non-Archival**. We will accept submissions as either Archival or Non-Archival. Archival papers, if accepted, will be included in the official workshop proceedings, while non-archival papers will only have a camera-ready version shared on the workshop website. For non-archival papers **we highly encourage submissions shorter than 8 pages** that demonstrate novel but preliminary results. Non-archival submissions can be subsequently or concurrently submitted to other venues.

**Double-blind review**: We will follow a double-blind review process. Submissions will be peer-reviewed by at least 2 reviewers. As an author, you are responsible for anonymizing your submission by not including any identifying information (author names, affiliations, acknowledgements, etc) in anywhere of the submission.

**Contact**: Please contact us at <tl4nlp.workshoporganizers@gmail.com> if you have any questions.

<!-- ## Topics

We welcome archival and non-archival submissions on theory and applications that relate to transfer learning in NLP including, but not limited to:
- Predicting and quantifying transferability
- Characterizing positive and negative transfer
- Modular Transfer Learning
- Parameter-efficient and Computationally Efficient Transfer
- Domain Adaptation
- Task Transfer
- Multitask, Continual, and Meta Learning
- Cross-lingual Transfer
- Robustness and Generalizability
- Datasets and Tasks for Pre-training and Intermediate fine-tuning. 
- Inductive Transfer Bias in Model Architectures
- Unsupervised/Self-supervised Learning for Transfer (eg. GPT-3)
- Multitask Learning for zero-shot task generalization (eg. T0, FLAN, etc.)



## Formats

TBA

## Submission Guidelines

TBA -->

