# Prompt Engineering Lab

## Setup

1. Install dependencies:
```bash
conda create -n prompt-lab python=3.11 -y
conda activate prompt-lab
pip install openai python-dotenv
```

2. Create `.env` file:
```
OPENAI_API_KEY=your-key-here
```

3. Run the notebook:
```bash
jupyter notebook prompt_engineering_lab_FINAL.ipynb
```

Or in VS Code: Open the notebook and run all cells.

## Files

- `prompt_engineering_lab_FINAL.ipynb` - Main lab notebook with all iterations
- `lab_summary.md` - One-paragraph summary at repo root
- `README.md` - This file

## Results

| Task | v1 Consistency | v3 Consistency |
|------|---------------|----------------|
| Sentiment Analysis | ~30% | 100% |
| Product Description | ~10% | ~95% |
| Data Extraction | ~20% | 100% |

## Techniques Used

1. Constraint injection
2. Schema specification
3. Few-shot examples
4. temperature=0 for determinism
5. Role prompting
