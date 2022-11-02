# Predicting Citation Counts of Artificial Intelligence Research Papers
### Using ROBERTA Document Embeddings and Linear Regression

In this quick notebook I show a Natural Language Processing and Machine Learning pipeline to predict 4.3% of variance (R2) in citation counts of research papers about Artificial Intelligence. This data is sourced from the ['aminer' database](https://www.kaggle.com/datasets/kmader/aminer-academic-citation-dataset), and the papers analyzed are those that were presented through the [International Joint Conference on Artificial Intelligence](https://www.ijcai.org/).

Linear Regression and XGBoost were benchmarked (without tuning), with Linear Regression outperforming. These results show that current NLP methods can explain some variance, but that research paper impact is likely the result of many factors, such as the structure of the academic graph, the institutions and researchers involved, the place of publication, the promotional efforts, and many other such factors not encompassed by the text in the abstract. Because of these systemic factors, improving citation prediction results will likely need to integrate data about these academic networks.

### Repository Structure
The full NLP and ML pipeline is contained in the ['Citation Prediction'](https://github.com/thegrandblooms/Predicting_Citation_Counts_of_AI_Research_Papers/blob/2324318f4fb87f3211358143f173a9fad739f613/Citation_Prediction_from_ROBERTA_Embeddings.ipynb) notebook, and just the NLP pipeline applied to an Arxiv snapshot can be seen within the ['Roberta_data_processing'](https://github.com/thegrandblooms/Predicting_Citation_Counts_of_AI_Research_Papers/blob/main/Roberta_data_processing.ipynb) Notebook.
