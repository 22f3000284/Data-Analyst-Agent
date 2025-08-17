# Data Analyst Agent

A FastAPI-based application that enables automated data analysis and visualization using natural language questions. Upload your questions and datasets, and the agent will generate answers and plots using Python data science libraries and LLMs.

## Features

- Upload questions and data files via a web interface
- Automated data scraping from URLs (HTML tables, CSV, Excel, JSON, etc.)
- Data analysis and visualization using pandas, numpy, matplotlib, seaborn
- LLM-powered code generation and execution for flexible analysis
- Returns results as JSON and base64-encoded images
- Docker and cloud deployment ready

## Getting Started

### Prerequisites

- Python 3.12+
- [Google Generative AI API key](https://ai.google.dev/)
- Docker (optional, for containerized deployment)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/Data_Analyst_Agent.git
   cd Data_Analyst_Agent