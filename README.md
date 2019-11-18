# Stock
requests库提取部分股票代码与价格
This is a project which used python library 'requests','BeautifulSoup','re' to analysis stock infomations
step 1:
GAIN INFOMATIONS FROM HTML PAGE
In this project we need two orginal URL
1:  'http://quote.eastmoney.com/stock_list.html'  
    which we use it for get sotck markup number,such as '600100'
2:  'https://www.laohu8.com/stock/'
    which we use it to cheak stock price,because HTML page don't show many javascipt element in this URL
    
besides:
  use library 're',apply regress regular rule to 'Beautifuled' line
    
step 2:
DECIDE WHAT KIND OF FORMAT WILL YOU OUPUT AND SAVE
  there is two way to print/output you final result
  first:use dictionary
    We can make your infoDict_name as KEY and your infoDict_price as Value
    Dict format is a convenience way to save result and make your output format clean and concise 
    DIC is Suggested
  second:use two list and ouput in nesting way
  Adventage: easy coding
  Disadventage: need some measure to contrl ouput format

    

 
