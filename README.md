# 🎓 NavigAI: Intelligent VR Companion

Welcome to the official repository for **NavigAI**, an interactive, mobile-based Virtual Reality walkthrough of the Saveetha Engineering College campus, guided by a fully interactive AI-powered NPC.

## 🚀 Project Overview

NavigAI is designed to modernize campus navigation and exploration. Instead of looking at static 2D maps, users can immerse themselves in a 3D VR environment and naturally converse with an AI guide. The NPC leverages local LLMs for real-time voice interaction, answering questions about the campus and utilizing advanced pathfinding to physically guide the user to their desired destination. 

**Overall Progress:** 100%
  <br> `▰▰▰▰▰▰▰▰▰▰ 100%`
  
## 📈 Current Status & Timeline

* **Status:** playable & fully optimized
* **Time in Development:** ~ 50 days (Initiated April 2026)

**How it's going:** The core foundation has been established over the last few weeks. The focus has been heavily on integrating the local LLM environment for responsive, low-latency conversational AI and mapping out the navigable mesh for the campus environment. The bridge between the voice input, the AI processing, and the NPC's pathfinding logic is currently being refined to ensure the interactions feel seamless without excessive delay or "yapping" from the guide.

## ✨ Key Features

* **Mobile VR Immersion:** Optimized for mobile VR platforms, allowing users to experience the campus using accessible hardware.
* **AI-Powered NPC Guide:** A virtual companion that you can speak to naturally.
* **Local LLM Integration:** Powered by local, lightweight models to process queries quickly and securely without relying solely on cloud APIs.
* **Intelligent Pathfinding:** The NPC doesn't just point; it dynamically calculates routes and walks you to specific departments, labs, or landmarks within the campus.
* **Voice Interactivity:** Features voice-to-text and text-to-speech pipelines, complete with sudden-stop interruptability so the AI stops speaking immediately when told to.

## 🛠️ Tech Stack

* **Game Engine:** Unity 3D
* **Target Platform:** PC - meta Quest
* **AI Backend:** Ollama (Hosting lightweight local models)
* **Scripting:** C#
* **Modeling/Rigging:** Blender (for custom stylized assets and NPC creation)

## 🔮 Future Roadmap

* [✅] Complete the 1:1 scale modeling of all primary campus blocks.
* [✅] Optimize local LLM response times for mobile constraints.
* [✅] Polish NPC animations and lip-syncing based on audio output.
* [✅] Implement a dynamic UI overlay for quick text-based queries if voice is unavailable.
      
--- 
