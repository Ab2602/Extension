# LinkedIn AI Reply Chrome Extension

## Description
This is a demo Chrome extension for the ChatGPT Writer coding assignment. It assists users in generating replies for LinkedIn messages. Built using React, TypeScript, Tailwind CSS, and the WXT framework.

## Demo
Short demo video (<30 seconds) demonstrating the tasks:

https://github.com/user-attachments/assets/ec91f0da-6b39-49a5-b72c-a8f70952f8f7

## Features
- AI icon appears when the LinkedIn message input field is focused and disappears when not.
- Clicking the AI icon opens a center-aligned modal. Clicking outside the modal closes it.
- Users can input commands in the modal's input field.
- Clicking "Generate" displays a static response:  
  `"Thank you for the opportunity! If you have any more questions or if there's anything else I can help you with, feel free to ask."`
- Clicking "Insert" places the generated response into the LinkedIn message input field.
- "Regenerate" button is present but non-functional.

## Tech Stack
- **WXT Framework**: Used for building the Chrome extension.
- **React with TypeScript**: Component-based architecture and type safety.
- **Tailwind CSS**: For styling the UI based on the Figma design.

## Design Reference
The extension UI follows the Figma file: [ChatGPT Writer Assignment Figma](https://www.figma.com/file/Ub2IeItSMfsgIGFJO98hKj/ChatGPT-Writer-Assignment)

## Installation and Setup
1. **Clone the Repository**
    ```bash
    git clone https://github.com/your-username/linkedin-ai-reply-extension.git
    cd linkedin-ai-reply-extension
    ```
2. **Install Dependencies**
    ```bash
    npm install
    ```
3. **Build the Extension**
    ```bash
    npm run build
    ```
4. **Load the Extension in Chrome**
    - Open `chrome://extensions/` in Chrome.
    - Enable "Developer mode".
    - Click "Load unpacked" and select the `dist` folder from the project directory.

## Usage
1. Go to LinkedIn and open the message input field.
2. Focus on the input field to see the AI icon.
3. Click the AI icon to open the modal.
4. Enter a command and click "Generate" for a dummy response.
5. Click "Insert" to add the response to the message input field.
6. Click outside the modal to close it.

## Project Structure
- `src/`: Source code for the extension.
- `public/`: Static assets for the extension.
- `manifest.json`: Chrome extension configuration.

## Design Decisions
1. **WXT Framework**: Used as required.
2. **React with TypeScript**: Ensures a robust codebase.
3. **Tailwind CSS**: Quick styling as per Figma.
4. **Manual DOM Manipulation**: Applied where needed.

## Constraints and Considerations
- No actual API calls made; a static response is used.
- "Regenerate" button is non-functional.
- Only manipulates the LinkedIn message input field as needed.

## Edge Cases Handled
- Icon visibility toggles with input field focus.
- Modal closes on clicking outside.
- Response inserted if message input field is present.

## Limitations
- This is a demo extension without real AI response generation.
- "Regenerate" button is not functional.

## Future Improvements
- Implement real AI response generation using APIs.
- Add multi-language support.
- Enhance error handling.

