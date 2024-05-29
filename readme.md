# <h1 align="center">**Natural Language Processing Models**</h1>

<p align="center">
<img src="NLP.png"> 
</p>

This repository contains a collection of links to my repositories, which showcase implementations of natural language processing (NLP) models in Python, using TensorFlow and Hugging Face's ``Transformers`` library.

## **What is Natural Language Processing?**

Natural Language Processing is a field of artificial intelligence that focuses on the interaction between computers and humans through natural language. It involves the development of algorithms and models to enable computers to understand, interpret, and generate human language.

## **Implemented Models**

The following are the natural language processing models that I have implemented to date:

1. [**Text Classification**](https://github.com/JersonGB22/TextClassification-TensorFlow): Text classification is a common NLP task that assigns a label or class to a piece of text based on its content. It is used for tasks such as sentiment analysis, spam detection, and topic categorization.

2. [**Token Classification**](https://github.com/JersonGB22/TextClassification-TensorFlow): Token classification involves assigning labels to individual tokens in a sentence or sequence of text. It is commonly used for tasks such as named entity recognition, part-of-speech tagging, and syntactic chunking.

3. [**Question Answering**](https://github.com/JersonGB22/TextClassification-TensorFlow): Question answering models aim to generate a relevant answer given a question and context. They are used in applications such as chatbots, virtual assistants, and search engines.

4. [**Causal Language Modeling**](https://github.com/JersonGB22/TextClassification-TensorFlow): Causal language modeling predicts the next token in a sequence of tokens, with the model only attending to tokens to the left. These models are frequently used for text generation tasks, where maintaining coherence and context is essential. GPT-2 is an example of a causal language model.

5. [**Translation**](https://github.com/JersonGB22/TextClassification-TensorFlow): Translation models convert text from one language to another, enabling cross-lingual communication and content localization. They can also be used for tasks such as speech-to-text and text-to-speech conversion.

6. [**Summarization**](https://github.com/JersonGB22/TextClassification-TensorFlow): Summarization models generate concise summaries of longer texts while retaining essential information. They are valuable for tasks such as document summarization, news article extraction, and content recommendation.

## **Contributions**

Contributions to this repository are welcome. If you have any questions or suggestions, please do not hesitate to contact me.

## **Technological Stack**
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=101010)](https://docs.python.org/3/) 
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white&labelColor=101010)](https://www.tensorflow.org/api_docs)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU+SHVnZ2luZyBGYWNlPC90aXRsZT48cGF0aCBkPSJNMS40NDQ2IDExLjUwNTljMCAxLjEwMjEuMTY3MyAyLjE1ODUuNDg0NyAzLjE1NjMtLjAzNzgtLjAwMjgtLjA2OTEtLjAwNTgtLjEwNTgtLjAwNTgtLjQyMDkgMC0uODAxNS4xNi0xLjA3MDQuNDUxMi0uMzQ1NC4zNzM3LS40OTg0LjgzMzUtLjQzMTYgMS4yOTNhMS41NzYgMS41NzYgMCAwIDAgLjIxNDguNTk3OGMtLjIzMTkuMTg2NC0uNDAxOC40NDU2LS40ODQ0Ljc1NzgtLjA2NDYuMjQ0OC0uMTMxLjc1NDMuMjE0OSAxLjI3OTRhMS40NTUyIDEuNDU1MiAwIDAgMC0uMDYyNS4xMDU1Yy0uMjA4LjM5MjMtLjIyMDcuODM3Mi0uMDM3MSAxLjI1LjI3ODMuNjI1OC45Njk2IDEuMTE3NSAyLjMxMjYgMS42NDY3LjgzNTYuMzI5MiAxLjU5ODguNTQxMSAxLjYwNTYuNTQzIDEuMTA0Ni4yODQ3IDIuMTA0LjQyNzcgMi45NjkuNDI3NyAxLjQxNzMgMCAyLjQ3NTQtLjM4NDkgMy4xNTI1LTEuMTQ0NiAxLjUzOC4yNjUxIDIuNzkxLjE0MDMgMy41OTIuMDA2LjY3NzMuNzU1NSAxLjczMzIgMS4xMzg3IDMuMTQ2NyAxLjEzODcuODY0OSAwIDEuODY0My0uMTQzIDIuOTY5LS40Mjc4LjAwNjgtLjAwMTkuNzctLjIxMzggMS42MDU2LS41NDMgMS4zNDMtLjUyOTIgMi4wMzQzLTEuMDIwOCAyLjMxMjYtMS42NDY2LjE4MzYtLjQxMjkuMTcxLS44NTc3LS4wMzctMS4yNWExLjQ2ODUgMS40Njg1IDAgMCAwLS4wNjI2LS4xMDU2Yy4zNDYtLjUyNS4yNzk1LTEuMDM0Ni4yMTQ5LTEuMjc5My0uMDgyNi0uMzEyMi0uMjUyNS0uNTcxNC0uNDg0NC0uNzU3OS4xMS0uMTgxNi4xODMxLS4zNzg4LjIxNDgtLjU5NzcuMDY2OS0uNDU5NS0uMDg2Mi0uOTE5My0uNDMxNi0xLjI5My0uMjY4OC0uMjkxMy0uNjQ5NS0uNDUxMy0xLjA3MDQtLjQ1MTMtLjAyMDkgMC0uMDM3Ni4wMDA4LS4wNTg4LjAwMTguMzE2Mi0uOTk2Ni40ODQ2LTIuMDUxOC40ODQ2LTMuMTUyMyAwLTUuODA3LTQuNzM2Mi0xMC41MTQ0LTEwLjU3ODktMTAuNTE0NC01Ljg0MjYgMC0xMC41Nzg4IDQuNzA3My0xMC41Nzg4IDEwLjUxNDRabTEwLjU3ODgtOS40ODMxYzUuMjcyNyAwIDkuNTQ3NiA0LjI0NiA5LjU0NzYgOS40ODNhOS40MjAxIDkuNDIwMSAwIDAgMS0uMjY5NiAyLjIzNjVjLS4wMDM5LS4wMDQ3LS4wMDc5LS4wMTEtLjAxMTctLjAxNTYtLjI3NC0uMzI1NS0uNjY3OS0uNTA1OS0xLjEwNzUtLjUwNTktLjM1MiAwLS43MTQuMTE1NS0xLjA3NjMuMzQzOC0uMjQwMy4xNTE3LS41MDU4LjQyMi0uNzc5My43NTk4LS4yNTM0LS4zNDkyLS42MDgtLjU4MzItMS4wMTM3LS42NDY1YTEuNTE3NCAxLjUxNzQgMCAwIDAtLjIzNDQtLjAxNzZjLS45MjYzIDAtMS40ODI4Ljc5OTMtMS42OTM1IDEuNTE3Ny0uMTA0Ni4yNDI2LS42MDY1IDEuMzQ4Mi0xLjM2MTQgMi4wOTc4LTEuMTY4MSAxLjE2MDEtMS40NDU4IDIuMzUzNC0uODM5NiAzLjYzODItLjg0My4xMDI5LTEuNTgzNi4wOTI3LTIuMzY1LS4wMDYuNTkwNi0xLjIxMi4zNjI2LTIuNDM4OC0uODQyNi0zLjYzMjItLjc1NS0uNzQ5Ni0xLjI1NjgtMS44NTUyLTEuMzYxNC0yLjA5NzgtLjIxMDctLjcxODQtLjc2NzMtMS41MTc3LTEuNjkzNS0xLjUxNzctLjA3OCAwLS4xNTY4LjAwNTQtLjIzNDQuMDE3Ni0uNDA1Ny4wNjMzLS43NjA0LjI5NzMtMS4wMTM3LjY0NjUtLjI3MzUtLjMzNzktLjUzOS0uNjA4MS0uNzc5NC0uNzU5OC0uMzYyMi0uMjI4My0uNzI0My0uMzQzOC0xLjA3NjItLjM0MzgtLjQyNjYgMC0uODA5NC4xNzEtMS4wODIxLjQ3ODZhOS40MjA4IDkuNDIwOCAwIDAgMS0uMjU5OC0yLjE5MzZjMC01LjIzNyA0LjI3NDktOS40ODMgOS41NDc1LTkuNDgzek04LjY0NDMgNy4wMDM2Yy0uNDgzOC4wMDQzLS45NTAzLjI2NjctMS4xOTM0LjcyMjctLjM1MzYuNjYzMy0uMTAwNiAxLjQ4NzMuNTY0NSAxLjg0LjM1MS4xODYyLjQ4ODMtLjUyNjEuODM2LS42NDg1LjMxMDctLjEwOTUuODQxLjM5OSAxLjAwNzguMDg2LjM1MzYtLjY2MzQuMTAyNS0xLjQ4NzQtLjU2MjUtMS44NGExLjM2NTkgMS4zNjU5IDAgMCAwLS42NTI0LS4xNjAyWm02Ljg0MDMgMGMtLjIxOTktLjAwMi0uNDQyNi4wNS0uNjUwNC4xNjAyLS42NjUuMzUyNi0uOTE4MSAxLjE3NjYtLjU2NDUgMS44NC4xNjY5LjMxMy42OTcxLS4xOTU1IDEuMDA3OS0uMDg2LjM0NzYuMTIyNC40ODY3LjgzNDcuODM4LjY0ODUuNjY0OS0uMzUyNy45MTYtMS4xNzY3LjU2MjQtMS44NC0uMjQzLS40NTYtLjcwOTYtLjcxODQtMS4xOTM0LS43MjI3Wm0tOS43NTY1IDEuNDE4YS44NzY4Ljg3NjggMCAwIDAtLjg3Ny44NzdjMCAuNDg0Ni4zOTI1Ljg3Ny44NzcuODc3YS44NzY4Ljg3NjggMCAwIDAgLjg3Ny0uODc3Ljg3NjguODc2OCAwIDAgMC0uODc3LS44Nzd6bTEyLjY0MzQgMGMtLjQ4NDUgMC0uODc5LjM5MjUtLjg3OS44NzcgMCAuNDg0Ni4zOTQ1Ljg3Ny44NzkuODc3YS44NzY4Ljg3NjggMCAwIDAgLjg3Ny0uODc3Ljg3NjguODc2OCAwIDAgMC0uODc3LS44Nzd6TTguNzkyNyAxMS40NTljLS4xNzktLjAwMy0uMjc5My4xMTA3LS4yNzkzLjQxNiAwIC44MDk3LjM4NzQgMi4xMjUgMS40Mjc5IDIuOTI0LjIwNy0uNzEyMyAxLjM0NTMtMS4yODMyIDEuNTA3OS0xLjIwMTIuMjMxNS4xMTY3LjIxOTEuNDQxNy42MDc0LjcyNjYuMzg4NC0uMjg1LjM3NC0uNjA5OC42MDU2LS43MjY2LjE2MjctLjA4MiAxLjMwMDkuNDg4OSAxLjUwNzkgMS4yMDEyIDEuMDQwNC0uNzk5IDEuNDI3OC0yLjExNDQgMS40Mjc4LTIuOTI0IDAtMS4yMjEyLTEuNTgzLjY0MDItMy41NDEzLjY0ODUtMS40Njg2LS4wMDYxLTIuNzI2Ni0xLjA1NTgtMy4yNjM5LTEuMDY0NXpNNC4zMTIgMTQuNDc2OGMuNTc5Mi4zNjUgMS42OTY0IDIuMjc1MSAyLjEwNTYgMy4wMTc3LjEzNzEuMjQ4OC4zNzEuMzUzNi41ODIuMzUzNi40MTg4IDAgLjc0NjUtLjQxMzguMDM5MS0uOTM5NS0xLjA2MzYtLjc5MS0uNjkxNC0yLjA4NDYtLjE4MzYtMi4xNjQyYS40MzAyLjQzMDIgMCAwIDEgLjA2NjQtLjAwNGMuNDYxNiAwIC42NjYuNzg5Mi42NjYuNzg5MnMuNTk1OSAxLjQ4OTggMS42MjEzIDIuNTA4Yy45NDIuOTM1NiAxLjA2MiAxLjcwMy40OTYxIDIuNjY2MS0uMDE2NC0uMDA0LS4wMTU5LjAyMzYtLjE0ODQuMjE0OS0uMTg1My4yNjczLS40MzIyLjQ2ODgtLjcxODguNjE1Mi0uNTA2Mi4yMjY5LTEuMTM5Ny4yNjk2LTEuNzgzMy4yNjk2LTEuMDM3IDAtMi4xMDE3LS4xODI0LTIuNjk3NS0uMzM2LS4wMjkzLS4wMDc1LTMuNjUwNS0uOTU2Ny0zLjE5MTYtMS44MjI0LjA3NzEtLjE0NTQuMjAzMy0uMjAzMS4zNjMzLS4yMDMxLjY0NjMgMCAxLjgyMy45NTUxIDIuMzI4My45NTUxLjExMyAwIC4xOTYtLjA4NjUuMjI4NS0uMjAzMS4yMjQ5LS44MDQ1LTMuMjc4Ny0xLjA1MjItMi45ODQ2LTIuMTY0Mi4wNTE5LS4xOTY3LjE5My0uMjc1Ny4zOTA3LS4yNzU0Ljg1NCAwIDIuNzcwNCAxLjQ5MjMgMy4xNzIgMS40OTIzLjAzMDcgMCAuMDUyNS0uMDA4NS4wNjQ1LS4wMjc0LjIwMTItLjMyMjcuMTA5Ni0uNTg2NS0xLjMwODctMS40Mzk1LTEuNDE4Mi0uODUzMy0yLjQzMTUtMS4zMjktMS44NjUzLTEuOTQxNi4wNjUxLS4wNzA3LjE1NzQtLjEwMTUuMjY5NS0uMTAxNS44NjExLjAwMDIgMi44OTQ4IDEuODQgMi44OTQ4IDEuODRzLjU0ODcuNTY4My44ODA5LjU2ODNjLjA3NjIgMCAuMTQxNi0uMDMxNS4xODU1LS4xMDU0LjIzNTUtLjM5NDYtMi4xODU4LTIuMjE4My0yLjMyMjQtMi45NzEtLjA5MjYtLjUxLjA2NDEtLjc2NzYuMzU1NS0uNzY3Ni0uMDAwNi4wMDguMTcwMS0uMDI4NS40OTQyLjE3NTl6bTE2LjIyNTcuNTkxOGMtLjEzNjYuNzUyNi0yLjU1NzkgMi41NzY0LTIuMzIyNCAyLjk3MDkuMDQ0LjA3NC4xMDkyLjEwNTUuMTg1NS4xMDU1LjMzMjEgMCAuODgxLS41Njg0Ljg4MS0uNTY4NHMyLjAzMzYtMS44Mzk3IDIuODk0Ny0xLjg0Yy4xMTIxIDAgLjIwNDQuMDMwOC4yNjk1LjEwMTYuNTY2Mi42MTI1LS40NDcgMS4wODgyLTEuODY1MyAxLjk0MTUtMS40MTgzLjg1My0xLjUxIDEuMTE2OC0xLjMwODcgMS40Mzk2LjAxMi4wMTg4LjAzMzcuMDI3My4wNjQ0LjAyNzMuNDAxNiAwIDIuMzE4MS0xLjQ5MjMgMy4xNzIxLTEuNDkyMy4xOTc3LS4wMDAyLjMzODguMDc4Ny4zOTA3LjI3NTQuMjk0IDEuMTEyLTMuMjA5NSAxLjM1OTctMi45ODQ2IDIuMTY0Mi4wMzI1LjExNjYuMTE1Ni4yMDMyLjIyODUuMjAzMi41MDU0IDAgMS42ODItLjk1NTIgMi4zMjgzLS45NTUyLjE2IDAgLjI4NjIuMDU3Ny4zNjMzLjIwMzIuNDU5Ljg2NTYtMy4xNjIzIDEuODE0OS0zLjE5MTYgMS44MjI0LS41OTU4LjE1MzUtMS42NjA1LjMzNi0yLjY5NzUuMzM2LS42MzUxIDAtMS4yNjEtLjA0MDktMS43NjM4LS4yNTk5LS4yOTQ5LS4xNDcyLS41NDg4LS4zNTE2LS43MzgzLS42MjUtLjA0MTEtLjA2ODItLjEwMjYtLjE0NzYtLjE0MjYtLjIwNS0uNTcyNi0uOTY3OS0uNDU1LTEuNzM3MS40OTAzLTIuNjc2IDEuMDI1NC0xLjAxODIgMS42MjEyLTIuNTA4IDEuNjIxMi0yLjUwOHMuMjA0NC0uNzg5MS42NjYtLjc4OTFhLjQzMTguNDMxOCAwIDAgMSAuMDY2NS4wMDM5Yy41MDc4LjA3OTYuODggMS4zNzMyLS4xODM2IDIuMTY0Mi0uNzA3NC41MjU3LS4zNzk3LjkzOTUuMDM5LjkzOTUuMjExIDAgLjQ0NS0uMTA0Ny41ODIxLS4zNTM1LjQwOTItLjc0MjYgMS41MjY0LTIuNjUyNyAyLjEwNTYtMy4wMTc4LjU1ODgtLjM1MjQuOTktLjE4MTYuODQ5Ny41OTE4eiIvPjwvc3ZnPg==&labelColor=F7931E)](https://huggingface.co/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white&labelColor=101010)](https://scikit-learn.org/stable/)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white&labelColor=101010)](https://plotly.com/)

## **Contact**
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=101010)](mailto:jerson.gimenesbeltran@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=101010)](https://www.linkedin.com/in/jerson-gimenes-beltran/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/JersonGB22/)