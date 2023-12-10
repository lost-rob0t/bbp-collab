### CSP Not Enforced (missing-csp) found on https://_wildcard.docsend.com

----
**Details**: **missing-csp** matched at https://_wildcard.docsend.com

**Protocol**: HTTP

**Full URL**: https://www.docsend.com/

**Timestamp**: Sat Dec 9 08:22:57 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | CSP Not Enforced |
| Authors | geeknik |
| Tags | misc |
| Severity | info |
| Description | Checks if there is a CSP header |

**Request**
```http
GET / HTTP/1.1
Host: _wildcard.docsend.com
User-Agent: Mozilla/5.0 (Windows NT 10.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 403 Forbidden
Connection: close
Transfer-Encoding: chunked
Cache-Control: private, max-age=0, no-store, no-cache, must-revalidate, post-check=0, pre-check=0
Cf-Mitigated: challenge
Cf-Ray: 832bd7e18ba87012-CDG
Content-Type: text/html; charset=UTF-8
Cross-Origin-Embedder-Policy: require-corp
Cross-Origin-Opener-Policy: same-origin
Cross-Origin-Resource-Policy: same-origin
Date: Sat, 09 Dec 2023 08:22:57 GMT
Expires: Thu, 01 Jan 1970 00:00:01 GMT
Origin-Agent-Cluster: ?1
Permissions-Policy: accelerometer=(),autoplay=(),browsing-topics=(),camera=(),clipboard-read=(),clipboard-write=(),geolocation=(),gyroscope=(),hid=(),interest-cohort=(),magnetometer=(),microphone=(),payment=(),publickey-credentials-get=(),screen-wake-lock=(),serial=(),sync-xhr=(),usb=()
Referrer-Policy: same-origin
Server: cloudflare
Set-Cookie: __cf_bm=JHvFNuASmAVgvdJ4ZaxIS6oN21_UM.3EBDbMAS4eujU-1702110177-0-AScuA/8u0I1GzoLwfhQa09RwObfXXKZ6P/DZwE/FMnraPDNpYlB5Mk75VYTqjJN7Ywwj3apepDZzEDesMglAZy0=; path=/; expires=Sat, 09-Dec-23 08:52:57 GMT; domain=.docsend.com; HttpOnly; Secure; SameSite=None
Strict-Transport-Security: max-age=31536000; includeSubDomains; preload
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html lang="en-US"><head><title>Just a moment...</title><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta name="robots" content="noindex,nofollow"><meta name="viewport" content="width=device-width,initial-scale=1"><link href="/cdn-cgi/styles/challenges.css" rel="stylesheet"><meta http-equiv="refresh" content="375"></head><body class="no-js"><div class="main-wrapper" role="main"><div class="main-content"><noscript><div id="challenge-error-title"><div class="h2"><span class="icon-wrapper"><div class="heading-icon warning-icon"></div></span><span id="challenge-error-text">Enable JavaScript and cookies to continue</span></div></div></noscript></div></div><script>(function(){window._cf_chl_opt={cvId: '2',cZone: "www.docsend.com",cType: 'managed',cNounce: '63192',cRay: '832bd7e18ba87012',cHash: '1f08a2ee944e453',cUPMDTk: "\/?__cf_chl_tk=UsdjbKUfEv3Csc3A0mIZdflQIKF0Ec9bnNJgUJ0Z3wE-1702110177-0-gaNycGzNClA",cFPWv: 'b',cTTimeMs: '1000',cMTimeMs: '375000',cTplV: 5,cTplB: 'cf',cK: "visitor-time",fa: "\/?__cf_chl_f_tk=UsdjbKUfEv3Csc3A0mIZdflQIKF0Ec9bnNJgUJ0Z3wE-1702110177-0-gaNycGzNClA",md: "WWDrZDp4XvFXkmrTGtB2nxG8fe7CiFMB.VMvWHQEwi4-1702110177-0-ASXVAgwstrmBt-7G3QyBcTQ5_Yweeet51JGNpaxw7z7D2NkXoz-9zCB6Vs0iR2Atyo5qlMux23uolLXzOqMjOApBrRBtA37fFHSkPwVKWD4ZUJml3iEvIJzJWdDfofW5VuMZscJHcx8pFBak16ZvL9w2pYJXoN8saKEmnlsXrk_8QA1KT16osX1NLn8I3NQgz7gCrLxSHzfa6Jmsn8qV0rm7J9H4yIOvxlENeXT3Lu3tVGM6SiEhi9cGVtf3hrpfj4qZPqq4pqxRpaBsxZUC76yjC5QYlhQarD-YIENLzfLXI7jCWvwiTAD0IDa0FW5Zy1RHtxS4NozERn45OUsffOGhOf8Qg-3MDAmVT5DZxcW6Glvou9oDHAnNQq8Nj6zzd8xp3jJfVK4k0Vzkqpbft0uFxxI5ZAABBDOqNpOLUOLUhTHuZIIkFq1jlQeIV2kGgVoiuPT1IkzbMVtBgb4JF64u9R75bt8BATcuMqUom6Z0dWi3XCJGhWxLhTwK5bx0vOC80S6MsISVphnuGSInHfV505JoN1t-Abv_ELYEi1Ie7E82GHoDJ4KFR2ekjcOOHX43-VaYkQLUZtlu89yAwxrrfATItEjTUIavy9U8KU1VMLuqyB-0qqZPskKqs26L1xCvru80cARUv39g-HeDUurjVJFcRBYPM4PnELa_zGWMYHv0YHoVpP1jRbwuRjfaBQIMv2P2-9ZrnHC1ysVpgHw7s43IVNiD2L6F9ISN6gIzfb3l_-U3K4EqjVuaXBx3HY8CuCvELOkKl-mvydCTqd1PLOP7RoVhuJQSh9jyjfOn3gJY93J_upxj0OUC8bh5AGy2ZEoWxEW9x3CbYLusb7-vQNQrRnCfGN1CFNJYgFaQ7QA4OKDorXuWr-b5lUF20k5WAMeylVv5fPlUCRQClu1T5MPXJNWNMg1Pd1kztvHs52rXRL0TO-u8aGbalq-EW1pYbd_FqhzNR88bqNELCdp8a4-1cJ6TE-BDKZh2M-YJLfP3wENFK7EGoZCq5j_WcrDQfmplM1Bu6S7KZfmyDr1j0jAcpZwGc-Aw1qktS5TPfyY5BI3J6vPuAxmZbahWcMci7r-0fW_WGLJyMULgVYSYgEhWRvjtIlt43x2YGiDXd0Qf_cl8oiRnw8AYUS-Dbj_nFsmd-5x_cmC344RbgKdvJAunpz1PP3Ooi1W7tzkQWSbyH-qSztsGFG0qHm2Vje5FBAawtbtoNG2KAzlZEIGIARZ7EtpxCbYvkD7XZt355P9b0ZWqs3pjuB9YGco2wO4VgUGx8rPqrPql-nfuNqj9cMiPD0JaSQ6H2WNH5zrfKLz1gM_SWRiY2eP5TyyaH0cBotNW0XgAGwcb1rAS75vYpzfdWWrGVgAttHhuX-__llOpJyAi9R1UUPoVzS0D09VrVqwZk9R1svPg7heVJcaY-AXlEX_r3jhnZlWMFjtFlU0Cwg0CJ6EsUF1DtotH32gL5vSmou0-jxawZ44QX_oOAUKb0V3t39qzxRMa2k9OG8K5TS9_QqvJzt70pdTeFIq968W6fE4eRJWvwJAAGUw4rHIqLgUoMBtOuQWtUGur0Hzpc7Yy4bweV4KTf0wrVBi55vxWcqBuzSS3GX116bqB3nYQmGDW_woTJbHL73EfGBR0SpLCnyiO--5mjAZiYjkoe5C6uomwMG2v3WUFfWrHbCp9kxdK51az-WE0tQMUa3aVOyHck8I46Lo5hjT72A9Z4cTArKBlQMNqLpafYh16aNu-WifW_EGh3yjjfzrJ48JO-6MzY3hlS3pUJ4t8hQc-8UhWnWe8brNf-DGAkQwVFBp24-mQqa60HW3ofqwe-mGU5xlTadI7SlOOcymlLn_91jlLLdmuNYfJJQry0nP1kVVetjkU3UgMEyiv1YsVJBEoH8szuCQ5KWF85oISIYzVlJBQcAjB4uMmSUV7IRo3uk_56XWL2w_63OSLYz1bw8T6-UQ1ggseX7BV8-j4jb240Nz64HwROMsh7kb_rtOLlYGpfkoqk-UnF0NESKrONipEkqr6yf9jn0RxTD6cwGYOlZ64Ufs81F2cBQSzSfzkn_K4agSthwNndDY4T42DI0ZZw1oX6rvNSAxg8oJWy-W70mqNSXVRIlosIFl-OrwNK3Mut2Ij3QDS-OviJcLwutNYkf8lEiDLprlW1nq1QaKz3BHfgyZYDjLnRn95OwCU2JQjAcU_csPweRsUIN6PUrkrOavhxUOwIIudR68vs3XKCY8uSG0OBSNGl4XeUW5hNYFOmgqxX2SIx6H4Nd7yWOzF50SMoUrYIegMTt34Mplnd85-7jKCN2GY2iAr44TQl0Xt5LQbiRi3nm913aGe6YUkdrytnXvcnY6EUI7tUB0SzUiDZTBDUZ96lT2jhQZphUAruMeII6mOebzmK3CLKlEAMdpvzSpKqwOpMYJxVzdVzO_6cL1tU6uGcmI8iWX5kx8I7IX9r-C_TnoMuyYuHKBCPqjfFwC-P8wnCqvL2wjPTC4H8oWn-_2Z5zMpkaJT2o7Zvruwevt4amAmGpysTNVLuowMz-sY5px8E5EvThntBMNlNabJ8TdIPKf502M",cRq: {ru: 'aHR0cHM6Ly93d3cuZG9jc2VuZC5jb20v',ra: 'TW96aWxsYS81.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36' 'https://_wildcard.docsend.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)