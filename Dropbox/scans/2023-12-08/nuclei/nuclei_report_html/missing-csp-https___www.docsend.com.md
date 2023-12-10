### CSP Not Enforced (missing-csp) found on https://www.docsend.com

----
**Details**: **missing-csp** matched at https://www.docsend.com

**Protocol**: HTTP

**Full URL**: https://www.docsend.com

**Timestamp**: Sat Dec 9 08:25:00 +0000 UTC 2023

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
Host: www.docsend.com
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
Cf-Ray: 832bdadebbedf8cd-CDG
Content-Type: text/html; charset=UTF-8
Cross-Origin-Embedder-Policy: require-corp
Cross-Origin-Opener-Policy: same-origin
Cross-Origin-Resource-Policy: same-origin
Date: Sat, 09 Dec 2023 08:24:59 GMT
Expires: Thu, 01 Jan 1970 00:00:01 GMT
Origin-Agent-Cluster: ?1
Permissions-Policy: accelerometer=(),autoplay=(),browsing-topics=(),camera=(),clipboard-read=(),clipboard-write=(),geolocation=(),gyroscope=(),hid=(),interest-cohort=(),magnetometer=(),microphone=(),payment=(),publickey-credentials-get=(),screen-wake-lock=(),serial=(),sync-xhr=(),usb=()
Referrer-Policy: same-origin
Server: cloudflare
Set-Cookie: __cf_bm=VeRLn1Mik.j_UL1grnFV2RNnhajAqk4h2NzAgm584qM-1702110299-0-ARDo5zPWNKZMI4tjqVaQ6/otI5DwsFhWQHg3/R0IGZ9cSsyVhTH64YHnaGwmPhsMFbrfk7jkgMVs5m13SPdyebc=; path=/; expires=Sat, 09-Dec-23 08:54:59 GMT; domain=.docsend.com; HttpOnly; Secure; SameSite=None
Strict-Transport-Security: max-age=31536000; includeSubDomains; preload
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html lang="en-US"><head><title>Just a moment...</title><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta name="robots" content="noindex,nofollow"><meta name="viewport" content="width=device-width,initial-scale=1"><link href="/cdn-cgi/styles/challenges.css" rel="stylesheet"><meta http-equiv="refresh" content="375"></head><body class="no-js"><div class="main-wrapper" role="main"><div class="main-content"><noscript><div id="challenge-error-title"><div class="h2"><span class="icon-wrapper"><div class="heading-icon warning-icon"></div></span><span id="challenge-error-text">Enable JavaScript and cookies to continue</span></div></div></noscript></div></div><script>(function(){window._cf_chl_opt={cvId: '2',cZone: "www.docsend.com",cType: 'managed',cNounce: '30844',cRay: '832bdadebbedf8cd',cHash: '42509807932f7fc',cUPMDTk: "\/?__cf_chl_tk=mdBOJhzWMGisN_a.LXFGcYF_ScFenkBgF_0B9xcFKLg-1702110299-0-gaNycGzNCjs",cFPWv: 'b',cTTimeMs: '1000',cMTimeMs: '375000',cTplV: 5,cTplB: 'cf',cK: "visitor-time",fa: "\/?__cf_chl_f_tk=mdBOJhzWMGisN_a.LXFGcYF_ScFenkBgF_0B9xcFKLg-1702110299-0-gaNycGzNCjs",md: "Vvz5HhdEc93cx4gElgHBNVVLHJPgXU_oG_Uq4Tn7F8k-1702110299-0-ASd2dGtI5tFCTT0xic58X43H02y4C-UN36u-1EniN_VvA8z8uQPM3tBzr73R-Zw2bFE1wm0EDENlQajNU95Hq828VvpEUBI_hkDSuE1aQiuSB1hjgBxGEK2KwoBHAAYyXW2mwm4yfBWueeyiUBT6xZFvi5h0V0J_b3opuum294kYucizDKnv-_7nXismYEVwbY1iYzf5LBnMDUd2Y_n1YPqjX5a4cNyM4wzjLZLaFVqufIVkChGfUTWpgS5qEUcfcVRoG-OgmjNbMZcT4RF7d7Pv0iu9jg24Mv3Em_JUThmNbrfOKzvLcYaMJTLWk0Kv13h49yBawKzO14OdTOFDaw2TjJGzFMACbHp9A_bSTKPTTbwlKN-5w1z7LBgjUueWV44JbQsFBy-6R5l0cTQoxPqeVOvAGt9P4t2O62it5mBEONc-mIRI-w4iaDnFeXS60M1sd6skxtZSeQ7psi6ZvFh1qAuxcl_dr4CDeDx7Y6CL3xlGIqiRPpypi2IEuFeRsSUSfmtXmL4iDmzbhdRt6K_c4p7u8Rl1KnDQqK1AW224T0ncQMGxLokFTd466xIRWgIEJzb3uoveBoowda95Cj_JCKNEiqjKaAtTIA-0UcXmuxI9d7poZV0ZcMhII-aU5BOvA-8vDSnUASxU2q2wX9Lq9v5c8ESyc_pzad971ZymE5k4PCTqEVVGCnwgC7JZhSzazM5fYv04wDgSIXBi7yMLjxLxjkbtccx4Ki0t5KaBT3NJZwji94SQZiCnwE-omKK3E1fsvT0H6l8Zd8rJE4V_-PD3whKKaC0661N7y-U-JlI3RJRLxboG7sPDSLIOR2Uv3VWlUUvAzbaquKipnrQELKKvKmOhTQ7LGEiOcDLNqB1d9mjLlh5TlWGohLaSMIf_f518XgeEliqYGmyq8xKTn6op5hYyk1gqjmP8Q_sXg4VxVeyejbN8MC9pHjlb2BzN4ARcNbvSgFzTDWHNxJa_3qwL9YtNwIZ6WXxM4uvzOTxaJLr2_VjSBmn2oOPHIPIIvxSGcVcVv4KvexTBe-Nm6K2c4okembLeM-YBgHb_Lq3JxfjbH5_TFRzNcg3ojItV7KWO1h35exg0SPsHduAEeoV9bUaIa7AvS1nT9brHS9v9_nbywAMg0BZJ8wWHY4SGY9Qw2N2T0XxaMt0SUiDUnMeQr74U10Jj1BtAosM4peRKNoprrmv3BIZfulH2Mv8GAOqGKk-WjuKvjL4QUZTtt8z4qzP4UyMUAmOELGmLdF-JuoyLExU4D4ZicY5JhMK9fpb_vJ-_Ll_R5iRm0gWG2vF2A9xrzPpwY1g6n5HAf9xtwDfNA7_ZEvXSF1ffX7vyyjZ29bkQg-UCc9QGzAub2xytJ85-_Uj28OD_Fd2ZaojBbViyYBwpGaRhOkD_MFzf25WeNhpUXM_uNLdSwyoLNm_t0AGMVsHxpyezDcaC2Wan0iGr080WUVIjrCCPD7c9gQnjxM0MuAkF1e5Gy4FeCB0QEOfj5vS-k0kj803RcBW6sT1Q234Q0gYfl2yCVxSQNE6dsBSvEyX-asd9wakqqYrCFjaf8ew6ImHi4B8cSJFbS5D6HsbdLS58kM9NdXvfyQOhifbdGGriWrQcKsJhRcFL6EHc6MmusJxqLIl-vqCOmlg0oMnX7xMcp30pJ8nf5ji1uSrWHtSHwCivjZSpztuBN3rxCctDkDBMfkeMZqo7_zhBJ59CWhenq6MtsZ7FdyKYYsJoQInhZo4fSJMQg_6Qv1w2e83fTycNnA2waPloYI4BDT383XczLV8ep2w1fJTat2MRcI9STlpYRkqITVUsYisuQfOJU6PT8Ch8bPnqpTCED5m7Ev2jer4vCNu2Jf-FfTzNVTZlqvRgGSOxjKGt5T8TeJIStHO_W5-5rZo34EtX5Rd7L_hIq0BJB3UsF-kiA934z5Et8kCGmmB8TBEfhzdd0tBAEI_DBZfhe3KzICP_uKRDaEXgofppZjB_EOxdcfHLaioihQxjRo1xWUlIXsdmkCL-pf3OdsGJUOtPC8My-1uQa3U-KodHwixtBV5D9B9fiijm427tk-bFHOjeVFacLbqSWhl4Ui20z3ip_a71FdxEHiWNpQTr3-_Wsh6mhIEALuxuklUDKudq3GG6k6Py1U7r0kxP12Cq7GOQgbA9IBfNIaSrFyULeHMvL98jM-dUJWjogItv7d5Fs6W5-bD_P-HarVuMNsCJmDY3F2K4OZRcFiMV3AM9ejxJlbDIq-kSUVCvGj8wvojyTR4d3BK-4yPrg7jEXPeVQuxvjNrN17lp8pw4zJFq9_HanPO-8kMid8rL5CaeiGLcZgKLvmEjLxEHq7xRgvd7Ckyh8zmllySFiZOBq5J1XLu5sFhtT_5g0vURwzHisUvO5m-lMIVuA7P25G9x4qf_VWC08ZCr80e176JHe9N9N52FIcg-4a-mFMIy7iPWIGOGyK7z03hH704bWuoRK6GNSXDH4TxP2dt-0Ug9TUvM0jm1N43D3HnGzRMOzi6_2RLr_SzxVYdDWdXmLQ2Nu_N32Rs-D9bX0laKdrBsUommAg",cRq: {ru: 'aHR0cHM6Ly93d3cuZG9jc2VuZC5jb20v',ra: 'TW96aWxsYS81LjAgKFdpbmRvd3MgTlQgN.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2227.0 Safari/537.36' 'https://www.docsend.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)