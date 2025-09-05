---
layout: single
permalink: /keynotes/
title: "Keynotes"
header:
  overlay_image: /assets/uni-bielefeld.jpg
  overlay_filter: 0.7 
  image_description: 
  caption: "Photo credit: [Andy1982, CC BY-SA 3.0](https://commons.wikimedia.org/wiki/File:Uni_Bielefeld.jpg) via Wikimedia Commons"
toc: false
---


* **Arabella Sinclair**: [The Many Reasons for Repetition in Dialogue](#arabella-sinclair)
* **Robert D. Hawkins**: [Foraging for Common Ground](#robert-hawkins)
* **David Schlangen**: [Meaningful Interaction with Unreal Speakers?](#david-schlangen)


## [Arabella Sinclair](https://j-anie.github.io)

<img src="../assets/arabella-sinclair.jpg" width="150" alt="Photo of Arabella Sinclair" />

**Title:** The Many Reasons for Repetition in Dialogue

**Abstract:** From children echoing caregivers to learn how to form utterances, to second-language learners mirroring teachers to gain fluency, to collaborators navigating knowledge asymmetries to ground goal-oriented dialogue, repetition shapes how we communicate and coordinate. This talk examines the multiple functions of repetition in conversational interaction, including easing processing demands, facilitating grounding, providing feedback, and signalling social alignment. I will show that repetition in human-human dialogue occurs across different levels of communication—lexical, structural, and gestural; that it is local in scope; varies with speaker relationships and communicative abilities; and can facilitate communicative success. I will then turn to repetition in Language Models. When generating next utterances within a dialogue context, LMs mirror some of the repetition behaviour associated with efficient collaborative dialogue in humans, including local repetition of lexical and syntactic forms. Moreover, in a behavioural task setting similar to priming studies in psychology, LMs’ expectations about upcoming structural material are modulated by similar contextual cues as in humans. In the final part of this talk, I will move beyond these broader parallels in repetition patterns to using LM priming effects to predict item-level neural correlates of priming in humans. Somewhat surprisingly, LMs do not robustly provide predictive power beyond a baseline model with established predictors. Comparing effects when prime and target are either linearly or hierarchically related, LMs more accurately predict human responses when the prime and target share sequence-level repetitions. 

Altogether, while LMs exhibit superficially similar patterns of repetition and expectation as humans, this does not imply that the mechanisms underlying repetition are the same. Understanding and potentially adapting these mechanisms to more closely reflect human reasons for repetition could enable a deeper, more meaningful alignment between human and artificial dialogue systems.


## [Robert D. Hawkins](https://rdhawkins.com)
<img src="../assets/robert-hawkins.jpg" width="150" alt="Photo of Robet Hawkins" />

**Title:** Foraging for Common Ground

**Abstract:** How do two minds reach mutual understanding? Meaningful dialogue requires speakers to do more than simply exchanging coherent messages. They must engage in an interactive negotiation over meaning, coordinating on ad hoc interpretations that may not exist outside the conversational context. In this talk, I'll sketch out a computational account of this negotiation process. In the first half of the talk, I'll argue for an inferential model of common ground. In this model, speakers maintain uncertainty about their partners' likely intended meaning and systematically update their beliefs based on feedback from their partner's responses. In the second half of the talk, I'll explore how this learning process may guide conversational dynamics. I examine patterns of topic shifts in a large corpus of natural conversations between strangers, finding that these conversations exhibit foraging dynamics. Speakers consistently begin in regions of broader consensus before dispersing to more specific, idiosyncratic regions. This pattern occurs both within individual topic boundaries and across entire conversations, suggesting that speakers may be guided by the goal of seeking common ground. Together, these findings point to a dynamic feedback loop at the heart of meaningful dialogue: increasing common ground enables speakers to actively steer conversations toward more idiosyncratic domains, while successful navigation of these personal territories licenses stronger social inferences that become part of subsequent common ground. These insights suggest new directions for computational dialogue systems that can engage in more adaptive meaning-making.


## [David Schlangen](https://www.ling.uni-potsdam.de/~das/)

<img src="../assets/david-schlangen.jpg" width="150" alt="Photo of David Schlangen" />

**Title:** Meaningful Interaction with Unreal Speakers?

**Abstract:** 
The last time that the semdial workshop took place in Bielefeld was almost 25 years ago, in 2001. Incidentally, this was also where my own first academic presentation happened (Schlangen, Lascarides, & Copestake 2001). This is too much symbolism to ignore, so I will use the occasion of "coming back" to reflect on what happened in these (almost) 25 years, to my research on "(formal and computational approaches to) the semantics and pragmatics of dialogue", and the field in general. (Because, oh boy, did something happen.)

The semdial workshop series, at least in my understanding, was founded on the idea that bringing together formal, empirical, and computational approaches to the study of dialogue would be possible in a certain way: Formal studies would be informed by empirical studies and in turn help guide computational modelling attempts, which would not need distinguish very clearly between being models of cognition and being human/computer interfaces, and in either way would be evaluated for how closely they mirror empirical findings. This particular way of setting up the relations between the constituent parts has been strained for a while now, with computational modelling becoming more and more "empirical" and machine learning-guided. But it has been exploded by modelling approaches that not even pretend to pay attention to any prior knowledge on the semantics and pragmatics of dialogue, and still (apparently?) succeed better than anything before in "modelling dialogue". (Yes, I'm talking about "chat optimized LLMs".)

In my talk, I will try to pick up the pieces, and hopefully show how they can be reassembled: First, I will show that the kind of analyses that we do are useful to understand the status of these "unreal speakers". In particular, I will analyse the speech act of "assertion", and show that LLMs perform an atypical variant of it, that in its consequences and how it relates to "real assertion" is not yet well understood. If this analysis is correct, this gives us an interesting new task, which is to devise a normative pragmatics of how the semantics and pragmatics of dialogue with machines ought to be understood and designed. As a direct consequence of this, the second part will make the claim that now that we see what "human-likeness" of human computer interfaces can lead to, we need to be more explicit about or goals for designing interfaces, and especially about how to separate desirable properties (ease of use) from potentially undesirable (blurring the boundaries between real and unreal speakers). In the final part, I will talk about how in my research group we set up the relation between non-computational models of cognition and computational behavioural models. In particular, I will talk about our "clembench" framework for evaluating LLMs through Dialogue Games, and very recent results on post-training of LLMs in this framework.


