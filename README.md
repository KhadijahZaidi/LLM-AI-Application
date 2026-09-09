# Computer Vision and LLM-Powered AI Application

*AI application concept / portfolio project*

## Purpose
Build an end-to-end application that accepts an image, extracts visual information, produces a structured prediction, and uses an LLM to generate a clear explanation or personalised recommendation.

## Overview
Designed an end-to-end AI workflow combining computer vision, machine learning, and large language models. The solution uses OpenCV to validate and preprocess uploaded images, a PyTorch CNN to identify visual characteristics, and Scikit-learn to combine structured features where required. FastAPI exposes the inference workflow, while PostgreSQL stores prediction metadata, user feedback, and audit records. Prompt engineering and response chaining are used to transform model outputs into clear, contextual explanations or personalised recommendations. The architecture also includes input validation, secure API handling, containerised deployment, and monitoring considerations.

## Technical Highlights
- Connected image preprocessing, model inference, and LLM reasoning in one workflow.
- Selected FastAPI as the single backend framework and PyTorch as the deep-learning framework.
- Designed database records for predictions, feedback, model versions, and operational logs.

## Tech Stack
Python, OpenCV, PyTorch CNN, Scikit-learn, LLM API, FastAPI, PostgreSQL

## Summary
Designed an end-to-end AI application combining OpenCV image processing, PyTorch CNN inference, structured ML predictions, and LLM-powered explanations through FastAPI and PostgreSQL.
