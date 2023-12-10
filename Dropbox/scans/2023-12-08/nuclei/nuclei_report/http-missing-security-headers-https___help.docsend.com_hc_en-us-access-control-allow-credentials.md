### HTTP Missing Security Headers (http-missing-security-headers:access-control-allow-credentials) found on https://help.docsend.com

----
**Details**: **http-missing-security-headers:access-control-allow-credentials** matched at https://help.docsend.com

**Protocol**: HTTP

**Full URL**: https://help.docsend.com/hc/en-us

**Timestamp**: Sat Dec 9 14:55:13 +0000 UTC 2023

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
Host: help.docsend.com
User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.2309.372 Safari/537.36
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
Cf-Ray: 832e167be97e2a35-CDG
Content-Type: text/html; charset=UTF-8
Cross-Origin-Embedder-Policy: require-corp
Cross-Origin-Opener-Policy: same-origin
Cross-Origin-Resource-Policy: same-origin
Date: Sat, 09 Dec 2023 14:55:13 GMT
Expires: Thu, 01 Jan 1970 00:00:01 GMT
Nel: {"success_fraction":0.01,"report_to":"cf-nel","max_age":604800}
Origin-Agent-Cluster: ?1
Permissions-Policy: accelerometer=(),autoplay=(),browsing-topics=(),camera=(),clipboard-read=(),clipboard-write=(),geolocation=(),gyroscope=(),hid=(),interest-cohort=(),magnetometer=(),microphone=(),payment=(),publickey-credentials-get=(),screen-wake-lock=(),serial=(),sync-xhr=(),usb=()
Referrer-Policy: same-origin
Report-To: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v3?s=Ye76XTQQI%2FpXr%2Bqg%2BremtQg2POJP7LLaq1yOvaF7LIovQHecXvs6Fx222Egppb0o72pES%2FbWjaGQXhd3xuwhZE0p2VeD5mxp7SmdFNvWdZi5xSN5bH5qvKXaCwwAYvQ0YOY%3D"}],"group":"cf-nel","max_age":604800}
Server: cloudflare
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html lang="en-US"><head><title>Just a moment...</title><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta name="robots" content="noindex,nofollow"><meta name="viewport" content="width=device-width,initial-scale=1"><link href="/cdn-cgi/styles/challenges.css" rel="stylesheet"><meta http-equiv="refresh" content="375"></head><body class="no-js"><div class="main-wrapper" role="main"><div class="main-content"><noscript><div id="challenge-error-title"><div class="h2"><span class="icon-wrapper"><div class="heading-icon warning-icon"></div></span><span id="challenge-error-text">Enable JavaScript and cookies to continue</span></div></div></noscript></div></div><script>(function(){window._cf_chl_opt={cvId: '2',cZone: "help.docsend.com",cType: 'managed',cNounce: '7092',cRay: '832e167be97e2a35',cHash: 'd09608e69779b07',cUPMDTk: "\/hc\/en-us?__cf_chl_tk=VedbPzDvjkzyqBdoOKJ8pytX7ojtEwyxSUZzPfx5ILw-1702133713-0-gaNycGzNC-U",cFPWv: 'b',cTTimeMs: '1000',cMTimeMs: '375000',cTplV: 5,cTplB: 'cf',cK: "visitor-time",fa: "\/hc\/en-us?__cf_chl_f_tk=VedbPzDvjkzyqBdoOKJ8pytX7ojtEwyxSUZzPfx5ILw-1702133713-0-gaNycGzNC-U",md: "pKYSl1Jx_UxU76bnHlG3xai.dgSmRPlWHrUXoGE7xFQ-1702133713-0-AU54wzw4UFj3Xm9PrVhWM5EaZU85F58mFNWWCWG-BbXEN6JOedTXcewT5D8-FXs6MTKz_eFOTAIpDUFCiu1FQ7q65C1lI0OCt4p0l7YXhK7q50-1TQd5uN7CGuZZ8hI0s-yYrnrXEtjoEkpvBoWHsU9cqRR4G-jfZHlTL19naPB0mLpwwjFUCCrhrNoG2xIBMCaCizWUsQiGWf7x5Ekk7RJ6O4udBaBddCNg-tB-2oFpO0VDkNL99-872FxWjD5O5mK-MYWtO8rTf2-Kck9QPzGzqfsVqZuOasN5oOysaQiL4ckxcJx_Kc3Hsc1L1x2m6DDC7BsLuBy37DJE7ngEbJ_RDlSEUPULInYcFi5sRF88clNhVb2g2B3gnrOHlpO0grg65iPaCLaJtVXIzPlEt7kRpYMQL6pZKqZPhgO7ergXFtGQgGz6IAemZ8PqIkt94aqb1Fl4Q3OJJZnugfAqNUhS1xAVl302oKPKff3F9W_Tx4jTfFiNX3cLVeQ16nE_3TL0qOiIqY0DRCZvXuvpI6yTV1tSpgFfyPi2_athiFY1TIPEcx_OQVQFOYF4YbxtyX7oPpP_VVSz9OHgzBtsJ5yKYpfSz67NDl12kTHm2Nd6j3VhIBi33CNLov-TGfMJzug1sWMsSf6nrJ5iSFbTXm4qLxVe6LngmHrIA_Jn_fn15g7osFnvuj7qI39UKUl6fb16i5m215SU_ISpmB8bRQrRRS8ANBVWmfSOwzJu5oCQPLjrOsMxcaepFcv7VNQ8rsfYrUkchFp7C4QRDDukuPhqWaw1xcLXxUHsq7ot7XgbcP-1uE-kmloBKr5mxorIALStlrAxakJgYrco_ZwHyNCFvBlQYUdbB1Gfn6IVCcQpNfNYeeVfwiZIz3zcUAMskhxSQF0w8_2ws00gCl3EdQy460szAYl0xB6Fe_POGbLOrCBaQpTWUyPOozus5uAgzPeucP_GiM-pvcAa9pW9pbRbjKEyOCQyNEp_brxYUa-htqHSAtifP8Po6ch5FcFrv3qYVRXmeXb-HFT6moHqR2vrKYYzV81C3tg8zCWzWX70WtL0FB0bp66aEznLugQKKYlcztKYn0fagZW39PvYg0Tg6uuhgxh27TO99-59rka-NchdvZwRz_XnRWJdg9EgSSGSI9BSwCd82X7sGi5ZuIGyBOxJuH1uZ6-NXr6fieaydd6Fx7_Zuri09NVV_wxmd884Zm9aVNKdaqDgi40W9wf3uOi6gxURwVJKfxXnc0vmGP0ivcw2s7RJqhnOsTAgfCvseoftFxF2L0M24gVoibUrFIys_2tsOzkDghOIY7poIQL3hDDOqZGA4J4QignVWtEYdrdEXIA_6yJdUWokHslXWEBdfI0D67JdM5jboaqnYUajp7msFbT3C45EQrcHXIqYEIOGhA80Cm3SifSZPCThNHlMkcOgkVf7s64xa-O1YzRNqfazOVA6wr3Uxq3-0Uwnmqz0mzq7ocmCm9cV3A20k3LHJya97Daa8SajlPAhrx3Em1Iysmrz0hmWwG-UKK_CgL4_VThz5PAltRGoEnbvWrJQes7jnUDQq5H8QRMp56jD3LXEupz-OZDFSPmWAxFqo_lhY9D9RZhdhoevbUa9eCjtVtW86qv67dAKwvVKIx6sAh72kogmStCh2bFQvuoyLdBGPPDZDki0ANcYGZ_M6LESTCBZNI1-MaBiGFBhoUZjBMcHyOgrQBq2ZpyzA0Ket1Cj5kAc7SoFlxjHcUz4bLzEvbu_0PpVXT29RT3f0Zj3r1teqV5k9OWo9FYk3fRCT5HgQJOqkhcvV4KfWSaN8t2ZP_7bSviq-icWFzKJbLnoqtLjOY0JGHsq5BhHA6FQ-EA4c040q4BZuVkNrXHplROXtbUnUbe08ZqB5xONhP6vtDSzlkRvD3RHS-viUF6WM9vU7MDAwqkYZTkO_uZW40hG_asR7GMKrqZHYxvcuqAWeXr_H_OUWSWQjcNqNMvCofYzDwwUWdIetKOPAdT3Lur6HuiwrmaN_bispKU-5TSrT98e1HUqMcqbMNY_CM1k2HgTd43d6VvkGN-nstsyywbOmA8nAi7B_ZaMA1gAcA9sYFJ3XlqtJXjTXqB0I-qFxKpzFef6MsNoIBLIcVrf9vqwTc1FDlsABjiBYGw-MBN6b_PdHGtkkxkPvNNCqaZuPqD5iH4VjypK9dr9kw963wmRyswTk6z19E-f3vOvK5CQatfI8COxXWs149KoDL5HGZE09ttdxzBOe0on_BAF4bTUwimpiL9KNQzZ8alBTEUzel0rjbDJ6bmcZIQwNxvjN0lbUr3kHzJ0jRypfUqO7LGJpi1PQsR0amXTdRNvBOJDzPnV3tWUuTqyTneAq_0VWBMeMzSiB0nxYUcHP0IvpB9cFafhfLuUqFrl5Qi9LNJOu_hIgAJQQm-uv8LKkZYg5N59TL3MW-yq1hdsOzX7LGJqYBEggHkCkaCHpfNSfp1NlkdXRw-tFPCGs5VSy2RNZ95XbNv6SZwUbd85mhFJG653J8MW32a4Fe9LGU6TxyIBw3TAVdP7jhVS7suZUJbQukDB_7D1Jde_kBzbNyVCrXkSj4VAoi8zYLPTh-BhKIuXyn9cGtwwYo2tgAyzEEraiGcR8cSipU.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.2309.372 Safari/537.36' 'https://help.docsend.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)