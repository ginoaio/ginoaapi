### Features

- It gives price to 4 NFT Collections at this moment.
-- Cryptopunks
-- Meebits
-- Bored Ape Yatch Club
-- Clone X
- It's now V1. Just gives some of information.

# Quick Start

API host is **api.ginoa.io/v1/**

> First you need to get an API Key. To do this, first contact via **info@ginoa.io**

You need 3 paramater.

| Parameter      | Value |
| --------- | -----:|
| API Key  | String |
| Collection name     |   String |
| Token ID      |    Integer |
#### Available Collections
| Name      | Slug |
| --------- | -----:|
| Cryptopunks  | cryptopunks |
| Meebits     |   meebits |
| Bored Ape Yatch Club      |    boredape |
| Clone X      |    clonex |
#### Usage
    /v1/<api-key>/<collection-slug>/<token-id>
#### Example Usage
    http://api.ginoa.io/v1/<api-key>/meebits/4323
**Returns**
```json
{"collection":"meebits","tokenId":4323,"ginoaPrice":7.41,"isSale":false,"salePrice":0,"success":true}
```
