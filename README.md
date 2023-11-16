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
```
python -m venv venv
```
3. Download the requirements to run the project :-
```
pip install -r requirements.txt
```
5. Run the API
```
python app.py
```
![1](https://github.com/atharvawasade20/QuickTubeSummarizer/assets/114360473/0d97ae9a-e85f-482c-b687-fefcb8885dc9)

7. Now we go to the frontend so open the command prompt through youtube-transcript-summarizer-frontend folder.

8. Run the below command to download all required node module!
s :-
```
npm install
```

9. Now run below command to all get set for the frontend :-
```
npm start
```
![2](https://github.com/atharvawasade20/QuickTubeSummarizer/assets/114360473/ec2fa052-c037-4906-aa05-9525dc61ede5)

![3](https://github.com/atharvawasade20/QuickTubeSummarizer/assets/114360473/84e384cd-17dd-4160-8334-8dceecba71f8)

10.Now your Chrome Extension is good to go......

![4](https://github.com/atharvawasade20/QuickTubeSummarizer/assets/114360473/976b82b8-dc40-4d02-93bd-9cf1ed9af002)

11. Paste the youtube transcript_id of a particular youtube video on the chrome extension and click on summarize.

![5](https://github.com/atharvawasade20/QuickTubeSummarizer/assets/114360473/88edb47b-1a9f-4eae-b2d6-f28b69fefcac)

12. Summary will be generated in different languages which is readable and downloadable and will also be audible in english.

![6](https://github.com/atharvawasade20/QuickTubeSummarizer/assets/114360473/76443afd-0aea-471e-93fc-d00e6e029e4b)

![7](https://github.com/atharvawasade20/QuickTubeSummarizer/assets/114360473/bc0e4d77-6948-41dd-acff-d20b4529e364)

![8](https://github.com/atharvawasade20/QuickTubeSummarizer/assets/114360473/93fecdee-7fc3-491b-8522-ae54071dc749)


