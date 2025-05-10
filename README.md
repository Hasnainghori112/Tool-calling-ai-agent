🤖 AI Assistant with Tool Use & Streaming
This project creates a smart AI assistant agent that can answer general knowledge questions and call external tools like a weather API — all with real-time streamed output.

🚀 Features
✅ Smart AI Agent
Answers general questions using an LLM model and follows detailed instructions.

🌦️ Weather Tool Integration
Calls a live Weather API to fetch current temperature and condition for any city.

🔄 Streaming Support
Uses Runner.run_streamed() to provide real-time streaming output as the assistant thinks, responds, and uses tools.

🧰 Tool Call Awareness
Auto-detects when a tool is needed (like weather info) and calls it on the fly during conversation.

🧪 Example Prompt
Prompt: "Write in 100 lines summary of Pakistan and get the current weather of its capital"

💡 What Happens:
Agent writes a detailed 100-line summary of Pakistan.

Recognizes Islamabad as the capital.

Calls the getWeather() tool to get live weather of Islamabad.

All responses and tool outputs are streamed live in the terminal.

