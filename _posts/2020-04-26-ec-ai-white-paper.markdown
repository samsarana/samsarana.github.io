---
layout: post
title: A critique of the European Commission's white paper on AI
date:   2020-04-26 16:00:00 +1300
categories: posts
comments: true
image: /assets/images/ec-ai-white-paper.png
---

The European Commission recently published a [white paper](https://ec.europa.eu/info/sites/info/files/commission-white-paper-artificial-intelligence-feb2020_en.pdf) (summarised [here](https://us19.campaign-archive.com/?u=eaeece823e606d2458a568db9&id=11daa72ee7)) outlining their current thinking on policies and strategies to help Europe harness the benefits of AI, whilst mitigating its risks. After reading the paper, I have three main critiques of its proposals.

## 1) Some significant risks are not addressed
In Section 5A, the white paper claims that the “main risks related to the use of AI” are 1) “risks to fundamental rights” (e.g. the design of AI algorithms or bias in the training data undermines rights to a fair trial or leads to discrimination based on sex, race, etc.) and 2) “risks for safety” (e.g. the failure of an image recognition algorithm in an autonomous car causes a crash).

It is not clear that these are in fact the main risks from AI. For example, AI may massively increase inequality: the advent of advanced AI could lead to its developers reaping a windfall profit, whilst rendering a proportion of the population unemployed[^1]. Alternatively, widespread optimization for easy-to-measure goals (enabled by machine learning) such as “reduce reported crime” or “increase reported life satisfaction” could lead to a world which is optimized for these proxies, rather than what we actually want[^2]. Equally, AI could facilitate the development of extremely powerful weapons which could be misused or accidentally triggered.

To alleviate this issue with the white paper, I would survey experts for estimates of the likelihood and severity of various risks (in fact I am currently doing something similar). These estimates could then be used to inform a discussion which focuses on the most likely and severe risks.

## 2) It will be difficult to enforce the requirements for “high-risk” systems
In Section 5D, the white paper specifies six broad types of legal requirements on those responsible for “high-risk” AI systems. It makes the obvious point that these requirements need to be “effectively enforced … by competent national and European authorities”.

However, progress in AI happens much faster than regulation is developed and implemented in the public sector [3]. Organisations that develop and deploy AI systems tend to be creative and agile, spotting opportunities and acting quickly to capitalise on them. Consider, for example, Cambridge Analytica, who recognised the potential of AI methods to swing “persuadable” voters in the 2016 US election, long before anyone else realised what they had done (in 2018). Yet the bureaucratic processes of the public sector tend to move slowly. For instance, the white paper mentions that “any changes [to the European regulatory framework] should be limited to clearly identified problems for which feasible solutions exist”; but as the Cambridge Analytica case demonstrates, harm can be caused long before a problem is fully and clearly identified.

Accordingly, new governance institutions, such as [global regulatory markets](https://arxiv.org/pdf/2001.00078.pdf), may be required for regulators to keep up with the pace of AI progress.

## 3) The need for global coordination
If Europe’s regulation is more stringent than in other areas, the development and deployment of AI may be slower, causing Europe to benefit less. However, if Europe’s regulation is more relaxed, other areas will be incentivised to loosen their regulation, in the interests of remaining competitive. These harmful race dynamics could lead to insufficiently tight regulation in Europe or other areas, undermining the white paper’s objective of fostering trust.

Furthermore, it is plausible that in the coming years, key global actors will need to coordinate to slow down progress in the capabilities of AI systems, while work is done to ensure the safety of those systems. This could happen, for instance, if the [alignment tax](https://www.effectivealtruism.org/articles/paul-christiano-current-work-in-ai-alignment/) turns out to be high, or we are faced with an [intelligence explosion](https://wiki.lesswrong.com/wiki/Intelligence_explosion). Such coordination will be impossible if each region has its own approach to AI regulation.

To alleviate this issue, the white paper should analyse the possibility of coordination with other important regions (e.g. the US, UK and China). I would start by conducting case studies of global coordination (or lack thereof) in the context of the Internet, nuclear or biological weapons, and pandemics.

<!-- Footnotes -->
[^1]: This kind of risk is analysed in the Future of Humanity Institute's [report](https://www.fhi.ox.ac.uk/wp-content/uploads/Windfall-Clause-Report.pdf) on the Windfall Clause.
[^2]: This kind of risk is outlined by Paul Christiano in this [blog post](https://www.lesswrong.com/posts/HBxe6wdjxK239zajf/what-failure-looks-like#Part_I__You_get_what_you_measure).