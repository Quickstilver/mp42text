# mp42text


This project aims to provide an easy-to-use pipeline for extracting transcriptions from lengthy video recordings, such as a summit, with minimal effort. By leveraging state-of-the-art technologies and models, this pipeline saves time and resources, enabling you to focus on analyzing and summarizing the content of the transcriptions.

## Project Highlights:

- Utilizes the OpenAI Whisper model for accurate speech-to-text conversion.
- Supports Google Colab environment for effortless setup and execution.
- Leverages MoviePy for video to audio conversion.
- Exports transcriptions to a text file for easy access and further analysis.

## Libraries and Dependencies:

- openai-whisper
- transformers
- pydub
- moviepy.editor
- torch

## Main Steps:

1. Upload the notebook on Colab into the 'Colab Notebooks' folder
2. Create a 'Colab Notebooks/data/' folder and upload you file.mp4
3. Run all the cells on Colab:

    - Install prerequisites and required libraries.
    - Load the pre-trained Whisper model.
    - Extract audio from the video file using MoviePy.
    - Transcribe the audio using the Whisper model.
    - Save the transcription to a text file.
## Conclusions:
This project showcases a streamlined approach to extracting transcriptions from lengthy video recordings. The video2text simplifies the process of obtaining transcriptions, allowing you to focus on analyzing and summarizing the content for further use. The pipeline can be adapted and extended to cater to various use cases, including interviews, lectures, and more.
