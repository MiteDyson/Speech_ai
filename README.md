
# Speech AI App

A Flutter application that leverages OpenAI's API to generate images using DALL·E and respond to prompts using ChatGPT-3.5 Turbo. The app is voice-controlled, offering a seamless and interactive user experience.

> **Note:** The app may not function optimally due to recent changes in OpenAI's API and pricing.

## Features

- **Speech Recognition**: Convert spoken words into text using the `speech_to_text` package.
- **Text-to-Speech**: Generate speech output using the `flutter_tts` package.
- **Image Generation**: Create images based on text prompts using OpenAI's DALL·E.
- **AI Conversations**: Get AI-driven responses to your prompts using ChatGPT-3.5 Turbo.
- **Smooth Animations**: Enjoy engaging UI animations powered by `animate_do`.

## Screenshots


![App UI ](https://github.com/user-attachments/assets/a57ebab7-1859-4029-8b83-4cc41b9be281)


## Demo

[Video Demo](https://github.com/user-attachments/assets/5a9caeac-7b7b-4638-9255-3f4f98084929)

## Prerequisites

Before you begin, ensure you have the following installed:

- **Flutter**: [Install Flutter](https://flutter.dev/docs/get-started/install)
- **Dart**: Included with Flutter installation.
- **OpenAI API Key**: Obtain it by signing up at OpenAI. [Get it here](https://openai.com/api/).

## Installation

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/MiteDyson/Speech_ai.git
    ```
2. **Navigate to the Project Directory:**
    ```bash
    cd speech_ai_app
    ```
3. **Install Dependencies:**
    ```bash
    flutter pub get
    ```
4. **Add Your OpenAI API Key:**
    - In the `lib/secrets.dart` file, add your OpenAI API key:
    ```dart
    const openAIAPIKey = 'YOUR_API_KEY_HERE';
    ```

## Usage

1. **Start the App:**
    - Run the app on an emulator or a physical device:
    ```bash
    flutter run
    ```
2. **Interact with the AI:**
    - Use the microphone button to speak your prompt.
    - The app will convert your speech to text and either generate an image or a response using OpenAI's API.

## Flutter Packages Used

- **`cupertino_icons: ^1.0.2`**: For iOS-style icons.
- **`speech_to_text: ^6.1.1`**: For converting speech to text.
- **`http: ^0.13.5`**: For making HTTP requests to OpenAI's API.
- **`flutter_tts: ^3.6.3`**: For converting text to speech.
- **`animate_do: ^3.0.2`**: For animations within the app.

## Acknowledgements

- **OpenAI**: For their powerful AI models.
- **The Flutter Community**: For extensive documentation and support.
- **Rivaan Ranawat**: For providing a [great tutorial](https://youtu.be/Q_pz4xFow3Q?si=hCkYFwpOrvhGUpB2) that inspired parts of this app.

---

This format enhances readability and clearly presents the necessary information for users and contributors.
