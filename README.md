# Generative AI with Amazon Bedrock

<a href="https://www.packtpub.com/en-us/product/generative-ai-with-amazon-bedrock-9781803247281?utm_source=github&utm_medium=repository&utm_campaign=9781786461629"><img src="https://content.packt.com/_/image/xxlarge/B22045/cover_image_large.jpg" alt="" height="256px" align="right"></a>

This is the code repository for [Generative AI with Amazon Bedrock](https://www.packtpub.com/en-us/product/generative-ai-with-amazon-bedrock-9781803247281?utm_source=github&utm_medium=repository&utm_campaign=9781786461629), published by Packt.

**Build, scale, and secure generative AI applications using Amazon Bedrock**

## What is this book about?
This book provides a hands-on approach to building generative AI applications at scale, covering several architectural patterns and use cases to help you solve business problems and innovate within your organization.

This book covers the following exciting features:
* Explore the generative AI landscape and foundation models in Amazon Bedrock
* Fine-tune generative models to improve their performance
* Explore several architecture patterns for different business use cases
* Gain insights into ethical AI practices, model governance, and risk mitigation strategies
* Enhance your skills in employing agents to develop intelligence and orchestrate tasks
* Monitor and understand metrics and Amazon Bedrock model response
* Explore various industrial use cases and architectures to solve real-world business problems using RAG
* Stay on top of architectural best practices and industry standards

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1803247282) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
#import the main packages and libraries
import os
import boto3
import botocore
```

## Chapterwise Notebooks
---

| Chapter No | Notebook Name                                | Notebook Link with Icon                                                |
|------------|----------------------------------------------|------------------------------------------------------------------------|
| Chapter 2  | AmazonBedrock_ConverseAPI.ipynb              | [📓 AmazonBedrock_ConverseAPI.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter02/AmazonBedrock_ConverseAPI.ipynb)              |
| Chapter 2  | AmazonBedrock_ConverseStreamAPI.ipynb        | [📓 AmazonBedrock_ConverseStreamAPI.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter02/AmazonBedrock_ConverseStreamAPI.ipynb)  |
| Chapter 5  | AmazonBedrockRetrieveAPI.ipynb               | [📓 AmazonBedrockRetrieveAPI.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter05/AmazonBedrockRetrieveAPI.ipynb)               |
| Chapter 5  | AmazonBedrockRetrieveAndGenerateAPI.ipynb    | [📓 AmazonBedrockRetrieveAndGenerateAPI.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter05/AmazonBedrockRetrieveAndGenerateAPI.ipynb) |
| Chapter 6  | AI21JurassicEmailSample.ipynb                | [📓 AI21JurassicEmailSample.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter06/AI21JurassicEmailSample.ipynb)                |
| Chapter 6  | GeneratingText.ipynb                         | [📓 GeneratingText.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter06/GeneratingText.ipynb)                         |
| Chapter 6  | SummarizingText.ipynb                        | [📓 SummarizingText.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter06/SummarizingText.ipynb)                        |
| Chapter 7  | AmazonBedrockQASample.ipynb                  | [📓 AmazonBedrockQASample.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter07/AmazonBedrockQASample.ipynb)                  |
| Chapter 7  | RAG_BedrockwithLangChain.ipynb               | [📓 RAG_BedrockwithLangChain.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter07/RAG_BedrockwithLangChain.ipynb)               |
| Chapter 7  | SmallDocumentIngestion_BedrockwithLangChain.ipynb | [📓 SmallDocumentIngestion_BedrockwithLangChain.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter07/SmallDocumentIngestion_BedrockwithLangChain.ipynb) |
| Chapter 8  | CodeGenerationAmazonBedrock.ipynb            | [📓 CodeGenerationAmazonBedrock.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter08/CodeGenerationAmazonBedrock.ipynb)            |
| Chapter 8  | CodeTranslationAmazonBedrock.ipynb           | [📓 CodeTranslationAmazonBedrock.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter08/CodeTranslationAmazonBedrock.ipynb)           |
| Chapter 8  | EntityExtractionAmazonBedrock.ipynb          | [📓 EntityExtractionAmazonBedrock.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter08/EntityExtractionAmazonBedrock.ipynb)          |
| Chapter 8  | EntityExtractionAmazonTitan.ipynb            | [📓 EntityExtractionAmazonTitan.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter08/EntityExtractionAmazonTitan.ipynb)            |
| Chapter 8  | EntityExtractionAnthropicClaude.ipynb        | [📓 EntityExtractionAnthropicClaude.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter08/EntityExtractionAnthropicClaude.ipynb)        |
| Chapter 9  | WatermarkDetection.ipynb                     | [📓 WatermarkDetection.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter09/WatermarkDetection.ipynb)                     |
| Chapter 10 | LangChainAgentswithAmazonBedrock.ipynb       | [📓 LangChainAgentswithAmazonBedrock.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter10/LangChainAgentswithAmazon%20Bedrock.ipynb)       |
| Chapter 12 | InvocationWithGuardrails.ipynb               | [📓 InvocationWithGuardrails.ipynb](https://github.com/PacktPublishing/Generative-AI-with-Amazon-Bedrock/blob/main/Chapter12/InvocationWithGuardrails.ipynb)               |
```

**Following is what you need for this book:**
This book is for generalist application engineers, solution engineers and architects, technical managers, ML advocates, data engineers, and data scientists looking to either innovate within their organization or solve business use cases using generative AI. A basic understanding of AWS APIs and core AWS services for machine learning is expected.

With the following software and hardware list you can run all code files present in the book (Chapter 1-12).
### Software and Hardware List
| Chapter | Software required | OS required |
| -------- | ------------------------------------ | ----------------------------------- |
| 1-12 | Python | Linux (Any) |
| 1-12 | Amazon Web Services | Linux (Any) |
| 1-12 | Jupyter-based notebooks, such as Amazon SageMaker | Linux (Any) |


### Related products
* Modern Data Architecture on AWS [[Packt]](https://www.packtpub.com/en-us/product/modern-data-architecture-on-aws-9781801813396?utm_source=github&utm_medium=repository&utm_campaign=) [[Amazon]](https://www.amazon.com/dp/1801813396)

* Unlocking the Secrets of Prompt Engineering [[Packt]](https://www.packtpub.com/en-us/product/unlocking-the-secrets-of-prompt-engineering-9781835083833?utm_source=github&utm_medium=repository&utm_campaign=) [[Amazon]](https://www.amazon.com/dp/1835083838)

## Get to Know the Author
**Shikhar Kwatra**
a senior AI/ML solutions architect at Amazon Web Services, holds the distinction of being the world’s Youngest Master Inventor with over 500 patents in AI/ML and IoT domains. He serves as a technical journal reviewer, book author, and educator. Shikhar earned his Master’s in Electrical Engineering from Columbia University. With over a decade of experience spanning startups to large-scale enterprises, he specializes in architecting scalable, cost-efficient cloud environments and supports GSI partners in developing strategic industry solutions. Beyond his professional pursuits, Shikhar finds joy in playing the guitar, composing music, and practicing mindfulness.

**Bunny Kaushik**
is an AWS solution architect and ML specialist who loves to build solutions and help customers innovate on the AWS platform. He is an Amazon SageMaker SME, generative AI hero, and ML thought leader within AWS. He has over 10 years of experience working as an ML specialist and managing projects across different teams and . Outside of work, he enjoys swimming, playing volleyball, rock climbing, and exploring new places.

