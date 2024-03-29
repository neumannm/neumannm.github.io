---
layout: single
title:  "My Bachelor's Thesis Code on GitHub"
date:   2020-01-01 19:29:50 +0100
tags: [coding, thesis]
---

While the [code to my Master's thesis](https://github.com/neumannm/JobAdInformationExtraction) has been on GitHub already for a while now, since I was already using version control back then, I just recently also added a repository containing the [code to my Bachelor's thesis](https://github.com/neumannm/TEIDramaReader) that I submitted back in 2012. At that time, Subversion (SVN) was still the main VCS we used in our institute, so this repository has no interesting commit history to follow my progress, sorry. ;)

The topic of my Bachelor's thesis was to develop a new component for the [TESLA](http://tesla.spinfo.uni-koeln.de/) software. Nowadays, people think of fancy cars when hearing "Tesla" - back then, we only knew of Nicola Tesla, who might have inspired this acronym. It stands for "Text Engineering Software Laboratory" and is some kind of a virtual laboratory for doing text analysis. Input modules are needed to process different input formats and transform them into a specific format that the text processing components of TESLA can understand. We figured it would be useful to have an input module for [TEI](https://tei-c.org/)-encoded texts, since this is a format that is heavily used in the field of Digital Humanities, where text analysis is an integral part of research. So I developed a new input reader for TESLA that is able to read and transform TEI-encoded drama texts.

I don't know much about the current status of TESLA, I didn't even have time to check if my code still works with the current version. But if you want to learn more about TESLA, I would suggest you read the [PhD thesis](https://kups.ub.uni-koeln.de/4571/) of my former colleague Stephan Schwiebert. A good impression of what kind of cool stuff can be done with the software is also given by the [PhD thesis](http://kups.ub.uni-koeln.de/4561/) of another former colleague, Jürgen Hermes, who analyzed the infamous Voynich manuscript with it. (Unfortunately, both theses are in German, but in case you are not proficient in German, maybe the DeepL could be of help. ;))
