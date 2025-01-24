# AI ChatBot App

An Android application developed using Android Studio, leveraging the Gemini 1.5 Flash API to provide intelligent conversational capabilities.

## Features

- **Intelligent Conversations**: Utilizes the Gemini 1.5 Flash API for natural language understanding and responses.
- **User-Friendly Interface**: Designed with a focus on simplicity and ease of use.
- **Real-Time Interaction**: Provides immediate responses to user inputs.

## Prerequisites

Before you begin, ensure you have the following installed:

- **Android Studio**: [Download Here](https://developer.android.com/studio)
- **Java Development Kit (JDK)**: [Download Here](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Rajeshaligeti/AI_ChatBot_App.git
   cd AI_ChatBot_App
   ```

2. **Open in Android Studio**:
   - Launch Android Studio.
   - Click on `File` > `Open` and select the cloned project directory.

3. **Configure the Gemini API Key**:
   - Obtain your Gemini 1.5 Flash API key from the [Gemini API Portal](#).
   - Navigate to the `app/src/main/res/values` directory and open `strings.xml`.
   - Add your API key:
     ```xml
     <string name="gemini_api_key">YOUR_API_KEY_HERE</string>
     ```

4. **Build and Run the Application**:
   - Connect your Android device or start an emulator.
   - Click on the `Run` button in Android Studio to build and deploy the app.

## Usage

- **Start a Conversation**: Open the app and type your message in the input field to begin interacting with the chatbot.
- **Receive Responses**: The chatbot processes your input using the Gemini API and provides intelligent responses in real-time.

## Project Structure

```plaintext
AI_ChatBot_App/
├── .idea/                  # Project configuration files
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/yourpackage/  # Java source files
│   │   │   ├── res/                   # Resource files (layouts, strings, etc.)
│   │   │   └── AndroidManifest.xml    # App manifest file
│   └── build.gradle                   # Module build configuration
├── gradle/
│   └── wrapper/                       # Gradle wrapper files
├── .gitignore                         # Git ignore file
├── build.gradle                       # Project build configuration
├── gradle.properties                  # Gradle properties
├── gradlew                            # Unix Gradle wrapper
├── gradlew.bat                        # Windows Gradle wrapper
└── settings.gradle                    # Settings for Gradle
```

## Dependencies

- **Gemini 1.5 Flash API**: Powers the chatbot's natural language processing capabilities.
- **AndroidX Libraries**: Utilized for modern Android development practices.


## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- Thanks to the developers of the Gemini API for providing the tools necessary for this project.
- Appreciation to the open-source community for continuous support and contributions.

