# JarvisAiProject
A voice-based conversational AI assistant inspired by Jarvis, built in Python using the ElevenLabs Conversational AI SDK. It streams real-time voice conversations, transcribes user speech, generates spoken agent responses, and supports custom tool/function calling for extended capabilities.
Features:

🎤 Real-time voice conversation via ElevenLabs' Conversational AI agent
🔊 Live audio input/output using the default system audio interface
🛠️ Custom client-side tools (see tools.py) for extending agent actions
📝 Console logging of user transcripts and agent responses (with correction support)
🔐 Environment-based configuration via .env (agent ID + API key)
⏹️ Graceful session handling with SIGINT (Ctrl+C) support

Tech stack: Python, ElevenLabs SDK, python-dotenv
