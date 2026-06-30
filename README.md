# lückenlos

*(adj., German): without gaps.*

An agentic AI project in progress. 🜂

---

## Structure

```
lueckenlos/
├── stage1_collect/   # gather raw input
├── stage2_extract/   # turn unstructured text into structured signal
├── stage3_compare/   # diff against a baseline
├── stage4_suggest/   # agentic resource discovery for what's missing
├── profile/          # baseline data
└── data/             # pipeline outputs (gitignored)
```

## Status

🚧 early build — stage 1 in progress.

## Setup

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
cp .env.example .env  # add your API keys
```

## Running

```bash
python -m stage1_collect.run
```

More to come as each stage is built out.
