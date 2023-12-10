### Strict Transport Security Not Enforced (missing-hsts) found on https://help.docsend.com

----
**Details**: **missing-hsts** matched at https://help.docsend.com

**Protocol**: HTTP

**Full URL**: https://help.docsend.com/hc/en-us

**Timestamp**: Sat Dec 9 08:23:59 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Strict Transport Security Not Enforced |
| Authors | dawid czarnecki |
| Tags | misc |
| Severity | info |
| Description | Checks if the HSTS is enabled by looking for Strict Transport Security response header. |

**Request**
```http
GET / HTTP/1.1
Host: help.docsend.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.1916.47 Safari/537.36
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
Cf-Ray: 832bd9626d23024f-CDG
Content-Type: text/html; charset=UTF-8
Cross-Origin-Embedder-Policy: require-corp
Cross-Origin-Opener-Policy: same-origin
Cross-Origin-Resource-Policy: same-origin
Date: Sat, 09 Dec 2023 08:23:59 GMT
Expires: Thu, 01 Jan 1970 00:00:01 GMT
Nel: {"success_fraction":0.01,"report_to":"cf-nel","max_age":604800}
Origin-Agent-Cluster: ?1
Permissions-Policy: accelerometer=(),autoplay=(),browsing-topics=(),camera=(),clipboard-read=(),clipboard-write=(),geolocation=(),gyroscope=(),hid=(),interest-cohort=(),magnetometer=(),microphone=(),payment=(),publickey-credentials-get=(),screen-wake-lock=(),serial=(),sync-xhr=(),usb=()
Referrer-Policy: same-origin
Report-To: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v3?s=1RnU%2BRR2ZhVFriBzkU1grtcHkzj7WbFTGkqJE8rHw3ARunOyQQ%2Bx8Sij5ktHCVf3cEpxOdhm%2B313g4vaG3S%2FuZjV3wVKHzIW8Xejx1mty872%2BGiEJFAPloYqJAeAiPE2gQI%3D"}],"group":"cf-nel","max_age":604800}
Server: cloudflare
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html lang="en-US"><head><title>Just a moment...</title><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta name="robots" content="noindex,nofollow"><meta name="viewport" content="width=device-width,initial-scale=1"><link href="/cdn-cgi/styles/challenges.css" rel="stylesheet"><meta http-equiv="refresh" content="375"></head><body class="no-js"><div class="main-wrapper" role="main"><div class="main-content"><noscript><div id="challenge-error-title"><div class="h2"><span class="icon-wrapper"><div class="heading-icon warning-icon"></div></span><span id="challenge-error-text">Enable JavaScript and cookies to continue</span></div></div></noscript></div></div><script>(function(){window._cf_chl_opt={cvId: '2',cZone: "help.docsend.com",cType: 'managed',cNounce: '16451',cRay: '832bd9626d23024f',cHash: 'a59d4f7d540fca1',cUPMDTk: "\/hc\/en-us?__cf_chl_tk=WrIbdyNeW1Bv_yIlcwyX5UVGNCnvkxO93t4plxU_Kws-1702110239-0-gaNycGzNC_s",cFPWv: 'b',cTTimeMs: '1000',cMTimeMs: '375000',cTplV: 5,cTplB: 'cf',cK: "visitor-time",fa: "\/hc\/en-us?__cf_chl_f_tk=WrIbdyNeW1Bv_yIlcwyX5UVGNCnvkxO93t4plxU_Kws-1702110239-0-gaNycGzNC_s",md: "4eh5lNJ9O6IPPJ7skMrk8SYTzzImoW5trdnVMb5vYO0-1702110239-0-AZGV4vwsO3IuElH-S1cGJ6VAHgmIfQpkBQIEd0ERNje7TnXQt4vnZMpGvpZE6KoLPO23tOkhEtlg2wOeJmTiqDeoLlHMkEe68G0x24hFb7kXt6H4NhEp6kzuwjzs-vY2seicKG1lTrJMGHatS-6_zNPnWRrHvmEKiBxx9Vcmr1ONGuGHR1kU70o344xh4N7n3K4Xm5JXpcJ7CGMe4zwWTshxjw4x9KuLmLjUMSEKlc1Z87U-iIYqhd8LQ3kvQgWGW1NpRRAklaeHiFtiYFtcnMqapD5hkcfAM3RoegEtm1WB_HzAQsbKcYHoB8WUuW6I5Pi3vGVCr7JVMPq6ZRtwgWCMj1BzWgQW2h9e0K6hFXqk5-mpNyldS8fk3r3MyOSrd_4NOKEHOJxYusJJawF2OkaMpyGYyMLtq8qTn34mpO8EBfowm___D59NsK09G7_0QCjlbhjsjT1jcEBDbzrUiBTy2AVZDKuhB8ZGLlJdzPKZWxogEk9rPwUiLve6mW8l2YPTY2VbCWAkb7MMUD1DUQx_105uOqh3f6_1dDXq90W-qS6LWpiRffPTYwhWsRytmKHS86UVa4EvhRr4zOsKzYgc4bYrDlyzaX5tMt-lTVx42za5WzjMFvgheD6PzA2_UQrezKimzPRcKnNKoph0JCmFbl6xgX6YwmlE4GZW4c5G2CzgDFo3X-JotCadF8jE9LZrYSGfomi_2Mq6cdRHOcurpFsdRRMf7lAutUBy2LEN_SVB598Gpf7ZT6Zg1zuHvORTvTJzyYBQSV2VvSFgZv2QSX09flN1F-O--VeDBLJscbpw0Jn4Fmw-dQxVCrtfNCuUbq0a6Z3fukQCxhntsgcL2qiXC8cSuieew75OVlsGr0QWFroraGesFRc19IXgXSUjczwHKFgmBs_oWrGhZ23uOM3h2XZwLSNxksd1FkcnVvWzguo15UjeQ1pwQnX4kJz6XJNWyn2-dwspeaTQARY7qgUdtA75_yCTKdwl3YxMPAPvoSHq2w5s1FiCUf2W_eSu8y7hk2G8oGgOMtnRLUzCHp3rZBDrHXIe5i-j7vXYQpoFypP40PFALhLuX7cFvI2J-3akaryE2zqq4ByU3Dt3H5VSbgJZB2m4a1W9g1ScR2uAhurep9yChKgFwoiD2_Ez0F7FsTGDli6Aozk-iNzhXZjwzGrZjnKaNQyvgqXvPgYaKdOfNJB05QDrPmbmSGWWVcO4KMzoI4SE8d4NodsxlIdG3Wx6c1g8p6Gs1HUN0xhJdxMBPyjzxHu_4lyD4ZjShFamNr49kFL29Xsr-iXk-IbPAaD-ODxewkXdk6xqUawRKkPo8astfxX9Nf9KsLsOAsr7tg76q1dhPwjblJfw0dMBxbDcNUos6SeRjGIB65J40y2PLAZqmcCVKppasbmx9gocJ-omz5GKdHak9eNSM6kIfzvJNoBQT9w7p7zuat92T_I4VDs8HCAv6b3kby-ahfJQm8_oR2Z561Hk7zOTjHxNRRVymbiQ0PM4wTid0ll4otFvDxIFdJ1dyMDEpo7jUetDmXH6wrbxPaqgqoHwl1CJKfD6czfchelX3ntabtldHVROe395ekLg7P2JtSC60iCXy4KSqOstkAaEsxWQ3ysdsOHRQm_cb2Ekg2WzNgLkA-owUS31rDu0PktlJRuRvjFRdF4OLwZJRBPk0WbV1SqAS-T5p5zJknoxE3Avbj6uKnsdwPrntPS0TZejEZdwqAyo-g57dymC8rzeuR2SWLvqBcClfQAxvPoQuZXa8UBuOn6OCzpJpHWiuKc0j1H-7xGjMYxim2rS8APUM6eB5xu_18Ai3E2bjAxciCqfgZ_wcWUtIDX4KjaNEhVpG08aup9wI6ATU5twxiA6AKCvdtiRrAIesMZViwzG2s_WfM1FIqiio_bocNT_M5VjK-8arK9sAsXuOMrHbBXpUyetMrNUkqYFZp8yoGUYSK4VJYWuru7QuWPQTvoTTI8p7v-P_XLpbBkMziJcC3Lp4sh9gW6cNKIxf0PLXNJE6G3Tdf9nEGEEXsmFpfP5XxQ52wSlfQQ_kEoAHBbNs1gNAMzYifNk5dhuP5PXzyx-ronkivWY9urxnNwiV9VRROpUMpz1TDzzH9dpe5Zfu10FWRfKE7yjgx3nxzteLX8YKffWrBhYNDQgDhgFqq0CiV6Gt-oEezWlaX6KYvI0MqVe55rcGODQcaMjEinN99WySHcVLwxdeHRcCKrSqV1zfA1hdshLZ4MyEzWnUndHOzdyWvnlSpbzekHGW5o4aLznPOSkTzbqHYMIWRaobN6cpANd9z4cx3GQ6NhkqukTyMrwx5Lb47ThFvk1zDTR38DzQV-u6co-RqcyIB2_72d_blKp5SIh1o3bAqVrrYrY5JAVhn_Z9FwuvaBQSy6L4KsTorFz15mz2Ke6-SXe9eNnE5KfWOcCVXjEBlfwS66CSZrMOtujelw1_jBbqXvokitOIu6KBdF_e-zTEqka2LJoD9w9JowXsP0Rn9dwLq-x2WpHva30ua0eXBFNOvHoRJnmPnOMPOD6WlzOZfu4jJsS8Qki19wJB-Jp6NSlX1rwbkc1gMSP5mOk6_C0WeQSt0rIQbcypipIWzneLUspBbZJhEX4Yzn0hSAgGBt.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.1916.47 Safari/537.36' 'https://help.docsend.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)