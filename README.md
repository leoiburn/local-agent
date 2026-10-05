# Local Agent 🤖

A small AI that lives on a **Raspberry Pi**, no internet needed.

## What is it?
A **Raspberry Pi** is a small, cheap computer. On it I run small AI language models (about **3 billion** "parameters", which is tiny for an AI) using a program called **Ollama**. The AI can answer questions and help with small automatic tasks.

The same Pi runs **Kali Linux**, a system made for **cybersecurity**. I use it to practice finding weak spots in my own projects, so I can fix them before someone else finds them.

## What I learned
- Small AI models can run on small computers if you "shrink" them (this is called quantization).
- Keep the AI private: only let the Pi itself talk to it, and connect from other computers through a secure tunnel (SSH).
- Security tools are best learned by testing your **own** stuff.

## Tools
Raspberry Pi 4 · Kali Linux · Ollama · small 3B models · Python

Part of my homelab: [psychos-lab](https://github.com/leoiburn/psychos-lab)
