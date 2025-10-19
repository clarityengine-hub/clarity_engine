# clarity_engine
Career Reality Check engine that scrapes job postings, standardizes experience/skills, and computes a user‑specific skill‑gap score for targeted roles using a modular Python pipeline (scraper.py, cleaner.py, analysis_engine.py). 
Recommended structure
/src/ with scraper.py, cleaner.py, analysis_engine.py to keep reusable, testable logic separate from data and notebooks. 
/data/raw and /data/clean to persist scraped CSVs and standardized outputs for reproducibility. 
/notebooks for quick EDA and ad‑hoc checks without polluting the src modules. 
/docs for specs like ClarityAI.pdf and future design notes.
