# AgentScholar 🎓

**Autonomous Research Paper Analyzer with Critique-Driven Multi-Agent Reasoning**

AgentScholar is a browser-based multi-agent system that automatically analyzes research papers using three LLMs (Claude, GPT-4o, Gemini) in a coordinated pipeline. It produces structured analytical reports with explicit critique and verification stages to minimize hallucinations and maximize factual accuracy.

## Features

- 📄 **PDF & text input** — upload a PDF or paste paper text directly
- 🤖 **6 specialized Claude agents** — Paper Understanding, Method Analysis, Experiment Analysis, Critic, Verification, Refinement
- 🔍 **Cross-model review** — GPT-4o and Gemini independently evaluate Claude's final report
- ✅ **Hallucination reduction** — dedicated Verification Agent cross-checks all extracted claims
- 📊 **Built-in evaluation module** — automatically compares multi-agent vs. single-agent outputs
- 💾 **Analysis history** — previous analyses saved locally via localStorage
- 🚀 **No backend required** — single HTML file, runs entirely in the browser

## Usage

1. Open `agent4.html` in your browser
2. Enter your API keys (Claude, OpenAI, Gemini) when prompted
3. Upload a PDF or paste your paper text
4. Click **Analyze Paper** and watch the agents work in real time
5. View results in the tabbed output panel (Claude / GPT-4o / Gemini)

## Tech Stack

| Component | Technology |
|---|---|
| Primary LLM (6 Agents) | Claude Haiku (Anthropic API) |
| Independent Critic | GPT-4o (OpenAI API) |
| Independent Reviewer | Gemini 2.5 Flash (Google API) |
| PDF Parsing | pdf.js |
| Frontend | HTML5 / CSS3 / Vanilla JavaScript |
| Data Persistence | localStorage |

## Authors

- Verda Janset Güvel
- Rana Kavak
- Ömer Söyler
- Mehmet Kıvrak

*Menedżerska Akademia Nauk Stosowanych w Warszawie*
