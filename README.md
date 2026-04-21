# SOC OPS

```
███████████████████████████████████████████████████████████████████████████████
█                                                                             █
█                           SOCIAL BINGO GAME                                 █
█                                                                             █
█          BREAK THE ICE. BUILD CONNECTIONS. GET 5 IN A ROW.                 █
█                                                                             █
███████████████████████████████████████████████████████████████████████████████
```

## REQUIREMENTS

```
┌─────────────────────────────────────────────────────────────────────────────┐
│ PYTHON 3.13+                                                               │
│ UV PACKAGE MANAGER                                                         │
│ WEB BROWSER                                                                │
└─────────────────────────────────────────────────────────────────────────────┘
```

## INSTALLATION

```
$ git clone https://github.com/yourusername/soc-ops.git
$ cd soc-ops
$ uv sync
$ uv run uvicorn app.main:app --reload --host 0.0.0.0 --port 8000
```

OPEN http://localhost:8000

## FEATURES

```
┌─────────────────────────────────────────────────────────────────────────────┐
│ 25 UNIQUE QUESTIONS                                                        │
│ CLASSIC BINGO GAMEPLAY                                                     │
│ MOBILE FRIENDLY                                                            │
│ REAL-TIME UPDATES                                                          │
│ MODERN UI                                                                  │
│ SESSION BASED                                                              │
└─────────────────────────────────────────────────────────────────────────────┘
```

## HOW TO PLAY

```
1. CLICK START GAME
2. READ QUESTIONS ON SQUARES
3. FIND PEOPLE WHO MATCH
4. MARK SQUARES WHEN FOUND
5. CONNECT 5 IN A ROW TO WIN
```

## TECH STACK

```
BACKEND: FASTAPI (PYTHON)
FRONTEND: JINJA2 + HTMX
STYLING: CUSTOM CSS UTILITIES
TESTING: PYTEST
LINTING: RUFF
```

## PROJECT STRUCTURE

```
soc-ops/
├── app/
│   ├── main.py          # FASTAPI APP
│   ├── game_logic.py    # BINGO LOGIC
│   ├── models.py        # DATA MODELS
│   └── templates/       # HTML TEMPLATES
├── tests/               # TEST SUITE
└── workshop/            # LAB GUIDES
```

---

## AGENT LAB WORKSHOP

THIS PROJECT IS A HANDS-ON WORKSHOP FOR AI-ASSISTED DEVELOPMENT.

🌐 [PORTUGUÊS (BR)](README.pt_BR.md) | [ESPAÑOL](README.es.md)

### LAB GUIDE

| PART | TITLE | DESCRIPTION |
|------|-------|-------------|
| 00 | OVERVIEW | PREREQUISITES AND CHECKLIST |
| 01 | SETUP | ENVIRONMENT AND CONTEXT |
| 02 | DESIGN | UI/UX IMPLEMENTATION |
| 03 | QUIZ MASTER | AI-POWERED FEATURES |
| 04 | MULTI-AGENT | ADVANCED AI COLLABORATION |

> LAB GUIDES IN [`workshop/`](workshop/) FOLDER.

START AT [PART 00](https://copilot-dev-days.github.io/agent-lab-python/step.html?step=00-overview)

## LICENSE

MIT LICENSE. SEE [LICENSE](LICENSE) FILE.

---

MADE FOR SOCIAL CONNECTIONS.
