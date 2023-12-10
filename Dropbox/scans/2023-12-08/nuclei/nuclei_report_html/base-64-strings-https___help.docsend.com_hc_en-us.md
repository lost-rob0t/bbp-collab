### Pull back base64 encoded strings in the url body (handy for javascript and html files) (base-64-strings) found on https://help.docsend.com

----
**Details**: **base-64-strings** matched at https://help.docsend.com

**Protocol**: HTTP

**Full URL**: https://help.docsend.com/hc/en-us

**Timestamp**: Sat Dec 9 09:13:02 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Pull back base64 encoded strings in the url body (handy for javascript and html files) |
| Authors | panch0r3d |
| Tags |  |
| Severity | info |

**Request**
```http
GET / HTTP/1.1
Host: help.docsend.com
User-Agent: Mozilla/5.0 (X11; CrOS x86_64 12239.92.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/76.0.3809.136 Safari/537.36
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
Cf-Ray: 832c213b7e150483-CDG
Content-Type: text/html; charset=UTF-8
Cross-Origin-Embedder-Policy: require-corp
Cross-Origin-Opener-Policy: same-origin
Cross-Origin-Resource-Policy: same-origin
Date: Sat, 09 Dec 2023 09:13:01 GMT
Expires: Thu, 01 Jan 1970 00:00:01 GMT
Nel: {"success_fraction":0.01,"report_to":"cf-nel","max_age":604800}
Origin-Agent-Cluster: ?1
Permissions-Policy: accelerometer=(),autoplay=(),browsing-topics=(),camera=(),clipboard-read=(),clipboard-write=(),geolocation=(),gyroscope=(),hid=(),interest-cohort=(),magnetometer=(),microphone=(),payment=(),publickey-credentials-get=(),screen-wake-lock=(),serial=(),sync-xhr=(),usb=()
Referrer-Policy: same-origin
Report-To: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v3?s=SyJMojlYtooybXEPow2wDGssok90W4dMj0pWK4CZa%2B%2BbImd5DfqBwTqi4ht2lk1ZjTTcECBcKNCdaunIRX98VyxQ33xrRcafz9y3bsWbwTKoOxm5d2%2Bq6ZKioV55cMVeGnU%3D"}],"group":"cf-nel","max_age":604800}
Server: cloudflare
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html lang="en-US"><head><title>Just a moment...</title><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta name="robots" content="noindex,nofollow"><meta name="viewport" content="width=device-width,initial-scale=1"><link href="/cdn-cgi/styles/challenges.css" rel="stylesheet"><meta http-equiv="refresh" content="375"></head><body class="no-js"><div class="main-wrapper" role="main"><div class="main-content"><noscript><div id="challenge-error-title"><div class="h2"><span class="icon-wrapper"><div class="heading-icon warning-icon"></div></span><span id="challenge-error-text">Enable JavaScript and cookies to continue</span></div></div></noscript></div></div><script>(function(){window._cf_chl_opt={cvId: '2',cZone: "help.docsend.com",cType: 'managed',cNounce: '2786',cRay: '832c213b7e150483',cHash: '0dc541a7ac00ee5',cUPMDTk: "\/hc\/en-us?__cf_chl_tk=tZ1vV9UvHHov_2gtJriKFQ22xQAL9kV2B88Urfp2UeQ-1702113181-0-gaNycGzNC-U",cFPWv: 'b',cTTimeMs: '1000',cMTimeMs: '375000',cTplV: 5,cTplB: 'cf',cK: "visitor-time",fa: "\/hc\/en-us?__cf_chl_f_tk=tZ1vV9UvHHov_2gtJriKFQ22xQAL9kV2B88Urfp2UeQ-1702113181-0-gaNycGzNC-U",md: "j.mJ9p47X8AS_D3mlT39wTlaDuSK7uZYYYxP8wDXqqo-1702113181-1-Acgs8wJR5scgxQzyFfJyL2_RfCJPXoUI0RJfnNrxNd2tY1_BSfzMmrgSki4wMogZ7d3BGzNL3D6gQL-Bskux0NllSgWbggJbS2lOHvfnaI-jTCTlVlYcATCO52amiCA_5cG0--sXPx12QI5hEEBJ_z5xTrkxGU8kTkgdXfkox51Y5z2fnqOnxQn_AoPAAQIXNl3vQeAWDpKHTHxNdopjPHsu5pHRedn2k4sRNvwqZIYb9UHVAm8jDTtzfDFBu2FYjIc7v0LZmS7xO-e7tWWXssktZBuhxsqpqh7VT4IHpb9mRMaanUeg9_wTgIX6zq2HG-WdoI0GX0LDu0k1o3I-R1DXkMpMoMgDssJmfU4TfhQ4cqWyjZVlxFdAkW0szRyLXknwAZRcdUQhxvgj6sltKxLr-f0bYt5V36HOQpWYGbPBtEMYNVnPY7hooTRwNGzkB1m5ZBSMBhMi6_fEuJfB2SE-kPzc0aLtQ_Hs5N--PNoDYeanYE5PK5-sqnafAsKfTjbRAFB9UX1HsZXVgNB8x6j8wSJ6ZUIcZQXvOLLEziy-IjqGjkDEUhAu0LUHyhFc2IGC_jbRQiJoGDZMgi8XsoOpciWW_tClcOhBNEqDp17W8HM8Z1ygJfeE-6LwYrCasLn5rYn9w3NlqOK0gdzy36F0oM0gZFo0rtIWpsBCapv2KZjlykQ4U5ys8jwmmzPRFG2-5FPoq5Od8aXd1dRDaEe5H9qmrISciwAZzMgVKltN7aEz-dHc5VhP6DrLJ0UtgQ4Ki9EIwq283LOQvC-BGXqwqKsiuP-CrswxsTGvshgLdSpV7bTUssXJliKuveH-mBCqyimeGaRk9sUZE0ix5cFyzgC6CaDQ0sZDbhHmG3T9C7I_fbs3QY6ah_DQHvYzD2ZQzxN26BlfM96_Y-g3CY450yNPjim3EATfaseqbQBWAPtddiOJc2z_oH4BWMDtdX-u6AbygUn6u3EEEEks0gTHlAVYBuk5O-XmXVkkzK88jJsTxkOS_a2vhH6RCX7R9TAhAIytL9PuE0NSMue6-ZfMPVLBqfe0Juqxi4Kc3Ac9wOOl5f407V_sQLGmF699R1V2sqonxfdy09hlAA72iKXovQe447295kdqkWAovNtI55x8LwwZSI7dxBKg54qhF02Bd3LMej76hAXFh5MPBLc7LqPbFfbcOAzYoyFyKf_ZlE4CogLK6d4jCKXiEWGkGipedcxF-ZDdWydO5Gd02nZHNC8bzBlPXuSW0RQvf1-2N3AdoZZFJ3EEu-zl4hmtg62dUVUWKZOAp9VL05hwrksgIqamK_Dy3RlsKRQXJOeKb6Enz4PyCj9BhKt9MZXtWtorreuiQ9K7ahnSgNsexnJ6FTUewzzA3CO5Hs7PWm9NUr9x7n7xMGistKN1ufySTbdgflF_yyW95eQUtuq5Yz9eryhqsg_8fOfL6cj7VIxqWm-zs8P4-nm6lVwHr5QuwVatjJM3CjKvBJpVsfYRGgnWfgC3Ve5p--kSQiVt3aW9SyTx5RKRKGFxdTp2fE_8XOVbIS027MYA-jT3YxmYacLwk4VAEIgDkbDxP5EG52VFWrgzSH_ef-E5nHPQa3cziGVoHlug8_bB6emYmFxCpATHM39vPDq0ZkP-F9HFrd3A-dpRNoS_D8yQ4VzgwMi7ya3KVqxVc4TPHY2JM7b2Z_ssPauvKSpIsoxZuwImXPgKNDb4SkGGg9wHAhb6Y2k7lfCEdgK8W76GkGyL4JxrvMrb21WppE_w95pVZSfYHxGvD0awvJSheNG5i_KKnadA6AEllx-FPXN3m4B06T7-VyQ9bdhM7-IplqDlrAyvfdQWzvFvy7cgvHneAVYPj8kt_wYDVnXjxa2ils0Kteq6CCqLTA-JXRo6U5efA5hsFCfuPHquybU1ZEvH4v34Zu4azcVVUBMSrNhb8XoVR_ypJy_Dmvn7PM0ELd3O7jr8wP5nkp6HWj__JpIbT6AauDBsPXoKPwEICCt8gB8SULuJcC6yxneGioaUVfcshOIuIJ_el796temuq2oxuM_-iJLjMW-e4lApCRKkMqIi_nRcK-YkrsiifcNZjnihDqf5RMly2uM_CGTafdF4AcqzyjGX-g6q9VcALq8ubN6e3I4a4GnwrtWCRQN6z-wwZwXFSP4MxHmoY04bFO7s4lKNUKsoBmRUEX-MwSivoWPhhKV9bi2IfzR1E-hiiEqqR_1pBaGBot3-zcMBKFZACYY1RGrK9BRwMumy5yfyEnoSL73Kvh8owDjP6ijirFzrR__fyNfDRtPK9VhzH_nwEryeDhWg4CeqFm1pELoccu0H0e3ERWCR_UT9QSd-cFk2VRIpxtgVdli7dJav6DIHRSwt6oLkQ3A-S6WFpieSzb9_70wN59fKFMfBy5Y5Y7OuVZKEuq-fMIM4VOOoTlQnzsDE1hBosmMBLW-0HlILazTuaNKEpJ-jNseuMF-5VPcszHzIRrrDZE8hDZztSi-3VPhajh6TYCNm-SKvGki8Dv9NvvABahJNQVgnwEaiDXNAuZAS5DICZld_-0_ZYmGLlvAuaL0kUfbq5xvBtjc3WGNegBuqnr3M21xB61CWzqM8iHZ1BtYRN8q7wcUlwBb9GiNuyGTO9fA3vWctqOlp1G43.... Truncated ....
```

**Extra Information**

**Extracted results:**

- aHR0cHM6Ly9oZWxwLmRvY3NlbmQuY29tL2hjL2VuLXVz



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; CrOS x86_64 12239.92.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/76.0.3809.136 Safari/537.36' 'https://help.docsend.com/'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)