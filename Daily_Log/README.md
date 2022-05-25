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

## 2022/05/18


## 2022/05/19
- Finished code review and teamwork skills reflection

## 2022/05/20
- I attended the friday talk and wrote the reflection about it.

## 2022/05/20 Reflection on Friday Speaker Series 2

1. MLOps is the fusion of traditional DevOps processes in the context of data science and machine learning. ML processes are data-centric contrasted with the code-centric philosophy of DevOps. Taking learnings and methodologies from DevOps and applying them to the context of Data and ML yields an operating model termed MLOps or DataOps.
2. DataOps is an operating model very similar to MLOps but applied to the context of data specifically. Without DataOps any ML initiative would have a hard time getting off the ground. DataOps enables teams to minimize the turnaround time of data analytics cycles while maintaining data quality and integrity.
3. The DataOps enabled pipeline is as follows:
  - Identify & Collect: The first step in a DataOps enabled pipeline is identifying sources and source systems where the target data lives. 
  - Process: Once the source data is identified it needs to be processed and transformed into a form that can be analyzed or explored.
  - Store: Using a data warehouse or a data lake is a typical storage option for organizations looking to serve transformed data.
  - Problem Formulation: Once a business problem or opportunity for improvement is identified, the data has been landed and transformed, it is time to now frame this problem in an analytical context.
  - Requirements: The first step of problem formulation would be to come up with hypotheses and requirements that would support this hypothesis.
  - Explore: This step involves a lot of back and forth between the users or stakeholders that identified the problem or opportunity and analyzing the underlying data to evaluate relationships between data points.
  - Analytical Framework Selection: The main aspect of the framework selection would be the underlying statistical model that is used to make the prediction or analysis, such as regression, classification or clustering.
  - Modelling: This is where the features are engineered from the data, the model is trained and tested and finally packaged for the next stage of MLOps which is operationalization.
  - Extract: In machine learning, features refer to characteristics relating to the proposed hypothesis. The goal is to extract features that contain information about or prove meaningful relationships with the target business problem or improvement opportunity. 
  - Train: Training is fitting a model to your train data set while maintaining optimal performance and meeting the requirements.
  - Optimize: Using offline evaluation, your data team can rapidly iterate and optimize the model before going live. 


## 2022/05/23
- I attended a coaching session with Angelique to talk about my job-hunting process. The session helped me reflect on my past experience and know myself better. 
- My password for the session is: Parachute-Labrador-Recital
- I read the blog about "Fine-tuning BERT for a regression task" and discussed with teammates about how to implement this to our project.

## 2022/05/24
- I implemented the BERT model to transcripts and response_1 score.
- I solved the memory error problem by reducing the batch size down to 4 and tackled the 512-input limitation of Transformer-based model. 

## 2022/05/25
- I attended the weekly meeting with CFI and got several questions solved.
