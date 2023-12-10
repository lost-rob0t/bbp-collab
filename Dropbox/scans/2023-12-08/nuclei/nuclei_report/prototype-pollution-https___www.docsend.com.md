### Various PP fingerprints created by Sergey Bobrov(https://github.com/BlackFan) (prototype-pollution) found on https://www.docsend.com

----
**Details**: **prototype-pollution** matched at https://www.docsend.com

**Protocol**: HTTP

**Full URL**: https://www.docsend.com

**Timestamp**: Sat Dec 9 00:01:46 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Various PP fingerprints created by Sergey Bobrov(https://github.com/BlackFan) |
| Authors | yavolo |
| Tags | xss |
| Severity | info |

**Request**
```http
GET / HTTP/1.1
Host: www.docsend.com
User-Agent: Mozilla/5.0 (Windows NT 6.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2228.0 Safari/537.36
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
Cf-Ray: 8328f9ba6fe50190-CDG
Content-Type: text/html; charset=UTF-8
Cross-Origin-Embedder-Policy: require-corp
Cross-Origin-Opener-Policy: same-origin
Cross-Origin-Resource-Policy: same-origin
Date: Sat, 09 Dec 2023 00:01:46 GMT
Expires: Thu, 01 Jan 1970 00:00:01 GMT
Origin-Agent-Cluster: ?1
Permissions-Policy: accelerometer=(),autoplay=(),browsing-topics=(),camera=(),clipboard-read=(),clipboard-write=(),geolocation=(),gyroscope=(),hid=(),interest-cohort=(),magnetometer=(),microphone=(),payment=(),publickey-credentials-get=(),screen-wake-lock=(),serial=(),sync-xhr=(),usb=()
Referrer-Policy: same-origin
Server: cloudflare
Set-Cookie: __cf_bm=qlehKvfWVHPV9kQrk9Uyl.6OdEu5rZy0KXlzSLZ6UYA-1702080106-0-ATnaVth7+tVt5DmKKcK+DsgJQzJQbIoIRwGGEFCSMofd6AvszQuuHJXJRul6CmIX3SD03gbr6GB6H21nX9Ova9A=; path=/; expires=Sat, 09-Dec-23 00:31:46 GMT; domain=.docsend.com; HttpOnly; Secure; SameSite=None
Strict-Transport-Security: max-age=31536000; includeSubDomains; preload
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html lang="en-US"><head><title>Just a moment...</title><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><meta http-equiv="X-UA-Compatible" content="IE=Edge"><meta name="robots" content="noindex,nofollow"><meta name="viewport" content="width=device-width,initial-scale=1"><link href="/cdn-cgi/styles/challenges.css" rel="stylesheet"><meta http-equiv="refresh" content="375"></head><body class="no-js"><div class="main-wrapper" role="main"><div class="main-content"><noscript><div id="challenge-error-title"><div class="h2"><span class="icon-wrapper"><div class="heading-icon warning-icon"></div></span><span id="challenge-error-text">Enable JavaScript and cookies to continue</span></div></div></noscript></div></div><script>(function(){window._cf_chl_opt={cvId: '2',cZone: "www.docsend.com",cType: 'managed',cNounce: '67531',cRay: '8328f9ba6fe50190',cHash: '097ba7a3a8426bb',cUPMDTk: "\/?__cf_chl_tk=P5N7D4vzZkp4wAzYDaf2n4TbBtM02xW.gspfPqdjw68-1702080106-0-gaNycGzNChA",cFPWv: 'b',cTTimeMs: '1000',cMTimeMs: '375000',cTplV: 5,cTplB: 'cf',cK: "visitor-time",fa: "\/?__cf_chl_f_tk=P5N7D4vzZkp4wAzYDaf2n4TbBtM02xW.gspfPqdjw68-1702080106-0-gaNycGzNChA",md: "w_gkEcMGLrJusdxS9heS3P4WTMXZKHeRdw2FP5bCZVQ-1702080106-0-ASsQ2ShtBGvWpUOF81jfK_RDQL73PC1EuLQo7rpBFCBuvT_y-XJed0YbW9fk0CQIhgLvBbqv-j5dC8YQ5cb8d1uVTzTQRwbtwBvzSsL_QN8NHukxwEdkYKJKFF-bpGO7ndgL32OLU83Au3jlSSJ6iNM2DGg4bHsNW7HkM50SaXwcrhC9M4emqzbUUUkRYshyy8D7sRu1Oz82NAG301Am8xljVXW2d9PKm3D2fcSfUX9bvXvuJE3Oht3qATODPILVuWjQTR4FYmioAxal2RvuSs43mPE3wx-8ew5Mw1A0wiBkCX9qKw1ppkJacNyUWhNGjcjQ59XF9jRH123j0BUQvK2IqmnQXkbCagXIrppVFvg-FNtqVN-7GZ9bCJM2YGu5yFPeFez5w5d4SfT1uyqix5enMof5Xt5qRL6yePC7RaXDfZKLtk2-kHYFcr9WzMDkw8GzR0MfbdCFNcsuZE3rr5WFdDAuc7xXM4HVri6MxbPkz5eVZmo1IfGNABBYjZ2ObntMvyUIAf2Rq1cSZDoWRsIPqHO8gzcSNloesm8MwJFNfoC565EumcfS9ayeo9O01BoU-pReC9chA7h6D7aQSclKFfisHU-ok1F8uoSBHo53a-5JmxAqgJeYOsKvm3oBD8SPiliH0suwqNACZM26R29O6k1ByUbGBi15GAso1obJfMEuQkhGQy7to3uhKIUnZAOBapETrJPa-1mxQrmUh-K2z-E26R_yId8vl8wp_N7-5dNZl0SAzsfm_nBX_fCuJ52ARnvOyl3ieQvnYCemCXD11VQGTdSd7L5gm2WJ_xyHNFKTQ-c9jSXWn9qUsbOK6U0h-KhPdySsTiFCzKRiYOxWHi4jhxhC9mL6UMx821s2FxeUIT9VPooTg0FCnlNP0KzatjhEzVIxNUuZg9A3QbOST0sWjaTfcCj6UvKm5Ubpx7WWuh-AgXc_PIhrG-1YRKIKay0cm3THxLnkcpu27nsj6_hRCxGrxSVl0sQFK7fkI6PwOsqfVeALpQh1OzEf1XRwV8X5mvcslxfgYRkYgLYc9eZZ5KV2YUGP_8zAMkE7SIU_yOk7Ur-oSggSYlzFmaZB8Inye4jpZdYci0sIUxXZmkIWQMw-c2A1pjSyd-aj41FqsRFa_Ng0W2ubOTrRlYXGv7GSfzByh2M9sacyyq86B2YpwThIKAMo3F7SydzcxrN9P2wfUa6yxMcgz2nOW46YcaMx4EgVsUN4O7X7jk01SPrCqFvvu4j0gDm23EbjWZxU1cYsUXfe1NRxD-bTeY-86sdyrrZA-YQwhip_Cvk1yuyL6L3aw9539RXtK9VEpcC0JgzjY8MTqOnpwqXvbT3gVYPhkiGgA5S8qdPK_0aAz5r_rdqilbgDAiC8Wv7jv3wKnwk2xZ8jvhINDfu9kJbpVyUrW1PjdmnjrAZXrxkt3HUzRwWqHNQIrIIB1WGYkN5jLUv4xieVa4KhFfpmxUWmMZFnJDLx_FDGu_pgCguSuUB4PIFTkmhmJzUAd2Q_LU6X9mOIGQ1IDgUXbPuxTjrPlojODOnfgyPhTBrGB-iHGc5YFEgJ5TmK0MsPXhhkLnUXRWw23vfQ7UTesBuBJcOl7th-MQVwRlmrDMn8789ub3ILoEQ5Q3z7_GBnC0IDtb6flU7LXSenJlFeer0WwxSFP5-DlhI23ZVJgjULBG0iAd4NJGBEz30HZsM4X0SdwwbeLqVPPJeWQzausBiVGWbsr7czFKtnItAHmwAxcUneu0P4-VMbrWIkaFn8C_71I79fggYy0EfGHkdG5oZLDI9Ok7-lqxAO-HkwR29MbPTpJVWKw-oBbEswzH9HTj8z3cbwOOInMzUCQ_UKhdNz0IP9wCIvlXnHAqhXy8iLnemhnQV7vfo1h6LZ-MiaDI0AFJcy_Xc6OpxlIVLcyw9RmSGf1RlErt0FgWtNu-y9zgqrN3b3T9A8dyrk2wao9rbsY7aG1z1o4_96gQHS5fan0bN83xgd2v5sRIRExzi52MwMOkDWQyTzVx7JcSp1tAt_uVhHPpga_U6N6kJefehz2DBYunVd6x9oHI-85Al5ggcuz8BmGKCeZOnX8JqvturNJ4uX_aZLKvjUi9n9mprtuHXhngxV9KB-xLalZk0L_GPBpHU1QQr8gWo1-p4P51plxriuLU66S6wr0cwRvn6-GlK8A6SlSabYHuraLVfq1TaMSsL8uPrUTr91_CddkazXAHQzmTFGjc9eujuaAsRaoFhmXye65dXyAxhNxqk2-LErKAkOEkgs_a6oPur-hk1gOOcYv7nU0dFfAUqwNSUoZJ8gPs1nf9f797a6nt2Z86e2FzKjikAdxcY95D97WxTtkzpvBK8dvXNsm4mtaY0MbqPonnw6LgQmHFtq5YIHtBuZJl62pjlOTY9rGz33B1y-fH2clAutR1zHwfxFImzd68Hg7MtYil1kM5wB_cOF2PCo3n-yjC7PnNSu3ZFde-FNT7IXMOR1ShtmAFW6CSPLPP-dqeoswEmwX2i8NtKiEts",cRq: {ru: 'aHR0cHM6Ly93d3cuZG9jc2VuZC5jb20v',ra: 'TW96aWxsYS81LjAgKFdpbmRvd3MgTlQgNi4xKSBBcHBsZVdlYktpdC81MzcuMzYgKEtIVE1MLCBs.... Truncated ....
```

References: 
- https://github.com/yavolo/nuclei-templates/

**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2228.0 Safari/537.36' 'https://www.docsend.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)