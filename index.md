---
author: 
- s_dwivedi
- hrc
---

# Introduction 
#### If you're here, you probably searched something related to Natural Language Processing, or maybe you're just an Interstellar fan. Well, in the latter case, I have some bad news for you. But hey, don't be disheartened, read on will ya? 

TARS-The very lovable, chatty, and 70% sarcastic robot. For those of you who don't follow the reference, I suggest you go to [this](https://interstellarfilm.fandom.com/wiki/TARS) link and learn what this Robot from the movie Interstellar was. 


![If your internet is slow, this was an image of TARS rolling](https://i.imgur.com/yaVftzT.jpg)



We have been shown that TARS was an entity with a near Human sense of Emotional bandwidth and at the very least, higher than average Intelligence as compared to us humans :). Is something like TARS possible in the near future? Or can it simply be shrugged off as a relentless dream being pursued by the likes of [Issac Asimov](https://en.wikipedia.org/wiki/Isaac_Asimov) and [Christopher Nolan](https://en.wikipedia.org/wiki/Christopher_Nolan)? 

Why don't we look at a Human body? It is a mass amalgamation of complex chemical reactions at the very root of our being. These _chemical reactions_ grant us the ability to percieve the world around us. They help us to think, decide and act. These chemical reactions act as storage units. These storage units influence our decisions and help us choose the right ones. Can we see the similarities between the human body and an ideal robot that the innovators of the world are striving to achieve? Is it too ambitious to look at a machine as a mass amalgamation of complex _Machine Learning_ algorithms? I guess **not**.

So what is this blog? If one were to blindfold themself and made to sit and talk with TARS, it's improbable that the person would find any discernable difference when compared with a human being. Through various posts in this blog, we will attempt to recognize and understand the innovations made in the field of **Natural Language Processing** which may facilitate an entity like TARS. We shall elaborate breakthroughs in research that have made all these advancements possible. We will also look at some basic architectures and models that have been proposed in the recent times.

It is a very exciting time to delve into the ocean of Language understanding. If I may daresay, this is the _**third epoch**_ of NLP. _**The first epoch**_ was in the decades surrounding the _1960s_, where most of the research was based on hand written rules and annotated grammars. This trend continued to highly demotivate researchers due to the slowness of any significant breakthroughs. The computation power was low, and rule-based approaches were saturating very quickly. But then, just as all was apparently lost, and researchers gave up hopes of actually building systems that could understand language, _entered the Dragon_. Cometh the 1980's, and with it, the introduction of Machine Learning algorithms for language processing. This would be, what we call _**The second epoch**_. Also, a simultaneous increase in computation power complemented them. Along with these algorithms, revolutionary [_Hidden Markov Models_](https://web.stanford.edu/~jurafsky/slp3/A.pdf) led the way making use of statistical probabilities for Language modelling. IBM Research emerged as one of the leading institutions where increasingly effecient statistical models were developed.


![I feel sorry for ypur Internet provider :( ](https://i.pinimg.com/474x/71/4b/0e/714b0ed301c1b92db29d0f7ed24419bd.jpg)



And finally, we move on to _**The third epoch**_. This includes various breakthrough models using _Deep-Learning Networks_ and _Representation Learning_. This was facilitated by increasing research in the domains of _Unsupervised_ and _Semi-Supervised_ learning algorithms. These techniques used together gave unprecedented _state-of-the-art_ results. In our blog, we shall mostly focus on the techniques which were developed in this third epoch.

A big motivation for starting this blog was the fact that, Natural Language Processing is a highly sought after _but_ an equally technially demanding field. It is very difficult to follow the various research trends which emerge. So, we aim to provide casual readers and enthusiasts a place to start. A place where one can find documented explanations for a wide variety of research papers in the domain. It's a place where we'll all learn along the way. _You_, while reading this blog and _us_ while trying to explain!

We'll be posting all the updates here on this page. Do visit and feel free to give us feedbacks or suggestions regarding the content, or any questions that you may deem us fit for answering.  
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<footer>
{% assign author = site.authors[page.author] %}
  <p class="byline">
      by {{ author.display_name }}
    </p> <!-- /.byline -->
</footer>

