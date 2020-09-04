# Inference problems in the linear regime: lessons from group testing

This page contains the slides for a talk I gave at the [Workshop on inference problems: algorithms and lower bounds](https://www.uni-frankfurt.de/84973818/Inference_problems__algorithms_and_lower_bounds), held online from 31 August to 4 September 2020, and hosted by Goethe University Frankfurt.

## Abstract

Modern techniques for inference are most effective for sparse problems, where the number of active inputs *k* is small compared to the total number of inputs *n*. Typically, this is represented mathematically by saying *k* = *o*(*n*) grows sublinearly as *n* gets large. But in many situations – for example, infected individuals in a pandemic that has spread through a population – it may be more reasonable to assume that *k* is a small but constant proportion of *n*. How might our inference problems look different in this linear regime? We look at this question through the example of pooled group testing – for example, screening for a disease by mixing samples together and testing the pooled samples. We consider both the nonadaptive (tests decided on in advance) and adaptive (tests performed in sequence) settings, and examine how algorithms and lower bounds differ from the sublinear regime.

## References

The best place to read more about what I spoke about – or about group testing more generally – is in the survey monograph

* M Aldridge, O Johnson, J Scarlett, ["Group testing: an information theory perspective"](http://dx.doi.org/10.1561/0100000099), *Foundations and Trends in Communications and Information Theory*, 15:3–4, 196–392, 2019. ([arXiv preprint](https://arxiv.org/abs/1902.06002))

The most relevant sections here are 1.1, 1.3, 1.4, 1.5, 4.1, and most of all 5.5.

The original papers are

* M Aldridge, ["Rates of adaptive group testing in the linear regime"](https://doi.org/10.1109/ISIT.2019.8849712), *2019 IEEE International Symposium on Information Theory (ISIT)*, 236-240, 2019. ([arXiv preprint](https://arxiv.org/abs/1901.09687))

on adaptive testing in the linear regime, and 

* M Aldridge, ["Individual testing is optimal for nonadaptive group testing in the linear regime"](https://doi.org/10.1109/TIT.2018.2873136), *IEEE Transactions on Information Theory*, 65:4, 2058–2061, 2018. ([arXiv preprint](https://arxiv.org/abs/1801.08590))

on nonadaptive testing in the linear regime.
