# arbitrito ![Alt text](other/readme_header.png?raw=true "Title")
Crypto arbitrage bot for "Crypto dot com" and "Kraken" exchanges

“Buy low, sell high” (Wall Street proverb)

## Setting up

*python3
*To run this project, you may need to install the following python modules:

```
pip3 install cryptocom.exchange
pip3 install yaml
pip3 install krakenex # it's recommended to install for the user -> pip3 install --user krakenex
```

## Config

1. Duplicate "config/default_config.yaml" file
2. Rename it as "user_config.yaml" and add there your API keys and set the other values as you wish

Be careful! -> Do not set your API keys in default_config.yaml and push the file to git!
