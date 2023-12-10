### HTTP Missing Security Headers (http-missing-security-headers:access-control-expose-headers) found on https://info2.hellosign.com

----
**Details**: **http-missing-security-headers:access-control-expose-headers** matched at https://info2.hellosign.com

**Protocol**: HTTP

**Full URL**: https://info2.hellosign.com

**Timestamp**: Sat Dec 9 14:55:15 +0000 UTC 2023

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
Host: info2.hellosign.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_8_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/54.0.2866.71 Safari/537.36
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
Cf-Ray: 832e16876fe0d6ba-CDG
Content-Type: text/html; charset=UTF-8
Cross-Origin-Embedder-Policy: require-corp
Cross-Origin-Opener-Policy: same-origin
Cross-Origin-Resource-Policy: same-origin
Date: Sat, 09 Dec 2023 14:55:15 GMT
Expires: Thu, 01 Jan 1970 00:00:01 GMT
Origin-Agent-Cluster: ?1
Permissions-Policy: accelerometer=(),autoplay=(),browsing-topics=(),camera=(),clipboard-read=(),clipboard-write=(),geolocation=(),gyroscope=(),hid=(),interest-cohort=(),magnetometer=(),microphone=(),payment=(),publickey-credentials-get=(),screen-wake-lock=(),serial=(),sync-xhr=(),usb=()
Referrer-Policy: same-origin
Server: cloudflare
Set-Cookie: __cf_bm=2AcftTLzNEEVtSPgCx6Ycp0RxMVYKk6qM8xJ.F5aggc-1702133715-0-ASh5zG/VNRkeEHxJsCXdkmwpYlxDRO1sXEhrFzH2scWD8xi+SV/4BsJmiewgCQoPXlftu3ICN9A6Kt8kmyNPwx0=; path=/; expires=Sat, 09-Dec-23 15:25:15 GMT; domain=.info2.hellosign.com; HttpOnly; Secure
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html lang="en-US"><head><title>Just a moment...</title><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta name="robots" content="noindex,nofollow"><meta name="viewport" content="width=device-width,initial-scale=1"><link href="/cdn-cgi/styles/challenges.css" rel="stylesheet"><meta http-equiv="refresh" content="375"></head><body class="no-js"><div class="main-wrapper" role="main"><div class="main-content"><noscript><div id="challenge-error-title"><div class="h2"><span class="icon-wrapper"><div class="heading-icon warning-icon"></div></span><span id="challenge-error-text">Enable JavaScript and cookies to continue</span></div></div></noscript></div></div><script>(function(){window._cf_chl_opt={cvId: '2',cZone: "info2.hellosign.com",cType: 'managed',cNounce: '91719',cRay: '832e16876fe0d6ba',cHash: '54292050a767223',cUPMDTk: "\/?__cf_chl_tk=HAemDjRDQuPBx_Nm2Nlojb.9MaxXfHzTMVoWRTNATlo-1702133715-0-gaNycGzNClA",cFPWv: 'b',cTTimeMs: '1000',cMTimeMs: '375000',cTplV: 5,cTplB: 'cf',cK: "visitor-time",fa: "\/?__cf_chl_f_tk=HAemDjRDQuPBx_Nm2Nlojb.9MaxXfHzTMVoWRTNATlo-1702133715-0-gaNycGzNClA",md: "rpgb2ycHqdL8j0EssB8NiJvWzbpIi5qb2sEKfTBJuwA-1702133715-0-AUVZpx7pIj0qwFNX800rAuzUx_wmDSssiCs0D8BU8R-UERArwiqDXtPjy1QK1F9aBdyuYhb4-iyUWSXamlb_HowBQ0X9Zg6KkFKFo6EaKSTskGp8dSVkgw3SNi-aokCJAiLupyEaiwQx1UWqKCxenDFXBIcLhHxHVcU3LdpcuzY5xv5Zj-jizbOZ6ggi6FljaHqgH2kAu5wMNjzeiyhHPRmA84DKgM4cdDUlbeWWcAl5pcVYRi8Kt8a7cm2W2gl6ONjGzF363xqMpjzSekv4UQQ32enOALAcpJEZdyVlPtE_fn6sw_15cB308kPAxKIFP6u-IlOLGDvdIXyHmo0mrVzED-4xo_60Iwj6d5aSx88mcjyAXdmbCoBGK2iqxsPLU0lyXJ2MzxeW6n8LWjLlDGeewRXqUbtqc_y2VTT_wbgoumPlrESZ4fZ4bKRV8_Gyd9NePx_NWurHGP8QaX1TAwktxN_U1JvJu9IRIyxKB0eYw_fgdB8ixX5jEU7igtq76lcTnzrE8xwjTbtVk95NlqNNE5VysqsgmAMZNmx4iBML6FWITeJA1ujwzg4Y1-9pnGRPAlsOsKTCeAMje7w9qVfpkidpD1sAarwtJ3gp90rjQEnUCbgP3rDEIVLr-cr2nv3i4aAo1S9zQI3rg_QEDzV1dVyYQEd_9PeyfgSzrQqGhHkIF7aljfygCYh9E25CTj1yVcZiKGH2sThFS70TnBWNWP7LjDilYTGXu8j4sFczmpFppG3HeRVm2d-9uq0A4gMLCFWZvKjKXTboCsPjXkaL9muiTm3ncVgD-tlvnpuxnc3lm4jT5Dat19K5PjSw6XXUXU9Eu5CAoDwAHJ7CQv9huC-gEUka467hIGiDV462xSXh7Ylzn9aT8HNYhNz9_esZvZAoa30B84LMd8nhwvjVPBHh5lK0yMgXC9gEGoZdM9FMoKjoPhdmz1SDuxG85KAlPEjdpUxvx-aXtcnd3wS_kviqj4KK3WrNkRJ3eRROrWTWRGSekPlWfsyM0jKlZP9eLu8ycXqvABHinhzPvei5zU9A_wN6268oSSESB41QPvyGQL6b9rqUYEXRGFGhUNLvnPUpYwAArEnUYgFtv8hCzyjORca8rWh0_2dAeh1V1DdMIGn99QLl4dN5OTSA0OkGLwl9mM8sfI_JjZCgT617oFVx31_umf6OEcYOfeDFyOk2KC_I-EsGOHArEeIAgIWcOarh0RD1UovdV9_nCCrsBXifXQb93qeMmeIidhPthPWivJKIi71I3BPsIzir5rvw21TbMDEikmSWckZJgCNqCZa7FGWPyFpEtC6l3I1ioqz-tCWe_X13Oo5anVSTHoR0i-sYT_HmGhCwjwdM_eWwy4e5UM4WrCOWDQNGSEJCOgX-mtq_APlCy5j6owTTP3ofzTVijByBXXMcwR165DFBFU5FXISuh4AQtB3Aqpcu2te6PyCX81fxK0w3_Tt_oDPVlFa8lIeSjjMUYnojngBynI20YNDRtPfWnX62dA3um0ApqMv7h8EJq1JzuMVdwa0B0JBT0JDQSuXKG1kYVqrOCNmg0lBksleLSowiSQ0QVBRdx5RymTmTxoOhne6ZgEbEBZIVSHQAaJRtEP9QSq-pJ9ekqYdnxIsGloyYSAYdcs_qM5NXDRE8GdYLmi8vzRYclQhVm4VHDOzxraZn7HbP0908rlcEJ5EOYLXeMjCNUYTpybTBf55plqmBDmT6ltoP0WVWiKxUAipZwfSCZndxdO-VA_3-3ttrUmPRg-96buk216eEfadeUJYZ1g61rEQtyf1GdwKfDlVDRrjTB6_27oadfjiJ8oM-IxEEMCSq9qpki1oLUH8XxWDk1C5jgy-XFF0PvWceA8DwVWzGLU1B7KqmU4-iYsYaNG_HgowXsdGDFsHPbxTKk2TET7scK1x8DUjT_gvXp8lbUSF7G7Y1rwmmxBJXVQuLrpy16yED7RRJXSeG1_Ex9ZKMB8jvjnk5aEFob65eqQcfW1-ECNrHWbOpYRXxW9FZoZYQemQ9zVf4ZIMrsk0SFX5aPV-v9Z8HjvPv7YoFe_8ztIvHwCeetYefzJgOII5F9N9K-Vn0c2JMKr6GqdzIkCiPAOBLQMg9HLPd5MxAl8X3Mb5zy90hX5jU6T_yJ9e5FxBiuqf-iSND_CSuf7HczagATBJMSdl4p__dV4SnMJm__sWfE3ODtL8cDqUxbeuH_F0saLvRNw8BQJaR7cffaYXc6iRtS06xOlWCT6tnpihR8fgSeGfkfV2KPadZOkhQtden0XET70ofPhLsPQ60bOz2ph01outdqCT7fT0kpVEpljEq6FN0M6H0MtmzLXW2890BVgjFvQnfUNhpP4boXkfeO-x6s5wnGHcYslyvldxT6ag3QwLLyMc1_KnZnItn-OsE7N2kpi88cxdRaFRWzOibiDFnz0wzgrFv-DP54oeWNzcjQeUKwniacPupbhcX68mRVZTDcnu9Rp5NbObb7CKq6D956IyDDlIONOTfNAZ4VEyIFqrky6hZvVyIYLlxZ5sLq8ZqgoxSJoFvjBzxVbal3oulsERBqNUzQjsbTx7OYcCY03c",cRq: {ru: 'aHR0cHM6Ly9pbmZvMi5oZWxsb3NpZ24uY29tLw==',ra: 'TW96aWxsYS81LjAgKE1hY2ludG9zaDsgSW50ZWwgTWFjIE9TIFggMTBfOF8zKSBBcHBsZVdlYktpdC81.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_8_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/54.0.2866.71 Safari/537.36' 'https://info2.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)