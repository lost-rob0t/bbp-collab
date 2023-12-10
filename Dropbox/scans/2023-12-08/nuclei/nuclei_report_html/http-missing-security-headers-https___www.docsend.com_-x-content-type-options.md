### HTTP Missing Security Headers (http-missing-security-headers:x-content-type-options) found on https://_wildcard.docsend.com

----
**Details**: **http-missing-security-headers:x-content-type-options** matched at https://_wildcard.docsend.com

**Protocol**: HTTP

**Full URL**: https://www.docsend.com/

**Timestamp**: Sat Dec 9 14:54:22 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | HTTP Missing Security Headers |
| Authors | socketz, geeknik, g4l1t0, convisoappsec, kurohost, dawid-czarnecki |
| Tags | misconfig, generic |
| Severity | info |
| Description | It searches for missing security headers, but obviously, could be so less generic and could be useless for Bug Bounty. |

**Request**
```http
GET / HTTP/1.1
Host: _wildcard.docsend.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2227.1 Safari/537.36
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
Cf-Ray: 832e153c2bf8f0a3-CDG
Content-Type: text/html; charset=UTF-8
Cross-Origin-Embedder-Policy: require-corp
Cross-Origin-Opener-Policy: same-origin
Cross-Origin-Resource-Policy: same-origin
Date: Sat, 09 Dec 2023 14:54:22 GMT
Expires: Thu, 01 Jan 1970 00:00:01 GMT
Origin-Agent-Cluster: ?1
Permissions-Policy: accelerometer=(),autoplay=(),browsing-topics=(),camera=(),clipboard-read=(),clipboard-write=(),geolocation=(),gyroscope=(),hid=(),interest-cohort=(),magnetometer=(),microphone=(),payment=(),publickey-credentials-get=(),screen-wake-lock=(),serial=(),sync-xhr=(),usb=()
Referrer-Policy: same-origin
Server: cloudflare
Set-Cookie: __cf_bm=r2OZQ4z_b2dcYHa_c5I.3RKZTR07B1lGaT61n6zAg0s-1702133662-1-AaZBW+8FitFXoz+/Wj+ee2Vy42tJfy9cHl4BWrJpzPmkinq2muFhEwXex+QJtxp11EfKEPHAGR0q11ABsxzJNrw=; path=/; expires=Sat, 09-Dec-23 15:24:22 GMT; domain=.docsend.com; HttpOnly; Secure; SameSite=None
Strict-Transport-Security: max-age=31536000; includeSubDomains; preload
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html lang="en-US"><head><title>Just a moment...</title><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta name="robots" content="noindex,nofollow"><meta name="viewport" content="width=device-width,initial-scale=1"><link href="/cdn-cgi/styles/challenges.css" rel="stylesheet"><meta http-equiv="refresh" content="375"></head><body class="no-js"><div class="main-wrapper" role="main"><div class="main-content"><noscript><div id="challenge-error-title"><div class="h2"><span class="icon-wrapper"><div class="heading-icon warning-icon"></div></span><span id="challenge-error-text">Enable JavaScript and cookies to continue</span></div></div></noscript></div></div><script>(function(){window._cf_chl_opt={cvId: '2',cZone: "www.docsend.com",cType: 'managed',cNounce: '52256',cRay: '832e153c2bf8f0a3',cHash: '64b7c45ea898b66',cUPMDTk: "\/?__cf_chl_tk=bY5HHYXv7LPK.Z.FaFvPmVpk.n0zJl5BfCJ4nMrW5Bc-1702133662-0-gaNycGzNCns",cFPWv: 'b',cTTimeMs: '1000',cMTimeMs: '375000',cTplV: 5,cTplB: 'cf',cK: "visitor-time",fa: "\/?__cf_chl_f_tk=bY5HHYXv7LPK.Z.FaFvPmVpk.n0zJl5BfCJ4nMrW5Bc-1702133662-0-gaNycGzNCns",md: "1uKOx1vo6YS8LvFzj9YCBMcL8w9ny1g4dvnLJOYhN7s-1702133662-1-ASivJ4pV7mHnStXFjYzfZtDw9uHz5J4e0WsRJKpG9kLNWsEPrDO1kKKXBC1OtRnt478vjvvVeHv88Uw8pm5FBGLSEQyKb3cyHqBWmgGhMZMwtEihaOMA63ExAtvUHW4m6YEBH6L-VOditmeTBy8A2H6A4yMUCx8zbp1ASAdmpj9YkacZEWt-oRcyNo2W0CEGkQmQMKgLtcMVSLC2Isp7jucB5HBHvKjadPyaHWUQRj6LH-8PzVQrmcDMeDatXxt5qNJ6tMS1lXEQPBashhR4ZRbx0KNvQWReAVnixWfvZ2-BMfPttJbQn-PmFkltObUBlsSMHfVnH7YMV7fT5NX82a0ucEAN4PakI5wGJsT-ySAmE636JI7Jed1VMJjulSkqrSvlsA0jWO5V9DO9duS6rFPr4t8DFTesdrEl2530twvHz93C7b2qOsa2PUgQvkTsE0q6jQ2yK77Upkdc3i-xLLSEmhGd69Iv0XFBNt4KrC7cipG849voZ2nEMWAE2Yb1_kDyQVvzQYFFIKehOSpEkKYxgdmQR_-5pVA-_BN6FkMhgRhXaLpG4svvUxlWTyYsngb749yA1NkiQhxEbmG2oC82TBauFG4UTlbmHhLOgSJqZDml_MW_reXmR45e0pyaBbIEtJrZxZFoEm2rTQsF41d88EiVYpHfr4Kvd1CQgtHKWCUsUd559i0Q45orrh6tZplfHeHK1B2lTA_O83FA4SblrMftKxMTJnAFKzZh5ekpadvzZ8rOFgKFPnqw66cjZIrvnJql_q0b6RYVFb4ZqlraFebc741Zozxy51SqQAyI-Pt6OkQeuEPGNOhFyZAvkFft7PTINyJjzCCKpYR-5hm3tSZtNGWQAbcMbcUWqoKL9JjWsOU5qyLjO0oKr3QlkhQwi6A9q1zdv6L7ecPP2wxIi2pTLRR9R6ogu9myFa9nHjxZFTdRLYz8ksFjhk8eXVJS7r85X63L53Us8dSkfg90NYpYhoBYI4scnlBsG5Rjn-YqVyOaZJuJm_E2iyf61MZssFCQJ36ue2mayUmY_CHzk8bFUz3mH_QrKkNrqqkLwmSrdwV27I0RlbJPu_LeYzSjFUaSYygLh7vrbPhgP8kNsldLNCFaU9lV5dI0dLiQ-wzEL13Zj1BbKf5EiI067vTSWFTt05blSts1vMJcvF3vKmTsWQQEoa1VIwLZq9gACo7eyXTd1tgryBD8w_WubHrt5_uBPvg607Ah4aOxKObfg4u8PbRclqJQIpumMOweFYlnADZ2IDjrcYUWYxwkryyINPKwiBudoRHSHSnij-zccNto5vI01E5Lx5RxBsjRSBJW4HHgrfE96gaEHbL3e5YbllB_YTcrfkrkDXGgoUh-mVSN4dvj2edh1rMP-EwtKv5SsW0GZgE1df38h9zFV6dCTqAI_3oWa7C7ex29aw5baXvKoSzMmgm3yE61NFEDYPDsYJJx-j2Je-f1DHmAjg8zg_8iCyEa3tkWue6kA383rkOaekTiDiWIZ0knmEIY9ueoRFak1aAEDczsnLGJdr9l_f9eUF4ytFscnBJqkjslThxOYXHM1xgpku5PYT9iieB8-C0lV-hvfKP0hzP04Wx0KGjJffr__0GScbPcxRUCjjN7p4vaeGMNrMzW-v96JaDU-c4CzZQpPsqTvwlcSpb7VcTHYlJt3un_gKA8ep8FVxAkSUJUyEexYRPtsfM74MNREOjjfF4cB1OWzuv4ZRhF0RTz_F4pELZCkA6tdRBP-hIT4H3iQhbd-i4HBA6N6Y0Tc7_nKf15DLwU4xpTQ_mJfstG0lGgUMxuu5I4sCpThYfJAFtvqON6e7_4kuPP60CAqrGqBGdSUPikY7y3Oeld36RLx8GAsb6sgsuE3O8KgD-r0r30egvTOllW4DjMNUhSYQ0TD4pMbfKWAvyCBE8z5Yf5ksOCQ63o-cqHbAB0IafKfAQvoTnk424T3NqIHAv7En8KuRIO8RH-d1L0oXQ9FsQ_A7l7i6-koJqXCZ8NgWu4mO3BvL0Z69lx59VG8hrBCs8Fp12ZdCn5QGb7_RJ8R_FQLC1_U9KEQkuYLfkVGMpEf0HaeCTMz4XKyXaRWNyCU9ZCEpE-fst5W6B0QBn5dCn9fQUNFb4RngnQEXMaaKXhV1xD5UD7YR_AlwqbzZQmpmRbIFzLGOTCa8i5S8C7Np4HCwcPHkvMOt5-ivmydv5p5fm7cPxYy033N10HGjlU-dxvRz6EyQ_fYq-aUiSHbIP4QMY4VeX8-4JffMaE1Zw5le6C-nxAJhzpsRZGgqECIEPt8sqkfQkIbru6pWbKon4mwqXmJ7vjpsGBmxBZeCe9jUiuQUJCKgVNywfhR4EhtldO7_s3EIN_XPxyg4ce4gTibGBTUrf9Qi99GO5AjLpBleq4bmHztJDRqfs7vnQ7LNywGOOaKk2uuI9g0kkaho4tdqeTkORpRqhgL9omehmTNc2pvh1UHQKtTDCQRZxV7vel7OPJ2HQM_6BNjl6SNmrpvJSPVtK9QJzPOfNWePuXbceAL9qxgFZqP4GmOSGTaINobRhtUeJmhM8anX8CW0zFLVxTXT_-9F3QHeLw_vCydf-YWwhc6_ieLqnxhb5S3GtNpTQxys8ubtWQBw",cRq: {ru: 'aHR0cHM6.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2227.1 Safari/537.36' 'https://_wildcard.docsend.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)