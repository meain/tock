<p align="center">
    <img src="https://i.imgur.com/JCw3WtB.png">
</p>

# `tock`

Simple shell script to check [Alphavantage](https://www.alphavantage.co/) for stock price.  
Shows current price and change from yesterday

### Installation

```
curl -o /usr/local/bin/tock https://raw.githubusercontent.com/meain/tock/master/tock
```

> Needs [`fzf`](https://github.com/junegunn/fzf) to be installed for search.


### Usage

- Check stock: `tock SYMBOL`
- Search stock: `tock search keyword`

> Add --may-wait to handle api rate limiting (sleeps until available)

Idea from [pstadler/ticker.sh](https://github.com/pstadler/ticker.sh), but was not available for listings in India (NSE or BSE).
