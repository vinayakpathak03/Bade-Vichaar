# Quick-Minutes-of-Meeting-using-ChatGPT. 
Developed a system using OpenAI's Da Vinci 003 (GPT-3.5) and Whisper to transcribe audio and generate Minutes of Meeting (MoM) from video files. ChatGPT acts like a co-founder.

# MoM Generator

This project is an automated MoM (Minute of Meeting) generator. It takes in a video file and generates the MoM in form of bullet points.

## Features

- Upload video file and generate MoM
- Automatically converts video to audio
- Automatically transcribes audio file
- Automatically generates MoM in form of bullet points

## Requirements

- ffmpeg
- whisper
- openai
- FastAPI
- aiofiles

## Usage

1. Install the required libraries using `pip install <library_name>`
2. Run the server using `uvicorn main:app --reload`
3. Upload the video file using the endpoint `/upload_video`
4. The MoM in form of bullet points will be returned

## Endpoints

- `/upload_video` (POST): Uploads the video file and returns the MoM in form of bullet points.
