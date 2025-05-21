git clone https://github.com/Eyob1061/solar-challenge-week1.git
cd solar-challenge-week1

Create and Activate Virtual Environment
On Windows (PowerShell):
bash
Copy
Edit
python -m venv venv
.\venv\Scripts\Activate

 Run CI Check (Optional)
To check that dependencies are installed properly using GitHub Actions:

CI will automatically run pip install -r requirements.txt and/or python --version upon push or PR.

Project Structure
graphql
Copy
Edit
solar-challenge-week1/
├── .github/
│   └── workflows/
│       └── ci.yml          # GitHub Actions for CI
├── data/                   # (Ignored via .gitignore)
├── venv/                   # Virtual environment (ignored)
├── requirements.txt        # Python dependencies
├── .gitignore              # Ignore rules
└── README.md               # Setup instructions