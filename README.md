# Syntactic Processing - Healthcare Treatment Prediction case study for MS - AI/ML
> This is a case study for Syntactic Processing - Healthcare Treatment Prediction

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Predict the Treatment for the Disease from the Healthcare data
- Load the data, data preprocessing, construct proper sentence from the individual data, Count number of sentences and labels
- Syntactic Tagging and Frequency Analysis, Extract and Count NOUN/PROPER NOUN
- Feature Engineering for CRF with PoS tagging
- Feature + Label Preparation
- Prepare CRF Model Inputs
- Train CRF Model
- Treatment Prediction + Evaluate
- Model Evaluation and Conclusion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- The CRF-based NER model has proven to be robust and reliable in identifying diseases and treatments within biomedical text.
- With a high F1 score and accurate predictions on domain-specific cases, it is well-suited for downstream tasks such as automated medical literature mining, treatment recommendation pipelines, and clinical decision support systems.

### The Key Insights and Outcomes:
### Dataset Overview
- Total sentences in training set: 2,599
- Total sentences in test set: 1,056
- Corresponding lines of entity labels align perfectly with the sentence counts, indicating clean and consistent dataset preparation.

### Corpus Insights
- The top 25 most frequent nouns and proper nouns highlight domain relevance, with high occurrences of terms like patients, treatment, cancer, therapy, and disease.
- This reinforces the biomedical focus of the corpus and the richness of vocabulary in the clinical treatment-disease context.

### Model Performance
- The CRF-based Named Entity Recognition (NER) model achieved a weighted F1-score of 0.9071, demonstrating high accuracy in tagging disease and treatment entities across the test set.
- This indicates the model’s strong ability to generalize and correctly identify biomedical entities even in unseen data.

### Use Case Validation
- In a targeted evaluation, the model correctly identified the treatment “radiotherapy” associated with the disease “hereditary retinoblastoma”, showcasing its practical applicability in extracting clinically relevant information from natural language text.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
- Python Programming
- Panda for Data Wrangling and Data manipulation purposes
- CRF (Conditional Random Fields) sequence modeling for structured prediction tasks like NER
- CRFsuite metrics for Flat F1 score to assess the performance of CRF models on sequence-labeled data
- spaCy is an NLP library for processing and analyzing large volumes of text, including tokenization, POS tagging, and NER
- NLP loads a small English language model in spaCy that includes vocabulary, syntax, and entity recognition capabilities.
- All the versions are the latest as of June 2025

<!-- As the library versions keep on changing, it is recommended to mention the version of the library used in this project -->

## Acknowledgements
I want to credit upGrad for the Master of Science in Machine Learning and Artificial Intelligence (AI/ML) degree alongside IIIT-Bangalore, and LJMU, UK
- This project was inspired by all the Professors who trained during the Lexical Processing and Syntactic Processing, namely
  - Srinath Srinivasa - Professor, IIIT-B

## Contact
Created by [@rajaravisekara] - feel free to contact me, Raja - Sr Architect - AI Cloud


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
