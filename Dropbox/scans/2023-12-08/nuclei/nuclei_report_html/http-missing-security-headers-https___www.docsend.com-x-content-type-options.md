### HTTP Missing Security Headers (http-missing-security-headers:x-content-type-options) found on https://www.docsend.com

----
**Details**: **http-missing-security-headers:x-content-type-options** matched at https://www.docsend.com

**Protocol**: HTTP

**Full URL**: https://www.docsend.com

**Timestamp**: Sat Dec 9 14:56:11 +0000 UTC 2023

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
Host: www.docsend.com
User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.67 Safari/537.36
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
Cf-Ray: 832e17e90bc2025f-CDG
Content-Type: text/html; charset=UTF-8
Cross-Origin-Embedder-Policy: require-corp
Cross-Origin-Opener-Policy: same-origin
Cross-Origin-Resource-Policy: same-origin
Date: Sat, 09 Dec 2023 14:56:11 GMT
Expires: Thu, 01 Jan 1970 00:00:01 GMT
Origin-Agent-Cluster: ?1
Permissions-Policy: accelerometer=(),autoplay=(),browsing-topics=(),camera=(),clipboard-read=(),clipboard-write=(),geolocation=(),gyroscope=(),hid=(),interest-cohort=(),magnetometer=(),microphone=(),payment=(),publickey-credentials-get=(),screen-wake-lock=(),serial=(),sync-xhr=(),usb=()
Referrer-Policy: same-origin
Server: cloudflare
Set-Cookie: __cf_bm=UQytEVnt3ckuhVubGx4EAxkiKGU6G4FkWRoudiX.Gug-1702133771-0-AaNsckEuSjitSA7MbR79C+MY9DgiIN+GsvYD20jsOemzFIwTAqy5YNCB6nXpAnUmwXB3qJ4OQeqyDWaBNm4yypE=; path=/; expires=Sat, 09-Dec-23 15:26:11 GMT; domain=.docsend.com; HttpOnly; Secure; SameSite=None
Strict-Transport-Security: max-age=31536000; includeSubDomains; preload
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html lang="en-US"><head><title>Just a moment...</title><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta name="robots" content="noindex,nofollow"><meta name="viewport" content="width=device-width,initial-scale=1"><link href="/cdn-cgi/styles/challenges.css" rel="stylesheet"><meta http-equiv="refresh" content="375"></head><body class="no-js"><div class="main-wrapper" role="main"><div class="main-content"><noscript><div id="challenge-error-title"><div class="h2"><span class="icon-wrapper"><div class="heading-icon warning-icon"></div></span><span id="challenge-error-text">Enable JavaScript and cookies to continue</span></div></div></noscript></div></div><script>(function(){window._cf_chl_opt={cvId: '2',cZone: "www.docsend.com",cType: 'managed',cNounce: '22424',cRay: '832e17e90bc2025f',cHash: 'a8a16fb321c9715',cUPMDTk: "\/?__cf_chl_tk=19XBTVg7_BYeq7Jv622R5mi4BJOJ9XTJRKkjaROSn5Q-1702133771-0-gaNycGzNCiU",cFPWv: 'b',cTTimeMs: '1000',cMTimeMs: '375000',cTplV: 5,cTplB: 'cf',cK: "visitor-time",fa: "\/?__cf_chl_f_tk=19XBTVg7_BYeq7Jv622R5mi4BJOJ9XTJRKkjaROSn5Q-1702133771-0-gaNycGzNCiU",md: "j8scvB3yN9Q04BXty5njGV8vELgi9lK5GiFDJbkcYPI-1702133771-0-AQWN9Ph6EbHGVqtyhZ8nGNAw-6MeRm-dWv44Jfa3gm3N2wE15kfspx_Ds-6ao6wKOb8EMOmCgCnxljoRZBF43suY8Aw3qa20tR6mjVcn5qgCpf4fSBWTFiooxk1bXEauZ0W7dZuJSQfzoPyRNP1eDiGK-SZ-1kXEDeH8417e8jXPXHb52cPKcHQcpbsT_i7_tY0MroU2kqvyST36MM4h5DReTPyqiHrk511gbTEjmnSk5Ev6sNVfguaeXmYFAAhn7793t7ixWdcwaTSWTEEwoZRVJO2goJzYMHZLs1ukrMEoQpjoMgj7D5KJJsyYCmyTPgyQlpsGaJOX8axuXswGhrER0MFCM6-i-1siSPkYmK4dUTMMedcS0uBvMNngyOwZ1fosjkIrCZ57m4Pm1qRZWQkNqFeMd8EWUwT7TkkkBmMU_DCHSH8S8WtrA5rYK2yNqsMQp-PCqXNXuaVwYJIaVpEjrJJmE1VfiXtdMjgeRPyEfQyQ2891m9xISO_RIFY6MNR2m1Foxi7dge-yYMSnAyYB5bjxGXBHPX8h-6XBLN6msGj6ZFZ6MZzE0XO0AHkLZkykU2TbA4D4Qh6RxYW3mh2m2ISwuGjPk2M_kHHY7AbTqUgJWjhLp8L5cPGqhLzuLnEP317xP8yI4y8nLuUER4ORlx2YkixlGuexY17Vo8MYB4AbdWIXrV45rGlvW_58eINSAeooCbQ7Cnpa9PiMwab4djGwPRtHYaoobsY7iT5tXMJ47Cq2j8nKHFoeEOI1BnYeuh2Y16Eyy8mV7FfEDd_OhVYdKIICer0ZIjWKoOWjcWY7ujRwIMU3ehpZaWYRO7iE5yf_BcKqQzEzwHyZJiM6UynJkCkKj602Ny3QQ0YwNMXMize0yNixi9BCYe4BZXSYCe4Jco9ppz1MTIN3YBsjCQ2v3CMcEd7fLpvg4oDbeCjE9C2o4Ryu8yGqojGFKuBXuI1uDKX1mWvIHlsFE1HbNBkMDn0m0bVpAW_077aG_4d1DXN9MWLMr8Et2dg7WqJ1395LbbZE4PdC99kz3QVXjXkCzkq44k-_exotfTwdsYRwtre4-yVMp8qW0Dh3SP8j3UcqvYIshuFIRALQO3vlPnLONnKgycU0dzvJHHIQWj47HMGqdyfFfI95czHYXf98dMfckUzesEx25zthoYe-Yows7mTtg-nFbrWslejBB32BmoTVlDs6jFZ43NzcPlh6LFz9eNHjIsTBDbm4cJT1wY_-1dTf2XMumQCyvNOI9ltm_yI3wm9c9yVUFSvy-EhJ35t0uPjJqf8ED0yI5VG2ASQAC5GsNWJu1iR9Nf7AxdLuYyg6i8xIXBaEdzLx63BCs54o8bWsGh-FDXvVDdhzlbdMGe9TflBUoQz6Rnv3nYvaUaZkiCme6keQxxAVZmLzabfW2FSHO97hOaSck6ZTQuynug1rMjLwWkSqTo8kEIROJyo63_2bPG5b7GE2T366VI7nLKTlwPoyp8eF-1yXtVKgmnDZo_JN-21s1zaZMVyhCLPZVRWz1TR9rZnfeiPFqRCz4DkBnXHJ7H62JLZEXwT6vGw9KQCFCfPeFr9BceYU3xtSQaK4216eG5ilZFKgwA56YHfwBemDGf0cQVMByfVIH6II9SlOjklvl7dc53-hg2WgF0BaIhScodEpjbrqAipN0W4MKY8qbR__BnYB2QWYrumITHZvtWa4SdwQOueeCEaSWXoeWAoQ_woVmGEMnxtSoEQvgOcGkooajrjg3c_rpQH8d_u1tvSYygxyB2qDm4GD2MeynMXRzXvekhAKG5M4W_xF_OYJZJpmWmvIy2dlqMqDnqOFt_zlUVKVAPFpt3C33FexhuW4IPiVc2OajOsSAFujuGmqMvaF8CMXFIX-8YIVTq2FUWucYXO2fwy81X3HzW7LRrJqO-ngAxTfDcFSe1yBtewJakAMDNsfV9IR4oAHZU2ncg81nWcYojhNWatXZj6_rO9w2fJW2YOzlI23JdYgIlZQdq7Fd_17Ht6rnqyvY3fwktQ2lm2FED6n95zcLcRi5FP35pVn2XZ3IBe4ycTiq1jZqYIc7MPVBLKAQAKDqeNER2oS41MaWT68Db8op4S5-2YMGKuZthF4zkhRJDmt7KysUcPgZWN61v67xo7_UUWt11theivQvnNYZ3HOHene5GFA-K7qzustePNsrjepYrNIMXEx-QZ0bdbE4oJ74e1k6OxnOQJUn7V5Ofi9StqUtlwxEaDl7VPhr45g7wKpZsCuDLnYgvXRN5nOYuBeWy9IS5QggRaUKYTrw2KsSTmBqmCE9yleubegbcp4kMSXxOd7UEBDK1nMe36Jfy8TSR3MuM8z5UoCayKGLxgGcVDuoXcI-BlKEU0z3oUK0tZLWTFq05V1X-GVxVXQnjWnLmJa4rngM9OfDAY3O1h1Sf9UySBwQ32D555mYd8gG_RJmolaDXSHI8P0t4mCUWelp5jVj8yYvpkbjQzlSArKM9hrWixJ26qTYISnQHOWZ_giBCh04q0xuwHh1QrstsecL9uxg8wWdVVO",cRq: {ru: 'aHR0cHM6Ly93d3cuZG9jc2VuZC5jb20v',ra: 'TW96aWxsYS81LjAgKFdpbmRvd3MgTlQgNi4xOyBXT1c2NCkgQXBwbGV.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.67 Safari/537.36' 'https://www.docsend.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)