
# Momentum

**Momentum** is a financial simulation web app that helps users understand how changes in Federal Reserve interest rates affect their personal finances.

Built at **Pearl Hacks 2026**, the project models how rate shocks influence assets, debt, and long-term financial outcomes.

## Features

* Simulate **interest rate shocks** and their impact on personal finances
* Model changes to **assets and liabilities** over time
* Interactive dashboard for exploring financial scenarios
* Uses real macroeconomic data from the **FRED API**

## Tech Stack

* Python
* FastAPI
* Streamlit
* FRED API

## How It Works

1. Users enter information about their assets and liabilities.
2. The backend simulation models how rate changes affect debt costs and investment performance.
3. The dashboard displays projected financial outcomes under different rate scenarios.

## Running the Project

Clone the repository:

```bash
git clone https://github.com/yourusername/momentum.git
cd momentum
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the backend:

```bash
uvicorn main:app --reload
```

Run the frontend:

```bash
streamlit run app.py
```

## Inspiration

Rising interest rates can significantly affect mortgages, loans, and investment returns. Momentum was created to help people better understand these dynamics and make more informed financial decisions.

---


