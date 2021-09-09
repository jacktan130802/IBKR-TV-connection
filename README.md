## Why is this necessary? 
TradingView always said that they want to integrate with IBKR but it never occur. It is an issue, particularly to me as I do not want to fork out extra money for the real time market data with IBKR.

## Prerequisites
* You probably need to have TV pro for auto buy alerts to ibkr
* Requires redis, Python3, and packages installed

```
pip3 install -r libs.txt

set FLASK_APP=webapp
set FLASK_ENV=development
flask run
```

Painfully coded from youtube video below when i did not find the github link 
- Youtube Link: https://www.youtube.com/watch?v=zsYKfzCNPPU


## Notes
- `set` command is used for **Windows**. If linux os is used, replace `set` to `export`

</br>
</br>

## What I learned - for my own references
- Learned how to host localhost using ngrock
- Learned how to mass install libraries using pip 
- Learn redis library
- POST/JSON
- H2 heading the best in readme!  
