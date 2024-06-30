# Sign Language to Text and Chatbot Communication System

Developing AI to enable communication for the deaf and dumb via a sign language recognizer and a conversational chatbot, aimed at fostering independence without the need for physical inputs

## Project Overview
This Capstone Project aims to bridge the communication gap for deaf and dumb individuals through the development of two interconnected AI models. The first model is a sign language recognizer that converts sign language gestures into text. The second model is a chatbot designed to engage in simple conversations based on the text input from the sign language recognizer. This system is developed to enable individuals who are deaf and dumb to communicate effortlessly with others and with AI, without the need for physical input devices like keyboards.

## Importance of the Project
This technology is crucial as it provides a voice to those who are often marginalized due to the communication barriers posed by their disabilities. Sign language, not being widely known, limits their ability to interact independently in society. Our system aims to empower these individuals by providing them the tools to communicate on their own terms.

## End Users
The primary users of this project are individuals who are deaf and dumb, including those with limited motor skills who cannot use traditional communication devices.

## Data Sources
- **Sign Language MNIST Dataset**: Used for training the sign language recognition model. [View Dataset](https://www.kaggle.com/datasets/datamunge/sign-language-mnist)
- **Chatbot Conversations Dataset**: Used for training the chatbot to conduct conversations. [View Dataset](https://www.kaggle.com/datasets/kreeshrajani/3k-conversations-dataset-for-chatbot)

## System Architecture
1. **Data Input**: Captured via webcam, sign language gestures are recorded in real-time.
2. **Sign Language Recognition Model**: Utilizes a CNN to interpret the gestures into text.
3. **Chatbot Model**: Receives the interpreted text and generates conversational responses.
4. **Output Display**: The chatbot's textual response is displayed back to the user.

## Technologies Used
- Machine Learning
- Computer Vision
- Convolutional Neural Networks (CNN)
- Natural Language Processing (NLP)

