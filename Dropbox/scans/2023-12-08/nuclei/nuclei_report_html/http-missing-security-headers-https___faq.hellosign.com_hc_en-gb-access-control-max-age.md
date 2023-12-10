### HTTP Missing Security Headers (http-missing-security-headers:access-control-max-age) found on https://faq.hellosign.com

----
**Details**: **http-missing-security-headers:access-control-max-age** matched at https://faq.hellosign.com

**Protocol**: HTTP

**Full URL**: https://faq.hellosign.com/hc/en-gb

**Timestamp**: Sat Dec 9 14:55:05 +0000 UTC 2023

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
Host: faq.hellosign.com
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/70.0.3538.77 Safari/537.36
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
Cf-Ray: 832e164c1bde2a3d-CDG
Content-Type: text/html; charset=UTF-8
Cross-Origin-Embedder-Policy: require-corp
Cross-Origin-Opener-Policy: same-origin
Cross-Origin-Resource-Policy: same-origin
Date: Sat, 09 Dec 2023 14:55:05 GMT
Expires: Thu, 01 Jan 1970 00:00:01 GMT
Nel: {"success_fraction":0.01,"report_to":"cf-nel","max_age":604800}
Origin-Agent-Cluster: ?1
Permissions-Policy: accelerometer=(),autoplay=(),browsing-topics=(),camera=(),clipboard-read=(),clipboard-write=(),geolocation=(),gyroscope=(),hid=(),interest-cohort=(),magnetometer=(),microphone=(),payment=(),publickey-credentials-get=(),screen-wake-lock=(),serial=(),sync-xhr=(),usb=()
Referrer-Policy: same-origin
Report-To: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v3?s=FC9miypntSpbtRQkh8uPrAin3TdvWBvnx3qHbN9LRFTow9tSlTxxd1CFPcQ6bgugXwIJPLomqK%2FBC%2BNFADReZkWywyzhfNStT2iQJ6yQgG%2BlCG3qyrYF7U4uT0S%2FI1k9x7a%2B"}],"group":"cf-nel","max_age":604800}
Server: cloudflare
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html lang="en-US"><head><title>Just a moment...</title><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta name="robots" content="noindex,nofollow"><meta name="viewport" content="width=device-width,initial-scale=1"><link href="/cdn-cgi/styles/challenges.css" rel="stylesheet"><meta http-equiv="refresh" content="375"></head><body class="no-js"><div class="main-wrapper" role="main"><div class="main-content"><noscript><div id="challenge-error-title"><div class="h2"><span class="icon-wrapper"><div class="heading-icon warning-icon"></div></span><span id="challenge-error-text">Enable JavaScript and cookies to continue</span></div></div></noscript></div></div><script>(function(){window._cf_chl_opt={cvId: '2',cZone: "faq.hellosign.com",cType: 'managed',cNounce: '62258',cRay: '832e164c1bde2a3d',cHash: 'ca22ee6a4b3eba8',cUPMDTk: "\/hc\/en-gb?__cf_chl_tk=O6rUtOLplHvZmK320rM9YzCwxitSHfFwsKwWTMcEVK8-1702133705-0-gaNycGzNC9A",cFPWv: 'b',cTTimeMs: '1000',cMTimeMs: '375000',cTplV: 5,cTplB: 'cf',cK: "visitor-time",fa: "\/hc\/en-gb?__cf_chl_f_tk=O6rUtOLplHvZmK320rM9YzCwxitSHfFwsKwWTMcEVK8-1702133705-0-gaNycGzNC9A",md: "9.EsfWkD8CT96eAuultheq48Q5ixC_A6Al49AbqgOyw-1702133705-0-AeN3qAz-YIbrzwoawzY8CLi6aFQO9e0qpskIkbLFhQzhGU377Eh6srfzOeOd17txpUZbLZ5yU8x2Hha3DeXgpJhMEG0H2a1xMfyyqtIO9pindwdHzWFqILnPi2oWy1pcHwpnjavIPbCcZlhbNRKDvmg95ULTxqbn2InWE55qWAOju1h0GdVu2yF6GXHwpIXWyXffFMbSx8CcjbtzS2twLhQPnmI1R0H2U5-gQ1vFzpGGgh1SGD8MSlIzJp05VIseFUH3LcT9vZ9l3BLUJ_fuPp3fJ100PbaCMjI_JBmsB40gkIungWrRfnRrJve_HNv3yckQTxf8YtLxOgo0R1lVmPTpPah93zvEQu9t4TzE1oqZlsEOt2xM4lhoDB5eLFSgEGxOq9m6AWdd58xXRUAD5s2NUtoEHsMGjC6YcTuSWv1228s2vlQoHbErvYb2_HDfiQkABJD9EsyDl2hb1BDQyH_T3hdZTzWrmW9yEGOsIk-swJVJhjHI2GGQw2GLb_aJKxKFOTe80rzhen3_cCTC_Z2JyOg0Wbho0wFcz_iN06Mhwvl5aqKE_rGZiDviHI18Yvln32GuprDKiNHSvNPz-q78EyTNYIDslPi8_qlcDx0ymsY5cH3tyVyKw4k06-fZIwsauStVfkCfi-0b3y5B5MAKq0nJbitYfIDus48OKo2xOOtXoXUDsz2Qm2CPzYe1Yl_wKdlQEf8otEpl80l31-MgtC_JHgzjsDmIibgAIM4UQgzSplanuDl9C3hN9kIz9txIDVv1vMEvNwPJFrtVj1stkqGF4wKLN08BEgmbwdIUP_J8WkAEqJqjkGZn4D4HHZiIMYxT6OdWg0UIRy88q18mXT6TbtpeJhrRTfsUlNcSS92RXCrQrU3dWzSSGZOj334R9UcPICa2CTL4koFNhPnliHjraUW8owIRoBY7VRJTgVlV48ZNiAoEwJ1LZLLMZbFTfKK6wpLYHUclNNfX7KQjvWsaERkkjzgMMOXRO8NJFToWT3XU61MRDOaRDclPO0OVQdK2i_IiFbfH2JFmgA6j9EOtkre6_r3EKQLb3vyZnAwl_k0penHcNgDOgi_Zs_ZZ7_NgVwbWDXvzjakE91eFKvxZphf2LAUspcZ-jrhqw5mAQgI4DNxen5-XD7LOhu1gZFbDYztYZsURa-7edLRLuTuQqDcM0x17N4MnyBOhkXOAmA8H9acNytuPn4KpsHkDZQGAS1XHVL220C4353ByRNWfTBU_qXQJUY-8R1UYOoJMWC6Ym0K0BHaYT1NZ9tBf8jITtYY1vB7uFEAY1LYSq6y0JIBXyNclfktL5LhMpWoG5KN0mMZoJYIXAF-ERpMaZDKAfGGB68eLyQ8OIbhhMEL_OITl2rQpt9iyInqZQSM4S0VUGDez4OOgmAq8dIlA4d8i4eCsjcr-kjzSKaX06bah8DFpRshxVwZLeLPzqUHV5BSJBclb0bNJSryNPbOz7RTvgxdT35uShW6wMw61U7ZPDdVl76OjVYIP5hyMBN-vMXv3W3jqiDXkndwTULp-8zPYH-Bv_RNsLcxv2UuDmXzIt33o7SsoaNbfKhWsgqEnHD2uR1mYwXLXb17txJHNkhLElahfCViFQEAy8Lsj_2FiYwBsbR4zh3_WmbA6AU7ewsf9pC5xobJy6ME6acdfB8PnK0pwwo_eEkQhTcf8-EghRY_JR-c6q1q4ETvJyhKo-pqZLxa9uBVor5GUJXjsmcSIFHtSXxUHuZIsXfkYLqSb-1Z0qWRPG0GRPUIav2T3pwVQFnLlEtktbS_Pjyw4XCxmhKPf4Rp0f5j3Ip2AndRKLsCsOADacX-SmCshYPEDLf061tgpQEDNzRTMYyB7sELYP87IpGX--hpW3Miid1RCsFJstU5Dma8KyvuozIX6mudj0uOWBPHZ7OTECoGQPwHDl5W8JXUjAHLCc8TQyiRFq72eNFfaphz1F2x9ymDzB80Djdb9IottPY-4-zZH7_pJcbS1zajpVI2agsaAiLByHySMIpUKFSG4FlyyqWF3YjPq4tGmyrm0Ob0833NrqT0A1OmAlhel84NNqMlteb5QVDWAoP2fz3OduOiN-cUSVFnyIf6ntAR5XD5cobIG3NZ7S0aI-KI6ZjLZJBUNA9M_j9oWidEEqoXXJj-HA5c93f9OyD_Yj1Q10jR8uX1aVT_1u8LNLm2a_DhDbWJYOttfxzqMg2i5DuVQRxr03K3_GpwAMiZXkYItpgsblp6WRLIEYK6fRfG4SKjyL2hSriMwJCDBAWru_uC5YkgRsvQ4sDJ5V2tjJw3-ayjXJCaBrsOYNR7laVA3eREqkha7_fDwkNFQtsNNhHS7Jjp_uTG5ruYtScdjew4Yr-_eDafLBOaPrXbiRXpCbWme-OuO-B_NbSoxfIHguINQFmp96ED4uTjK7rlu__eYdt9ujk3K4jjUbw4cKBHGcwwD9iZt6VPTbvd9NQo_ysxldwUH3xPavZzr9xIIdFdyYdz1ng59hWOFXP8YI6mCcgzMTe_mVYS_oxcljEb9ZeGECBgJQd_9DSL-hR6NnU16tTk927tHbcpaQaqtU1QqG-4wLUuczIVD2ByyNWDjMSLhBWF-a2PuNqpVSnM6pL9dn9t3d3vBkqQ0dsau.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/70.0.3538.77 Safari/537.36' 'https://faq.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)