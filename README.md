Speech AI App (App Does Not work well due to change in OpenAi's changes to Api's and Pricing )

A Flutter application that uses OpenAI's API to generate images using DALL·E and respond to prompts using ChatGPT-3.5 Turbo. 
The app is controlled via speech, providing a seamless and interactive user experience.

Features
Speech Recognition: Convert spoken words into text using the speech_to_text package.

Text-to-Speech: Generate speech output using the flutter_tts package.

Image Generation: Create images based on text prompts using OpenAI's DALL·E.

AI Conversations: Get AI-driven responses to your prompts using ChatGPT-3.5 Turbo.

Smooth Animations: Leverage animate_do for smooth and engaging UI animations.



Prerequisites

Ensure you have the following tools and packages installed:

Flutter

Dart

An OpenAI API key. You can obtain it by signing up at OpenAI. [Found](https://openai.com/api/)



Installation

Clone the Repository:

https://github.com/MiteDyson/Speech_ai

cd speech_ai_app

Install Dependencies:

flutter pub get

Add Your OpenAI API Key:

In the lib/secrets.dart file, add your OpenAI API key as follows:

const openAIAPIKey = 'API KEY HERE ';

// add your own api key before running the project 



Flutter Packages Used

cupertino_icons: ^1.0.2: For iOS-style icons.

speech_to_text: ^6.1.1: For converting speech to text.

http: ^0.13.5: For making HTTP requests to OpenAI's API.

flutter_tts: ^3.6.3: For converting text to speech.

animate_do: ^3.0.2: For animations within the app.



Usage

To Start the App

Run the app on an emulator or a physical device:

flutter run



Interact with the AI:

Use the microphone button to speak your prompt.

The app will convert your speech to text and either generate an image or a response using OpenAI's API.



Screens: 

Main Screen:

<img src="https://github.com/user-attachments/assets/39ecbb8d-014d-4c76-9d1a-23058da819bb" width="720" height="1280">

Image Generated Screen:

<img src="https://github.com/user-attachments/assets/584b3e33-d64b-4b3c-ae49-460bd331ed09" width="720" height="1280">


[Video Demo](https://github.com/user-attachments/assets/5a9caeac-7b7b-4638-9255-3f4f98084929)


Acknowledgements

OpenAI for their powerful AI models.

The Flutter community for the extensive documentation and support.

Youtuber Rivaan ranawat for providing a [Great Tutorial](https://youtu.be/Q_pz4xFow3Q?si=hCkYFwpOrvhGUpB2)
