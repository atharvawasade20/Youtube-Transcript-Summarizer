## Overview

The YouTube Transcript Summarizer Chrome Extension is a browser-based tool designed to enhance the user experience when watching YouTube videos. This extension leverages the power of natural language processing and machine learning to automatically generate concise and informative summaries of video transcripts, making it easier for users to quickly grasp the key points of a video without having to watch the entire content.

## Implementation strategy

So basically, it will be a chrome extension, having an option to copy to current URL of the video being selected. After providing the link, it will access the transcript of the particular audio using the YouTube transcript API and then the transcript will be provided to a machine learning model will in return provide the summarized text of the transcript. The summarized text would be downloadable by the user.

## Features

- 4 Language Support (Hindi,English,Gujarati,Braille)
- Real-time Text-to-Speech (English)
- Get Transcripts of videos of long length eventually saving time.
- Downloadable Transcripts.


## Installation

1. Clone the repository in your local machine.

2. We need to set the virtual environment to run api so open the command prompt through youtube-transcript-summarizer folder and run :-
'''
python -m venv venv
'''
3. Download the requirements to run the project :-  
'''
pip install -r requirements.txt
'''
4. Run the API
'''
python app.py
'''
5. Now we go to the frontend so open the command prompt through youtube-transcript-summarizer-frontend folder.

6. Run the below command to download all required node modules :-
'''
npm install
'''
7. Now run below command to all get set for the frontend :-

npm start




