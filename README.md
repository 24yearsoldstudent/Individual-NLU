# Individual-NLU
Datasets related to the paper [Understanding and Tackling Label Errors in Individual-Level Nature Language Understanding](https://arxiv.org/abs/2502.13297). 

## Dataset Introduction
### Stance Detection 
The original dataset is derived from [SemEval-2016 Task 6: Detecting Stance in Tweets](https://aclanthology.org/S16-1003/). In 2019, [Aldayel et.al](https://github.com/AbeerAldayel/Stance_detection) expanded the dataset and collected the UserID corresponding to some tweets. 

We further extended the dataset based on the work of Aldayel et al. Since some users post more than one tweet, we retained the dataset from Aldayel et al. You can find UserID and its original tweets in testing_timelines_streaming_info.csv and added tweets from stance_detection.csv.

### Topic-based Sentiment analysis
The original dataset is derived from [SemEval-2016 Task 4: Sentiment Analysis in Twitter](https://aclanthology.org/S16-1003/](https://arxiv.org/abs/1912.01973). We do not collect UserIDs, so we only keep the original tweet IDs.
