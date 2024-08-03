---
layout: default
title: Summer 2024 DREU Project Site
---

* TOC
{:toc}

## About Me

Hi, all! My name is Dylen Greenenwald. I've recently obtained my B.S. in Computer Science from the University of Illinois Chicago -- this will be my last undergraduate experience! I will be starting my Ph.D. in Computer Science at the University of Illinois Urbana-Champaign during the fall 2024 semester, broadly studying security and privacy.

Feel free to reach out and contact me at dgree21 [at] illinois (dot) edu. I am currently working on launching my first attempt at a [personal website](https://greenenwald.com), so while it's not accessible in a functioning capacity yet, you should be able to find out more about me there in the near future :)

## About My Mentor

This summer I will be mentored by Sameer Patil, a prominent Associate Professor of Computer Science at the University of Utah. Professor Patil works largely on usable security and human-computer interaction, but additionally participates in extraneous forms of interdisciplinary research. Find out more at his [faculty homepage](https://faculty.utah.edu/u6038392-Sameer_Patil/hm/index.hml).

## About My Project

I'm ecstatic to get started on some research in a subdomain I'm unfamiliar with this summer! What we will be working on is essentially a large-scale analysis of social engineering campaigns through the examination of thousands of user-reported phishing scams (through email) at the University of Utah. While we are still working out details, the milestones are *roughly* as follows:

1. Perform a literature search to understand the state of the art in terms of common elements of user-identifiable social engineering campaigns
2. Work with a Ph.D. student from Prof. Patil's lab in parsing the emails into a compact, analyzable format (e.g. stripping MTA fields from the emails, leaving only client-client information where relevant).
3. Identify common components across parsed emails, along with those that differ. This will likely consist of two phases: one where a few dozen emails are manually analyzed, followed by another that is automatically processed by a system we develop based on the insights derived from manual analysis.
4. Synthesize results into a meaningful analysis. Potentially derive organizational mitigations based on key takeaways. This milestone is difficult to articulate early on because it is largely dependent on what we encounter during the previous milestones.
5. If time permits, obtain a dataset (whether through searching existing repositories or through generation) that contains phishing emails that were successful in deceiving their victim to facilitate a comparative examination of social engineering through email communication.
6. Repeat milestones 2-4 on the new dataset, taking into account the additional burden of the comparative nature.

### Update

We ended up trying out several different avenues for an interesting project. We experimented with the above, a CAPTCHA collection and acceptance threshold testing idea, along with (finally) a two factor authentication log analysis project. In the end, we settled on the latter. While I wasn't able to complete a whole lot, it's totally okay! I got to try out different stuff in a space I'm not comfortable with, and that is plenty to gain from an experience like this. I ended up learning that usable security isn't really for me, but it's cool nonetheless!

[My Final Report](files/paper.pdf) (temporary link)

## My Blog

[My Blog](blog.html)
