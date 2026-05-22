Voice Assistant using ElevenLabs Conversational AI

A real-time AI voice assistant built with Python and the ElevenLabs Conversational AI API.
This assistant can hold live voice conversations, respond naturally, and use custom prompts, schedules, and dynamic conversation settings.

🚀 Features
Real-time voice conversations
Powered by ElevenLabs Conversational AI
Custom AI personality and prompts
User-specific scheduling context
Live microphone input
Interrupt handling support
Environment variable security with .env
Simple and beginner-friendly setup
🛠️ Tech Stack
Python
ElevenLabs Conversational AI API
dotenv
PyAudio
WebSockets / Streaming Audio
📂 Project Structure
├── voice_assistant.py # Main voice assistant script
├── .env # API credentials
├── settings.json # VS Code settings
└── README.md
⚙️ Installation

1. Clone the Repository
   git clone https://github.com/your-username/voice-assistant.git
   cd voice-assistant
2. Create Virtual Environment (Recommended)
   python -m venv venv

Activate it:

Windows
venv\Scripts\activate
Mac/Linux
source venv/bin/activate 3. Install Dependencies
pip install elevenlabs python-dotenv pyaudio
🔐 Environment Variables

Create a .env file in the root directory.

AGENT_ID=your_agent_id
API_KEY=your_api_key

Get your credentials from:

ElevenLabs Official Website

▶️ Run the Project
python voice_assistant.py

After running:

The assistant starts listening through your microphone
You can talk naturally
The AI responds in real time
🧠 How It Works

The assistant:

Loads API credentials using dotenv
Connects to ElevenLabs Conversational AI
Applies custom prompts and first messages
Starts a live audio conversation session
Handles:
User speech
AI responses
Interruptions
Session ending events
📌 Example Custom Prompt
schedule = "Sales Meeting with Taipy at 10:00; Gym with Sophie at 17:00"

prompt = f"You are a helpful assistant. Your interlocutor has the following schedule: {schedule}."

This allows the assistant to respond contextually based on user information.

🎯 Future Improvements
GUI interface
Wake word detection
Memory system
Multi-language support
AI task automation
Calendar integration
Local voice cloning
Conversation history storage
🐛 Common Issues
PyAudio Installation Error
Windows
pip install pipwin
pipwin install pyaudio
Microphone Not Detected
Check microphone permissions
Ensure default audio input device is selected
📄 License

This project is licensed under the MIT License.

🙌 Acknowledgements
ElevenLabs
Python Community
Open Source Contributors
⭐ Support

If you found this project useful:

Star the repository
Fork the project
Share improvements
Build your own AI assistant on top of it
👨‍💻 Author

Built with Python and AI Voice Technology.
