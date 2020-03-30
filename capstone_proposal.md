# Machine Learning Engineer Nanodegree

## Capstone Proposal

Haitham Alhad Hyder

March 30th, 2019

## Proposal

Note: _(approx. 2-3 pages)_

### Domain Background

The Titanic data set is famous data set that is part of an introductory Kaggle competition.

> **Citation:** Kaggle. (n.d.). Titanic: Machine Learning from Disaster. Retrieved from <https://www.kaggle.com/c/titanic/overview>

It is about the infamous RMS Titanic, an "unsinkable" ship that made the headlines on April 15, 1912. Out of the 2224 passengers and crew, only 1502 of them survived. Although it comes down to chance if a person survives, the data shows that some groups of people have a higher chance of surviving. To solve the problem of identifying those who have a higher chance of survival we will have to come up with a machine learning model that can gives us the probability of someone surviving or not.

I am motivated to finish this project, since I want to get involved with Kaggle. A journey of a thousand miles starts with a single step and also begins at the door.

### Problem Statement

What we want our Machine learning model to identify is the pattern that yields the survival of a passenger or crew member. The output of our model would be a probability of survival and therefore a possible solution would be building a logistic model.

To quantify the problem we would have a test data set that would help us evaluate how well our model is doing by looking at the precision and recall numbers of our model.

### Data sets and Inputs

The data set is obtained from Kaggle's Titanic competition. We will only make use of the train data set since we don't know the labels of the test data set and we want to be able to evaluate our models ourselves.

> **Citation:** Kaggle. (n.d.). Titanic: Machine Learning from Disaster. Retrieved from <https://www.kaggle.com/c/titanic/overview>

The data contains information on the amount of fair someone paid, the number of parents or children involved with them as well as other characteristics. The labels are only provided in the _train_ data set.

The different characteristics of the people on board will help us generate a model that identifies that patterns that increase chances of survival.

Finally, when we deploy the model, we can send in characteristics of a person and get their chance of survival.

### Solution Statement

The solution that we will implement are two different models, an XGBoost logistic model as well as a PyTorch neural network. Since our expected output is binary then getting a probability between 0 and 1 can easily be rounded of to a binary value.

In the deployed web app that we can input characteristics of a person, the output would not be binary but a probability of survival.

### Benchmark Model

Note: _(approximately 1-2 paragraphs)_

In this section, provide the details for a benchmark model or result that relates to the domain, problem statement, and intended solution. Ideally, the benchmark model or result contextualizes existing methods or known information in the domain and problem given, which could then be objectively compared to the solution. Describe how the benchmark model or result is measurable (can be measured by some metric and clearly observed) with thorough detail.

### Evaluation Metrics

Note: _(approx. 1-2 paragraphs)_

In this section, propose at least one evaluation metric that can be used to quantify the performance of both the benchmark model and the solution model. The evaluation metric(s) you propose should be appropriate given the context of the data, the problem statement, and the intended solution. Describe how the evaluation metric(s) are derived and provide an example of their mathematical representations (if applicable). Complex evaluation metrics should be clearly defined and quantifiable (can be expressed in mathematical or logical terms).

### Project Design

Note: _(approx. 1 page)_

In this final section, summarize a theoretical workflow for approaching a solution given the problem. Provide thorough discussion for what strategies you may consider employing, what analysis of the data might be required before being used, or which algorithms will be considered for your implementation. The workflow and discussion that you provide should align with the qualities of the previous sections. Additionally, you are encouraged to include small visualizations, pseudo-code, or diagrams to aid in describing the project design, but it is not required. The discussion should clearly outline your intended workflow of the capstone project.

-----------

**Before submitting your proposal, ask yourself. . .**

- Does the proposal you have written follow a well-organized structure similar to that of the project template?
- Is each section (particularly **Solution Statement** and **Project Design**) written in a clear, concise and specific fashion? Are there any ambiguous terms or phrases that need clarification?
- Would the intended audience of your project be able to understand your proposal?
- Have you properly proofread your proposal to assure there are minimal grammatical and spelling mistakes?
- Are all the resources used for this project correctly cited and referenced?