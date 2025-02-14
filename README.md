# PROJECT-9

## NEWS RESEARCH TOOL -- LLM MODEL

![image](https://github.com/user-attachments/assets/70492236-3f0c-4e85-94f9-590d4e8b0805)

## PROJECT OVERVIEW

## Objective:
Build an AI-powered tool for summarizing news articles

## Technologies:
LangChain, OpenAI API, Streamlit, NewsAPI

## Features:
Query-based summarization, UI for interaction, export options

## Phase 1:  Environment setup

## INSTALL REQUIRED LIBRARIES:  pip install langchain openai streamlit newsapi-python
from dotenv import load_dotenv
import os
from newsapi import NewsApiClient
from langchain_groq import ChatGroq
from langchain_core.prompts import PromptTemplate
import streamlit as st
from langchain_config import get_summary

## OBTAIN API KEYS:  - 
OpenAI API Key
NewsAPI Key

## Phase 2: LangChain Configuration
This is the screenshot of file langchain_config.py

![image](https://github.com/user-attachments/assets/f5db12af-3425-49d9-8222-43b6f3af762c)

## Phase 3: Building Streamlit Interface:

Below is the screenshot of the same

![image](https://github.com/user-attachments/assets/65be2484-1456-4354-a1ef-ed571a3eef92)

## Phase 4: Testing and Validation:

Test basic functionality: Ensure app runs and responds correctly

![image](https://github.com/user-attachments/assets/f5d22b6f-f3f1-4624-9572-605aca1ffd85)

The screenshot below shows that the news summary displayed about the query entered is valid.  Hence the validation is perfect.

![image](https://github.com/user-attachments/assets/6b4a853e-940f-40d6-881f-44a16f4fb187)

## Acknowledgement:

I would like to express my sincere gratitude to Ms. Twinkle Baid for her invaluable guidance, support, and mentorship throughout this project. Her expertise, encouragement, and constructive feedback have played a crucial role in shaping the direction of this work.




