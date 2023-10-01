# OCR-free Document Understanding with Donut Transformer

## Overview
This project addresses the real case scenario of the automation of processing client information and documents for mortgage granting, aiming to optimize document classification, error detection, data extraction, and validation.

## Problem
The goal is to enhance efficiency in mortgage granting by automating the identification and processing of documents provided by clients, both in physical offices and digital channels. The purpose is to reduce response times, enhance customer experience, and minimize operational costs and risks.

## IA Team KPIs:

* **Precision**: >=98% (This means 98% of the documents are processed correctly in all stages)
* **Automation**: >=60% (60% of the documents are processed automatically without human intervention)
* **SLA**: <2 hours

## Objectives

* Reduction in response times and improvement in customer experience.
* Research in the field of Visual Document Understanding (VDU).
* End-to-end automation with high precision and efficiency.
* Selection and adaptation of suitable AI models.
* Evaluation of results and project viability.

## Methodology
The Donut architecture was adopted to address document classification and data extraction. 

This model was proposed in <a href="https://arxiv.org/abs/2111.15664" target="_blank">OCR-free Document Understanding Transformer</a> by Geewook Kim, Teakgyu Hong, Moonbin Yim, Jeongyeon Nam, Jinyoung Park, Jinyeong Yim, Wonseok Hwang, Sangdoo Yun, Dongyoon Han, Seunghyun Park. Donut consists of an image Transformer encoder and an autoregressive text Transformer decoder to perform document understanding tasks such as document image classification, form understanding and visual question answering.

![donut_architecture](https://github.com/javier-marti-isasi/OCR-free-Document-Understanding-with-Donut-Transformer/assets/73080100/015b1eb4-6679-480a-981d-74945d390b57)

The Donut model will be fine-tuned to address the document classification problem. For the data extraction challenge, inference will be applied directly to a pre-trained Donut model.

## Results
The OCR-free Donut model proved to be efficient and precise for document comprehension, overcoming challenges associated with traditional OCR-based methods.

## Metrics obtained:

* **Document classification**: 98.63% precision and 62.43% automation.
* **Data extraction**: 100.00% precision and 95.24% automation.

Note: These results come from experimental datasets and might need adjustment for datasets more representative of business reality. However, the current results are promising and suggest a viable practical application.

---

For more information about the project, please check the `Project_Workflow.pdf`.

