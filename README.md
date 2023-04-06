# Project Proposal: Speech Emotion Recognition

## Abstract
Our project aims at predicting the emotion expressed by the human speech based on the Mel Frequency Cepstral Coefficient (MFCC) features, which contain information about the rate changes in the different spectrum bands. We plan to approach the problem by 1) cleaning the data and transforming the audio files to a machine-readable format, 2) exploring the data with a focus on the MFCC features, 3) using deep learning models to train the test dataset, and 4) testing with the test dataset. Evaluation of the success will be based on: 1) completeness in data cleaning, training, and testing; 2) use of plots that demonstrate comprehensive data exploration and data analysis; 3) level of detail in documentation; 4) level of model accuracy[^1]; 5) depth of discussion on implications and potential biases; and 6) the clarity, conciseness, and accessibility of the presentation.

[^1]: Evaluation of the model accuracy ranges from high to low in the following sequence: "higher than the accuracy achieved by publicly available algorithms" --> "slightly lower than the accuracy achieved by publicly available algorithms" --> "higher than the baseline accuracy" --> "lower than the baseline accuracy"

## Motivation and Question
Recognizing emotions from human speech is an important task with various applications in human-centered computing, because it allows automatic systems to interpret users’ emotions, and make decisions and provide responses accordingly. Machine learning models provide a solution to recognizing speech emotions by learning from examples interpreted and labeled by humans. In real life, people convey emotions not necessarily through the semantics of their speech, but more often with voice qualities such as intonation. We are therefore interested in developing models that predict emotions based on voice qualities rather than the literal meaning of the speech. For this purpose, we have a data set containing vocalizations of only two different sentences that share the same lexical structure. They were spoken by 24 actors, male and female, each in eight emotions of two levels of intensity. Each combination of sentence and emotion was repeated twice by the same actor. This would hopefully provide the model with rich information to uncover patterns in speech emotion. 

Previous work has demonstrated that deep learning algorithms combined with MFCC features are well-suited for speech emotion recognition tasks [^2]. Therefore, we plan to focus on classifying speech emotion using deep learning models and MFCC features in this project. 

[^2]: H. S. Kumbhar and S. U. Bhandari, "Speech Emotion Recognition using MFCC features and LSTM network," 2019 5th International Conference On Computing, Communication, Control And Automation (ICCUBEA), Pune, India, 2019, pp. 1-3, doi: 10.1109/ICCUBEA47591.2019.9129067.

## Planned Deliverables
### Full Success

In the case of full success, we expect our deliverables to be:

- A Python package containing a machine learning model that classifies emotions in the test data with accuracy similar to or higher than publicly available algorithms. The package will contain all code used for algorithms and analysis with documentation. 
- A Jupyter notebook illustrating the use of the package to analyze data. 

### Partial Success

In the case of partial success, we expect that we will still deliver the Python package and the Jupyter notebook, with a complete pipeline for data cleaning, processing, and model training. However, the model may have low training or testing accuracy. 

## Resources Required
The data that we will be using comes from the [Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio).  

In addition to data, we would also need a deeper understanding of deep learning algorithms, especially the Convolutional Neural Network (CNN) model, since it is commonly used for speech emotion recognition tasks. We may need to learn about the basic math behind its algorithms, its implementation, and any necessary tools for training it on real data. 
## What You Will Learn
Diana’s Project Goals & Learning Intentions:

The goals that I set for this course focus on experimentation and social responsibility. Based on these goals, I plan to practice experimenting through the process of applying deep learning models to a real data set. This would include exploring data cleaning and processing choices, model and parameter choices, and visualization and communication of results. I also hope to learn more about social responsibility by assessing and communicating the potential biases and societal implications of our model. 


Alice's Project Goals & Learning Intentions:
- Submit all project milestones (proposal, progress report, etc) on time.
- Set deadlines and try hard to meet them.
- Communicate with partners in a clear and timely manner.
- Draft designated sections of the project report.
- Revise sections of the project report in response to feedback.
- Contribute equally with partners to the creation and presentation of the final project presentation.

Based on the goals I set for this project, I plan to learn about the MFCC from scratch and learn deep learning algorithms and the Python packages associated with it. I also look forward to learning how to collaborate via GitHub.

## Risk Statement
One challenge for fully delivering our project comes from the way in which we may handle our data. It is possible that we picked a poor strategy for data processing that resulted in loss of important information from the data, which would prevent us from detecting patterns even with a good model choice. This is especially applicable for our data type because there can be many possible ways to process audio data. 

Another challenge we might face is the lack of knowledge in the deep learning algorithms that we will be using. Depending on the difficulty of learning the specific algorithms we need, we might face unpredictable obstacles which would slow down the training process. 

## Ethics Statement
In general, this project on audio emotion detection and classification will open more opportunities for AI functionality and related industries. Commercial industries that produce such systems as products and customers that use them may both benefit from the potential application of this project. For example, Intelligent voice systems such as Siri could advance in understanding humans based on not only the meaning of the words but also the emotion behind them. Another example is applications/websites that use AI to generate text-reading audios and their potential users who may experience visual challenges. Other examples include improving AI that makes music recommendations and automated customer service. In addition to the commercially focused industries, our project could benefit the medical field. For instance, emotion classification could be used as a side tool for psychiatric disease diagnosis, psychological counseling, mental state monitoring for risk prevention, etc. It could also be used in the detection of speech-related disorders such as hyperkinetic dysphonia and hypokinetic dysphonia. Another application of the project might be in the anticriminal field. For example, it could be used to improve lie detection algorithms and devices or as an assisting tool to facilitate negotiations with criminals.

Groups that are potentially excluded from this project are hearing-disabled individuals since they rarely communicate via voice, and even if they do, the samples would be limited to developing viable models. Groups that are potentially harmed are hostages and their families since kidnappers could use such algorithms to detect the emotions of the family and gain more success in blackmail. 

Additionally, if the model is biased against certain groups, those groups could be harmed by low accuracy of emotion recognition. One of the major potential biases is the language used for training. Since our dataset uses only standard English, our project will only develop English training models, which leads to biases against dialect speakers and non-English speakers. However, since English is arguably the most globally used language, developing some basic pipeline based on the “standard” version of English is a promising start. Nonetheless, with inclusivity in mind, more dialects and languages should be added gradually to construct more maturely developed speech-emotion recognition algorithms. 

A few assumptions behind our project are:
- People can engage in empathetic conversations with automated systems in daily life
- Patients will benefit from accessible counseling services that are more realistic
- The criminal justice system will run more efficiently with automated sentiment recognition to support decision-making and negotiation with criminals

## Tentative Timeline
### Three Weeks
We expect to finish data cleaning, processing, and exploration after the first three weeks. We will be ready to present a pipeline for cleaning and processing the data, as well as insights from preliminary exploration of the data. 
### Six Weeks
After six weeks, we will have a full pipeline that includes training and testing processes, and a model derived from the pipeline. 
