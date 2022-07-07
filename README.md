# AlphaFold-beyond-structure
Using AlphaFold protein language model to predict protein functions

AlphaFold has revolutionized protein structure prediction, while its capacibility has not been examined for protein function prediction. We have recently carefully studied AlphaFold's Evoformer --- a specicial protein language model--- representation in terms of function prediction, including both protein annotation prediction and
protein fitness prediction tasks (stability, fluorescence and zero-shot mutational effect prediction). Please see our paper on Arxiv: https://arxiv.org/pdf/2206.06583.pdf. We would release our code and datasets soon.


Large-scale Protein Language Models (PLMs) have improved performance in protein prediction tasks, ranging from 3D structure prediction to various function
predictions. In particular, AlphaFold [20], a ground-breaking AI system, could potentially reshape structural biology. However, the utility of the PLM module in
AlphaFold, Evoformer, has not been explored beyond structure prediction. In this paper, we investigate the representation ability of three popular PLMs: ESM-1b
(single sequence) [32], MSA-Transformer (multiple sequence alignment) [27] and Evoformer (structural), with a special focus on Evoformer. Specifically, we aim
to answer the following key questions: (i) Does the Evoformer trained as part of AlphaFold produce representations amenable to predicting protein function?
(ii) If yes, can Evoformer replace ESM-1b and MSA-Transformer? (iii) How much do these PLMs rely on evolution-related protein data? In this regard, are
they complementary to each other? We compare these models by empirical study along with new insights and conclusions. Finally, we release code and datasets for
reproducibility.



