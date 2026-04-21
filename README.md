# 🎯 Soc Ops - Social Bingo Game

[![Python](https://img.shields.io/badge/Python-3.13+-blue.svg)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.115+-green.svg)](https://fastapi.tiangolo.com)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> **Break the ice and build connections!** A fun, interactive bingo game designed for in-person social events, team building, and networking mixers. Find people who match the quirky questions and get 5 in a row to win!

## ✨ Features

- 🎲 **25 Unique Questions** - Carefully crafted prompts to spark conversations
- 🎯 **Classic Bingo Gameplay** - Mark squares, get lines, celebrate wins
- 📱 **Mobile-Friendly** - Works great on phones and tablets
- ⚡ **Real-Time Updates** - No page refreshes needed with HTMX
- 🎨 **Modern UI** - Clean, responsive design with smooth animations
- 🔒 **Session-Based** - Private games with automatic cleanup

## 🎮 How to Play

1. **Start a Game** - Click "Start Game" to begin
2. **Read Questions** - Each square has a fun social prompt
3. **Find Matches** - Talk to people and find someone who matches each question
4. **Mark Squares** - Click squares when you find a match
5. **Get Bingo!** - Connect 5 in a row (horizontal, vertical, or diagonal)

## 🚀 Quick Start

### Prerequisites
- Python 3.13+
- [uv](https://github.com/astral-sh/uv) package manager

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/soc-ops.git
cd soc-ops

# Install dependencies
uv sync

# Start the development server
uv run uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser and start playing!

## 🛠️ Tech Stack

- **Backend**: FastAPI (Python web framework)
- **Frontend**: Jinja2 templates with HTMX for interactivity
- **Styling**: Custom CSS utility classes
- **Testing**: pytest with httpx
- **Linting**: Ruff for code quality

## 📚 Development

### Run Tests
```bash
uv run pytest
```

### Code Quality
```bash
uv run ruff check .
uv run ruff format .
```

### Project Structure
```
soc-ops/
├── app/
│   ├── main.py          # FastAPI application
│   ├── game_logic.py    # Bingo game mechanics
│   ├── models.py        # Data models
│   └── templates/       # Jinja2 HTML templates
├── tests/               # Test suite
└── workshop/            # Development workshop guides
```

---

## 🎓 Agent Lab Workshop

This project serves as a hands-on workshop for learning AI-assisted development with GitHub Copilot. Follow the guided labs to explore modern development practices.

🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

### Lab Guide

| Part | Title | Description |
|------|-------|-------------|
| [**00**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview) | Overview & Checklist | Prerequisites and workshop overview |
| [**01**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup) | Setup & Context Engineering | Environment setup and AI context |
| [**02**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=02-design) | Design-First Frontend | UI/UX design and implementation |
| [**03**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=03-quiz-master) | Custom Quiz Master | Building AI-powered features |
| [**04**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=04-multi-agent) | Multi-Agent Development | Advanced AI collaboration |

> 📝 Lab guides are also available in the [`workshop/`](workshop/) folder for offline reading.

Head to **[Part 00: Overview](https://copilot-dev-days.github.io/agent-lab-python/step.html?step=00-overview)** to get started!

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Made with ❤️ for social connections and fun!**
