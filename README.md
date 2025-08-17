# Metrics Q&A (CSV → LLM)
**Problem → Outcome:** Quick “why/how” from CSVs is slow; this returns an answer **with cited columns**.  
**Stack:** Python · Streamlit · OpenAI API · Pandas

## Demo
(Screenshot/GIF coming)

## How it works
- **Input →** upload a CSV + ask a natural-language question
- **Logic/Model →** schema check, structured prompt, compute answer; show which columns were used
- **Output →** answer + cited columns (mini calc table in roadmap)

## Results (v0.1)
- Protocol: 10-prompt internal QA  
- Score: *(fill Sunday)* ; Notes: top 2 issues → fixes planned

## Try it
1. `pip install -r requirements.txt`
2. `export OPENAI_API_KEY=...`
3. `streamlit run app.py`

## Docs
- **PRD (view-only):** <PASTE_LINK_TO_METRICS_QA_PRD> *(if you made one)*
- **4-week roadmap:** <PASTE_LINK_TO_METRICS_QA_ROADMAP>
- **Portfolio hub:** <PASTE_LINK_TO_NOTION_PORTFOLIO>

## Changelog
- 2025-08-17: init public repo
