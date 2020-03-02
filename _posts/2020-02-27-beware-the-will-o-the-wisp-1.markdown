---
layout: post
title:  Beware the will-o’-the-wisp! and other lessons (Part I)
date:   2020-02-27 17:50:00 +1300
categories: posts
comments: true
---

Last year I wrote a master’s thesis, which proved to be a pretty challenging experience. If I could go back in time and help out Sam-one-year-ago, this is the advice I would have given him.

This first post covers two lessons that I expect might be helpful to beginner researchers in scientific or analytic disciplines, while those in the [second post](/posts/2020/03/02/beware-the-will-o-the-wisp-2.html) apply to beginner researchers in general.

## 1) Don’t try to “make it work”

The goal of my thesis was to implement a method to solve a certain problem more efficiently than in previous work, or in other words, to “make the method work”[^1]. I think this choice of goal has (and had for me) three undesirable side-effects:

1. It’s bad for mental health---because “doing well” means “making the method work”, which makes it easy to worry about failure every time it seems like the method might not work.
    
2. It discourages a curious, scientific mindset, and makes it harder to notice confusion[^2]---because often, “following the evidence where it leads” and “being confused” are antithetical to “making it work as soon as possible”.
    
3. If the method fails, then the project is unlikely to make an interesting contribution. This is especially true if it’s hard to know why it failed---because in this case, it’s hard to say whether it’s due to faulty implementation, or the method not working in general.

What are some alternative goals? For my thesis, a goal of “gathering information about whether the method works, and then testing hypotheses to explain its success/failure” would have been a good bet. This is a subtle reframing, but it alleviates the three negative side-effects mentioned above:

1.  “Doing well” only means “gathering information” and “testing hypotheses”, which, sure, are still tricky and failure prone, but don’t require betting on an uncontrollable outcome (the method working). It’s much easier to take steps that will lead predictably to success.
    
2.  I claim that “following the evidence where it leads”, “noticing confusion” and other good scientific practices are the best strategy for succeeding at this kind of goal.
    
3.  If the method fails, the hypotheses explaining the failure could inform future progress on the problem by suggesting possible improvements to the method, which is still an interesting result.  

I think the idea of reframing a goal to have these three properties is similar to [leaving a line of retreat](https://www.lesswrong.com/posts/3XgYbghWruBMrPTAL/leave-a-line-of-retreat), except applied to research goals rather than dearly held beliefs. Another way of stating it would be that it’s desirable to have research goals which fail gracefully. I’d be curious if anyone can think of general ways to do this kind of reframing.

## 2) Check *all* the baselines

I was aware of the advice that in interpreting results, it’s important to check the performance of baselines (i.e. simple/off-the-shelf/brute force methods), in order to know whether your new fancy method is actually making a contribution.

For one part of my problem, I checked two such baselines[^3], which ticked that box in my mind. However it turned out that there was another very simple method[^4] which (quite unexpectedly) solved it. I could have saved a week of meaningless experiments if I had spent a few minutes brainstorming other possible baselines before trying my method.

Check out my [next post](/posts/2020/03/02/beware-the-will-o-the-wisp-2.html) for two more lessons!


<!-- Footnotes -->
[^1]: For those who like concreteness, the problem was [deep RL from human preferences](https://arxiv.org/pdf/1706.03741), and the method was to query the human for their preferences about the agent’s behaviour that would be *most informative*, rather than querying at random.
[^2]: If this term is new to you, the ability to “notice confusion” means: when you see something odd - something that doesn't fit with what you expected, given your other beliefs, being able to promote this realisation to conscious attention and think "I notice that I am confused" (explanation borrowed from [here](https://www.rationality.org/resources/updates/2013/when-do-you-notice-confusion)). See [these posts](https://www.lesswrong.com/s/zpCiuR4T343j9WkcK) for lots more about that!
[^3]: Concretely: using a randomly initialised policy, and making queries to the human uniformly at random.
[^4]: Concretely: using a randomly initialised reward model. Unbelievably, for several of the random seeds I tried, training a policy on the rewards from a random reward model solves the [Acrobot environment](https://gym.openai.com/envs/Acrobot-v1/) in OpenAI Gym.


{% if page.comments %} {% include disqus.html %} {% endif %}