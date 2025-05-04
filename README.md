Supermarket Analytics

      ├── app.py # Main application entry point
      ├── sales_forecaster.py # Sales prediction module
      ├── inventory_reordering.py # Inventory management module
      ├── retail_price_suggester.py # Price optimization module
      ├── promotional_items.py # Promotion recommendation module
      ├── chatbot.py # Conversational interface
      ├── data/ # Data storage directory
      │ └── SuperMarket Analysis.csv # Core dataset
      ├── models/ # Trained model storage
      └── downloads/ # Generated reports director

## Core Features

* **Sales Forecasting**
  Uses time series models (e.g., ARIMA, ETS) to predict  sales.

* **Inventory Reordering**
  Calculates optimal order quantities based on historical sales and stock gaps.

* **Retail Price Suggestion**
  Recommends price adjustments using price elasticity models to improve profit margins.

* **Promotional Item Selector**
  Identifies items that should be promoted based on performance and forecasted lift.

* **Chatbot Assistant**
  A Streamlit-integrated assistant to handle inventory and performance queries.

## Dataset

Located at: `data/SuperMarket Analysis.csv`
Includes:

* Product categories
* Sales transactions
* Branch-specific data

## Getting Started

1. Clone the repository
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

   to run program
   streamlit run app.py
