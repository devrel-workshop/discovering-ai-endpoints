# 🔎 Why and What? 🔍

This repository contains the source code to discover how to use [OVHloud AI Endpoints](https://endpoints.ai.cloud.ovh.net/).  
The repository have a main branch with the all coded examples and other branches with the step by step of the tutorials.  
The special branch `live-coding` is used to do live coding sessions.

At any moment you can switch to another branch to go to a specific step of the tutorial (or merge the desired branch into the `live-coding branch` branch).

# ⚙️ Setup ⚙️

A `.env` file is needed in order to run the examples. You can copy the `.env.example` file and rename it as `.env`.

## 📝 Snippets 📝

The repository contains VSCode snippets to help you with the code.
One file by language: 
  - `python.code-snippets` for Python

Each of this files is created using the tools [snippets](https://github.com/bots-garden/snippets).
Here is an example of usage: 
```bash
snippets generate \
  --input ./.vscode/python-snippets.yml \
  --output ./.vscode/python.code-snippets
```

## 🐍 Python 🐍

Create a virtual environment and install the dependencies:
```bash
cd python
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## 🕸️ JavaScript 🕸️

```bash
cd javascript
npm install
```

## ☕️ Java ☕️

```bash
cd java
mvn clean compile
```