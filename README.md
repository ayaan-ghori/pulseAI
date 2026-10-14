PulseAI - Healthcare Assistant 🩺✨

PulseAI is an intelligent, responsive, and beautifully designed web-based healthcare assistant. Powered by Google's Gemini API, it provides personalized wellness advice, tracks daily habits, calculates health metrics, and even analyzes uploaded images (like nutrition labels or mild skin conditions).

🌟 Features

Intelligent Conversational AI: Integrates with gemini-3-flash-preview to provide context-aware health and wellness guidance based on the user's profile (Age, Height, Weight).
Vision & Image Analysis: Users can upload images directly into the chat. The AI can analyze food portions, read nutrition labels, or provide general observations on physical symptoms.
Natural Voice Output (TTS): Uses gemini-2.5-flash-preview-tts to read AI responses aloud in a natural, human-like voice.
Health Dashboard & Metrics:
Real-time BMI Calculator based on saved user metrics.
Daily hydration tracking widget.
Quick wellness tips and checklists.
Explore & Discover: A dedicated tab for users to explore fitness habits, sleep hygiene, and dietary guides.
Secure Profile Management: Client-side authentication and user profile management (Name, Age, Height, Weight, Avatar).
Export Data: Users can download their complete chat history and profile data as a JSON file.

📁 Project Structure

Note: In this specific interactive environment, the application is bundled into a single file for live compilation. In a standard repository, the structure would look like this:

healthcare-chatbot/
	├── index.html        # Main HTML structure and UI layouts
	├── style.css         # Custom animations and CSS overrides (Tailwind is used for core styling)
	├── script.js         # Application logic, Gemini API integrations, and state management
	├── assets/           # Directory for static assets (images, icons)
	└── README.md         # Project documentation


🚀 Getting Started

Prerequisites
To run this application with full AI capabilities, you will need a valid Google Gemini API Key.
Installation & Setup
Clone this repository or download the source code.
Open the main HTML file (pulseai_interface.html or index.html) in your code editor.
Locate the generateGeminiResponse and speakText functions in the <script> section.
Replace the empty apiKey variable string with your actual Gemini API Key:
const apiKey = "YOUR_GEMINI_API_KEY_HERE";

Open the HTML file in any modern web browser (Chrome, Firefox, Safari, Edge). No local server is strictly required, though a tool like VS Code Live Server is recommended for the best experience.

🎨 Technologies Used

Frontend: HTML5, JavaScript (ES6+), Tailwind CSS (via CDN)
AI Integration: Google Generative AI (Gemini 3 Flash, Gemini 2.5 Flash TTS)
Data Storage: Browser LocalStorage (for chat history and user accounts)
Audio: Web Audio API (for notification sounds and TTS playback)

⚠️ Medical Disclaimer

PulseAI is an AI assistant, not a doctor. All information provided by this application is for general wellness and educational purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of a qualified health provider with any questions you may have regarding a medical condition.

