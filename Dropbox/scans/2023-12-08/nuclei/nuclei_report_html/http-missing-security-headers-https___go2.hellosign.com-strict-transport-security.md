### HTTP Missing Security Headers (http-missing-security-headers:strict-transport-security) found on https://go2.hellosign.com

----
**Details**: **http-missing-security-headers:strict-transport-security** matched at https://go2.hellosign.com

**Protocol**: HTTP

**Full URL**: https://go2.hellosign.com

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
Host: go2.hellosign.com
User-Agent: Mozilla/5.0 (Windows NT 6.3; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2225.0 Safari/537.36
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
Cf-Ray: 832e165f787f0281-CDG
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
Set-Cookie: __cf_bm=RqlGCWi5gYDHdxLG_V2MvV088KYgvfqFeF71i01GWog-1702133708-0-AR/NO9uBnD2UQDAlnJMN/au0pkgi+So0lTlZjSGQKiPkO7zOtoerwfgITvDZqvegpZQyA/CJiUrF+H+EcMnzGHI=; path=/; expires=Sat, 09-Dec-23 15:25:08 GMT; domain=.go2.hellosign.com; HttpOnly; Secure; SameSite=None
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html lang="en-US"><head><title>Just a moment...</title><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta name="robots" content="noindex,nofollow"><meta name="viewport" content="width=device-width,initial-scale=1"><link href="/cdn-cgi/styles/challenges.css" rel="stylesheet"><meta http-equiv="refresh" content="375"></head><body class="no-js"><div class="main-wrapper" role="main"><div class="main-content"><noscript><div id="challenge-error-title"><div class="h2"><span class="icon-wrapper"><div class="heading-icon warning-icon"></div></span><span id="challenge-error-text">Enable JavaScript and cookies to continue</span></div></div></noscript></div></div><script>(function(){window._cf_chl_opt={cvId: '2',cZone: "go2.hellosign.com",cType: 'managed',cNounce: '98251',cRay: '832e165f787f0281',cHash: '0aa60a3e50ba448',cUPMDTk: "\/?__cf_chl_tk=DbkHLA8MFawUaFsxI2gjNRtQEyj4P.ubWUfutqa6wc0-1702133708-0-gaNycGzNCjs",cFPWv: 'b',cTTimeMs: '1000',cMTimeMs: '375000',cTplV: 5,cTplB: 'cf',cK: "visitor-time",fa: "\/?__cf_chl_f_tk=DbkHLA8MFawUaFsxI2gjNRtQEyj4P.ubWUfutqa6wc0-1702133708-0-gaNycGzNCjs",md: "7Q.wnLuT7.sguZIm5mWvueLSIBvWHHZAPSrdqsHEHH0-1702133708-0-ARa5ExzIr8dYtQVskP-vr7nGNweDnn30eXetOAMJaRBCOg7pKxWOkQLlc4ah93TLdkMoadLsW69xh7DxDeW92FJdPqOlkB2u4uY077dGe12g9fUrjTmq8BLCjHg1GZBiBl7ti-MqA75yp10wCgAJWEEJ_YoRtRKBHSfVIkPVNCuoCQhMqWcJ-1ehNDCoKnmt6yFTbQ-cydGFsQUrtmoyUAsNU8gyjwOr1T70CG-Ai1XXWNwYvoqO-qTsR6spVhtoW3K60Sq_uWtrmCvxQ9n7o7zz6qPtHxMffSLfQIDZyOFubqIZ6dXilK6M3lulotffzMJeggojQY67eoVpFi4e8tt8S2CtZ8HWMx0Lemjypc53UQk1eMGBSmq3YWNwmBrUd4boU1HKFr92TBnMMkDH6MTU2RxadBTiX9LBZqDH1sQOlGC1l5eWikTbf9Wc9eL5lEzgDvGUbj4gpHDbp7fgvHL20gmiDcO3om00UAznQZYeAaCMZiPIfK9v9BglMYt9mMYk5ADWOcPTr4e2I_mfPktX2D5EkQBQtwh_5D1pCoRba1YGdaOD0EwyQ8Ttzipx241_3ePB4UqfiBtCv89dNqfQTAm2HAJFw0OaK2oXV8AR-UWg4cF501yABtouRDoKFN32TLw2R_-0UA_VdFB6Fxzob4o_RPAFoK9XUexitdLHqnNtwXjMQvHtJBXrJeyYsc3AWdU6Lvj6BvFSoH2MuhH2Y8AgvTrPghYBKsbtisNnGv2GMyIJcoZw0CIyKxcxMkB1NPyjCHUilg3pRf1O00cawRHvSJZbHuVXQLh7KS0RhEl59PoouU-2oCaTevuatYVWYBbnyEtnQWzfVfsW6dPiAy9i0_afUGIabCPqc_Bvd-XV_30Jese933wUm7n9BCDjSRHm7NPtXKfWNclB-f1N2pD3v-cIzHEOAq28G0GabRdL5QMRn0_4dcFF0DtVcqoMjzfB6LWX6_H2zrWRhE2c4xmqdIHOb8mk6lDEoXzmEL49mJ36xBqyMeqpzwHVFG3F-rBf1LmbEHiewsd1hg3pbErCjKGOcO2Eb4WxNVOCh6TTl5YLhEatdQBKbUoz4XQxaOkltxUDHSe9g6b6wW9_gjsqOw3mI_wfaG_IauCXmUQjjA-ZjATIfmh2RYyoPEb49jTcdlz-yv4efqwIyssUtXphe9qburfYjLT-BBl_sNqJEksRd3v8SCEmiQtw7Ko3ivpYEGlqOc7E025iVzSgjAueiFa4p2rxApw-Z0u9cM0LfrhHHLX3WI_2G2_4PEmgTObeBVP8jD7YZLKq9bGRkXUYdjsxfIKbGnzx2efR2kqAFqSQX4y_dA-y-4OHchqjy9f3qDwKzHwJMaZRjrb3zkpdVrlzn4N7H70mkH7kMm0XpXsvLs1XnfDYI7r6QoJ5EWMsXh_2bVWmqTtIGldFgxUuF3HrDHMRQyXwYZ2rHcVjFDCSYuBTB0P1I8jNEnDhDHwzJNpgYRpWwUUL9KP696e7DdRvtBXvVAyzE0KgX_wMgoB_HLtvIb8AJ6tK7BlVD9lI4VRhHzea3pXx19Z5FoNfNW4Huu5sI0rU2Y8G3RY2dO3DWTqOMnRWY0xG1ByKoWi5r8cAs-BPFiPyZZzI0e12M1WWCY90oey5j5rI_QKFgKHvFdBLAJMrn_1XTOvqTV0iqELpMXl6XIkgFGKei6CkeYbv84mwKFcQuj4t8ASrxvmpXA8rWT3pl1MR7ETzIH2YipX6QuyC73bfu7VzNS7hig1YPMTUZqGxPEi1OQqrbefKGIHAtBhF8sIdKs8FjdRz9TrFPynay1VL_bQdKhMvhtD_uPXC6uJtdjNFKUPXalRth5m9R7pV1Uyr9fVdJ4HNcHo1JFmwsKTu4qPqInWh-fkNfM_eTtm1G_HrJMY-j73UyU3UKupdCC38ai3CYoNoQM86boZwuQs_dqNm8h7v2E0ulCbth_34gMRzFjHqnWLyuT4OhczQfqQ2ixAjahHzFpk2cFdC59gJBGmw6Lw5ePcluGIhenv_pta77sEI0zfrO-ouo64A7R-nOasiIc3JBAgjaTLrcBaOytfQKzbpR2ML55GKZYIb3C3YiMsvY4S0FF15bZBQT1SLLRoXPhk2AbFeAPE1EeoIPFxjo1IJC5dCkbJsOqrDYRdjbLeniMcDhuCVpaXR2pbi_C8nYHtqjvj0idv3DQiuvgLWUn6J15TeJIhlzAfqSKpq9019lddAaPPC75Z6-T8r7DgwhyQ4y7SdzbPSUazuIuuTBOFmRQmahoz1z_ySD2U6jpr4esFzWV8j-AcBiTMBpKNvyH1prptpgZ9hTz57gCyoG8XkqylSvfjc8CERH_asSNgInyRu7tZlfYEMf6LUZhI9L07h1XQxjAUJ0Wdv_hZZSV3CZDzf70DVRF6ljMjLo-Gnt6EFBFGyFyZjHb5-CCA8MqU-9TKfP0HyYDVZRhKIUK_6jun9uxbwJzTZYQG_d0KAqqV1WhYu5HRRl8Q_lQFHHNVbiteDBqNpW1v1BmXm8fCeW0CC0lVs3TXBy6jHnPbhO3Wzm0rydOhk1zqj0w",cRq: {ru: 'aHR0cHM6Ly9nbzIuaGVsbG9zaWduLmNvbS8=',ra: 'TW96aWxsYS81LjAgKFdpbmRvd3MgTlQgNi4zOyBXT1c2NCkgQXBwbGVXZWJLaXQvNTM3LjM2IChLSFRNTCwgbGlrZSBHZW.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.3; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2225.0 Safari/537.36' 'https://go2.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)