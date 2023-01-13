---
layout: page
title: Program
permalink: /Program/
nav_order: 3
---

# Schedule

8:50 AM - 5:00 PM (Central Time), Dec 3rd, 2022

| Event | | Time |
| :--- | --- | :--- |
| Opening Remarks | Organizing Team | 8:50-9:00am |
| Invited Talk | Jonas Pfeiffer | 9:00-9:45am |
| Invited Talk | Graham Neubig | 9:45-10:30am |
| Invited Talk | Percy Liang & Ananya Kumar | 10:30-11:15am |
| Break | - | 11:15-11:30am |
| Debate | Sara Hooker & Kyunghyun Cho | 11:30am-12:30pm |
| Lunch | - | 12:30-2:00pm |
| Invited Talk | David Adelani | 2:00-2:45pm |
| Invited Talk | Mike Lewis | 2:45-3:30pm |
| Poster Session | - | 3:30-5:00pm |

# Talk Details

## Jonas Pfeiffer

**Title:** Modular and Composable Transfer Learning

**Abstract:** With pre-trained transformer-based models continuously increasing in size, there is a dire need for parameter-efficient and modular transfer learning strategies. In this talk, we will touch base on adapter-based fine-tuning, where instead of fine-tuning all weights of a model, small neural network components are introduced at every layer. While the pre-trained parameters are frozen, only the newly introduced adapter weights are fine-tuned, achieving an encapsulation of the down-stream task information in designated parts of the model. We will demonstrate that adapters are modular components which can be composed for improvements on a target task and how they can be used for out of distribution generalization on the example of zero-shot cross-lingual transfer. Finally, we will discuss how adding modularity during pre-training can mitigate catastrophic interference and consequently lift the curse of multilinguality.

**Bio:** Jonas Pfeiffer is a Research Scientist at Google Research. He is interested in modular representation learning in multi-task, multilingual, and multi-modal contexts, and in low-resource scenarios. He worked on his PhD at the Technical University of Darmstadt,  was a visiting researcher at the New York University and a Research Scientist Intern at Meta Research. Jonas has received the IBM PhD Research Fellowship award for 2021/2022. He has given numerous invited talks at academia, industry and ML summer schools, and has co-organized multiple workshops on multilinguality and multimodality.

**Recording:**

<div id="presentation-embed-38993239"></div>
<script src="https://slideslive.com/embed_presentation.js"></script>
<script>
  embed = new SlidesLiveEmbed("presentation-embed-38993239", {
    presentationId: "38993239",
    autoPlay: false,
    verticalEnabled: true,
  });
</script>

## Graham Neubig

**Title:** Automating Auxiliary Learning

**Abstract:** When faced with data-starved or highly complex end-tasks, it is commonplace for machine learning practitioners to introduce auxiliary objectives as supplementary learning signals. While much work has been done to formulate useful auxiliary objectives, their construction is still an art which proceeds by slow and tedious hand-design. Intuitions about how and when these objectives improve end-task performance have also had limited theoretical backing. In this talk I will present two works. First, I will discuss the widely used pre-train and fine-tune paradigm, and argue that when we know an end-task of interest before-hand we should also consider joint multi-task learning as a credible alternative. I will discuss an algorithm that we propose, META-TARTAN, that allows us to automatically learn the weights for the multi-task objective. Second, I will present AANG, an approach for automatically generating a suite of auxiliary objectives. AANG deconstructs existing objectives within a novel unified taxonomy, identifying connections between them, and generating new ones based on the uncovered structure. This leads us to a principled and efficient algorithm for searching the space of generated objectives to find those most useful to a specified end-task. We empirically verify that our automated auxiliary learning pipeline leads to strong improvements over competitive baselines across continued training experiments on a pre-trained model on 5 NLP end-tasks.

**Bio:** Graham Neubig is an associate professor at the Language Technologies Institute of Carnegie Mellon University and CEO of Inspired Cognition. His research focuses on natural language processing, with a focus on multilingual NLP, natural language interfaces to computers, and machine learning methods for NLP system building and evaluation. His final goal is that every person in the world should be able to communicate with each-other, and with computers in their own language. He also contributes to making NLP research more accessible through open publishing of research papers, advanced NLP course materials and video lectures, and open-source software, all of which are available on his web site.

## Percy Liang & Ananya Kumar

**Title:** Fine-Tuning without Distortion: Improving Robustness to Distribution Shifts

**Abstract:** Fine-tuning foundation models (such as BERT or CLIP) is one of the most successful ways to achieve high accuracy. But achieving high in-distribution accuracy is not enough: high-stakes applications such as self-driving cars, medical diagnosis, and poverty mapping, also require models that generalize to circumstances not seen in the fine-tuning distribution. To examine this, we also evaluate models on out-of-distribution (OOD) test data. We show that standard full fine-tuning of all the model’s parameters can distort pretrained information and underperform OOD. Instead, we explain why selectively tuning parts of the model (e.g., prefixes, linear probes, embedding layers) can preserve pretrained information and lead to better OOD performance. Our analysis suggests the easy two-step strategy of linear probing then full fine-tuning (LP-FT), which improves pretrained features without distortion, and leads to even higher accuracies. These works underscore the importance of preserving pretrained knowledge when using powerful pretrained models.

**Percy:** Percy Liang is an Associate Professor of Computer Science at Stanford University (B.S. from MIT, 2004; Ph.D. from UC Berkeley, 2011) and the director of the Center for Research on Foundation Models.  His research spans many topics in machine learning and natural language processing, including robustness, interpretability, semantics, and reasoning.  He is also a strong proponent of reproducibility through the creation of CodaLab Worksheets.  His awards include the Presidential Early Career Award for Scientists and Engineers (2019), IJCAI Computers and Thought Award (2016), an NSF CAREER Award (2016), a Sloan Research Fellowship (2015), a Microsoft Research Faculty Fellowship (2014), and multiple paper awards at ACL, EMNLP, ICML, and COLT.

**Ananya:** Ananya Kumar is a PhD student at Stanford University. His research focuses on understanding and developing better algorithms for pretraining and fine-tuning, and building ML models that are robust to distribution shifts. He has done some of the first work on theoretically analyzing fine-tuning and self-supervised learning. His theories and methods have led to practical methods and state-of-the-art accuracies on many datasets including ImageNet and WILDS. His work has been recognized by an SGF Fellowship, and oral and spotlight presentations at ICLR, ICML, and NeurIPS.

## David Adelani

**Title:** Cross-lingual Transfer for Named Entity Recognition: A study on African Languages

**Abstract:** Multilingual pre-trained language models (PLMs) have demonstrated impressive performance on several downstream tasks for both high-resourced and low-resource languages. However, there is still a large performance drop for languages unseen during pre-training, especially African languages. Similarly, in limited labelled data scenario, cross-lingual transfer learning with PLMs provides an opportunity for fast adaptation to new languages in both zero- and few-shot scenarios. In this talk, we will discuss five components of effective cross-lingual transfer for named entity recognition (NER) task including (1) availability of typologically diverse multilingual benchmark datasets for transfer (2) development of highly effective and easy-to-adapt multilingual PLMs (3) building effective and parameter-efficient cross-lingual transfer frameworks (4) making use of the same domain for both source and target transfer languages (5) choosing the best source transfer language for adaptation. Our evaluation on MasakhaNER -- a benchmark dataset for 21 African languages shows that each of these components significantly improves transfer results.

**Bio:** David Ifeoluwa Adelani is a research fellow at University College London, United Kingdom. and an active member of Masakhane NLP - a grassroots organization whose mission is to strengthen and spur NLP research in African languages, for Africans, by Africans. Previously, he was a PhD student in computer science at Saarland University, Saarbrücken, Germany. His current research focuses on NLP for under-resourced languages with a focus on African languages, multilingual representation learning, and privacy in NLP.

## Mike Lewis

**Title:** Training Language Models to Negotiate in the Game of Diplomacy

**Abstract:** Despite much progress in training AI systems to imitate human language, building agents that use language to communicate intentionally with humans in interactive environments remains a major challenge. I will describe how we adapted language models to negotiate with people, reaching human-level performance in Diplomacy. A typical game involves generating hundreds of messages, which must be grounded in the game state, dialogue history, and the agent’s intended actions - all in a domain far from the pre-training data. The core of our approach is a method for linking language models to a symbolic planning module. Across 40 games of an anonymous online Diplomacy league, Cicero achieved more than double the average score of the human players and ranked in the top 10% of participants who played more than one game.

**Bio:** Mike Lewis is a research scientist at FAIR Seattle, working on representation learning and reasoning for natural language. Previously he was a postdoc at the University of Washington (working with Luke Zettlemoyer), developing search algorithms for neural structured prediction. He has a PhD from the University of Edinburgh (advised by Mark Steedman) on combining symbolic and distributed representations of meaning. He received a Best Paper award at EMNLP 2016, Best Resource Paper at ACL 2017, and Best Paper Honourable Mention at ACL 2018. His work has been extensively covered in the media, with varying levels of accuracy.
