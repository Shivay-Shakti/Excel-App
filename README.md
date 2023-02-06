# Sales Dashboard
Excel Automation &amp; Dashboard App Deployment Through Python Streamlit!

This project is a sales dashboard that analyzes sales data and displays the key performance indicators (KPIs). It uses the following libraries:

1. openpyxl
2. pandas
3. plotly.express
4. streamlit

The data for this dashboard is taken from a sales excel file, supermarket_sales.xlsx, which is read into a pandas dataframe using the openpyxl library. The data is then filtered and analyzed using pandas functions such as groupby and sum. The resulting KPIs are displayed using the streamlit library. The visualizations of the sales data are created using the plotly.express library.

On the main dashboard page, users can select the city, customer type, and gender to filter the sales data. The KPIs displayed include total sales, average rating, and average sale per transaction. The dashboard also includes two bar charts showing sales by hour and sales by product line.


