🧠 Stock Market Prediction App
A machine learning web app built using Streamlit, TensorFlow, and Yahoo Finance API to predict stock market prices. The model analyzes historical stock data and visualizes trends using moving averages (MA50, MA100, MA200), along with model-based future price predictions.

🚀 Features
-Fetches real-time stock data from Yahoo Finance.
-Visualizes stock trends using moving averages.
-Predicts future stock prices using a pre-trained LSTM deep learning model.
-Interactive Streamlit interface for easy use and visualization.

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/<your-username>/Stock-Market-Prediction.git
cd Stock-Market-Prediction

2️⃣ Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # for Linux/Mac
venv\Scripts\activate      # for Windows

3️⃣ Install dependencies
Create a requirements.txt file if not already present and include:
streamlit
yfinance
numpy
pandas
tensorflow
scikit-learn
matplotlib

4️⃣ Run the app
streamlit run app.py

🛠️ Technologies Used
Tool          | Library	Purpose
Python 3.x	  | Programming language
Streamlit     |	Web app framework
TensorFlow    | Keras	Deep learning model
yFinance      |	Stock data API
Pandas        | NumPy	Data manipulation
Matplotlib    |	Data visualization
Scikit-Learn	| Data preprocessing (MinMaxScaler)

🪪 License
This project is licensed under the MIT License — feel free to modify and use it as you wish.


Then install:

pip install -r requirements.txt
