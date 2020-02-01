# Server

```sh
npm install
```

## How to Run

### Localhost

Create a .Env File

```js
EBAY_APP_ID = 'YOURAPPID'
EBAY_APP_SECRET = 'YOURAPPSECRET'
EBAY_MODE = 'SANDBOX'
EBAY_BASE_URL_SBOX = 'https://api.sandbox.ebay.com/buy/browse/v1/item_summary/'
EBAY_BASE_URL = 'https://svcs.ebay.com/services/search/FindingService/v1'
EBAY_TOKEN_SBOX_URL = 'https://api.sandbox.ebay.com/identity/v1/oauth2/token'
EBAY_TOKEN_URL = 'https://api.ebay.com/identity/v1/oauth2/token'
EBAY_RESULT_COUNT = 3
```

then run **npm start**

### Production

Change ENV *EBAY_APP_ID* on Dockerfile

the run

```sh
docker build -t ebayapi .
```