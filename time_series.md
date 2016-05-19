# Time series

Most attention in the literature and in the news has gone to deep learning in image processing, e.g. video analyses, while relatively little attention is given to the potential of deep learning for time series analyses. 

Building a deep learning algorithm requires specific expertise with neural networks and high-performance computing, which prohibit uptake by domain scientists.  Further, domain scientists may be skeptical about using deep learning because of its black box nature. The aim of this project is to develop a generic tool for deep learning that is useful for time series classification in science.

## Trends in literature: 
* 20 documents identified, 10 were reviewed
* All state: DL with RNN for time series is promising
* Nobody releases their code or models
* No attempts made to cross-validate models and re-use model architectures between research groups: undermines standardised comparisons and level of evidence
* Proof of validity often limited to convenient and small datasets
* Lack of critical discussion about DL
* Unclear there is domain science success

### Brief summaries of papers

Author: Abdel-Hamid
Title: Exploring Convolutional Neural Network Structures and Optimization Techniques for Speech Recognition
Year: 2013
Summary: Quite technical 4 page report of a specific project, possibly not ideal for learning about the techniques. The TIMIT training data they use may be an interesting test-case.
Computing lnguage: not specified
Input: Voice data
Pattern or event being classified: Speaker?

Author: 
Title:
Year:
Summary: 
Computing language:
Input: 
Pattern or event being classified:



## User examples 

## Summary of requirements 

* Easily accessible for scientists with no expertise in deep learning or HPC
* Gives the scientist the opportunity to embed their scientific models, such that deep learning is more than a black box to them. For example, the scientific model is the starting point for the training process
* Demonstrate that our tools are more accurate and/or more feasible than conventional approaches. 

* Utilize state of the art deep learning techniques
* Flexible to handle range of time series types/dimensions
* Visualization tool:
  * Label and classification check relative to raw data
  * Visualise new DL features relative to raw data
* Ability to output new DL features
* Accessible to domain scientists
* Publication in domain science journal, with:
  * Demonstration of validity in representative dataset and based on multiple performance metrics
  * Clear guidance on expected limitations of the classifier
  * Guidance on how to link ‘new’ deep learning features to biological/physical phenomena and theory
* Early stage interaction with domain scientists to ensure long term uptake

## Useful links:
* http://deeplearning.net/reading-list/tutorials/
* http://deeplearning.net/software/theano/
* http://www.h2o.ai/
* http://www.deeplearningbook.org/
* http://colah.github.io/
* http://neuralnetworksanddeeplearning.com/
* http://www.cs.ucr.edu/~eamonn/time_series_data/
