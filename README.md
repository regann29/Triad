# Triad – AI-Powered Release Readiness Checker

**Triad helps developers decide whether their software is ready to launch or needs more work.**

It uses three smart agents to check a project, identify possible problems, and give a clear **GO** or **HOLD** decision.

## What Does Triad Do?

Before launching software, developers need to make sure everything works properly.

Triad automates this process using three agents:

| Agent | What It Does |
|---|---|
| **Tracker** | Checks the project for errors, failed tests, and other issues. |
| **Predictor** | Analyzes the results and calculates the risk level. |
| **Commander** | Makes the final GO or HOLD decision. |

## How It Works

1. Select a software project.
2. Tracker checks the project.
3. Predictor calculates the risk.
4. Commander decides whether it is ready to launch.

**GO:** The project meets the release requirements.

**HOLD:** Problems need attention before release.

## Key Features

- Automatically checks Python and Node.js projects.
- Finds errors and potential problems.
- Calculates a project risk score.
- Provides a clear release decision.
- Supports optional AI assistance.
- Works offline without requiring an API key.
- Includes safety controls for automated fixes.

## Technologies Used

- Python
- AI Agents
- Anthropic API (optional)
- Git and GitHub
- Automated Testing Tools

## Getting Started

**Requirements:** Python 3.10 or newer.

Install and run Triad:

```bash
git clone https://github.com/regann29/Triad.git
cd Triad
pip install -e .
triad run . --no-deps --trace
```

## Why Triad?

Triad saves developers time by checking their projects automatically instead of relying only on manual testing.

It helps teams find problems earlier and make more informed decisions before releasing software.

## Future Goal

To make software testing smarter, safer, and easier through AI-powered automation.

## License

See the [LICENSE](LICENSE) file for details.
