# Kucoin-Futures-OHLCV-Data-Fetcher
An example implementation using Kucoin Futures API and CCXT to fetch OHLCV data for all desired symbol

This repository contains a Jupyter Notebook that demonstrates how to fetch OHLCV (Open, High, Low, Close, Volume) data from the Kucoin Futures exchange using the `ccxt` library in Python.

## Overview

This repository demonstrates how to use the `ccxt` library to fetch OHLCV data for a specified trading pair (symbol) and timeframe from the Kucoin Futures exchange. The OHLCV data is retrieved and stored in a Pandas DataFrame for further analysis and visualization.

## Prerequisites

Before running the Jupyter Notebook, ensure you have the following installed:

- Python 3
- Jupyter Notebook
- `ccxt` library
- Pandas library
- `dotenv` library

## Setup

1. Clone the repository to your local machine:

```
git clone https://github.com/your-username/kucoin-fetch-ohlcv-jupyter.git
```

2. Install the required Python libraries:

```
pip install ccxt pandas python-dotenv
```

3. Create a `.env` file in the root directory of the repository and add your Kucoin Futures API credentials:

```
API_KEY=your_kucoin_api_key
SECRET_KEY=your_kucoin_secret_key
PASSPHRASE=your_kucoin_passphrase
```

Replace `your_kucoin_api_key`, `your_kucoin_secret_key`, and `your_kucoin_passphrase` with your actual API credentials obtained from the Kucoin Futures platform.

## Usage

1. Open Jupyter Notebook:

```
jupyter notebook
```

2. Navigate to the repository folder and open the `kucoin-fetch-ohlcv.ipynb` file.

3. Run each cell in the notebook sequentially to fetch OHLCV data from Kucoin Futures for the specified trading pair (symbol) and timeframe.

4. The notebook will display the retrieved OHLCV data, check for the presence of the 'close' column, and verify if the DataFrame is empty or not.

## License

This project is licensed under the [MIT License](LICENSE).

## Contribution

If you find any issues or have suggestions for improvement, feel free to create a pull request or raise an issue in the repository.

---

Replace `your-username` in the clone command with your actual GitHub username. Additionally, update the prerequisites and usage sections as needed to match your specific environment and instructions for running the Jupyter Notebook.

I'm you're looking a algo programmer to hire, feel free to message me 
