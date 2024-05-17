# Product-Description-Generator---LLM-Pipeline
This study addressed the challenge of incomplete or inadequate product descriptions in e-Commerce by integrating Large Language Models (LLMs) and image-to-text technology. 

## Business Problem:

In the competitive landscape of e-Commerce, high-quality product descriptions are crucial for enhancing customer engagement, satisfaction, and sales. Retailers often face challenges in generating complete and effective product descriptions due to the high cost of human labor and the difficulty of maintaining consistency across vast product ranges. This study focuses on addressing the issue of incomplete or inadequate product descriptions, a significant problem that affects 33% of a national retailer's stock-keeping units (SKUs), resulting in missed sales opportunities.

## Methodology

<img width="452" alt="image" src="https://github.com/hchitnen/Product-Description-Generator---LLM-Pipeline/assets/148294077/2aea4bf9-3f4f-4260-a54d-395382adde72">


To tackle this issue, we employed a combination of Large Language Models (LLMs) and image-to-text technology, integrated within a cloud-based analytical pipeline on Microsoft Azure. The approach involved several steps:

**Data Collection**: The dataset included 309,826 unique products from a major US grocery store, with varying levels of completeness in descriptions and images.

**Image-to-Text Models:** Two models, Optical Character Recognition (OCR) and Image Captioning, were used to extract textual information from product images. The Azure AI Vision was selected for its high accuracy and compatibility with our cloud deployment.

<img width="375" alt="image" src="https://github.com/hchitnen/Product-Description-Generator---LLM-Pipeline/assets/148294077/da844913-b342-4561-97e8-35dc4f3bfde1">



**Text-to-Text Models (LLMs):** Four LLMs were evaluated, and the Mixtral 8X7b instruct model was chosen for generating product descriptions based on its superior performance in a small-scale experiment.


**Scoring Model:** A scoring model was developed to evaluate the quality of descriptions based on relevance, completeness, readability, and confidence scores. Descriptions had to meet specific thresholds in these areas to be published.

<img width="360" alt="image" src="https://github.com/hchitnen/Product-Description-Generator---LLM-Pipeline/assets/148294077/9e609a05-eec8-44c1-9a9a-a2ac5cf67bad">



**Cloud Deployment:** The solution was deployed on Azure Cloud, utilizing services like Azure Blob Storage, Azure Machine Learning Workspace, and Azure Compute Instance to automate and scale the process.

<img width="452" alt="image" src="https://github.com/hchitnen/Product-Description-Generator---LLM-Pipeline/assets/148294077/c1df3df6-1793-4656-ab5d-8e2880bac128">

## Results and Conclusion

The implementation of our methodology resulted in significant improvements in product description quality. Initially, only 40% of product descriptions met the quality standards. After employing our solution, 59% of previously inadequate descriptions passed the evaluation, and overall, 73% of products with unqualified descriptions or only images were improved. This enhancement in product descriptions not only addresses the immediate business problem but also contributes to a better online shopping experience by providing customers with more accurate and engaging product information.In conclusion, integrating LLMs with image-to-text technology offers a scalable and cost-effective solution for improving product descriptions in e-Commerce. Future research could focus on refining these models and exploring alternative evaluation methodologies to further enhance description quality and reliability.
