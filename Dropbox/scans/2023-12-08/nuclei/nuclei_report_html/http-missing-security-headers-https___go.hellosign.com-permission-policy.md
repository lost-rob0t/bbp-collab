### HTTP Missing Security Headers (http-missing-security-headers:permission-policy) found on https://go.hellosign.com

----
**Details**: **http-missing-security-headers:permission-policy** matched at https://go.hellosign.com

**Protocol**: HTTP

**Full URL**: https://go.hellosign.com

**Timestamp**: Sat Dec 9 14:55:08 +0000 UTC 2023

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
Host: go.hellosign.com
User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.67 Safari/537.36
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
Cf-Ray: 832e165f9c68026f-CDG
Content-Type: text/html; charset=UTF-8
Cross-Origin-Embedder-Policy: require-corp
Cross-Origin-Opener-Policy: same-origin
Cross-Origin-Resource-Policy: same-origin
Date: Sat, 09 Dec 2023 14:55:08 GMT
Expires: Thu, 01 Jan 1970 00:00:01 GMT
Origin-Agent-Cluster: ?1
Permissions-Policy: accelerometer=(),autoplay=(),browsing-topics=(),camera=(),clipboard-read=(),clipboard-write=(),geolocation=(),gyroscope=(),hid=(),interest-cohort=(),magnetometer=(),microphone=(),payment=(),publickey-credentials-get=(),screen-wake-lock=(),serial=(),sync-xhr=(),usb=()
Referrer-Policy: same-origin
Server: cloudflare
Set-Cookie: __cf_bm=JpKnOnvcaaZvEhU.EmY3SU_QhuJN7nP5qZ8nzy0czx8-1702133708-0-AUCwGDP0NbuA50a/3sslCwChlwaYCmsKOIwDf4ReQZGQxE9H6bGbElCOR7ocVGrvCXGjOyCSt+m9K2aNN0GFzHg=; path=/; expires=Sat, 09-Dec-23 15:25:08 GMT; domain=.go.hellosign.com; HttpOnly; Secure; SameSite=None
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html lang="en-US"><head><title>Just a moment...</title><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta name="robots" content="noindex,nofollow"><meta name="viewport" content="width=device-width,initial-scale=1"><link href="/cdn-cgi/styles/challenges.css" rel="stylesheet"><meta http-equiv="refresh" content="375"></head><body class="no-js"><div class="main-wrapper" role="main"><div class="main-content"><noscript><div id="challenge-error-title"><div class="h2"><span class="icon-wrapper"><div class="heading-icon warning-icon"></div></span><span id="challenge-error-text">Enable JavaScript and cookies to continue</span></div></div></noscript></div></div><script>(function(){window._cf_chl_opt={cvId: '2',cZone: "go.hellosign.com",cType: 'managed',cNounce: '37171',cRay: '832e165f9c68026f',cHash: '5533ca94e993611',cUPMDTk: "\/?__cf_chl_tk=ortp2pMIT8tEo.aJ_x3LfE_SppVEuZ8IWEWNiMOKs1g-1702133708-0-gaNycGzNCiU",cFPWv: 'b',cTTimeMs: '1000',cMTimeMs: '375000',cTplV: 5,cTplB: 'cf',cK: "visitor-time",fa: "\/?__cf_chl_f_tk=ortp2pMIT8tEo.aJ_x3LfE_SppVEuZ8IWEWNiMOKs1g-1702133708-0-gaNycGzNCiU",md: "s5FDM6a.xqzT8.8TnKYA2qOVSpG3eW1UfBkssvJUJVY-1702133708-0-AQCsxYUu5jrJDmW-6seS1sPnEq3OxEBHiED3PZ_ZwZQc9BG05oBOOeKWoYnn0_kkK0lkz-MLOLFo7foPYJ3WkXvidLwzb5PzzsWoqPJra_jl4JQGVtGPGCG_QPrHRLM3gIxT0qQ8dbgFabHDroScTQTlCXNP1Vvu361cKo8teQGQTRWbcLBYzO-R9lGQD3GFnc6MOcNKmVWVxtHTzrgqHJFj1pgsQwJxv_SKw1hwbxPu7q4qCbMcXyBjQw3LrDfH64DdoOUjngFP2hEQ2_Hj-OU2OSB94qxQC7rdwNwZgvQp2Sro-Hpt9H_1hFP9sW23WCcYPsWk0bPbNaStZVUdLMSe0MLOq2dkRQDuTngirQcllBioAWfLjrhZxvSQjZzuoyKzIjkl4XiKfIJqZjUDnnGoVy24W7OHyEfecqpoG91zQwNagRtd6NNydp2WZ40cuEp0VaYO2VZnJXCOf4HDRTm-4_H_-64ua6a9AngTst-6QxrVrnrjQ6QFJ8YQJOwDX3elOZF4mMVb10twzoNfdcl-U9ahfAr-rytGVsBR_3bNRIXwXtIZ1BvV7qXMIa2paN6haNDzQE0VZ90vNjG2nd86Mb-GnIvAq1Uwd6OuGNsGrHV1hnLRRRJWb18N6G9R1Cremhy8GP4_blOhBbiC0DGaTJ6XSWpS48GpaieWj7N-tgTT8dynkv4vTiTx8mXjjGzgMyHVMe1-F9qarTE59GksPHBnDPithrsUi3vBGjxi3Ml29UXb9pz_wFzELdrjwEm5_nBR2XuogzYq0uZRQPVxHSmLovHPSIYfDq8kqIPsSgU2rF13tHdjTAop0JYEBsN5gzTJhuAhrVvZdqoOaRFckWd3Hb7o4QRpcZrmBh72m5w0GQ_t_0e4KvqMTUR24A5gnZhMTLhwFeLTMH3NsfTz8lDUYs48MjEzWZmIJ88aCqsxd-QnEad6h0JNt2qmYhSBd1nZtkABtmaK6Ey_vTjBjNhnQYVex100Zlr4DBF3-Ez2I2VQxxW7hpU-TNV25r_EBnfhLtKWQx6FS6klpNm8PoQzSARCCfZg4eATFCg9UFknfkWVNb-LMg9oNO4ZrzYJwcy93utUgrCzhiUEk76h8_vqsaicE1XEYOtJFnrxWhJchRsOPUyONsdn7qMXfiYyH0yDWY0hminDu8b5_9l3F877gaXgRaAQ6jEdkYZWBlTsRtaLsnTXopQShQxJy9tOJKnL0F9mQUvOQ-s_wsXgIToqX2zhqUp1BzM3BP9r8cgQ9d-nLm1cm2AzgR7w6rDP4A0U0ZLG9OAEgwqPyXTzKO7NNzoKbo2rZazyU-e0DcnXs5wQ5b2zNOZ__pdLzM7o6sEKVI2zZo8-g-1BKGNh0T8pK_MgQhhLjAAUoqUil9d0iUQNm2MvwIOAOqT0_oN4WYSQc0mXHs-ym7p7Wp31fP_OHDIvnM1F8MnpE4Rpl7rg3XMflXawoZHAs8kqBptKXRPmJjsyEUAxycqgZxD4N6CpUIb3FbJ5_Fj1gVEVXYV2gC-vZA8crDxAoZN4OQ0ulxqvjKin6kzBKkwNWYvvopUJC-1I4bwD6p88Y2cEuzrSN1CR0jBeriBTNsH8_Bp8BAwCSdLcrDgn9Puyt_SOy2Xtf7c7_4Dczy2w3Tv9Jq3sclIBSTVdW248hHHzDKEsEkgI269n5gApIfrDQozR7zar49ZX-64bIc1ARea9v64CKm6eDwYPsvOkqWbbkRmpM8WPsqO0yuzRer38KbiXI07BzMuLuUff0OAGAoD1IDV-t1JP0p2oBC7CJYy5cob38K8DRBN4Z2It3RoCfth8URZYVt9KtAVePXBtqwkQA45WkG9yFfm-aCYIcai_MzaYqZEPCTevHiL9A6WZbqKorHKMpkn1p9dowwpSXzJVdy2paQr7DR76yD6AKKC1DDaEbkZ2lwReSB7AZe16z8bnNn6nLDIU8Gs8LHqC-HzMoV09D7BQWG4FBS7mlDABBgBHlUwuxNMDXjLYpJE7LlZRwexbhks6_IQeUgcav-TXa5asSkMoTJIHgn6rkgT1-9HWtA8uemc6D_RnmWi45lHadOHw0-Ri24TUn1EdSjL4cjVzy27liWrpeTFAMVKiMRliTPKTbBDFJCSuMvLsUODNcsHUkC8zzBpsiVZwBihWsBoIDVUONct6CnKToDg15cUdUgKQVpF0g5c3HDLNZ1as6Ll1IYlA7qFO79vwjZsO_wYm8KLSF6MTXWeo2zLC-XuA0x_stAj97iRBZuQ0nzNJ5eRF77Tv5qsnEY8o4ewQM4r-TnZVHNkCxSlDleoVDTRXjRWh32YvQFKUj-enpImaebbh8XteLqs00Jx5nWsFIawXAEFXSw7_8PMaGZ7_SusaHWliSwFehVFE_9J53fdGEZIe_2yIz7w0VNq0GTjXfKlDsTa6Ri5Ctyug_jnkq_qf06UNVKszjFcIGWGahpVA25s7Q1ndfW5nmQZuJ1a-punU80dgBiixIQr6cMFt2GhKadQ7WW-GEMSEqSk22JiQpUOpLo-19kx5GqgJMLRr",cRq: {ru: 'aHR0cHM6Ly9nby5oZWxsb3NpZ24uY29tLw==',ra: 'TW96aWxsYS81LjAgKFdpbmRvd3MgTlQgNS4xKSBBcHBsZVdlYktpdC81MzcuMzYgKEtIVE1MLCBsaWtlIEdlY2tvKSBDaHJvbWUvMzYuMC4xOTg1LjY3IF.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.67 Safari/537.36' 'https://go.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)