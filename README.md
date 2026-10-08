# AI-Voice-Assistant

Python voice assistant with wake-word recognition, website shortcuts, music playback, news, and AI responses.

## Setup and repository reference

### Project structure

- [client.py](client.py)
- [main.py](main.py)
- [musicLibrary.py](musicLibrary.py)
- [requirements.txt](requirements.txt)

### Getting started

```bash
git clone https://github.com/Raimal-Raja/AI-Voice-Assistant.git
cd AI-Voice-Assistant
```

Create and activate a virtual environment, then install the project dependencies:

```bash
python -m venv .venv
# Linux/macOS: source .venv/bin/activate
# Windows PowerShell: .venv\Scripts\Activate.ps1
python -m pip install -r "requirements.txt"
```

Application entry point:

```bash
python main.py
```

### Configuration and limitations

Microphone/audio and live cloud requests were not exercised. Set OPENAI_API_KEY for AI responses and NEWS_API_KEY for news.

### Maintenance fixes

- Handle empty and unknown music commands without IndexError or KeyError.
- Read API configuration from environment variables and bound news requests.

### Validation

Audit: 2026-10-08. Repository structure, setup instructions and description were reviewed. 3 existing Python files passed syntax checks; changed files and new regression tests were checked separately. Syntax checks do not establish full runtime correctness. External APIs, live scraping, GUI interaction, notebook training and production deployment were not comprehensively exercised.

### Repository description

The short GitHub description is provided in [REPOSITORY_DESCRIPTION.md](REPOSITORY_DESCRIPTION.md).

### Contributions

Describe the issue, reproduction steps, environment, and expected behavior when proposing a change. Keep generated environments, credentials, and unnecessary build artifacts out of new commits.

### License

No top-level license file was found during this review.
