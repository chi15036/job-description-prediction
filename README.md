# job-description-prediction


<!-- GETTING STARTED -->
## Getting Started

1. 解壓縮該檔案，將 csv 檔案放置於專案 `csv` 目錄下
2. 將虛擬環境 kernel export 到 jupyter notebook
   ```sh
   $ conda create -n venv python=3.6
   $ pip install --user ipykernel
   $ python -m ipykernel install --user --name=venv
   $ source venv/bin/activate
   ```
3. 安裝 python packages
 ```sh
 $ pip install -r pip-requirements.txt
 ```
4. 執行程式
   ```sh
   $ jupyter notebook home_price_prediction.ipynb 
   ```
