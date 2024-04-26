#### May 1, 2024 

- **Where/When:** JBHT 535, 1-2P ([U of A](https://www.uark.edu/))
- **Reading:**
  - [Evaluating the Impact of Local Differential Privacy on Utility Loss via Influence Functions](https://arxiv.org/pdf/2309.08678)
- **Meeting Link (opt):** email me!
- **Abstract:** 
How to properly set the privacy parameter in
differential privacy (DP) has been an open question in DP
research since it was first proposed in 2006. In this work, we
demonstrate the ability of influence functions to offer insight
into how a specific privacy parameter value will affect a model’s
test loss in the randomized response-based local DP setting. Our
proposed method allows a data curator to select the privacy
parameter best aligned with their allowed privacy-utility trade-off
without requiring heavy computation such as extensive model
retraining and data privatization. We consider multiple common
randomization scenarios, such as performing randomized response
over the features, and/or over the labels, as well as the more
complex case of applying a class-dependent label noise correction
method to offset the noise incurred by randomization. Further, we
provide a detailed discussion over the computational complexity
of our proposed approach inclusive of an empirical analysis.
Through empirical evaluations we show that for both binary and
multi-class settings, influence functions are able to approximate
the true change in test loss that occurs when randomized response
is applied over features and/or labels with small mean absolute
error, especially in cases where noise correction methods are
applied.


