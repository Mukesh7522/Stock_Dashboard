# Stock Market Dashboard & Data Pipeline

This repository contains a complete system for fetching, storing, and visualizing stock market data.

## Project Structure

- **[dashboard/](dashboard/)**: A web application for visualizing stock market data.
  - **[backend/](dashboard/backend/)**: Node.js/Express API for fetching data from the PostgreSQL database.
  - **[frontend/](dashboard/frontend/)**: React-based frontend for the dashboard.
- **[pipeline/](pipeline/)**: Python-based data pipeline for fetching stock data and storing it in the database.
  - **[stock_pipeline_v3_cloud.py](pipeline/stock_pipeline_v3_cloud.py)**: The main pipeline script.

## Getting Started

### Data Pipeline
To update the database with the latest stock data, run the pipeline script:
```bash
python pipeline/stock_pipeline_v3_cloud.py
```

### Dashboard Backend
Install dependencies and start the backend server:
```bash
cd dashboard/backend
npm install
npm run dev
```

### Dashboard Frontend
Install dependencies and start the frontend application:
```bash
cd dashboard/frontend
npm install
npm run dev
```

## Database Configuration
The system uses a Neon PostgreSQL database. Configuration details for both the pipeline and the dashboard backend can be found in their respective configuration files and environment variables.
