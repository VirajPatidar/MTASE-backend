# MTASE (Multilingual Text Analyzer and Summarization Engine) Backend

_This project serves as backend for [MTASE frontend](https://github.com/VirajPatidar/MTASE-frontend)._

The objective of this project is to build a Multilingual Text Analyzer and Summarization Engine that can analyze, translate and summarize a piece of unlabeled/unidentified/unknown text provided by the user as input and make its services available via a web application.


### Features ###
| Functionality | Description |
| :---         | :--- 
| Language Identification | Identify the language of input text provided by the user |
| Language Translation | Convert non English input text to English for further processing |
| Keyword Extraction | Extract the most important keywords that define the provided text |
| Abstractive Summarization | Concise summary generated by paraphrasing and capturing meaning of input text |
| Extractive Summarization | Summary generated stitching together important sentences or phrases of original text |
| Meta Data | Basic statistics of text are returned |


### Work Flow ###

<img src="https://github.com/VirajPatidar/MTASE-backend/blob/main/data/readme_data/MTASE_workflow.png" alt="MTASE Summarisation Workflow" width="600"/>


### Usage ###
| API Endpoint | `POST: /api/summarise` |
| :---         | :--- 
| Input | Piece of text desired to be summarised |
| Output | Meta data, Translated Text, Abstractive Summary, Extractive Summary and Keywords of original text blob |


### Tech Stack ###
* Django REST Framework v3.13.1
* Django v4.0.1
* PyTorch v1.8.2+cpu
* SQLite
