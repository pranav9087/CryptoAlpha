# CryptoAlpha

CryptoAlpha is a cryptocurrency tracking and prediction web application. It fetches real-time price data using the CoinGecko API and provides future price forecasts through a Django backend. The backend leverages machine learning models from Scikit-learn to predict future prices based on historical data. The frontend is developed using React.js for an interactive and seamless user experience.

## Features

- **Real-Time Price Tracking** – View up-to-date prices of various cryptocurrencies.
- **Price Prediction** – Predict future cryptocurrency prices using Scikit-learn models on the backend.
- **Modern Interface** – Responsive and intuitive frontend built with React.js.

## Installation

Follow the steps below to set up the project locally:

### 1. Clone the Repository
```
git clone https://github.com/pranav9087/CryptoAlpha.git
cd CryptoAlpha
```

### 2. Backend Setup
```
cd Back-end
python -m venv env
source env/bin/activate  # For Windows: env\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```
- The Django server will start at `http://127.0.0.1:8000/`.

### 3. Frontend Setup
```
cd ../Front-end
npm install
npm start
```
- The React app will be available at `http://localhost:3000`.

## Usage

- **Home** – View the current prices of cryptocurrencies.
- **Predictions** – Access future price predictions.
- **Search** – Look up specific cryptocurrencies.

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
```
git checkout -b feature-branch-name
```
3. Make your changes and commit:
```
git commit -m "Add new feature"
```
4. Push to your forked repository:
```
git push origin feature-branch-name
```
5. Open a pull request.

