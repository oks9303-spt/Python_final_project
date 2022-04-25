# Python_final_project
#Team members: Diana , Juliet , Vivek

Work process: 

### step 1: Git repository created

### Step 2: Downloaded both CSVs from the provided URLs

### Step 3: Used Pandas to create two dataframes, find the aggregate sum of deaths and confirmed cases ( one table - 2 columns)

### Step 4: Stock market research
1. American company:  FB Meta Platforms Inc

2. Canadina company: SHOP.TRT - shopify

3. Precious metals - GFI  - Gold Fields Ltd

4. Real estate : CIGI - Colliers International Group Stock

5. Travel sector : BKNG -  Booking Holdings Inc

### step 5: 
We obtained tickers for various companies listed in an Excel file for companies in the stock exchange worldwide. Then
we checked on this page https://www.buyupside.com/alphavantagelive/searchforsymboluser.php if the stock's symbol has an
AlphaVantage api.

### Step 6:
For each company we took the output from step 3 and appended the highs and lows to match the transaction dates.

* Since not all the data is there, we used the DataFrame option to merge only the matching values, skipping over empty cells. Since
we do not have extensive knowledge of the stock market, we did not substitute the empty cells with any aggregate value such as the mean, median or mode.

### Step 7:
First, we plotted the number of deaths and confirmed cases due to covid. Then, for each company, we plotted one graph showing the highs and lows for that company's stock price so as to have a visual illustration of the trends for corresponding dates.
We used matplotlib functions to do so;  we used a subplot to place 2 graphs in a single row, to enable comparison.
We used the trend graph and made each line a different color and line style and added a legend to indicate which line represents what data. 

************************************************************************************************
#### List of files:
1. covid cases - step 3 - 1 file
2. for each stock indusrty one file -- total 5 files 
3. death and confirmed covid cases + exported data from 1 to use in 2 - total 3 csv files 

##### total 9 files 
************************************************************************************************

Thank you, 

Diana , Juliet , Vivek


