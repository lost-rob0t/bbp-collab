### CSP Not Enforced (missing-csp) found on https://faq.hellosign.com

----
**Details**: **missing-csp** matched at https://faq.hellosign.com

**Protocol**: HTTP

**Full URL**: https://faq.hellosign.com/hc/en-gb

**Timestamp**: Sat Dec 9 08:23:40 +0000 UTC 2023

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
Host: faq.hellosign.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/37.0.2062.124 Safari/537.36
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
Cf-Ray: 832bd8e90a0a01f1-CDG
Content-Type: text/html; charset=UTF-8
Cross-Origin-Embedder-Policy: require-corp
Cross-Origin-Opener-Policy: same-origin
Cross-Origin-Resource-Policy: same-origin
Date: Sat, 09 Dec 2023 08:23:39 GMT
Expires: Thu, 01 Jan 1970 00:00:01 GMT
Nel: {"success_fraction":0.01,"report_to":"cf-nel","max_age":604800}
Origin-Agent-Cluster: ?1
Permissions-Policy: accelerometer=(),autoplay=(),browsing-topics=(),camera=(),clipboard-read=(),clipboard-write=(),geolocation=(),gyroscope=(),hid=(),interest-cohort=(),magnetometer=(),microphone=(),payment=(),publickey-credentials-get=(),screen-wake-lock=(),serial=(),sync-xhr=(),usb=()
Referrer-Policy: same-origin
Report-To: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v3?s=ouErC%2B6u4%2FqZA3RHO9zaisu9Js44W19momZYvc4erqrP4F3x0e4wuPxBL1bgOUY7sS%2FFbh8Qn5BtjqGLFwVG0vbxfvhChtxudyf%2BqRdM67607oRR%2BRWDjusxFmIO9LWeH%2Fqa"}],"group":"cf-nel","max_age":604800}
Server: cloudflare
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html lang="en-US"><head><title>Just a moment...</title><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta name="robots" content="noindex,nofollow"><meta name="viewport" content="width=device-width,initial-scale=1"><link href="/cdn-cgi/styles/challenges.css" rel="stylesheet"><meta http-equiv="refresh" content="375"></head><body class="no-js"><div class="main-wrapper" role="main"><div class="main-content"><noscript><div id="challenge-error-title"><div class="h2"><span class="icon-wrapper"><div class="heading-icon warning-icon"></div></span><span id="challenge-error-text">Enable JavaScript and cookies to continue</span></div></div></noscript></div></div><script>(function(){window._cf_chl_opt={cvId: '2',cZone: "faq.hellosign.com",cType: 'managed',cNounce: '8765',cRay: '832bd8e90a0a01f1',cHash: 'b36fbb042925433',cUPMDTk: "\/hc\/en-gb?__cf_chl_tk=9_5S_IMR5ZHoxJuyqtgPStZOSkKmObpt6Ox8G0MrNMg-1702110219-0-gaNycGzNC-U",cFPWv: 'b',cTTimeMs: '1000',cMTimeMs: '375000',cTplV: 5,cTplB: 'cf',cK: "visitor-time",fa: "\/hc\/en-gb?__cf_chl_f_tk=9_5S_IMR5ZHoxJuyqtgPStZOSkKmObpt6Ox8G0MrNMg-1702110219-0-gaNycGzNC-U",md: "fzP_MTgc07WcjV7VJw_lVNT6pSlAgMbZJrZ1.V3vHgo-1702110219-0-AesP22quAWX9h8h-KUBERET1O9cFSxJShD7OjNpPkGcGgCHA2o8bjt5yTXVlZQ_iA90U-dPUkDVkhZFFY6YUL5ejwis4rMCzL3a2kzJ3EXRvYI0kaCPvR03EwZRxbukXXQfK7C_sZ4TrzYEazpHLimt2gIONgMHuzX-cs3c1xoBfK3s7FRwXoRFA8AsE--g0v-t0e6D0gHjHSv_sY4ibU9hnSAmnVayHHURvHwh02ss3X9prRR5jTue9aQ1Ovu8UAxbk1WkZY2dSaGMabb8r7qPGaqoa12C3LgO1WTrCmS5DL4n0USD6-Gz6MfQZn16b6ty6cipXYClbuwGtD0DmyFJlo7MaduaAW6btnU7mUy_UjZ_qFmKaLlabXY2HOlQXEhY4z8dJTeogZDvr4iAoPcDxIzGhfAnukBPjzilWSyl_A-7nYsaqtCiGvWw-vL_3V2zJFU6kSZdTp4IUFjNLjAhizMHHJJJzYkgfNl95xsrIbq85SxbwBAMpgVVdr2CEZMfPSm4sD-iF7IugcFWeOsbiO5mNShmfruM9P-6WLnbGkor53HEwjFdS2XRkUd7TcjgfCHsr10wYfX70ChLos_iJT9ph23MtF8skTKDTXA0o641QfvDPsUCUY0hX2zJXcpJGOyQpiV9q4P8JNJCxWN3ZbLBJXFwjy6ZWcZnJl_4_HdHNcoQc3mu3Lpnd9r9ii1XifmbAvOmlg7T4uHEo57SCmarBfqhPGDUp1hVyGT-FR9deVvB02QE-R4_AfpLybQ3F51t3t7A6Xns8Gq9fRpigF0wWKoOvUqiHlygQ6zWDDPdtJJjAJjFqpPSuX5yEvYgqSunyijaSGZT9x0bE5O6Uja0zpB_qSjXctdzvT-nm0rNmO-aD6qItnVoU7fKBmVJX2seVrDDQtD3JV1CIu_IQzc0-4NKP_AcxBU-DO-OwkBWX-5Y01SA5EKI3wAiLoSlRr_6PB69tk6w2x02jY29WQ2dARFfW8012VNXMhInIxWLpxynmC0v-qWKkIvhYme_WfaoI0D5gVMuT2ePd3IlX9Oh3ID5wA7q3vHAdVBYBy_4S27qYxxm-lPxxk3uGwIpGT6qBbgL4rzCqzD8Z0pX32D7P2DkmtNoAtmowFs-FljKjtHPP64Y91kLDEzqxlilg22iDhpTcytbkZsavLW9ProeZw6bqkQDSLCXYObU-UsJMgT7HsCrlr05f5ZaYxzv9QKG7bkDusEEcs__NT5f29x_yWUNRLhzxc2fyEkCn4MOCFyPpNw-JX26MNdxKNzrUmjzBg4FRi4z7NsIlsmiVsQX7Z0Qpl-zKg3Oil-Yipxbyfxs4HrBig5SoQ35EXv9Atepb0kIq3jkwjLuLLgdcX7wRqJFE017nHavDeyQiEa3j8ROT0oUUr6f_xQhFbDVS3e0odi-qIbSnCWeyCwT-9Lswf0qs0NRH051CGSvQtNCB1CXnlNWgthBMfatb0fJmjDwPKLC0hyBksXzLxpBmR92FZmaiMrnUNf6OEvg9KbNCIxpHMm_uiUjP7tCYgQ3VSMKMbV0rlReBZb39EMYvJ5WQ-51ekuuC7O2qw8J6gR2wy6tLIj8GdwOr5odzcM4EpsnHclK4roiHI1_MmWZOfLfFFP3PIQ49lQs1gtMcZor_BxkM--ruBG-kU2MnjtAXkglNpPkfQ-ZsMYGEuGqp91TaNmKOpdWUmleyGOjto3YWDyr1SDXGbqF2mvF9_PTpBtKCsekg-SRT3oER9ifllFwKUV3V513E9tGiCVZ0RwfjF_vFXa-fAzRs0c6Jo5WSQDP6QOQsmAst8W6kkHfKWBcsleBjhe7786MxHfX4g66d5OdZK8tShdUU2MLyCPVlvIrVwdvIxTALYrkbqt2pTX9cFQDR9gQTUgVgEQGnkkeAseBGKbqjFX_vljxdqv3tmywptkUtY55gUKPNEZRS5x6DA8qG2D7Xl3B_FwJwkqUgZ7aUnDjvCvwLn25c_nwLCZzQUIXlkZIVT667oh8URYlVXfjp4A_RuGo3ToFPpzzdajIOzkhrnH9mfLAFvu1PGQnLBIzwcsgIolccB4LJjoVwxR9c0ca6SOXUU2USUZN7xjhv64YxUbcz126VVr2tLWOHnFQuXlr1ljKnIO2a9Y-H1dYzDOMTJPWJ-CWq_vtD1aLDPYUEcF-QpmXfrCWWHWTLGFvYedy_ohAFuQ1rQfA1Ar588sckorN_Jj_6nzxdpcMIT6DhpzJepgZhIoa1_PEWnF7YUZZ5uDqm8oc_dIOjRNLB_jGR16H72yZsYDjPuQFb22QdjZyFWyUObZSrImC_rEq2Dkra4Z3xhnmqlPPlc_zgiXfq0vMIkTB2AFMIplkgn4g5VtH6yxy5AIjFiaiqVcofr2la5DMtz-OUOLNWJcaSParCqGvXeQ5VxWGG768bFNPvdpE9GKxFOp8-EFcYZSOaXq5GNK1SjAM_iCvyF_l8oQlQmBRgDNJxxmmR_UUSFIzyvOylQeR2GeQoRSe3q2Omg23aLktAt82KJ7Hf2mqWoP6TQGme9DprREfDvHSqXEhcZ8KnDUIa3njmMo8_JUNCr1HLBu7gmSD99A0E-cLgxc2Hl_SsHkQSnyEslsIuIyXaU-DrgB3LouwzBXjZ1KX.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/37.0.2062.124 Safari/537.36' 'https://faq.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)