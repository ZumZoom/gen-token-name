# Token ticker generator

Genereate token names from templates and check their avaliability on coinmarketcap, mycrypto and etherscan.

## Installing

pip3 install -r requirements.txt

## Run

Run on full english vocabulary to get list of 3- and 4-letter symbols.

```
python gen_token_names.py
```

You can also check your own templates.

```
python gen_token_names.py ET* AB *S*
```

Algorithm will check all available symbols in place of *.
It will also extend the string to 3 symbols in all possible ways.
