# Research literature

* In our first quick literature search we identified 20 documents out of which we reviewed 10
* All publications state that DL with RNN for time series is promising
* No publication comes with open access code, classifier or data
* No attempts have been made to cross-validate models and re-use model architectures between research groups which undermines standardised comparisons and level of evidence
* Proof of validity is often limited to convenient and small datasets
* Lack of critical discussion about deep learning, people tend to focus on selling the novelties, while little effort is done to understand when and why deep learning may not work for time series
* It is unclear whether there is domain science success with deep learning for time series

## Paper review summaries

| **Author:** | Abdel-Hamid |
| -- | -- |
| **Title:** | Exploring Convolutional Neural Network Structures and Optimization Techniques for Speech Recognition |
| **Year:** | 2013 |
| **Summary:** | Quite technical and difficult to read report. The TIMIT training data they use may be an interesting test-case. |
| **Tools:** | not specified |
| **Input:** | Voice data |
| **Pattern or event being classified:** | Speaker? |
| - | - |
| **Author:** | **Busseti** |
| **Title:** | Deep Learning for Time Series Modeling |
| **Year:** | 2012 |
| **Summary:** | They demonstrate/conclude that it is better for the NN to find the non-linear relationships itself compared with 'hand-crafted' Fourier transform. No evidence found that anomaly filtering is worth the effort. RNN performs drastically better than feedforward network based on same complexity |
| **Comments:**| Unclear how features were identified and trained in the non-deep learning benchmark. In appendix C and on page 3 the authors state that hand-crafted data features outperform the automatically learned features |
| **Tools:**| ? |
| **Input:**|  Power consumption |
| **Pattern or event being classified:**| Power needs |
| - | - |
| **Author:** | **Langkvist** |
| **Title:** | A review of unsupervised feature learning and deep learning for time-series modeling
| Year: 2014 |
| **Summary:** | Overview of several time series sub fields and for each a brief discussion of methods used and an indication of state-of-the-art. See Table 2 at page 40 for a good summary.
| **Tools:** | ? |
| **Input/patterns or events being classified:** the manuscript comes with several user-case examples with a variety of data types as input |
| - | - |
| **Author:**| **Lipton** |
| **Title:**| A critical review of recurrent neural networks for sequence learning |
| **Year:**| 2015 |
| **Summary:**| Review of how RNN's work. Starte of the art are: LSTM (memory inside each node) and BRNN (connecting time steps, but not suitable for online data) possibly extended with NTM (good for more complex tasks like sorting data). |
| **Tools:**| ? |
| **Input:**| Mostly word sequences |
| **Pattern or event being classified:**| ? |
| - | - |
| **Author:** | **Martinez** |
| **Title:** | Learning Deep Physiological Models of Affect |
| **Year:** | 2013 |
| **Summary:**| Reviews deep learning for time series, develops a model, and evaluates it. Code not released and algorithm only describe at a high level with no formulas or specifications of libraries. Sequantial Forward Feature Selection not clearly explained |
| **Tools:**| Theano |
| **Input:**|  Physiological signals |
| **Pattern or event being classified:**| Affection (emotional state in response to playing a video game) |
| - | - |
| **Author:**| **Mirowski** |
| **Title:**| Comparing SVM and Convolutional networks for epileptic seizure prediction from intracranial EEG
| **Year:**| 2008 |
| **Summary:**| At first it seems that they are going to run CNN on raw data, but it later turns out that CNN is only applied to signal features. So, this is not really deep learning? |
| **Tools:**| Matlab, Octave, Lush |
| **Input:**|  EEG |
| **Pattern or event being classified:**| Forecasting epileptic seizures |
| - | - |
| **Author:** | Yang |
| **Title:** | Deep CNN on multichannel time series for human activity recognition. Claims to be the first to try CNN on activity data |
| **Year:** | ? |
| **Summary:** | Gesture recognition and activity type recognition based on multiple data streams. Paper describes clearly how CNN can be applied on time series. Major weakness is that they train and evaluate in the same three subjects affecting generalizability. Code not released, unclear how representative classification challenge is. It seems that they use some form of RNN by linking weights with the weights of previous time steps, but this is not discussed or clarified |
| **Tools:** | Matlab |
| **Input:** | ? |
| **Pattern or event being classified:** | Gestures and activity types |
| - | - |
| **Author:** | Zen |
| **Title:** | Deep learning in speech synthesis |
| **Year:** | 2013 |
| **Summary:** | slides of a google talk on speech classification. good educational, e.g. slide 9 is summary of what makes DNN different from old NN (GPU, more data, unsupervised pretraining) and slide 18 as well. Slides give the impression that DNN is not necesarily the best yet (it seems that authors consider DNN as a potential winner for the future). Reference list at the back is potentially useful. Although they recommend feature free approach, a number of dataset decision are made which require expertise with the data, e.g. mel-cepstrum and removal of silence periods. |
| **Tools:** | ? |
| **Input:** | not applicable |
| **Pattern or event being classified:** | not applicable|
| - | - |
| **Author:** | Zheng |
| **Tools:** | Convolutional Nonlinear Neighbourhood Components Analysis for Time Series Classification |
| **Year:** | 2015 |
| **Summary:** | Proposes enhancement of time series classification by using convolutional neural networks to train distance metrics for Nonlinear neighborhood components analysis (sounds like 1NN) classification. Although the idea might be novel, the evaluation is not thorough and it is unclear whether the complexity of the method is truly worth the effort. Overall the papers lacks clarification on a number of the methods it uses. The decisions made in the evaluation are not motivated which creates the appearance that results were selected to fit the hypothesis (e.g. in the selection of the subset). Claim of covering 90% of the variance/patterns of data in the world is ridiculous. No attempt made to understand measurement error. |
| **Tools:** | ? |
| **Input:** | A variety of benchmark time series from the UCR time series repository |
| **Pattern or event being classified:** | Classifications from the UCR time series repository |