---
title: Zebpay API Reference

language_tabs:
  - javascript
  - python
  - curl


toc_footers:
  - <a href='#'>Sign Up for a Developer Key</a>
  - <a href='https://github.com/slatedocs/slate'>Documentation Powered by Slate</a>

includes:
  - errors

search: true

code_clipboard: true

meta:
  - name: description
    content: Documentation for the Zebpay API
---

# Introduction

Welcome to the Zebpay API! You can use our API to access various endpoints for trading, wallet services, market data, and account information related to Zebpay's cryptocurrency platform.

We have language bindings in Shell, Ruby, Python, and JavaScript! You can view code examples in the dark area to the right, and you can switch the programming language of the examples with the tabs in the top right.

This example API documentation page was created with [Slate](https://github.com/slatedocs/slate). Feel free to edit it and use it as a base for your own API's documentation.

# Authentication

> To authorize, use this code:

```javascript
const zebpay = require('zebpay');

let api = zebpay.authorize('your_api_key');
```

```python
import requests

url = "https://www.zebapi.com/api/v1/tradepairs/IN"

payload = {}
headers = {}

response = requests.request("GET", url, headers=headers, data=payload)

print(response.text)
```

```curl
testing = f
```
