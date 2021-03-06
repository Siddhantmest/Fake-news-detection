# Fake News Detection

The rise of fake news is one of the downsides of the internet age and concern over the problem is global. Aggravating the problem, much information remains unknown regarding the vulnerabilities of individuals, institutions and society to manipulations by malicious actors. Resolving the problem using natural language processing is a hot topic of discussion among data scientists.

The project focuses on implementing Natural Language Processing on a dataset consisting of claims and a list of articles supporting those claims, there by developing a supervised machine learning model that will be able to predict the truthness label of each claim from one of the three categories namely "True", "Partly Ture" and "False". 

Extending further, considering the claim labels in the dataset as "ground truth", we analyse the predictions of claims made by prominent US politicians to deduce the degree of fake news being spread.

## Insights into the dataset:

    The chosen dataset has features like:

        1. date - when the claim was made
        2. id - unique identifier for each claim
        3. label - truthness category
        4. claim - headline or brief statement
        5. article id's - Id's of articles related to the claim
        6. claimant - name of the person/organization made the claim
        
## Improvement

The code to concatenate the articles and preprocess them corresponding the claims was taking considerable amount of time (1300 Sec). In order to speed up the code as well as improve the accuracy of the predictions **cosine similarity is used along with text summarization**. It helped to speed up the code by 54.77%
