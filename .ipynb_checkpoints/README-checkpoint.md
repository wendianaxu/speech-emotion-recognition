# Project Proposal: Speech Emotion Recognition

## Abstract
Our project aims at predicting the emotion expressed by the human speech based on the Mel Frequency Cepstral Coefficient (MFCC) features, which contain information about the rate changes in the different spectrum bands. We plan to approach the problem by 1) cleaning the data and transforming the audio files to a machine-readable format, 2) exploring the data with a focus on the MFCC features, 3) using deep learning models to train the test dataset, and 4) testing with the test dataset. Evaluation of the success will be based on: 1) completeness in data cleaning, training, and testing; 2) use of plots that demonstrate comprehensive data exploration and data analysis; 3) level of detail in documentation; 4) level of model accuracy[^1]; 5) depth of discussion on implications and potential biases; and 6) the clarity, conciseness, and accessibility of the presentation.

[1^]: Evaluation of the model accuracy ranges from high to low in the following sequence: "higher than the accuracy achieved by publicly available algorithms" --> "slightly lower than the accuracy achieved by publicly available algorithms" --> "higher than the baseline accuracy" --> "lower than the baseline accuracy"

## What You Will Learn
Alice's Project Goals & Learning Intentions:
- Submit all project milestones (proposal, progress report, etc) on time.
- Set deadlines and try hard to meet them.
- Communicate with partners in a clear and timely manner.
- Draft designated sections of the project report.
- Revise sections of the project report in response to feedback.
- Contribute equally with partners to the creation and presentation of the final project presentation.

Based on the goals I set for this project, I plan to learn about the MFCC from scratch and learn deep learning algorithms and the Python packages associated with it. I also look forward to learning how to collaborate via GitHub.

## Ethics Statement
In general, this project on audio emotion detection and classification will open more opportunities for AI functionality and related industries. Commercial industries that produce such systems as products and customers that use them may both benefit from the potential application of this project. For example, Intelligent voice systems such as Siri could advance in understanding humans based on not only the meaning of the words but also the emotion behind them. Another example is applications/websites that use AI to generate text-reading audios and their potential users who may experience visual challenges. Other examples include improving AI that makes music recommendations and automated customer service. In addition to the commercially focused industries, our project could benefit the medical field. For instance, emotion classification could be used as a side tool for psychiatric disease diagnosis, psychological counseling, mental state monitoring for risk prevention, etc. It could also be used in the detection of speech-related disorders such as hyperkinetic dysphonia and hypokinetic dysphonia. Another application of the project might be in the anticriminal field. For example, it could be used to improve lie detection algorithms and devices or as an assisting tool to facilitate negotiations with criminals.

Groups that are potentially excluded from this project are hearing-disabled individuals since they rarely communicate via voice, and even if they do, the samples would be limited to developing viable models. Groups that are potentially harmed are hostages and their families since kidnappers could use such algorithms to detect the emotions of the family and gain more success in blackmail. 

Additionally, if the model is biased against certain groups, those groups could be harmed by low accuracy of emotion recognition. One of the major potential biases is the language used for training. Since our dataset uses only standard English, our project will only develop English training models, which leads to biases against dialect speakers and non-English speakers. However, since English is arguably the most globally used language, developing some basic pipeline based on the “standard” version of English is a promising start. Nonetheless, with inclusivity in mind, more dialects and languages should be added gradually to construct more maturely developed speech-emotion recognition algorithms. 

A few assumptions behind our project are:
- People can engage in empathetic conversations with automated systems in daily life
- Patients will benefit from accessible counseling services that are more realistic
- The criminal justice system will run more efficiently with automated sentiment recognition to support decision-making and negotiation with criminals

