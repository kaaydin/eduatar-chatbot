# Eduatar Chatbot

## Introduction

The Eduatar Chatbot project leverages Natural Language Processing (NLP) and Deep Learning to assist Swiss apprentices, teachers, and parents in navigating the complexities of the apprenticeship system. This project is a collaborative effort with the vocational training office in Bern and aims to enhance productivity and provide timely responses to common inquiries related to apprenticeships.

## Project Overview

**Objective**: To develop an intelligent chatbot, Eduatar, using large language models (LLMs) for automating responses to common queries about Swiss apprenticeships.

**Key Features**:
- **Automated Responses**: Quick and reliable information on topics like working hours, compensations, and legal questions.
- **Advanced NLP Techniques**: Utilizing state-of-the-art LLMs like GPT-3.5/4 and VICUNA for accurate and relevant answers.

## Methods

The project methodology encompasses:
1. **Dataset Generation**: Building a dataset tailored for fine-tuning BERT-style models.
2. **Model Selection & Fine-Tuning**: Evaluating and fine-tuning models like BERT, GPT-3.5, and VICUNA.
3. **Pipeline Setup**: Implementing a retriever-reader model using the LangChain framework.
4. **Model Evaluation**: Employing manual and automated methods to assess model performance.

## Results

- **GPT-3.5** demonstrated the highest accuracy in both manual and automated evaluations.
- **VICUNA models** showed competitive performance, suggesting potential for further improvement.
- **GELECTRA models** require additional refinement for better performance.

## Discussion

Key insights from the project:
- **Model Efficacy**: Advanced LLMs like GPT-3.5 outperform older models in response accuracy.
- **Fine-Tuning**: Critical for enhancing model performance, with a focus on data quality.
- **Evaluation Methods**: Importance of diverse evaluation approaches for comprehensive assessment.
- **Scalability**: Emphasizing the need for expansive and diverse document databases.

## Conclusion

This project establishes a foundational proof of concept in the application of LLMs for educational chatbots. Further research and development are required to optimize the performance and utility of such systems.

---

For more details, please see the [report](https://github.com/kaaydin/eduatar-chatbot/blob/main/report/nlp-report-final.pdf)
