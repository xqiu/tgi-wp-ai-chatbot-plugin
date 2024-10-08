# TGI WP AI Chatbot Plugin

## Description
The TGI WP AI Chatbot Plugin is a WordPress plugin that adds a floating ChatGPT chatbot icon to your website. This plugin allows users to interact with an AI chatbot, which can provide responses using the OpenAI API. It can also hook up with Microsoft Azure Speech and Avatar service to enable audio/video chat.

## Features
- Floating chat icon on the right side of the screen.
- Modal chat interface for user interaction.
- Sends user messages to OpenAI's API and displays the AI's response.
- Stores chat history in the WordPress admin panel.
- Displays chat history with timestamps.
- Error logging for troubleshooting.
- Publicly accessible chat for all users.
- One independent ChatGpt assistant thread for each user
- Multi language support
- Rate limit support
- Enable it in all pages or use short code [tgi_chatgpt_icon]
- Allow session reload based on the session id cookie
- Permanent chat clear which clears the database records and the OpenAI thread
- Allow preset as many questions as you want in a select element
- Allow use Microphone + Microsoft Azure Speech Cognitive Service and Avatar for Audio/Video Chat

## Installation

### Method 1: Direct Upload
1. **Download the Plugin**: Download the plugin files as a ZIP archive.
2. **Upload the Plugin**:
    - Go to your WordPress admin area.
    - Navigate to `Plugins` > `Add New`.
    - Click on the `Upload Plugin` button at the top.
    - Choose the downloaded ZIP file and click `Install Now`.
3. **Activate the Plugin**: Once installed, click `Activate Plugin`.

### Method 2: FTP Upload
1. **Download the Plugin**: Download the plugin files as a ZIP archive and extract them to your computer.
2. **Upload via FTP**:
    - Connect to your web server using an FTP client.
    - Navigate to the `/wp-content/plugins/` directory.
    - Upload the extracted plugin folder (`tgi-wp-ai-chatbot-plugin`) to this directory.
3. **Activate the Plugin**:
    - Go to your WordPress admin area.
    - Navigate to `Plugins`.
    - Find the `TGI WP AI Chatbot Plugin` in the list and click `Activate`.



## Usage

### Configuration
1. **Access Plugin Settings**:
    - Navigate to `AI Chatbot` in the WordPress admin menu.
2. **Enter API Credentials**:
    - **ChatGPT API Key**: Enter your OpenAI API key.
    - **Assistant ID**: Enter your Assistant ID from OpenAI.
3. **Enable ChatGPT Icon Globally, you can use [tgi_chatgpt_icon] shortcode if not want to enable the chat globally**:
    - Enable globally or use short code [tgi_chatgpt_icon]

4. **Save Changes**:
    - Click `Save Changes` to store your configuration settings.

### Interacting with the Chatbot
1. **Chat Icon**:
    - A floating chat icon will appear on the right side of the screen for all users.
    - Hovering over the icon displays a tooltip saying "Talk to our AI chatbot".

2. **Chat Modal**:
    - Clicking the chat icon opens the chat modal.
    - The modal allows users to type messages and interact with the AI chatbot.

3. **Sending Messages**:
    - Type a message in the input field at the bottom of the modal.
    - Press Enter or click the `Send` button to submit the message.
    - The user message appears on the right side of the chat area.
    - The AI response appears on the left side of the chat area.

4. **Chat History**:
    - All chat sessions are stored in the WordPress admin panel under `AI Chatbot > Chat Records`.
    - Chat records are displayed with timestamps for each session.
    - You can view detailed logs of user messages and AI responses.

### Error Logging
1. **Access Error Logs**:
    - Navigate to `AI Chatbot > Error Logs` in the WordPress admin menu.
    - View logs of any errors that occurred during chat interactions.
    - Use this information to troubleshoot issues with the plugin or API interactions.

### Settings
1. **Translations**:
   - locale translations for appearance text

2. **Rate Limit**:
   - how many chats can be done within a limited time

3. **Microsoft Avatar / Speech Recognition / Voice Chat Settings**:
   - the Microsoft Azure API keys and speech avatar settings, please see https://github.com/Azure-Samples/cognitive-services-speech-sdk/tree/master/samples/js/browser/avatar for more information on what the settings means



## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
- Zeeshan Ahmad
- [Tabsgi](https://tabsgi.com)

## Changelog
### 1.0
- Initial release of the TGI WP AI Chatbot Plugin.

## Contributing
Please feel free to submit issues, fork the repository, and send pull requests!
