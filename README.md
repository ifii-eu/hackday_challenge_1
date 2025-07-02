# Challenge 1: Video Transcription & Chunking
## Challenge Overview

The goal of this challenge is to develop a robust pipeline system that automatically generates a transcription from a given video (https://limewire.com/d/Gln68#lUJbsoQrws) and then produces a high-quality summary based on that transcript. A key aspect of this task is to explore and evaluate different chunking strategies to determine which approach yields the best overall summary.

## Tasks

1.	Transcription
    1.	Extract the audio from the video and transcribe it using a suitable speech-to-text model (e.g., Whisper).
    2.	Ensure the transcript is accurately segmented, linguistically coherent, and time-aligned.
2.	Chunking Strategies
    1.	Implement at least three different chunking approaches, such as:
    1.	Fixed-length chunks (based on characters, tokens, or time)
    2.	Semantic segmentation based on topic shifts
    3.	Pause-based or time-based chunking
    4.	LLM-based dynamic chunking
3.	Summarization
    1.	Generate partial summaries for each chunk and then aggregate them into a final overall summary.
    2.	Optionally compare this chunked summarization with a direct full-transcript summary.
    3.	Use an appropriate language model (e.g. Mistral, LLaMA) to create the summaries.
4.	Develop an Evaluation Criterion
    1.	Design an objective evaluation framework to assess the quality of the generated summaries, considering factors like:
        1.	Information coverage
        2.	Coherence and readability
        3.	Redundancy reduction
5.	Goal
    1.	Identify which chunking strategy, in combination with your chosen model, produces the best final summary.
    2.	Provide a well-reasoned recommendation for real-world use of such systems in similar scenarios.
## Expected Deliverables

1.	Complete code for the end-to-end pipeline (Transcription → Chunking → Summarization → Evaluation)
2.	Documentation of the different strategies and evaluation results
3.	Visualization of the results (e.g., comparative scores across strategies)
4.	Optional: Web demo or API endpoint for pipeline usage

# Material:

## Data
* Videos: https://limewire.com/d/Gln68#lUJbsoQrws

## links
|Service| URL| user | password|
|-|-|-|-|
|RAGflow|https://blissful-diffie.46-4-9-235.plesk.page|intern@ifii.eu|4!-Haxx0r-25

