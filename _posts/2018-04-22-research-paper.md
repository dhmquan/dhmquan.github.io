---
layout: post
title: Research Paper Report
#gh-repo: daattali/beautiful-jekyll
#gh-badge: [star, fork, follow]
#tags: [test]
---
## Summary ##

In their 2005 paper, Millen et al. explore common usage patterns in a collaborative virtual environment. To do so, the researchers monitored for five months the vital analytical data of ActivityExplorer (or AE) - an in-house collaborative virtual environment. AE’s main function is to share items, which can be “synchronous” - media that need constant, instantaneous updates such as chats and screen shares - or “asynchronous” - other media types such as documents, images, emails, and tasks. The researchers conclude that collaborative users often employ relatively specialized strategies for sharing and organizing items. For example, a software development team tends to have large item collections with a lot of task items and few collaborators (coordination pattern), while a more administrative team would have large collections of documents, messages, and emails (archive/communication pattern). A surprising finding is that a mixed pattern is quite common: a lot of teams share both small synchronous items, such as chats, and bigger asynchronous items, such as large documents and images. Millen et al. speculated that teams often begin their projects with short, quick chat exchanges, then later scale the project up with more substantial work.

The researchers are very rigorous in presenting evidence to support their claims. They also acknowledge that since all participants are employed at the same research institution, this may introduce research biases. I appreciate Millen et al.’s findings, but also wish that they have also kept track of how AE users actually organize their shared work. There are so many questions to ask here: do users group their items by types, or by items’ content themes? Do they use threads whenever possible to organize work? What are their strategies when a project gets too big?

## Application ##

I am particularly interested in this paper because it offers some insight on how to expand a2a’s capability to support artist collaboration. Currently, we choose to gear a2a more towards establishing artist connections to facilitate the creation of collaborative opportunities, instead of focusing on the collaborative process itself. I would not have done this differently, since I think our target users lack such important access to collaborative opportunities in the first place. At the same time, there are rooms to improve a2a, allowing the app to better assist collaborators, perhaps through setting up a Group functionality that handles group-work and large scale projects. Millen et al.’s research really sheds some light on the diverse ways users would make use of a sharing/collaborative environment. Considering the wide range of art media that a2a supports, the existence of collaborative projects with wildly different needs is definitely inevitable, so the paper would definitely be a helpful guide as we develop an a2a Group system.

I do not think our design improves upon the collaborative environment discussed in the paper. Since we do not have a Group system yet, the ideas raised by the researchers open up exciting opportunities to expand a2a. At the same time, we think that our current highly organized design would enable us to very inefficiently develop and integrate such new collaborative environment into the existing framework.

## Reference ##
Millen, David R., et al. “Patterns of Media Use in an Activity-Centric Collaborative Environment.” Proceedings of the SIGCHI Conference on Human Factors in Computing Systems - CHI 05, 2005, doi:10.1145/1054972.1055096.
