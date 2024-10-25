#### 29 October 2024 (Tuesday)

- **Where/When:** JBHT 535, 12:30-1:30P ([U of A](https://www.uark.edu/))
- **Reading:** 
  - [Selective Generation for Language Models](https://openreview.net/forum?id=jHU3tpL5Of) - *Minjae Lee, Kyungmin Kim, Taesoo Kim, Sangdon Park*
- **Meeting Link (opt):** email me!

**Abstract:** 
Trustworthiness of generative language models (GLMs) is crucial due to the recent surge of GLMs in critical decision making systems. Conventional certified uncertainty learning methods, including selective classification and conformal prediction, have been gradually addressing the trustworthy issues of classical models but they still lack for mitigating the metric misalignment issue in GLMs, i.e., good metrics for language generation tasks in measuring the semantic correctness of the true and generated answers are missing. In this paper, we leverage the concept of logical entailment to identify the relation between the true and generated answers to define an entailment-based false discovery rate (FDR) and propose supervised selective generation that exploits entailment labels to control the FDR. As obtaining the entailment labels is expensive, we mitigate this by proposing semi-supervised selective generation that leverages samples without entailment labels by learning an entailment set, which plays a pseudo labeling function, and by designing neuro-selection functions, which further enhances a data space for entailment set learning to minimize the FDR. The proposed neuro-selective entailing-generation algorithm (NSeGen) is theoretically justified to provide the correctness guarantee in the entailment-based FDR, where we also provide sufficient conditions to always satisfy the PAC guarantee on the desired FDR. We demonstrate the efficacy of NSeGen in achieving a desired level of the FDR and better efficiency compared to baselines on open and closed source GLMs.





