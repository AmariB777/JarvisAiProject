# JarvisAiProject
Jarvis AI 🤖🎙️
A voice-based personal assistant inspired by Jarvis, built in Python using the ElevenLabs Conversational AI SDK for real-time voice interaction and OpenAI's DALL-E 3 for image generation. Jarvis listens, talks back, and can take real-world actions through a set of custom tools.
Features:

🎤 Real-time voice conversation via ElevenLabs' Conversational AI agent
🔊 Live audio input/output using the default system audio interface
🌐 Web search powered by DuckDuckGo (via LangChain)
🖼️ AI image generation using OpenAI's DALL-E 3
📝 Save notes/data to .txt files on command
🌍 Generate simple HTML files from spoken content
📝 Live console logging of user transcripts and agent responses
🔐 Environment-based configuration via .env (API keys + agent ID)
⏹️ Graceful session handling with SIGINT (Ctrl+C) support

Tech stack: Python, ElevenLabs SDK, OpenAI API (DALL-E 3), LangChain, DuckDuckGo Search, Pillow, python-dotenv
