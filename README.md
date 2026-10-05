# Local Agent
Small local AI on a **Raspberry Pi 4** in my homelab, [psychos-lab](https://github.com/leoiburn/psychos-lab).

## What it does
- Runs small (~3B parameter) LLMs fully offline with Ollama
- Uses them as a lightweight local agent for automation tasks
- Doubles as a cybersecurity box (Kali Linux): tooling, practice labs and the attacker side of my AI purple-team cyber range

## Lessons
- 3B models in 4-bit quantization fit and run on a Pi's RAM
- Keep the model API bound to localhost; reach it via SSH tunnel

## Stack
Raspberry Pi 4 · Kali Linux · Ollama · 3B models (e.g. qwen2.5 3B) · Python
