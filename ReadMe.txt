I wrote a Google Sheets JS script that uses the Gmail API to parse your Robinhood buy/sell notifications. The parsed info is laid out onto a spreadsheet orderly so you can pivot table your orders.

To use the Script follow these steps: 
1. Copy the below link to your Google Drive. 
2. Go to Tools > Script editor
3. In the drop down box select 'main' and hit the play button. 
4. Your going to get a message box asking you to approve the Gmail API call. 
5. Go back to the spreadsheet and notice that the 'Parsed' tab populates with all your buy/sell info. 

Notes:

 - The Summary tab automatically sorts whats on the parsed tab. 

 - The Visualize tab is just an example chart of the latest 200 data points in your data. 

 - The Script checks for duplicates using each emails unique ID. You can run this script multiple times daily and it will only parse new notifications. 

 - Partial order completions do not work using this method - however if an order partially completes and then later fully completes - that full order will be parsed. 

https://docs.google.com/spreadsheets/d/1_jHJ81Pa4q7r_lhkeArGNRKAnSRNyUkW0fRYcs1eQj8/edit?usp=sharing