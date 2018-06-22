# AutoSpearman: Automatically Mitigating Correlated Software Metrics for Interpreting Defect Models

### Abstract
---
>The interpretation of defect models heavily relies on software metrics that are used to construct them.
>However, such software metrics are often correlated in defect models.
>Prior work often uses feature selection techniques to remove  correlated metrics in order to improve the performance of defect models.
>Yet, the interpretation of defect models may be misleading if feature selection techniques produce subsets of inconsistent and correlated metrics.
>In this paper, we investigate the consistency and correlation of the subsets of metrics that are produced by nine commonly-used feature selection techniques.
>Through a case study of 13 publicly-available defect datasets, we find that feature selection techniques produce inconsistent subsets of metrics and do not mitigate correlated metrics, suggesting that feature selection techniques should not be used and correlation analyses must be applied when the goal is model interpretation.
>Since correlation analyses often involve manual selection of metrics by a domain expert, we introduce **AutoSpearman**, an automated metric selection approach based on correlation analyses.
>Our evaluation indicates that **AutoSpearman** yields the highest consistency of subsets of metrics among training samples and mitigates correlated metrics, while impacting model performance by 1-2\%pts.
>Thus, to automatically mitigate correlated metrics when interpreting defect models, we recommend future studies use **AutoSpearman** in lieu of commonly-used feature selection techniques.
---

### Experimental Results

The repository consists of:

1. **Supplementary Experimental Results** - Subsets of metrics that are produced by 9 studied feature selection techniques and **AutoSpearman** for all studied defect datasets.