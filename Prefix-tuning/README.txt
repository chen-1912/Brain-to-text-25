This folder provides information about Prefix-tuning, including paper, training data, experimental results, etc.

Prefix-tuning (Lisa):
Paper : https://arxiv.org/abs/2101.00190
Github: https://github.com/XiangLi1999/PrefixTuning


A research on Prefix-tuning (Chen):
Paper :https://ieeexplore.ieee.org/document/10191910


For applying prefix-tuning, install transformer as introduced in the github above, then dive in train_e2e.py to modify data root. 
The transformer package is hardly compatible with any online environments like Kaggle or Colab anymore, so we'd suggest do experiments locally. 
Do not use prefix-tuning provided by peft, it behaves differently from the paper.


training data  :train.csv
validation data:validation.csv


experimental results:
It is so efficient and lightweight that only half an hour of training on a 1650Ti with 4GB of VRAM, 
the model start to generate plausible sentences combining phonemes and its own prior. Please compare gold and gen.


Contact me if you are interested in this method and want more details.
