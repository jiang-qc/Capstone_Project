# Daily Log

## 2022/05/02 Jigsaw Activity

- Maximizing Collective Intelligence: the shared or group intelligence that emerges from the collaboration, collective efforts, and competition of many individuals and appears in consensus decision
making
- Trust: assured reliance on the character, ability, strength, or truth of someone or something
- Forms of conflicts:
  1. Task Conflict: a disagreement over the goal or objective of a project/discussion/meeting
  2. Relationship Conflict: the conflict resulting from either personality clashes or 
negative emotional interactions between two or more people
  3. Process Conflict: a disagreement over how to achieve the goal
 
- Team Emotional Intelligence: the ability to identify and manage one's own emotions, as well as other people's emotions
- Psychological Safety: a belief that you won’t be punished when you make a mistake


## 2022/05/03 Conception to Deployment + Coding Challenge Day

- We listened to the presentation from Kim about working in a startup company.


## 2022/05/04 Team Contract and EDA

- The data is structured but umbalanced. We might need to do some preprocessing and cleaning.
- Another concern is the bias behind the data because the responses from strudents are subjective.
- When training data, the features might be corelated. To achieve a better performance, random forest models might be better than regression models.
- Jungyeul proposed to use transformer because we are dealing with text data. Neural networks might performs better. 

## 2022/05/05

- I reviewed the EDA code, structured the notebook and wrote some reviews about the code.

## 2022/05/06 

- I read some papers about applying machine learning model to course evaluation.

## 2022/05/09 

- Met with Jungyeul and confirmed that we are gonna use Transformer as the baseline model.
- We need to get the baseline before May 20 and after that we will try to add some complex linguistic features.

## 2022/05/10
- I extracted the text from srt files, using regex to exclude the timestamps and special tokens

## 2022/05/11
- We met with CFI partner, presented what we have done and discussed what we should do in the following week.
- We finished the project plan.

## 2022/05/12
- Read the Long-Document Transformer paper to see how can we apply it to our model

## 2022/05/13
- I attended the Scott Mackie's talk about working in Amazon online.
- We had a meeting to discuss the what we should present on the meeting with Jungyeul.
- I used pysrt to extract the transcript and duration of each course and made them a dataframe.

## 2022/05/13 Reflection on Friday Speaker Series 1


## 2022/05/15 Code Review
1. Whose code are you reviewing, and where can the review be found?
  - I'm reviewing Xinyi and Chao's EDA code which can be found in the [shared notebook](https://colab.research.google.com/drive/1m8aMhuFXtgO7hhz9OMt_rWaap_GBK0HF#scrollTo=aIjjdXOq7HUA)
  - I organized the the notebook and documented some code to make them more understandable.

2. Where is one review of your code that you found particualrly helpful? What was helpful about it?
  - In order to aggregate and compare the features engineered by different teammates, I'd better store them as a dataframe.

## 2022/05/16
- We met with Jungyeul to discussion the two indications we've came up with, and the next step of our project.

## 2022/05/17
- I explored more about the readability scores that can be used in our features and some other features like coherence.

## 2022/05/19
- Finished code review and teamwork skills reflection

## 2022/05/20
- I attended the friday talk and wrote the reflection about it.

## 2022/05/23
- I attended a coaching session with Angelique to talk about my job-hunting process. The session helped me reflect on my past experience and know myself better. 
- My password for the session is: Parachute-Labrador-Recital
- I read the blog about "Fine-tuning BERT for a regression task" and discussed with teammates about how to implement this to our project.

## 2022/05/24
- I implemented the BERT model to transcripts and response_1 score.
- I solved the memory error problem by reducing the batch size down to 4 and tackled the 512-input limitation of Transformer-based model. 

## 2022/05/25
- I attended the weekly meeting with CFI and got several questions solved.

## 2022/05/26
- Wrote functions to visualize the course speed and redability score to help troubleshoot. 

## 2022/05/27
- Added the visualization to the presentation

## 2022/05/30
- Used the general NPS formula to calculate the NPS score and reset the model target to improve the model performance.

## 2022/05/31
- Built a NPS prediction model based on the survey data and get a high performance.

## 2022/06/01
- Discussed with teammates to add some features from the survey model to our linguistic model to improve the model performance.
- Had the meeting with CFI to present the high performance model

## 2022/06/02
- Extracted some outlier courses that are counter-intuitive in terms of their NPS score and the feature values.
- Discussed with teammates the reason behind.

## 2022/06/03
- Viualized the line graph for the speech of speed in each course

## 2022/06/06
- Added coherence and readability to the line graph to trouble shoot some problematic sections

## 2022/06/07
- Made the slides for the presentation and rehearsed with teammates

## 2022/06/08
- Had the meeting with Pavel and decided the content and date for final presentation
- Discussed with teammates about how to interpretate our model performance and the linguitic features to audiences


## 2022/06/09
- Generated the positive and negative word coulds separately for each courses

## 2022/06/10
- Brainstormed about how to make our presentation in a storytelling way

## 2022/06/13
- Revised the final presentation and discussed to improve the quality

## 2022/06/14
- Had the meeting with Jungyeul and Ryan to get some suggestions about the final presentation and kept polishing it. 

## 2022/06/15
- Made the presentation in CFI office and got a bunch of suggestions from the business perspective.
