### Strict Transport Security Not Enforced (missing-hsts) found on https://go.hellosign.com

----
**Details**: **missing-hsts** matched at https://go.hellosign.com

**Protocol**: HTTP

**Full URL**: https://go.hellosign.com

**Timestamp**: Sat Dec 9 08:23:55 +0000 UTC 2023

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
Host: go.hellosign.com
User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2227.0 Safari/537.36
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
Cf-Ray: 832bd9485b81021e-CDG
Content-Type: text/html; charset=UTF-8
Cross-Origin-Embedder-Policy: require-corp
Cross-Origin-Opener-Policy: same-origin
Cross-Origin-Resource-Policy: same-origin
Date: Sat, 09 Dec 2023 08:23:54 GMT
Expires: Thu, 01 Jan 1970 00:00:01 GMT
Origin-Agent-Cluster: ?1
Permissions-Policy: accelerometer=(),autoplay=(),browsing-topics=(),camera=(),clipboard-read=(),clipboard-write=(),geolocation=(),gyroscope=(),hid=(),interest-cohort=(),magnetometer=(),microphone=(),payment=(),publickey-credentials-get=(),screen-wake-lock=(),serial=(),sync-xhr=(),usb=()
Referrer-Policy: same-origin
Server: cloudflare
Set-Cookie: __cf_bm=osGW4_L4VeEfHSqYABrqFepzA.veOGjVHfRG_iP6SqE-1702110234-0-AQ+zkhCz2qYmcudBCd7Rdf30qNrktxctBZVULWhSKsOVFbrxBzJmetU9+Xo9HfrzAZMTpebEh5C4OyB9wL3eQwU=; path=/; expires=Sat, 09-Dec-23 08:53:54 GMT; domain=.go.hellosign.com; HttpOnly; Secure; SameSite=None
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html lang="en-US"><head><title>Just a moment...</title><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta name="robots" content="noindex,nofollow"><meta name="viewport" content="width=device-width,initial-scale=1"><link href="/cdn-cgi/styles/challenges.css" rel="stylesheet"><meta http-equiv="refresh" content="375"></head><body class="no-js"><div class="main-wrapper" role="main"><div class="main-content"><noscript><div id="challenge-error-title"><div class="h2"><span class="icon-wrapper"><div class="heading-icon warning-icon"></div></span><span id="challenge-error-text">Enable JavaScript and cookies to continue</span></div></div></noscript></div></div><script>(function(){window._cf_chl_opt={cvId: '2',cZone: "go.hellosign.com",cType: 'managed',cNounce: '14131',cRay: '832bd9485b81021e',cHash: 'e08da743a0955eb',cUPMDTk: "\/?__cf_chl_tk=LMuIstLXb4l0xtRZb4chSwgwq.aXnte667imdsRMG00-1702110234-0-gaNycGzNCjs",cFPWv: 'b',cTTimeMs: '1000',cMTimeMs: '375000',cTplV: 5,cTplB: 'cf',cK: "visitor-time",fa: "\/?__cf_chl_f_tk=LMuIstLXb4l0xtRZb4chSwgwq.aXnte667imdsRMG00-1702110234-0-gaNycGzNCjs",md: "Bkizoek8zBkbkTnrIKaJ4lG8KPpbBDtnqfwQWR7Ufm4-1702110234-0-ASqMPf2zGBwbo3JSxk5Tr3fIPUxsCtL_LQ24WK8svLGJp7e_qxhiIOj2socofvmgkDyCppUzKDxdo_MYObix-2tZzEFPzdF3lPwmMBNUz5uoLN6iJf20WJg-rA0MitG3yVYxuHwvGK0BtJWGcctvhCquEjIEMeBWgsuF6Hd2yk0_kjRKhWfEH8pKpxP0c-Owsu6oclmPEGCD0VMveqyfeDmC4OaydlJ65jQynavcM25hdQLVmFZCzi-XUDxN0VVl592L-ovFeWjyWbEm8VnLgALIg-BdJwjqDaetiejQcDluzZuYRrhG-BLMLvainYEKmnoU8jGQS35NoMD1M-tLtAMcynLxWN8VCKqcL46txr5y8JxtwdEIJFhNJwg9ziJXnWG69ny2tMPVne0JrykCnkPftIzOPm5FE7pNObV0Bisl63Ec-0t7BEGIWoe3a8oZCrR3Lup84gUq68IexQdOAwxhxlhA02KWqOpQKpFgVufihyedhmmyWD4dEY6je363nvc4TlW2XUfCX4JRwuwPopZ7wfLf3UUCPm1iStQq6YXH_hDaesYcqovVAUbSFr5Axo_Lxsp-V1Q7tucmpMBsngd3goaiaEpIDyAwZ1QSHGKE3G5wfgzMrWA-iVverrzhiWN1o1IiO6SpO6dn9KfMLbCHE7bXznKKrJ1icpOOwV6p5hkF9un4EeFv68m_5X5gZijMoY8s5TqX74lUmH1nomRS_gRev-TGQhqRT17YHa-dqetD72HhS9S1Ibotm0KqicoNK0yknp1OZ7OhzJTIXsi_PEBBkAjZ0ZM3WsbdGIRXoK_NBFGTh5n9_giaqZcndavpUm312BhF8Uy_wqBOxjnumQNQ1_xz2LobJOsSsiAK7tIu7HzVKPsdqDsr4AqbWKmV7iP3IsxBVViBpsN7T6Ljk7pl9csjLbUZ7Xq-oU8okzsVKhW8MmnKp1AkAgZlztC8xMrQ38dgE_nmO5EV86Q8WF_lUE9CZTEG747F6nF3VnJ5SzerfUkRY6T5WdM18evYXwuFu-K-wO-d6ISZrbCtFNfpo-1sGcdlvLI51WD2D51eX8kZQhVKBdKwLLW-FCX7fQwiRNvEWY0M8nDj9rhOj5sn0vR67sFBFAZIvdjb68pCX2P9Y956sxoP22MPcYUQgr1PhdtDU055uBSFMx_ymvTKeZi2zGQgC9snJ6RuECosL8WEUcO1uLyGYCQhkrp6kZ_9S56V37TdqqixDB_NGiv_mbUqOKCDocWnr2peNb6g4OWO3afdAOmAPd7ZeXf4gQRfOwn1Yjtwr2mnw9mvvKrCWjr7TO1t9VNxP-i_UvhddejX1nWCjwswXPV4IUvdrWJbXfObIUX2_OT-SeYi89udCX41XcQdYrJFDKaYgkDxahSYiwWYNgULtTOlkErcaJEuLdrAoHhqHLqTB3XVp_yNirF2vTJ5oObnaUeQsWvaFqSKJIQA4oqaoRv6oVH1BnovMD7WcOBzzkrA4fiXLp5RJnaaGTDyyIB1BqD-JMeWzAT6qcxrq081RTcXlk3on_-TZnXXR9O10pyOVTqj1zQ47EM8Eta4U2rrhcoKW_Bb0yRlZFMvAGgi7RpuDAT3v7JHTM9GvpOPgjelYmuM_D86YWjbA_QCgCNqT572_s2UJ_L-lbmNNMzVFAawhHHBidwwCdU8ewvY1tsNjA6Fc65x2EXdwwT4BWvFOGBtp5oK2V1Pa1YTPRTOuDmnsUEgZ8jSoYLy2VZesTnunG5qzjCkklxjEzdOQDlQkb5cazaUVP8zKilTPOev5ILYCbBxkkqdBN-FLtuR5MBx-XszLAx_JQZmWbKtMKcNRubjKsiRAvUAztU-VHhdzgol1psiP_tNsd5LUja8XrESUrfXJfaXp8L1ERqm57wJphiuQ9EA1FPngVXLl-12Ej4OI6R6NLMS57ZzdO7JwNyi4Ub6A-CvHys_otnfi4DQ3aI_xDwvziz6fhjbiiykbWyZI3B2W4TvWNOQIPi7_w5AGB-AM52JiwgS_qYkBt9I9Qr7Rrxc6KiqmOVtITNmuUBXvNWhD7F_C96IBb88E-4tJXztctNeNwsjTFWJ0SOKNM01DKmfDjZRDejMCnBw3nKZvUdhGCXF28U160nWL4yJHEvHGINCwxQGxGuJ_5Q_CvoNKah0HDoGEYha4qguT65MrXwlUCnGO6uk8OaPTy2LgVini_tX2gz0_o5xuLCr1d4KR7xvLYH4YtspmxLC7y35oD4JnjhTTMSNATKRrMrz0_dH9ozx2t0ptfHExiUxzFq-C18O-oZ-xVhidTyMd-eI1r0kftx6vOpgm_iVBPh2h5h-6EvcA7BQafHkAr3K_SaEhFfvjZ483hg9yKBLO-s0PLFYYaJFI5xYyP32xMrGxNsdlcY9wLHThHECsSj7V-skDy_F1WD5jCUUwCf5D-lmL2epn7h2clM2v20wCCk4hQdlZHa-3fOlDscGgpkrb-uqgOK4Hs5MPND2Td0hWzVFC0Z2qrts8lsIF3FiorkUGj5NMFOJy24GI4uyQqxtjYZ9m4D4gCQiJDumhlIWMEUGHg",cRq: {ru: 'aHR0cHM6Ly9nby5oZWxsb3NpZ24uY29tLw==',ra: 'TW96aWxsYS81LjAgKFdpbmRvd3MgTlQgNi4xOyBXT1c2NCkgQXBwbGVXZWJLaXQvNTM3LjM2IChLSFRNTCwgbGlrZSBHZWNr.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2227.0 Safari/537.36' 'https://go.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)