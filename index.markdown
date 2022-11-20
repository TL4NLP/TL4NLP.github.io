---
layout: page
title: Transfer Learning for NLP Workshop 2022
nav_order: 1
---

# Abstract

Transfer learning has become ubiquitous in natural language processing due in part to the ease of access to large pre-trained language models (PLM). Current transfer learning methods, combined with PLMs, have seen outstanding successes in transferring knowledge to new tasks, domains, and even languages. However, existing methods still suffer from some common weaknesses that restrict their potential applications.

**One particular hope for this workshop is to help to answer the question:**
*Can we characterize the transfer behaviors between source and target tasks/domains/languages in terms of their fundamental properties?*

A current weakness of transfer learning is the limited understanding of when transfer will lead to performance improvements, or predicting how positive or negative the effect of transfer will be. Although negative transfer is a known issue in transfer learning, multitask learning, continual learning, and domain adaptation, the causes remain unclear. As research efforts scale up to address an ever expanding set of domains, tasks, and languages, understanding positive and negative transfer becomes increasingly valuable.

**Another hope we have for this workshop is to help answer the question:**
*Given a specific set of circumstances (task, dataset size, available resources) how can we efficiently and effectively transfer knowledge?*

With the ever-increasing size of language models, fine-tuning on downstream tasks becomes increasingly expensive (computationally and fiscally). This can lead to unequal opportunities for the application of such large models. Recent works have proposed prompting and parameter efficient fine-tuning methods to mitigate this risk and ensure equal access for underrepresented groups and languages. However, these methods still lack consistently good performance across different tasks, varying sizes of data resources, and wordings of textual prompts.

## Topics

We welcome archival and non-archival submissions on theory and applications that relate to transfer learning in NLP including, but not limited to (see the [call for papers](/Calls/) for more details):
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

# News
* 07/27/2022: First Call for Papers is out! Check it out [here](/Calls/)
* 08/01/2022: Now accepting submissions on [OpenReview](https://openreview.net/group?id=NeurIPS.cc/2022/Workshop/TL4NLP)

# Important Dates

* ~~**Sep 22nd AoE**: OpenReview submission deadline~~
* **Sep 30th AoE**: Extended OpenReview submission deadline
* ~~**Oct 14th AoE**: Acceptance notifications~~
* **Oct 20th AoE**: Acceptance notifications
* **Nov 3rd AoE:** Camera-ready submission deadline
* **December 3rd:** In-person workshop

# Invited Speakers

<table>
    <tbody>
        <tr>
            <td width="33%"><a href="https://scholar.google.co.uk/citations?user=SnQnQicAAAAJ&hl=en"><img src="images/mike_lewis.jpg" width="200px" style="border-radius: 25%"></a></td>
            <td width="33%"><a href="https://cs.stanford.edu/~pliang/"><img src="images/percy.jpg" width="200px" style="border-radius: 25%"></a></td>
            <td width="33%"><a href="http://www.phontron.com/"><img src="images/graham.jpg" width="200px" style="border-radius: 25%"></a></td>
        </tr>
        <tr>
            <td><a href="https://www.cs.washington.edu/people/faculty/lsz">Mike Lewis (FAIR)</a></td>
            <td><a href="https://cs.stanford.edu/~pliang/">Percy Liang (Stanford)</a></td>
            <td><a href="http://www.phontron.com/">Graham Neubig (CMU)</a></td>
        </tr>
    </tbody>
</table>
<table>
    <tbody>
        <tr>
            <td width="33%"><a href="https://dadelani.github.io/"><img src="images/david.jpg" width="200px" style="border-radius: 25%"></a></td>
            <td width="33%"><a href="https://pfeiffer.ai/"><img src="images/jonas.jpg" width="200px" style="border-radius: 25%"></a></td>
            <td width="33%"><a href="https://ananyakumar.wordpress.com/"><img src="images/ananya.png" width="200px" style="border-radius: 25%"></a></td>
        </tr>
        <tr>
            <td><a href="https://dadelani.github.io/">David Adelani (Universität des Saarlandes)</a></td>
            <td><a href="https://pfeiffer.ai/">Jonas Pfeiffer (Google Research)</a></td>
            <td><a href="https://ananyakumar.wordpress.com/">Ananya Kumar (Stanford)</a></td>
        </tr>
    </tbody>
</table>

# Invited Debaters

<table>
    <tbody>
        <tr>
            <td width="50%"><a href="http://www.sarahooker.me/"><img src="images/sara.jpeg" width="200px" style="border-radius: 25%"></a></td>
            <td width="50%"><a href="https://kyunghyuncho.me/"><img src="images/kyunghyun.jpg" width="200px" style="border-radius: 25%"></a></td>
        </tr>
        <tr>
            <td><a href="http://www.sarahooker.me/">Sara Hooker (Cohere For AI)</a></td>
            <td><a href="https://kyunghyuncho.me/">Kyunghyun Cho (NYU & Genentech)</a></td>
        </tr>
    </tbody>
</table>


# Workshop Organizers
<table>
    <tbody>
        <tr>
            <td width="33%"><a href="https://alon-albalak.github.io/"><img src="images/alon.jpg" width="200px" style="border-radius: 25%"></a></td>
            <td width="33%"><a href="https://violet-zct.github.io/"><img src="images/chunting.jpg" width="200px" style="border-radius: 25%"></a></td>
            <td width="33%"><a href="http://colinraffel.com/"><img src="images/colin.jpg" width="200px" style="border-radius: 25%"></a></td>
        </tr>
        <tr>
            <td><a href="https://alon-albalak.github.io/">Alon Albalak (University of California, Santa Barbara)</a></td>
            <td><a href="https://violet-zct.github.io/">Chunting Zhou (FAIR)</a></td>
            <td><a href="http://colinraffel.com/">Colin Raffel (UNC Chapel Hill & Hugging Face)</a></td>
        </tr>
        <tr>
            <td width="33%"><a href="https://research.google/people/107300/"><img src="images/deepak.jpg" width="200px" style="border-radius: 25%"></a></td>
            <td width="33%"><a href="https://ruder.io/"><img src="images/sebastian.jpg" width="200px" style="border-radius: 25%"></a></td>
            <td width="33%"><a href="https://xuezhemax.github.io/"><img src="images/xuezhe.png" width="200px" style="border-radius: 25%"></a></td>
        </tr>
        <tr>
            <td><a href="https://research.google/people/107300/">Deepak Ramachandran (Google Research)</a></td>
            <td><a href="https://ruder.io/">Sebastian Ruder (Google Research)</a></td>
            <td><a href="https://xuezhemax.github.io/">Xuezhe Ma (USC ISI)</a></td>
        </tr>
    </tbody>
</table>

# Program Committee

Aishwarya Kamath - New York University

Akshat Shrivastava - Meta

Aleksandra Piktus - HuggingFace

Alfonso Amayuelas - University of California, Santa Barbara

Alham Fikri Aji - Amazon

Chenghao Yang - University of Chicago

David Ifeoluwa Adelani - Universität des Saarlandes

Emmy Liu - Carnegie Mellon University

Feng Cheng

Genta Indra Winata - Bloomberg

Hao Zhu - Carnegie Mellon University

I-Hung Hsu - University of Southern California

Ivan Vulić - University of Cambridge

Jason Phang - New York University

Jiao Sun - University of Southern California

Jonas Pfeiffer - Google Research

Jun Yan - University of Southern California

Junxian He - Carnegie Mellon University

Kexun Zhang - University of California, Santa Barbara

Kris Cao - DeepMind

Mengzhou Xia - Princeton University

Michael Saxon - University of California, Santa Barbara

Michihiro Yasunaga - Stanford University

Mozhdeh Gheini - University of Southern California

Nicholas Lourie - AI2

Nuan Wen - University of Southern California

Patrick Fernandes - Carnegie Mellon University

Phillip Rust - University of Copenhagen

Prateek Yadav - University of North Carolina, Chapel Hill

Qinyuan Ye - University of Southern California

Shamsuddeen Hassan Muhammad - Bayero University, Kano

Tianyi Zhang - Stanford University

Trapit Bansal - OpenAI

Tu Vu - University of Massachusetts, Amherst

Vamsi Aribandi - ASAPP

Weixi Feng - University of California, Santa Barbara

Xi Ye - University of Texas, Austin

Xiang Kong - Carnegie Mellon University

Xiang Lisa Li - Stanford University

Xin Xu - Google Research

Xinyi Wang - Carnegie Mellon University

Zhisong Zhang - Carnegie Mellon University

Zhiyu Chen - Meta

Zi-Yi Dou - University of California, Los Angeles
