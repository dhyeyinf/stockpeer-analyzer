# StockPeer Analyzer

A powerful Streamlit dashboard for analyzing and comparing stocks against their peer groups. This app enables investors and analysts to gain rapid insights into market peers using financial data, visualization, and automated workflows.

## Features

- Interactive stock peer group comparison
- Real-time financial data fetching with yfinance
- Visualizations using Altair for clear data representation
- Easy-to-use dashboard built with Streamlit's modern UI
- Configurable environment via `pyproject.toml`
- Supports Python 3.10+ and modern dependency management

## Technologies Used

| Technology  | Purpose                                         |
|-------------|------------------------------------------------|
| Python 3.10+| Core programming language                       |
| Streamlit   | Web app framework for interactive dashboards   |
| yfinance    | Fetching real-time and historical stock data   |
| Altair      | Declarative statistical visualizations          |
| Pandas      | Data manipulation and analysis                   |

## Installation

1. Clone or copy repository files locally.
2. Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate # Linux/Mac
venv\Scripts\activate # Windows
```
3. Install dependencies:

```bash
pip install "altair>=5.5.0" "pandas>=2.2.3" "streamlit>=1.44.2" "yfinance>=0.2.55"
```
4. Run the app:

```bash
streamlit run app.py
```


## Usage

- Access the app in your browser at `http://localhost:8501`
- Enter stock tickers to compare within peer groups
- Explore interactive charts and insights
- Customize configurations in `.streamlit/config.toml`

## Repository Structure

```
├── app.py # Main Streamlit app
├── .streamlit/config.toml # Streamlit configuration settings
├── utils.py # Helper functions and data processing
├── pyproject.toml # Project metadata and dependencies
├── README.md # Project documentation
```
