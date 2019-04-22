# TVQA+: Spatio-Temporal Grounding for Video Question Answering

![qa_example](imgs/qa_example_pair.png)

We present the task of Spatio-Temporal Video Question Answering, which requires intelligent 
systems to simultaneously retrieve relevant moments and detect referenced visual concepts 
(people and objects) to answer natural language questions about videos. 
We first augment the TVQA dataset with 310.8k bounding boxes, linking depicted objects to 
visual concepts in questions and answers. 
We name this augmented version as TVQA+.
We then propose Spatio-Temporal Answerer with Grounded Evidence (STAGE), 
a unified framework that grounds evidence in both the spatial and temporal domains to 
answer questions about videos. 
Comprehensive experiments and analyses demonstrate the effectiveness of our framework and 
how the rich annotations in our TVQA+ dataset can contribute to the question answering task. 
As a side product, by performing this joint task, our model is able to produce more insightful 
intermediate results. 


In this repository, we provide PyTorch Implementation of the STAGE model, along with basic 
preprocessing and evaluation code for TVQA+ dataset.


TVQA+: Spatio-Temporal Grounding for Video Question Answering.<br>
[Jie Lei](http://www.cs.unc.edu/~jielei/),  [Licheng Yu](http://www.cs.unc.edu/~licheng/), 
[Tamara L. Berg](http://Tamaraberg.com), [Mohit Bansal](https://www.cs.unc.edu/~mbansal/). 
   [[PDF]](~) [[Dataset]](http://tvqa.cs.unc.edu)


### Model Overview
Overview of the proposed framework, Spatio-Temporal Answerer with Grounded Evidence (STAGE) for 
spatio-temporal video question answering. 
![model_overview](imgs/model_overview.png)


### Prediction Examples
Below, we show example predictions from STAGE:
![example_predictions](imgs/model_prediction.png) 


### Citation
```
@inproceedings{lei2019tvqa,
  title={TVQA+: Spatio-Temporal Grounding for Video Question Answering},
  author={Lei, Jie and Yu, Licheng and Berg, Tamara L and Bansal, Mohit},
  booktitle={EMNLP},
  year={2018}
}
```

### TODO
1. [ ] Add data preprocessing scripts
2. [ ] Add model and training scripts
3. [ ] Add inference and evaluation scripts
