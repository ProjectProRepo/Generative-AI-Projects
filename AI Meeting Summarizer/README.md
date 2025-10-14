# AI Project to Build a Meeting Summarizer with Whisper and Gemini

## Overview

In the modern workplace, meetings are the backbone of decision-making, project planning, and collaboration. However, keeping track of key points, action items, and insights from long discussions can be overwhelming. This project introduces an **AI-powered Meeting Summarizer** that automates the transcription, analysis, and summarization of meeting content using **Whisper** and **Gemini** models.  

By combining speech-to-text accuracy with large language model (LLM) reasoning, the system produces concise summaries, identifies action items, and highlights discussion themes, ensuring that no critical insights are lost. This intelligent automation helps teams focus on outcomes rather than note-taking.

Traditional meeting documentation methods rely on manual note-taking or partial recordings, often leading to inconsistencies and missed follow-ups. This project solves that challenge by integrating **Whisper** for transcription, **Gemini/OpenAI models** for summarization and action item detection, and **VADER** for sentiment analysis to capture emotional tone—offering a complete, end-to-end meeting intelligence solution.

> **Note:** Completion of the **LLM Fine-Tuning Project** is recommended before attempting this project.

---

## Project Objectives

- Build an AI meeting summarizer capable of **transcribing and analyzing meeting content**.  
- Use **Whisper** for timestamped transcription of meeting audio.  
- Implement **Gemini** and **OpenAI models** to summarize content and identify action items.  
- Perform **sentiment analysis** to gauge meeting tone and participant engagement.  
- Store and visualize structured insights for easy access and follow-up.

---

## Introduction to the Project

This project focuses on streamlining meeting management by leveraging AI for real-time transcription and summarization. It begins by processing meeting audio or video inputs, converting them into accurate, timestamped transcripts using **Whisper**. These transcripts are analyzed by **Gemini** and **OpenAI GPT-4** models to extract themes, questions, and next steps.  

Additionally, **VADER sentiment analysis** quantifies emotional tone, helping organizations assess communication effectiveness. The final output provides structured, actionable summaries that empower teams to make informed decisions and track accountability.

---

## Prerequisites

Before beginning, ensure you have:

- Completed the **LLM Fine-Tuning Project**.  
- Basic knowledge of **Python**, **Prompt Engineering**, and **LLMs**.  
- Familiarity with **OpenAI Whisper** for speech-to-text processing.  

> **Note:** Using OpenAI or Google Generative AI APIs may incur usage costs. Review their pricing documentation before implementation.

---

## Aim

The goal of this project is to build an **AI-based system** that automates meeting transcription, summarization, and sentiment analysis to produce clear, actionable insights. This tool minimizes manual note-taking effort and enhances productivity in collaborative work environments.

---

## Data Description

- **Input:** Meeting audio or video files (e.g., `.mp4`, `.wav`).  
- **Processed Data:** Timestamped transcripts generated via Whisper.  
- **Output:**  
  - Action items with assigned speakers.  
  - Key questions and discussion points.  
  - Sentiment analysis scores (positive, neutral, negative).  
  - JSON-based structured summaries and visualization-ready data.

---

## Tech Stack

- **Language:** Python 3.10  
- **Libraries:** pandas, langchain, langchain-openai, openai, vaderSentiment  
- **Models:** Google Gemini, OpenAI Whisper, GPT-4  

---

## Solution Approach

### 1. Data Ingestion
- Accept meeting audio or video files in supported formats (`.mp4`, `.wav`, `.m4a`).  
- Validate and prepare audio files for transcription.

### 2. Transcription
- Use **Whisper** to transcribe meeting content with high accuracy.  
- Include timestamps and speaker diarization if available.  
- Save transcriptions in a structured **JSON** format for downstream processing.

### 3. Sentiment Analysis
- Apply **VADER** to evaluate the emotional tone of the conversation.  
- Calculate sentiment scores (positive, negative, neutral, and compound).  
- Visualize trends in mood throughout the meeting duration.

### 4. Meeting Summarization
Use **Gemini** or **GPT-4** models to:
- Summarize discussions into key takeaways.  
- Extract timestamped **action items** with assigned speakers.  
- Identify **key questions** raised during the meeting.  
- Produce concise summaries for email or documentation purposes.

### 5. Storage and Error Handling
- Store processed outputs (transcripts, summaries, and sentiment data) in JSON or database format.  
- Implement error-handling and logging mechanisms for audio processing, API calls, and file management.

---

## Expected Outcomes

By completing this project, you will:
- Gain hands-on experience with **speech-to-text and text summarization pipelines**.  
- Learn to combine **Whisper**, **Gemini**, and **GPT-4** for multimodal meeting analysis.  
- Build a system capable of generating structured, actionable meeting summaries.  
- Understand how to integrate **sentiment analytics** to enhance team feedback loops.

---

## Project Link

[AI Project to Build a Meeting Summarizer with Whisper and Gemini](https://www.projectpro.io/data-science-use-cases/ai-meeting-summarizer)

---

## Next Steps

- Integrate with **Slack or Teams APIs** for real-time transcription and summary sharing.  
- Add **topic classification** and **speaker identification** for richer context.  
- Create a **Streamlit dashboard** for visualizing sentiment and key metrics.  
- Extend to **multi-language transcription** using Whisper’s multilingual support.  
- Implement **action item tracking** through integrations with project management tools.
