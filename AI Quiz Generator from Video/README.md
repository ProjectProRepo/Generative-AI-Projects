# Build an AI Quiz Generator from Video with OpenAI API

## Overview

Video content is widely used in education, corporate training, and media, yet it often lacks interactivity and accessibility. Transcribing videos into text improves searchability, supports learners with hearing impairments, and enhances content navigation. Generating quizzes from this content engages users and helps assess comprehension.  

This project leverages **OpenAI’s Whisper** for transcription and **GPT-4o** for summarization and quiz generation. By automating these processes, the project provides a scalable, high-accuracy solution that converts videos into structured text and interactive quizzes. Traditional manual approaches are time-consuming, less accurate, and lack scalability—limitations that LLM-based solutions overcome efficiently.

> **Note:** Completion of the **LLM Fine-Tuning Project** is recommended before starting this project.

---

## Project Objectives

- Extract video and audio content using **MoviePy**.  
- Handle large audio files by splitting into chunks with **AudioSegment**.  
- Transcribe video content accurately using **OpenAI Whisper**.  
- Summarize transcribed content using **GPT-4o**.  
- Generate **contextually relevant quiz questions** from summaries.  
- Structure LLM outputs into **JSON** using **LangChain**.  
- Evaluate LLM responses for accuracy and relevance using **G-Eval**.  
- Develop a **Flask API** for video upload, transcription, and quiz generation.  
- Build a **Streamlit frontend** for user-friendly interaction.  

---

## Prerequisites

- Basics of **LLMs**, **Prompt Engineering**, and **Python**.  
- Familiarity with **Flask** and **Streamlit** for API and UI development.  
- Understanding of **video/audio processing libraries** (MoviePy, pydub).  

> **Note:** Using OpenAI APIs may incur costs; review their pricing and usage policies before starting.

---

## Aim

The aim of this project is to build an automated system that:  
1. Transcribes video content using **Whisper**.  
2. Summarizes key concepts with **GPT-4o**.  
3. Generates interactive quizzes aligned with the content.  
4. Evaluates output quality and relevance.  

This solution enhances accessibility and engagement, streamlining content interaction and assessment for educational, corporate, and media contexts.

---

## Data Description

- **Input:** Tutorial or educational videos across various topics.  
- **Output:** Timestamped transcriptions, summarized content, structured quiz questions (with options and answers).

---

## Tech Stack

- **Language:** Python 3.10  
- **Libraries:** langchain, langchain-openai, openai, flask, streamlit, ffmpeg, moviepy, pydub  
- **Models:** OpenAI Whisper, GPT-4o  

---

## Solution Approach

### 1. Video Transcription with Whisper
- Extract audio from video files using **MoviePy**.  
- Process audio using **Whisper** to generate high-accuracy text transcriptions.  

### 2. Summarization of Transcribed Content
- Summarize transcription using **GPT-4o**.  
- Create structured summaries that capture key points and concepts.

### 3. Quiz Generation with GPT-4o
- Design prompts to generate meaningful multiple-choice or short-answer questions.  
- Use **LangChain** to structure responses into JSON format (questions, options, answers).  

### 4. Response Evaluation
- Validate summaries and quizzes for accuracy, relevance, and alignment with video content using **G-Eval**.

### 5. Backend Development with Flask
- Create a **Flask API** to manage video uploads, transcription, summarization, and quiz generation.  
- Test API endpoints locally using **Postman**.

### 6. Frontend Interface with Streamlit
- Build a **user-friendly interface** for video uploads.  
- Display transcriptions, summaries, and quizzes in an interactive format.  

---

## Expected Outcomes

By completing this project, you will:  
- Gain expertise in **video transcription and summarization using LLMs**.  
- Automate **quiz generation** from video content.  
- Build a **full-stack solution** integrating Flask APIs with Streamlit UI.  
- Enhance accessibility and engagement for educational content.  

---

## Project Link

[AI Quiz Generator from Video with OpenAI API](https://www.projectpro.io/project-use-case/ai-quiz-generator-from-video)

---

## Next Steps

- Extend quiz generation to include **adaptive difficulty levels**.  
- Support **multi-language transcription and quizzes**.  
- Integrate analytics for **user performance tracking**.  
- Explore **self-hosted LLM models** for offline transcription and quiz generation.
