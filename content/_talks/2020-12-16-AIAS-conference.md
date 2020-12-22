---
layout: page
img: /files/images/aias.jpg
title: AIAS conference
url: talks/2020-12-16-AIAS-conference.md
description: "I presented my work on robustness of AI from epistemological and policymaking standpoints as part of my master thesis. I addressed the motivation of the need of defining more precise definitions of robustness for AI than the usual score on a test set. I try to propose a good notion of robustness and to present (practical) mathematical formulations of such a notion."
---

I presented my work on robustness of AI from epistemological and policymaking standpoints as part of my master thesis. I addressed the motivation of the need of defining more precise definitions of robustness for AI than the usual score on a test set. I try to propose a good notion of robustness and to present (practical) mathematical formulations of such a notion.

One of the main problem of ML today is to assess its successfulness because it recently appeared (especially thanks to adversarial attacks) that our usual criteria failed to capture whether or not the fitting function generalizes or learns what we (as human being) expected. Indeed, Adversarial attacks showed that our methods learn something totally different from what we would expect since a small noise, which does not affect the input at a macroscopic level changes dramatically the output. The point is that these problems are not detected by our evaluation metrics and it is not that surprising. It is crucial to keep in mind that we do not make our functions learn concepts directly but by using a proxy (the training set) thus it learns to behave well on the proxy problem (which is obviously far less general than the true problem) inducing biases. Robustness aims at measuring the gap between the proxy problem and the true problem or more practically, robustness aims at measuring the size of the domain of the true problem where tests give some kinds of guarantees.
