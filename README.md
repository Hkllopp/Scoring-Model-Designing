# Scoring-Model-Designing

This project was completed as part of the OpenClassroom training course to become an AI Engineer. Although all the code and instructions are public, they own the rights to the project.

## Instructions :

You are a Data Scientist in a financial company, named "Prêt à dépenser", which offers consumer credits for people with little or no loan history. To grant a consumer credit, the company wants to implement a "credit scoring" tool that calculates the probability that a customer will repay it or not, and then classifies the request: credit granted or refused. The company therefore wants to develop a classification algorithm to help decide whether a loan can be granted to a customer.

The scoring tool will be used by the **customer relationship managers**. Since they are talking to customers, they need your model to be **easily interpretable**. In addition, the relationship managers want to have **a measure of the importance of the variables** that caused the model to give that probability to a customer.

To build this model, Michael, your manager, has provided you with [the following dataset](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Impl%C3%A9menter+un+mod%C3%A8le+de+scoring/Projet+Mise+en+prod+-+home-credit-default-risk.zip) that contains:

-   a history of loans
-   a history of financial information
-   borrower behavior information (whether the borrower has defaulted or not)

After an initial briefing meeting, Michael sent you this summary email:

## Email :

---

From: Michaël

Sent: yesterday 17:14

To: you

Subject: Recap. Scoring algorithm

---

Hello,

Thanks for our meeting. I wanted to complete it by giving you some resources:

-   To go faster on the data preparation, you can use a [Kaggle kernel](https://www.kaggle.com/willkoehrsen/start-here-a-gentle-introduction). However, make sure that it is adapted to your needs. In particular, try to build at least three new variables from the existing ones that you think are relevant to improve the predictive power of the model. Also try to make the kernel as appropriate as possible by adapting it for the project.
-   We mentioned that your model must be interpretable by the teams that will use it. Do not hesitate to consult [this site](https://towardsdatascience.com/interpretability-in-machine-learning-70c30694a05f) and [this Github](https://christophm.github.io/interpretable-ml-book/) on this subject. Remember to explain in a few lines the method of importance of the variables you will use.
-   The model will be presented to the teams, so make sure that your presentation is understandable by all, and that your Jupyter is well documented. For the slides, I suggest this plan:
    -   Understanding the business problem
    -   Description of the dataset
    -   Transformation of the dataset (cleaning and feature engineering)
    -   Comparison and synthesis of the results for the models used
    -   Interpretability of the model
    -   Conclusion

Good luck !

Michaël

---

## Deliverables

-   A Jupyter Notebook presenting the different parts of your modeling work.
    -   This notebook must be able to be used by another person, like Michaël for example. Its presentation and structuring must be carefully done so that the notebook can be used by someone other than you, without you having to train them to use it.
-   A presentation (PowerPoint or an alternative):
    -   This deliverable will be used to present your methodological approach to modeling the scoring problem during the oral defense in front of Michaël.

## Defense

During the defense, the evaluator will play the role of Michael, to whom you present your work. Special attention will be paid to your speech. Michael wants to make sure that your presentation is at the right level to be understood by a non-technical audience.

- Presentation (20 minutes)
    -   Reminder of the problem, presentation of the data set and exploratory analysis (5 minutes)
    - Presentation of your methodological approach and synthesis of results (15 minutes) Discussion (5 minutes) The evaluator, playing the role of Michael, will challenge you on your choices.
- Debriefing (5 minutes)
    -   At the end of the presentation, the evaluator will stop playing the role of Michael to allow you to debrief together.

Translated with www.DeepL.com/Translator (free version)
