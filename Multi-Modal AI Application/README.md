# MultiModal-AI-App
An AI-driven vision model that can provide contextual information for images and video. This application allows a user to upload an image and/or a video clip and the transformer model will answer a set of pre-defined questions about the image or what is happening in the video. The prompted questions are regarding scenes during an American football game. The user can alter the questions in the code to prompt questions for other scene types.

This application can be a useful tool in the sports domain by allowing team players and coaches to view images/video of game play situations and can ask the AI system for guidance or to explain the situation. The ultimate goal would be to provide this as a tool that could help sports teams gain a strategic advantage over their opponents. The model did not answer all questions correctly, however, and it also requires a lot of computing power to run. These challenges will need to be overcome before a real-time application can be deployed.

## Features
1. Image and Video Scene Description
2. Question Answering
3. Interactive web application using Streamlit

## Requirements
Python 3.8+

Install required libraries:
```
!pip install transformers torch pillow opencv-python openai
!pip install streamlit
!npm install localtunnel
!pip install streamlit-webrtc
```

## Usage
1. Clone the repository into Google CoLab
```
https://github.com/your_username/MultiModal-AI-App.git
```
2. Upload code to Google Colab
3. Run the Streamlit application
```
1. Press Ctrl-F9 to run application from Google Colab.
2. Copy the IP address listed after cell 3.
3. Click the link provided after cell 4.
```
4. The application will automatically open in your browser
```
Paste the IP address into the password field and the application will run.
```
5. Alternate option
```
1. Save the file to the current working directory as your_app.py.
2. Run the application via the terminal using the command:
    streamlit run your_app.py
```
Application demonstration video:
https://umsystem.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=60c16e68-54c0-4763-9bf1-b293001b5f30

Jupyter notebook link:
https://colab.research.google.com/drive/1HTXiWRAhBNIzwMQeoQwasYznkddr2BuP?usp=sharing
