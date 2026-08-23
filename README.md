# deadline-runtime

deadline-runtime is an execution runtime that sits on a coding agent's tool boundary and parallelizes, caches, and deadline-manages its tool calls.

## Setup

1. Create a virtual environment with Python 3.11 or later: `python -m venv .venv`.
2. Activate it: `source .venv/bin/activate`.
3. Install the project dependencies: `pip install -e .`.
4. Copy `.env.example` to `.env` and set `OPENAI_API_KEY`.
5. Run the tests: `pytest`.

Status: scaffold
