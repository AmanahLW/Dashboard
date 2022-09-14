# Dashboard
A timeseries showing the number of individuals on the ventilator and hospital admissions. 


1.Loading data

Load json data in read mode with with open () method and save as json data 
Embed matplotlib ouput into frontend jupyter notebook with an enlarged size using special character %matplotlib inline and .rcParams() method


2. Data cleaning

Create function as def parse_data() to convert dates to datetime object and sort data
Index dates using date_range() method, sort, check for None value and convert to 0.0 and fill dateframe using def wrangle_data() function


5. Fetching api data 

Create function for a button which fetches PHE data and wrangles it using def access_api () and def api_button_callback()
