# ShortLinkAPI
Shorten your long links and get a 13 character link with this API.

## Getting Started
Read the description below to get started with **shortlinkAPI**.

## How to use?
You need to send 2 parameters to the server and wait for the response.
**The values to send are as follows:**
1. `link`; Your Link for shorten.
2. `APIKEY`; Your Api-Key for identification.
> [!IMPORTANT]
> The submitted `link` must be encoded with <ins>**Base64**</ins> structure.

## What is the API response?
If there is no problem with the values you sent, Api return below fields:
1. Shortened link; named `shorted`
2. The 6 character word used in the shortened link; named `code`
3. The link you submitted; named `link`
4. Mondified DateTime in Tehran Time; named `datetime`
5. _time()_ method in php; named `time`
6. Your IP; named `ip`

## What is the code and meaning of the errors?
If the API give error, it is definitely one of the following values:
1. APIKEY expired <sub>code: **100**</sub>
2. APIKEY is incorrect <sub>code: **101**</sub>
3. APIKEY is empty <sub>code: **102**</sub>
4. APIKEY don't send <sub>code: **103**</sub>
5. Link is invalid <sub>code: **104**</sub>
6. Link is empty <sub>code: **105**</sub>
7. Link don't send <sub>code: **106**</sub>
8. APIKEY limit is over <sub>code: **107**</sub>
> [!NOTE]
> If an error occurs, the return values ​​are named `error_code` and `error_text`.

## Attentions!
- Contact me to get `APIKEY`.
- You must be send your fields to `https://a86.ir/API/index.php` with **`POST`** method.
- See example in [here](example.html).
- You are can shorten your long links in [my website](https://khoshghalb2c.ir/shortlink) without Api.
- You are can shorten your long links in [telegram bot](https://t.me/a86irbot) without Api.

## Licence
```
Copyright © 2022-2025 Khoshghalb2c.ir. All Rights Reserved.
```
