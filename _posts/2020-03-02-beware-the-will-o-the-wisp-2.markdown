---
layout: post
title:  Beware the will-o’-the-wisp! and other lessons (Part II)
date:   2020-03-02 13:40:00 +1300
categories: posts
---

This is a second post with advice I would have given Sam-one-year-ago to help him with his master's thesis. Unlike the [first post](/posts/2020/02/27/beware-the-will-o-the-wisp-1.html), I think these lessons might be helpful for beginner researchers in most disciplines.

## 3) Don’t “try”

<!-- <img src="https://vignette.wikia.nocookie.net/starwars/images/d/d6/Yoda_SWSB.png" alt="drawing" width="275" style="float:right"/> -->
This idea is [not my own](http://mindingourway.com/there-is-no-try/), but I like it so much that I wanted to rearticulate it here. I’ll describe my implementation of the advice first, and then the problem it’s intended to solve.

When I’m working on a problem, I like to imagine that Yoda is sitting next to me. Every hour, he gently reminds me that *there is no try*, or in other words, that “I’m trying to do X” (or “I’m thinking about how to do X”) is rarely the best strategy for actually achieving X.

A much better strategy, according to Yoda, is to take low-level actions that you expect will move you closer to a solution. This strategy, he says, would help me avoid two failure modes I run into often.


Firstly, it ensures that my actions (towards a solution) are at the right level of granularity. For example, while working on my thesis, I once had to admit to Yoda that I was “trying to apply an active learning algorithm in the setting of RL from preferences”. And as he predicted, this resulted in nothing more than two hours of chewed pencils and staring with ponderous visage into the distance. More effective (lower level) actions could have been:

-   “I’m searching Google Scholar to see if anyone has applied active learning in this setting before”, or
    
-   “I’m confused about whether I should treat the problem as classification or regression, so I’m resolving that confusion by writing down examples of both and seeing which one fits my intuitions better”.
    

  

Secondly, it ensures that I’m clear how my actions will move me to a solution. For example, Yoda once caught me setting up an experiment without knowing how the outcome would actually provide evidence for or against the hypothesis I was testing (because, on reflection, the experiment’s possible outcomes were equally likely regardless of whether the hypothesis was true). This action was sufficiently low level, but I had flinched away from the work of checking whether it was actually a helpful action to take.

## 4) Beware the will-o’-the-wisp!

In English folk tales, the [will-o'-the-wisp](https://en.wikipedia.org/wiki/Will-o%27-the-wisp) is a ghostly light, seen by travellers at night. Because it recedes as travellers approach, it earned an infamous reputation for leading astray the curious or confused. Apparently, it might look something like this:

  ![alt text][will-o-wisp-pic]

In my nighttime travels through the treacherous terrain of RL, I was enticed by two such receding targets. Firstly, I intended to get in touch with the authors of a related paper, which I expect would have resulted in some invaluable guidance. Before doing so, however, I felt a need to “prove myself” by making a solid start and “having something to show for it”. But of course, the target of “having something to show for it” receded as I approached---and so I never sent the email.

  

Secondly, I was enticed by the light of “being seen to be making good progress” by my supervisor. So, when I inevitably encountered setbacks, I avoided checking in until I was “back on track”. But of course, by the time I’d resolved the setback, the criterion for “back on track” had moved along, and so I worked furiously to try to catch up. Sometimes this worked, but more often I got stuck again while chasing that target, and the cycle repeated---until I was “embarrassingly” behind and hadn’t spoken to my supervisor for weeks.

  

What could I have done differently? If I had pre-committed to sending the email at the end of week 3 of my research, or pre-committed to regular check-ins with my supervisor, then I wouldn’t have wasted energy chasing those receding, ghostly lights.


<!-- References -->
[yoda-pic]: https://vignette.wikia.nocookie.net/starwars/images/d/d6/Yoda_SWSB.png "There is no try!"
[will-o-wisp-pic]: http://internationalphotomag.com/wp-content/uploads/2019/05/frang_dushaj_ww_10-1024x614_c.jpg "Beware the will-o’-the-wisp!"





<!---
{% if page.comments %} <div id="disqus_thread"></div>
<script>

/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://samsarana.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript> {% endif %}
-->
