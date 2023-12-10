### Strict Transport Security Not Enforced (missing-hsts) found on https://info2.hellosign.com

----
**Details**: **missing-hsts** matched at https://info2.hellosign.com

**Protocol**: HTTP

**Full URL**: https://info2.hellosign.com

**Timestamp**: Sat Dec 9 08:24:00 +0000 UTC 2023

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
Host: info2.hellosign.com
User-Agent: Mozilla/5.0 (Windows NT 6.4; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2225.0 Safari/537.36
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
Cf-Ray: 832bd96859bdd682-CDG
Content-Type: text/html; charset=UTF-8
Cross-Origin-Embedder-Policy: require-corp
Cross-Origin-Opener-Policy: same-origin
Cross-Origin-Resource-Policy: same-origin
Date: Sat, 09 Dec 2023 08:24:00 GMT
Expires: Thu, 01 Jan 1970 00:00:01 GMT
Origin-Agent-Cluster: ?1
Permissions-Policy: accelerometer=(),autoplay=(),browsing-topics=(),camera=(),clipboard-read=(),clipboard-write=(),geolocation=(),gyroscope=(),hid=(),interest-cohort=(),magnetometer=(),microphone=(),payment=(),publickey-credentials-get=(),screen-wake-lock=(),serial=(),sync-xhr=(),usb=()
Referrer-Policy: same-origin
Server: cloudflare
Set-Cookie: __cf_bm=q3Dm1PaCHLcX4gcagP9jhZJkegOe5gNuMbmCxNYul5A-1702110240-0-AZ3zlkTfApdwCyPFek55AOaaiBJV+h1lPYathXkJoPvJgq3gyBDr3KsBz7TSI5kTzgcRS57kxoZZtUxWnC1lDg4=; path=/; expires=Sat, 09-Dec-23 08:54:00 GMT; domain=.info2.hellosign.com; HttpOnly; Secure; SameSite=None
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html lang="en-US"><head><title>Just a moment...</title><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta name="robots" content="noindex,nofollow"><meta name="viewport" content="width=device-width,initial-scale=1"><link href="/cdn-cgi/styles/challenges.css" rel="stylesheet"><meta http-equiv="refresh" content="375"></head><body class="no-js"><div class="main-wrapper" role="main"><div class="main-content"><noscript><div id="challenge-error-title"><div class="h2"><span class="icon-wrapper"><div class="heading-icon warning-icon"></div></span><span id="challenge-error-text">Enable JavaScript and cookies to continue</span></div></div></noscript></div></div><script>(function(){window._cf_chl_opt={cvId: '2',cZone: "info2.hellosign.com",cType: 'managed',cNounce: '40026',cRay: '832bd96859bdd682',cHash: '6d86c665f39824a',cUPMDTk: "\/?__cf_chl_tk=yZm.qUzduhI__rOFUPkU5e_SAc2RtycPcl6BqDKj7es-1702110240-0-gaNycGzNCiU",cFPWv: 'b',cTTimeMs: '1000',cMTimeMs: '375000',cTplV: 5,cTplB: 'cf',cK: "visitor-time",fa: "\/?__cf_chl_f_tk=yZm.qUzduhI__rOFUPkU5e_SAc2RtycPcl6BqDKj7es-1702110240-0-gaNycGzNCiU",md: "460Dj4zoesgV8kRwqeuTvxPjDBkhwTRkLIRePPN2AXk-1702110240-0-AYmnUmx3INbW1whKZoMR5T_HOORM1W0Dk-sQtd4BCvYOTvexZiWGFRnioKCR0dhtN326hjAnLRicuFVm7Av-2tGhrq4ZQ2v-S1ed_BzgNgOXNX7a4ch2F0kc-8LZ-kX9Zz8RfkryiS3E5ig3em8eMaJEZ94y1xK7owTOsNsLyLUg7emFADgOk4l6u-NP5CAxkRysIsImvKhaByBG-7VIiPsrHKvu6ar8IciEvQ8N_YIfK5TFrDBnyxbKTxcwhjcqWR7NO_w058qkMctg9NXT0aNWnRIDxClkhrq6068gZtxvhib0WtrfBXF6v6Lkt0IO9imljFlCXe5NZdVr1ZS8AGoBP06aSrmtdiFR7IYeUbygAidGOs7J716CvrDTW8nspTKrYnURRk1Bk3TfAZ5cmHjBcN_qHfNN1puZXxgAUHhknnjlnqv9AXuU4NB8SVgI5_hoVbe65DqrdJqchflWu6B0a4wikisEPtR8uUBEXXg1vxAgNvs2FvcttOlilKOAKml6KzN63wlndwjGnV8jFmLRKQWWa3KPV5QrnFwRoTGtVrBdWTEcbpDPKlJ9AoVKyLA1Wv_m9waWGrI4mIqRqZ-2idUfLnHhYL9RCmtcw0GQbL738PUUnlCbQTWyAnPA3CyKbr4VftPFzx70m-2zVMLX0DmQD5bMVszqFe8geZ_VVb4P-IFjvpfwBpGrnAzxHLxumbBM2wsPefnazExxpHrbMFKvXNiLnSAF3kbWqIGFncKfLpianwc21oJoVq6dZW8mjefVif0pIjbhuaACD8rRwAWls6HVuS3e4NiQxLl5Q7ZmMVG6MHHtBorEGg4jgV1y1fhA_mkbY7RrDmELddw2Hji6FMbUrlURD4dmqPpwONPoAQgVeJdVqAGSPrZH3f8Ekaegln93QEzgtZFGboUi-CHbIGrKlVsoQfKxCTmdZ-_gvM3aZj4kVqmMEH7KslJ8xOx-BRoY2r3YXZ-wxPEqi-DGzbxOj3dMlF8v9wPh-tHkELrJT0q-LyOb9grjHtb5-Y-TVMs8BfEW6qew-RJiyjAa-U5HWpGUUUuNOQnb0goO4yVWqNLC19cr141jpf8aqBVtsIqf0PFHDlYi7UnbLJo7Om80Aqr-qu7q7zKVuQZ8A2AGEnAVTiwOgkKnkJKrbE_FfM8aP4NspXhOOcNAhrsGlFMqqNPZ6BKfqAsCTbAmxJ2CuFbG0V2dPemjuiaZ18qo7wYVCn13Cri12RZsq_ZEjNQstvDMMVPS0gP-5I8RAVVfQYCkU0CxnkJLPEbFzZ-MnjU6PLkCJzi9IdKKKO19fhM9mkDODBxWGaeWgfFMOfQ07zWiN89pDgBD7xD7OXcl6CvBP9NBimijMF_ZzcBwBpiJ2atTbMHZLrJiUew9zwZUU-QHrK3DCCOplbX_YYNFk-j4B-hUU5sshppuRx6_2JZhLRESz84xndf-fAgujwPAxoEpOPOVUpKoN6LGOHdJgnunjX-pTFNzurBvC__jaktuAob4ETRcVqq4wydn08Ht2zYsBjSaRNm88p7pAcEFRvCCShorNJA5W2lbER0CpL3SgGxBarokMSpSHD8XOKm0Wt1GJCDv6GNT7IFHKwb0_jlUhkNWqcER6TfpjJOqDHQc786lqN3EdGZXIe6glDFPjwfOFxE8Wh_c4Lg6pWuy7oVoPWV9SBEReLifv7hyAG0pym9s2yzZga5x7l-823jcvn5EGnsZYLlbyEBDllChWVaUUpZF-hytMZD9d9monOsbvKK9Jy6cg7oGP8xzXwZYdbCHYLcfQN28llh4aLOWo8C955kvtBKi-nsJpBPjUIuJqwwnwQd3bLoEXFbeg07VgjFe5P7y847_xy_eeG1JdZvFhiODiYBb72ZrMal_hHIqb2wuClPrpgtlbx7LLWTwz5vvOkBq-S60RMoxb_Q0EylD3Dcc1_VnAiU_ZaQsRlNWlbZxOxv3fymX-PPoRMLi4QEt0uuMtO3mPyeSrDf12t8JGwl7tdBGtKxuwGUjGvDS2f0KqbbzP9crotYtTwbV-YfAFYI-hBK8WqnABFb70l8yWwdTuZz1MI2lh_awvmKg1PtPaxrWj3cs0dmeWaeTArugbhlXQKmPWPGzkbeobe56K4_92V8cRt1E7HNXa_8iO78TBmSaDZZwFI_lERpfx-WaiyfKALjLHfkqE4zAwTTNnakuf111fMHwDFLw9IAZRdb6AeN1RJUa_BNR4nudAPAfT7HK55Oo3dOwSVCHZ78ifObzJgZ-2SN9gcm3SSPdsKzYnI2Z5IjRciMnA1C70nDDnZRA03nD9Yy3sa5WM3rlwZNOw0dzDWeaZYNVAk-0n4uMlk55gAE2V8qvoXjo0-TxMdo-p497S-chzHzoQazeSVgGKMiI7s-xMD7QbJFKJ9x3Se98oUmuqOtbzZILar2L0GZpLDoZIdpKV_G0yjTh_oOxXoWxPzHL6sWk5mCrCZW056ppxLKS8e5xcex2jGKDTINgeAt8cos095FcZLy9lmc2L5CP0Y0YcREcc5nSOk6lpFsHSygH",cRq: {ru: 'aHR0cHM6Ly9pbmZvMi5oZWxsb3NpZ24uY29tLw==',ra: 'TW96aWxsYS81LjAgKFdpbmRvd3MgTlQgNi40OyBXT1c2NCkgQXBwbGVXZWJLaXQvNTM3LjM2IChLSFRNTCwgbGlrZSBHZWNrbykgQ2hyb21l.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.4; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2225.0 Safari/537.36' 'https://info2.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)