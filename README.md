Speech AI App (App Does Not work well due to change in OpenAi's changes to Api's and Pricing )

A Flutter application that uses OpenAI's API to generate images using DALL·E and respond to prompts using ChatGPT-3.5 Turbo. <br>
The app is controlled via speech, providing a seamless and interactive user experience.

Features
Speech Recognition: Convert spoken words into text using the speech_to_text package.<br>
Text-to-Speech: Generate speech output using the flutter_tts package.<br>
Image Generation: Create images based on text prompts using OpenAI's DALL·E.<br>
AI Conversations: Get AI-driven responses to your prompts using ChatGPT-3.5 Turbo.<br>
Smooth Animations: Leverage animate_do for smooth and engaging UI animations.<br>

Prerequisites:<br>
Ensure you have the following tools and packages installed:<br>
Flutter<br>
Dart<br>
An OpenAI API key. You can obtain it by signing up at OpenAI. [Found Here](https://openai.com/api/)<br>

Installation:
Clone the Repository:
https://github.com/MiteDyson/Speech_ai<br>
cd speech_ai_app<br>
Install Dependencies:<br>
flutter pub get<br>
Add Your OpenAI API Key:<br>
In the lib/secrets.dart file, add your OpenAI API key as follows:<br>
const openAIAPIKey = 'API KEY HERE ';<br>

Flutter Packages Used<br>
cupertino_icons: ^1.0.2: For iOS-style icons.<br>
speech_to_text: ^6.1.1: For converting speech to text.<br>
http: ^0.13.5: For making HTTP requests to OpenAI's API.<br>
flutter_tts: ^3.6.3: For converting text to speech.<br>
animate_do: ^3.0.2: For animations within the app.<br>

Usage<br>
To Start the App<br>
Run the app on an emulator or a physical device:<br>
flutter run<br>

Interact with the AI:<br>
Use the microphone button to speak your prompt.<br>
The app will convert your speech to text and either generate an image or a response using OpenAI's API.<br>


Screens: <br>

Main Screen:<br>

<img src="https://github.com/user-attachments/assets/39ecbb8d-014d-4c76-9d1a-23058da819bb" width="720" height="1280"><br>

Image Generated Screen:<br>

<img src="https://github.com/user-attachments/assets/584b3e33-d64b-4b3c-ae49-460bd331ed09" width="720" height="1280"><br>


[Video Demo](https://github.com/user-attachments/assets/5a9caeac-7b7b-4638-9255-3f4f98084929)<br>


Acknowledgements:<br>
OpenAI for their powerful AI models.<br>
The Flutter community for the extensive documentation and support.<br>
Youtuber Rivaan ranawat for providing a [Great Tutorial](https://youtu.be/Q_pz4xFow3Q?si=hCkYFwpOrvhGUpB2)<br>
