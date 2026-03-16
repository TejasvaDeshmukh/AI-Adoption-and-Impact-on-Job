## AI adoption visualization (Midterm Project)

This project uses the dataset `share-companies-using-artificial-intelligence.csv` (downloaded from Our World in Data’s AI indicators) and generates charts showing how AI adoption changes over time.

### Run

In PowerShell, from this folder:

```bash
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python visualize_ai_adoption.py
```

Charts will be saved into `outputs/`.

