**Abstract** 
Offensive language is pervasive in social media. Individuals frequently take advantage of the perceived anonymity of computer-mediated communication, using this to engage in behavior that many of them would not consider in real life. The automatic identification of offensive content online is an important task that has gained more attention in recent years. This task can be modeled as a supervised classification problem in which systems are trained using a dataset containing posts that are annotated with respect to the presence of some form(s) of abusive or offensive content. The objective of this study is to provide a description of a classification system built for SemEval-2019 Task 6: OffensEval. This system classifies a tweet as either offensive or not offensive (Sub-task A) and further classifies offensive tweets into categories (Sub-tasks B \& C). We trained machine learning and deep learning models along with data preprocessing and sampling techniques to come up with the best results. Models discussed include Naive Bayes, SVM, Logistic Regression, Random Forest and LSTM.


## Task Description

In this study, the task under consideration is divided into three sub-tasks as follows.

### Sub-task A - Offensive language identification:

In this sub-task, we are interested in the identification of offensive posts and posts containing any form of (untargeted) profanity. In this sub-task, there are 2 categories in which the tweet could be classified -

Not Offensive - This post does not contain offense or profanity.
Offensive - This post contains offensive language or a targeted (veiled or direct) offense. To sum up, this category includes insults, threats, and posts containing profane language and swear words.

### Sub-task B - Automatic categorization of offense types:

In this sub-task, we are interested in categorizing
offenses. Tweets are labeled from one of the
following categories -

Targeted Insult - A post containing an insult or a threat to an individual, group, or others.
Untargeted - A post containing non-targeted profanity and swearing. Posts containing general profanity are not targeted but they contain non-acceptable language. On the other hand, insults and threats are targeted at an individual or group.

### Sub-task C - Offense target identification:
Finally, in sub-task C we are interested in the target of offenses. Only posts that are either insults or threats are included in this sub-task. The three categories included in sub-task C are the following - 

Individual - The target of the offensive post is an individual: a famous person, named individual or an unnamed person interacting in the conversation.
Group - The target of the offensive post is a group of people considered as a unity due to the same ethnicity, gender or sexual orientation, political affiliation, religious belief, or something else.
Other - The target of the offensive post does not belong to any of the previous two categories (e.g. an organization, a situation, an event, or an issue).
