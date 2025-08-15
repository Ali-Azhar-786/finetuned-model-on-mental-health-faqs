# finetuned-model-on-mental-health-faqs
Fine tuned pretrained model "TinyLlama/TinyLlama-1.1B-Chat-v1.0" on the mental health queries &amp; created a chatbot to answer the mental health queries. The purpose is to provide an open source interface where people can get answers to their mental health queries. I have used the kaggle dataset "mental_health_faqs" for this project.
# Calm-Compass

This is an open source chatbot which uses finetuned model to answer mental health queries. It is can be used to by any individual to easily get answers to any mental health related query just by chatting with asistant.
It solves many complex mental health problems. Many people hesitate to book appointments with doctors and Other platforms like GPT, Grok, Gemini e.t.c lack the accurate and precise information related to mental health problems.
So, Calm-Compass provide accurate and precise asnwers to any sort of query related to mental health problem.


## Tools

NOTE:Min 8GB GPU RAM is rquired to run this project

Following Tools are used:

HARDWARE:
KAGGLE(GPU T4 x 2)

DATASET:
mental_health_qa.csv

MODEL:
TinyLlama/TinyLlama-1.1B-Chat-v1.0

LIBRARIES:
Pytorch
Transformers
Pandas
DATASET
Evaluate
Streamlit
## Installation

Download the zip file
Extract the zip file
    
## Run Locally

If you want to fine tune the model & use chatbot then:

1).Run the main.py file
"python main.py"

2).Select the option
"--all"

3).It will start fine tuning process

4).After fine tuning you can chat with assistant


But, if you want to ignore fine tuning process and use chatbot directly then:

1).Change directory
"cd streamlit"

2). Run the streamlit_run.py file
"streamlit run streamlit_run.py"

3).It will install necesary dependencies and redirect you to streamlit app

4). There you can interact with the chat assistant
