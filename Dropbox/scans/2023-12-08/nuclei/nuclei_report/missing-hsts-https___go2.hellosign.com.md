### Strict Transport Security Not Enforced (missing-hsts) found on https://go2.hellosign.com

----
**Details**: **missing-hsts** matched at https://go2.hellosign.com

**Protocol**: HTTP

**Full URL**: https://go2.hellosign.com

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
Host: go2.hellosign.com
User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36
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
Cf-Ray: 832bd9486c452a71-CDG
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
Set-Cookie: __cf_bm=XosAv5QaSq86iq8KxSEQtiLmiiN6PfoWtTRDYE0fsCU-1702110234-0-AcDS6X84HQr5VwIV/WWfd2ri/YJCDd3C7CiWQhYUPMX+eVySCR1eu19CRh0V4unpLU/1a5J/OOeNZTLuFggUAUc=; path=/; expires=Sat, 09-Dec-23 08:53:54 GMT; domain=.go2.hellosign.com; HttpOnly; Secure; SameSite=None
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html lang="en-US"><head><title>Just a moment...</title><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta name="robots" content="noindex,nofollow"><meta name="viewport" content="width=device-width,initial-scale=1"><link href="/cdn-cgi/styles/challenges.css" rel="stylesheet"><meta http-equiv="refresh" content="375"></head><body class="no-js"><div class="main-wrapper" role="main"><div class="main-content"><noscript><div id="challenge-error-title"><div class="h2"><span class="icon-wrapper"><div class="heading-icon warning-icon"></div></span><span id="challenge-error-text">Enable JavaScript and cookies to continue</span></div></div></noscript></div></div><script>(function(){window._cf_chl_opt={cvId: '2',cZone: "go2.hellosign.com",cType: 'managed',cNounce: '21641',cRay: '832bd9486c452a71',cHash: '6d3f9cde0b07395',cUPMDTk: "\/?__cf_chl_tk=.02XIKP6y6rNPV2HoxHs23AZPYQA8LKCIqFUU29wILE-1702110234-0-gaNycGzNCiU",cFPWv: 'b',cTTimeMs: '1000',cMTimeMs: '375000',cTplV: 5,cTplB: 'cf',cK: "visitor-time",fa: "\/?__cf_chl_f_tk=.02XIKP6y6rNPV2HoxHs23AZPYQA8LKCIqFUU29wILE-1702110234-0-gaNycGzNCiU",md: "mfLm8Uj.NaMQMJ.AE0m6rW9QaweqipIVrkjkFeRXOFw-1702110234-0-AaOhp4U9dHaUYNdSyICGQvQd1Z7Yka3lvM_AvOWNOXyZT6Q-DwhvV5OF1AquNX8cbByshRxqWDKKxOpH_vC9THaws2eYaxkaGJRvNhxm-b-79dksG_5hgQ6hlD1fJhL16k3Fwzz5XjkpcQhyVMXUTbltPCFZFZViDDKw-Vv3vFQBuod5VXegkYSyUtFV87v5FY4GU9N1M5Spxp2JZVP9E8VUnouBF2TmUU8KdEUWlG0dQKUMY1HIrW12lyfhsS9OvqAbsO4WKag77gxpn8dhbVP4YloQdtN01qFXTufLS8njefOunNehUrQI_79ctPS99bdZhW0MF4PWNeZcui9Z707m06kJ_pcfmjzRPN1-xneaiFcIazsivTwyoEp9JZyK9Le3OWrhVi8tiDlZoD10NBEOrPNkyZElrUcyffFOicgmBvf3_GtmhbueCYVGOmmARuDNr7imGzbhsSe8znjOvk3KwzwQ7cpkLbhq8gkdu-8eW-sxn3x2rxPB5jT6FZA3_UcIBJL_iSABlvgjRUFe6POO9KnlN0pjWo9OEzxLZMsyXXDTg4zqc6Gpstl2pejLv-WkvE_lpfAYhknpk-fpfCCys2691GkEhEOfPsi2408MTwUHHXNxQsuvn_QLQm7dO9C-O2kmwiog29Q5yuhD9z-rSJrNQST-PmdJKl5E3G7J-E_HLIq2tDwwn4oDZKeM6juIHn1nG5J4OujkVkXtkt5lSEXaxOKErWdsDm3BHXAc9B_7Yo0YLnLRIsjiQEc1G5__TplisRzY2iyoA8iR3j9w6FfEoTTbxz_Z1jna3wTexvDfYjLXd8bNF5t93bld9vKXrjw2fF8d3lNk_72tEYfIEgprU6YCqOdyEqVWUuz_BmzamBebtTOHmRVsWHDp6of5qRH2ypdCxC9M9XmNbZtBnZSbNuLkdJIvOSRrmkjR9kQVGibYva7ZqaxipFnX9e5NgYVR7Vn-IYWF6exyp1PZJOgIV-Xae5qUDLuof-6U4Dv8BB1C28EoV7-ZmLoqs9eb40-W0HVYL79W-Hx1H8fI0Repaf1Z7NHt71XYCpsqG1Xd7skh-Tax9etqNt_r9HIvIxEui9SM8UoPGJ8vtZSyq451lF4FCdINXK_120bhgjSnJNPc_leMXI8Zb1K4dA1kLFY9Of5eWAa65X6BKM_abx_x7Ic1wfdjlS8YWCF-WA9IXWcdPInbiOKF398N44--mYfFrpXJKi2p7dLZ8m4jMAuJ9OoXNVb0anpySxAej5fUUZCW8K3b1A1S7Prp8POLT0nhzHqb3OQ6sBteHUKuyxM2bTDpXA5RzTUPDN-fvhx0bH5PCkp2fqzGkUUSyCDlaSZ_mA0qczQYrYrsuYMlxDZZ404G2WorUanzneBvPvsjMejA2EcrCAvz_HqDO8_qWVccwhaic5iAEuzB_XVO_n2Gj864mPa7j4at-UdOkVWQmnq_wBL3MeQXenIsovoLHoen7ybBNky8y-vd5MFbAsrBCM1YFOjfwBxukVY1J4FBtqC8dSxfinFK2d0rFuE3gPW9vPRenqg9Rq3PHz8jjcgVx0QJj3oHscxrfqGWr4tG_o4lG-d88b83K5kBmUecs7gcFdoc6oPijTx1NfbEZFmCHjZuaCC34TBeLE_1BZwJaEka5QuLKb3AgXdfBB_EvmYUOo-IZ_3uZSizai_YNQmZYhy1lQdHSpUgozzyluBi1x9_tvEioMW_-ns4AG__RFZM71yWLokNmS3w853tUsQ5G6dHOeRWIKoWviK6k50SUXU-pwgIKqe7FJ5phduhe1zob7kEs6dq_NchdjCpAUhbKE1ndxre1J8WpifPlAUnblB9ti_XRq3LPnPlPBgVUyFQkcAef92sYclHlrbQlsha6uhb0nOKcYrNTkeTGUsVsWI_C_r3OLr2LTHxTHIw_631oxjCCbNzkoE6aGCykgo8ZRjB1zFeZy4kB8YV172Nhr4aWpcpHGsuqvBHvFy9DX_EIsmX9kgmKg_MXFu74fYrWv97OkcUAz0PpqQIZD6ITeCnMMRpSsK-fLh-PCRWud-3ZevZLinY9aSU-Vtk1pkc7SFmZT_VL2xlwNrjZpT6IiWLuhXTOaZyxes0mvBUFhvzB1MWEg-zAxNj0YBWDHQ3CXLGs2Obwb0Pm_ynfOcJLn-wxR9bOG-6sHnU2Vt34TgBsrb6A4J1xijaN0H6vFEqfk0WxbDh0ywS07w4sBYL51w1O-a0UdMnARm-AP4vI3025BNXdlTg24alAiigznaWOEH9PtI3h311lWOK1-WytTlYnLALOOrUPsz1ZhIRWWPgYdPxQ8NrU7DAV47NGQiS-eWSM0_qLSZ7VeJaJBSa_pXmaD2ABhkeDTEBjQtMAI-ub-UOJdmsbg5Ch1m0IwNXNJ9S2VJXd2VqWPBNFxgVwttlK2UJOY25v1yZgZIKDx8LWuk4hGRYSgKqf0sD0pJ9nY0WNf0LMrw7uunEre0-xaDAXq9V55oablta0RG5Hwlkx3yTUkVbYLjxo7ak-Hvk0lZQCv9J4NPjRdrK",cRq: {ru: 'aHR0cHM6Ly9nbzIuaGVsbG9zaWduLmNvbS8=',ra: 'TW96aWxsYS81LjAgKFdpbmRvd3MgTlQgMTAuMDsgV09XNjQpIEFwcGxlV2ViS2l0LzUzNy4zNiAoS0hUTUwsIGxpa2UgR2Vja28pIENocm9tZS84OS4w.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36' 'https://go2.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)