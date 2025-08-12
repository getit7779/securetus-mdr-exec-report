# MDR Executive Report Generator

Turn raw MDR/SIEM alerts into an executive-friendly HTML report and CSV.

## Quick start
```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# Mac/Linux: source .venv/bin/activate
pip install -r requirements.txt
python src/report_generator.py
```
Outputs land in `output/`.
