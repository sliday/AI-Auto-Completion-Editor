# Single-File AI Auto-Completion Editor

Super simple, single-file text editor with real-time AI-powered auto-completion suggestions, supporting multiple AI models from Anthropic, OpenAI, and GROQ. 

![CleanShot 2024-11-20 at 00 24 37@2x](https://github.com/user-attachments/assets/b9fb7a32-133a-418c-907c-abb8393a34cd)

## Features

- Real-time AI text completion suggestions
- Support for multiple AI providers:
  - Anthropic (Claude 3 models)
  - OpenAI (GPT-4 models)
  - GROQ (Various LLaMA and Mixtral models)
- Adjustable AI temperature/creativity settings
- Mobile-friendly with touch/swipe support
- Persistent settings and content via localStorage
- Clean, minimal interface using Pico CSS
- JetBrains Mono font for optimal readability
- Paste plain-text context to fine-tune the tone
  
![CleanShot 2024-11-20 at 00 29 38@2x](https://github.com/user-attachments/assets/13e5a15c-22b8-462e-b3eb-05782dcda141)

## Technologies Used

- HTML5
- CSS3
- JavaScript/jQuery
- Pico CSS for styling
- Various AI APIs (Anthropic, OpenAI, GROQ)

## Setup

1. Clone the repository
2. Open `index.html` in a web browser
3. Click the Settings panel
4. Enter your API key(s) for the desired AI providers:
   - GROQ API key
   - OpenAI API key
   - Anthropic API key

## Usage

1. Start typing in the editor
2. The AI will automatically suggest completions after you stop typing
3. Accept suggestions:
   - Desktop: Press Tab or Right Arrow key
   - Mobile: Tap suggestion or swipe right

## API Requirements

You'll need at least one API key from the following providers:

- GROQ: [Get API Key](https://console.groq.com)
- OpenAI: [Get API Key](https://platform.openai.com)
- Anthropic: [Get API Key](https://console.anthropic.com)

## Configuration

The editor allows customization of:
- AI model selection (based on available API keys)
- Temperature/creativity level (0.0 - 1.0)
- Settings persistence across sessions

## Privacy

- API keys are stored locally in your browser
- No data is sent to any server except the AI providers
- All text processing happens client-side

## Browser Support

- Works on modern browsers (Chrome, Firefox, Safari, Edge)
- Fully responsive design for mobile and desktop
- Touch-optimized for mobile devices

## License

MIT License - feel free to use and modify as needed.
