Technical Analysis GUI Tool
A simple Python-based desktop application that lets you upload Excel stock data and visualize price trends, moving averages, RSI, and drawdown metrics — all without writing a single line of code.

🚀 Features
📁 Upload Excel File with historical stock price data

📅 Select Date and Price Columns dynamically

📈 Visualize Price Chart with:

Moving Averages: MA20, MA50, MA100, MA200

📉 Plot RSI (Relative Strength Index) with overbought/oversold markers

📉 Calculate Drawdowns:

Max Drawdown (Worst dip from peak)

Average Drawdown (Typical correction)

🛠️ Requirements
Python 3.x

Required libraries:

pandas

matplotlib

tkinter (standard with Python)

openpyxl (for Excel file support)

Install missing packages using:

bash
Copy
Edit
pip install pandas matplotlib openpyxl
📂 How to Use
Run the script:

bash
Copy
Edit
python your_script_name.py
In the GUI:

Click Upload to select your Excel file.

Enter the Date column name (e.g., Date)

Enter the Price column name (e.g., Close)

Click Generate Plots

Output:

A two-panel chart will be displayed:

Top: Price with MAs

Bottom: RSI

A pop-up will show Max and Average Drawdowns

📌 Sample Data Format
Date	Close
2024-01-01	1025.50
2024-01-02	1030.10
...	...

Make sure your Excel file has:

A date column (in a recognizable format)

A numeric price column (e.g., Close, Price, etc.)

📧 Support
Feel free to open an issue or submit a pull request if you'd like to contribute or report bugs.

📝 License
This project is licensed under the MIT License.
