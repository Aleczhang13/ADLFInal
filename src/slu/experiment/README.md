# exp1

Naive approach:
speech_act f1 : 0.3853
semantic_tagged f1 : 0.0057
Test_Acc: 0.2588

model:  ( 3900.ckpt )
1. use top hypo as translation
2. use the first one label as label data
3. no pruning
4. default parameter of rnn-nlu