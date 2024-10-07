---
layout: page
title: A HeARTfelt Robot
description: AI-powered social robot guided art discussion for social emotional learning in kids
img: assets/img/publication_preview/heartfelt.png
importance: 2
category: media lab
related_publications: true
---

This project, initially developed as a class project for MAS.630 in Fall 2023 as a collaboration with Golda Nguyen, involves the use of a novel social robot interaction where Jibo, powered by generative AI, guides children ages 7-11 through discussion about art to practice social-emotional learning competencies. In our work, we compare how kids respond to this interaction based on whether they are shown emotional or neutral art.

In this interaction, kids are shown several different pieces of artwork, and Jibo asks them the following questions:
 1. Can you tell me a story about this picture or describe this picture to me?
 2. What emotion does this picture make you feel?
 3. Why does this picture make you feel that emotion?
 4. Can you tell me about the last time you felt that emotion?

Jibo then uses GPT-4 to generate dynamic and responsive utterances based on what answers the kids provide.

This work demonstrates that **conversations about emotional art with a social robot can foster empathy in children** by showing that kids display significantly more empathetic reasoning when discussing emotional art vs. neutral art.

We also demonstrate that **children are engaged in social robot-driven SEL practice, even when vulnerable or uncomfortable**. Based on behavioral analysis, we see that children remain engaged in the interaction even when displaying uncomfortable behaviors and when sharing vulnerably.

Finally, we demonstrate that **a social robot can help mitigate the discomfort a child feels when sharing vulnerable feelings**. We observed that Jibo's utterances effectively comforted children following moments of vulnerability. In numerous instances, children expressed discomfort after sharing vulnerably, which was notably alleviated by Jibo's utterances, in contrast to cases where their discomfort persisted after an utterance.

This work is further described in our paper {% cite pu2024heartfelt %} published at RO-MAN 2024, which won the *RSJ Pioneering Research Award in Robot and Human Interactive Communication*.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/heartfelt/emo.png" title="emotional images" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/heartfelt/neutral.png" title="neutral images" class="img-fluid rounded z-depth-1" %}
    </div>
</div>