# Welcome! 👋

## ES COCO is an ongoing project to create the largest open-access data repository of Spanish-English bilingual speech data. Our data comes from podcasts and existing text corpora. These will be combined into one giant database that can be accessed via a user-friendly inteface. 

## Overview
This project aims to create an open-access data repository of Spanish-English bilingual speech called ES COCO (English-Spanish COde-switching COrpus). Some Spanish-English bilingual speech data sources already exist, such as BilingBank (MacWhinney, 2019). However, these data sources are not easily amenable to analysis because researchers must aggregate data across many files and sites. ES COCO will contain annotated speech from podcasts and already-existing corpora and metadata such as speaker and demographic information. This will be the largest self-contained Spanish-English corpus, enabling researchers to analyze the data without manually aggregating across many disparate sources.

## Method
Speech-to-text conversion: ES COCO will draw much of its data from recorded audio conversations between bilingual speakers (podcasts). We will convert this data to text so that it can be annotated using natural language processing techniques. To accomplish this, we will use OpenAI’s Whisper (Radford et al. 2022), a neural network model for automatic speech recognition.
Text annotation: For both transcribed audio and existing textual corpora, we will annotate each word with linguistic features such as which language it comes from, what part-of-speech it is, and its sentiment in context. We will achieve this using XLM RoBERTa, a transformer language model (Conneau et al., 2019), that we will fine-tune using bilingual-focused datasets from LinCE (Aguilar et al., 2020).

## Product and End Goal
ES COCO will have a user-friendly interface that can run locally on a user’s machine or be accessed via web browser. Users will be able to search and filter the corpus by linguistic features (e.g., part of speech, language, code switch), view the linguistic context (i.e., the sentence), access speaker information (e.g., demographics, proficiency), access file information (i.e., source), and download data for their own analyses. ES COCO removes the largest barriers in language research: the time and financial cost of collecting, transcribing, and tagging data. This corpus is particularly beneficial for researchers who are not at R1 institutions and who have limited access to funding, personnel, time, and the language communities required for language research.
