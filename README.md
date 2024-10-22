---
title: CogVideoX-5B
emoji: 🎥
colorFrom: yellow
colorTo: blue
sdk: gradio
sdk_version: 4.44.0
suggested_hardware: l40sx1
suggested_storage: large
app_port: 7860
app_file: app.py
models:
  - THUDM/CogVideoX-5b
tags:
  - cogvideox
  - video-generation
  - thudm
short_description: Text-to-Video
disable_embedding: false
---

# Gradio Composite Demo

This Gradio demo integrates the CogVideoX-5B model, allowing you to perform video inference directly in your browser. It
supports features like UpScale, RIFE, and other functionalities.

## Environment Setup

Set the following environment variables in your system:

+ OPENAI_API_KEY = your_api_key
+ OPENAI_BASE_URL= your_base_url
+ GRADIO_TEMP_DIR= gradio_tmp

## Installation

```bash
pip install -r requirements.txt 
```

## Running the code

```bash
python gradio_web_demo.py
```


