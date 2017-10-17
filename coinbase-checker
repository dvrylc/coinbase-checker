#!/bin/bash

# BTC
BTCBUY="$(curl -s -H 'CB-Version: 2017-10-17' 'https://api.coinbase.com/v2/prices/BTC-USD/buy' | python -c "import sys, json; print json.load(sys.stdin)['data']['amount']")"
BTCSELL="$(curl -s -H 'CB-Version: 2017-10-17' 'https://api.coinbase.com/v2/prices/BTC-USD/sell' | python -c "import sys, json; print json.load(sys.stdin)['data']['amount']")"
echo -e "Ƀ\t↓ ${BTCBUY}\t↑ ${BTCSELL}"

# ETH
ETHBUY="$(curl -s -H 'CB-Version: 2017-10-17' 'https://api.coinbase.com/v2/prices/ETH-USD/buy' | python -c "import sys, json; print json.load(sys.stdin)['data']['amount']")"
ETHSELL="$(curl -s -H 'CB-Version: 2017-10-17' 'https://api.coinbase.com/v2/prices/ETH-USD/sell' | python -c "import sys, json; print json.load(sys.stdin)['data']['amount']")"
echo -e "Ξ\t↓ ${ETHBUY}\t↑ ${ETHSELL}"

# LTC
LTCBUY="$(curl -s -H 'CB-Version: 2017-10-17' 'https://api.coinbase.com/v2/prices/LTC-USD/buy' | python -c "import sys, json; print json.load(sys.stdin)['data']['amount']")"
LTCSELL="$(curl -s -H 'CB-Version: 2017-10-17' 'https://api.coinbase.com/v2/prices/LTC-USD/sell' | python -c "import sys, json; print json.load(sys.stdin)['data']['amount']")"
echo -e "Ł\t↓ ${LTCBUY}\t\t↑ ${LTCSELL}"
