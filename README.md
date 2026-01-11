# Privacy-Utility trade-off for code completion

This repository aims to measure and plot the privacy-utility trade-off for code completion tasks.

## Running the notebook
To run the `Privacy-Utility trade-off.ipynb` notebook:
 - Make sure [Python](https://www.python.org/downloads/) is installed.
 - Clone the repository: 
   - `git clone <URL>`
 - Create virtual environment (optional/recommended)
   - using venv:
   ```bash
    python -m venv venv
    source venv/bin/activate       # On macOS/Linux
    venv\Scripts\activate          # On Windows
   ```
   - alternatively using conda:
   ```bash
     conda create -n myenv python=3.14 -y
     conda activate myenv
   ```
- Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
- Launch Jupyter Notebook:
    ```bash
  jupyter notebook
  ```
  When the notebook interface opens in your browser, navigate to the .ipynb file and open it.