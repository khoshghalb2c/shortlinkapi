# ShortLinkAPI
Shorten your long links and get a 13 character link with this API.

[![Donate](DonateIDPay.svg)](https://idpay.ir/khoshghalb2c/)
## Getting Started
Read the description below to get started with `shortlinkAPI`.

## How to use?
You need to send 2 parameters to the server and wait for the response.
**The values to send are as follows:**
1. `link`; Your Link for shorten.
2. `APIKEY`; Your Api-Key for identification.

## What is the API response?
If there is no problem with the values you sent, Api return below fields:
1. Shortened link with the name `shorted`
2. The golden word used in the shortened link with name `code`
3. Your sent link with name `link`
4. Mondified DateTime in Tehran Time with name `datetime`
5. Time method with name `time`
6. Your IP with name `ip`

## What is the code and meaning of the errors?
If the API give error, it is definitely one of the following values:
1. APIKEY is incorrect <sub>code: **101**</sub>
2. APIKEY is empty <sub>code: **102**</sub>
3. APIKEY don't send <sub>code: **103**</sub>
4. Link is invalid <sub>code: **104**</sub>
5. Link is empty <sub>code: **105**</sub>
6. Link don't send <sub>code: **106**</sub>

## Attentions!
- The `link` sent must be encrypted with structure `Base64`
- In case of an error, the name of the returned values is `error_code` and `error_text`.
- Contact me to get `APIKEY`.
- You must be send your fields to `https://khoshghalb2c.ir/api/shortlink/index.php` with **`POST`** method.
- See example in [here](example.html).
- You are can shorten your long links in [this](https://khoshghalb2c.ir/shortlink) link without Api.

## Licence
```
Copyright © 2022-2024 Khoshghalb2c.ir. All Rights Reserved.
```
