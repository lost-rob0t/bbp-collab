### 帝发货100 M_id SQL注入漏洞（CNVD-2021-30193） (Shipped100-sqli) found on https://msoid.dropbox.com

----
**Details**: **Shipped100-sqli** matched at https://msoid.dropbox.com

**Protocol**: HTTP

**Full URL**: https://msoid.dropbox.com/?M_id=1%27&type=product

**Timestamp**: Sat Dec 9 08:20:41 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | 帝发货100 M_id SQL注入漏洞（CNVD-2021-30193） |
| Authors | str1am |
| Tags | shipped100, sqli |
| Severity | high |

**Request**
```http
GET /?M_id=1%27&type=product HTTP/1.1
Host: msoid.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.3319.102 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Cache-Control: no-store, no-cache
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 08:20:41 GMT
Expires: -1
Link: <https://aadcdn.msauth.net>; rel=preconnect; crossorigin
Link: <https://aadcdn.msauth.net>; rel=dns-prefetch
Link: <https://aadcdn.msftauth.net>; rel=dns-prefetch
P3p: CP="DSP CUR OTPi IND OTRi ONL FIN"
Pragma: no-cache
Set-Cookie: buid=0.AUgAqzBRR7ViQUKp00fjfJvCFakreHKQRANPjYJWI3DqNWYBAAA.AQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-0dfvcyDBgh20JEzuvI0lMu-FnXbKKwqCcUIkijfZvubMcxLm8jKECs2HVcWfC1Op1Hdui3K2O3hxJUso-AAG_5DI8Gnef9-fSp0Ls7a9GWMgAA; expires=Mon, 08-Jan-2024 08:20:41 GMT; path=/; secure; HttpOnly
Set-Cookie: esctx=PAQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-CKGHe1MhVznx4LNpIobAqhbRz8VWPp2dhbzuatd3DWN1FMuZGiZVDxV9UHANPtNNV6LOjvQJmw0WpDNsYxOfit3VAcyKVRKnHMatTl_GsmJhGowmb2_OA9vyV41Fc0XksL9Q5v8y4T5763-BMqN4ggvxQYTSRsL-bCRIl9WwQOwgAA; domain=.msoid.dropbox.com; path=/; secure; HttpOnly
Set-Cookie: esctx-R9WoS1RNwuI=AQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-Vzm2KdtBiSVn3F2YzdKU94sxSLfY7eyOKxaOSQtt1rkS9s9d1s1kwBVuAgVLjSXOYFJipium6umVHv18t-VAIJ52kj_x3MvRC8ejnhjrNxx9Uf_lSNpaVxksiL71MK5A3q9hNUQxFBrpHIqATcnuZSAA; domain=.msoid.dropbox.com; path=/; secure; HttpOnly
Set-Cookie: fpc=ApHIuO0EPllHsMq2QcLb4-e4vjNwAQAAAFkaBt0OAAAA; expires=Mon, 08-Jan-2024 08:20:41 GMT; path=/; secure; HttpOnly
Set-Cookie: x-ms-gateway-slice=estsfd; path=/; secure; httponly
Set-Cookie: stsservicecookie=estsfd; path=/; secure; httponly
Vary: Accept-Encoding
X-Content-Type-Options: nosniff
X-Dns-Prefetch-Control: on
X-Frame-Options: DENY
X-Ms-Ests-Server: 2.1.16942.4 - NEULR1 ProdSlices
X-Ms-Request-Id: a032a696-70c1-455b-9037-d00ad0b90300
X-Xss-Protection: 0



<!-- Copyright (C) Microsoft Corporation. All rights reserved. -->
<!DOCTYPE html>
<html dir="ltr" class="" lang="en">
<head>
    <title>Sign in to your account</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=2.0, user-scalable=yes">
    <meta http-equiv="Pragma" content="no-cache">
    <meta http-equiv="Expires" content="-1">
    <link rel="preconnect" href="https://aadcdn.msauth.net" crossorigin>
<meta http-equiv="x-dns-prefetch-control" content="on">
<link rel="dns-prefetch" href="//aadcdn.msauth.net">
<link rel="dns-prefetch" href="//aadcdn.msftauth.net">

    <meta name="PageID" content="ConvergedSignIn" />
    <meta name="SiteID" content="" />
    <meta name="ReqLC" content="9" />
    <meta name="LocLC" content="en" />

        <meta name="referrer" content="origin" />

        <meta name="format-detection" content="telephone=no" />

    <noscript>
        <meta http-equiv="Refresh" content="0; URL=https://login.windows.net/jsdisabled" />
    </noscript>

    
    
<meta name="robots" content="none" />

<script type="text/javascript">//<![CDATA[
$Config={"fShowPersistentCookiesWarning":false,"urlMsaSignUp":"https://login.live.com/oauth20_authorize.srf?scope=openid+profile+email+offline_access\u0026response_type=code\u0026client_id=51483342-085c-4d86-bf88-cf50c7252078\u0026response_mode=form_post\u0026redirect_uri=https%3a%2f%2flogin.windows.net%2fcommon%2ffederation%2foauth2msa\u0026state=rQQIARAA42Kw0skoKSkottLXL8gvKknM0cvNTC7KL85PK8nPy8nMS9VLzs_Vyy9Kz0wBsYqEuAQi5F6-7s2y81orObug0a55xixGzviczDKwylWMyoSN07_AyPiCkfEWk6B_UbpnSnixW2pKalFiSWZ-3gUWgVcsPAbMVhwcrAKMEgwKDD9YGBexAm2dtsxowcGCaNcJ5he4LuxkZjjFqu8TmeLtnlLqmlgalm5plJvu61tc6u6T7KWt7ZWe4mGaHWJcYFqQnxiYGxJqa2xlOIFNaAIb0yk2hg9sjB3sDLPYGQ5wMm7gYTzAy_CDb_ubhfd-T_z31uMVv05RebaJk2myRbphSkR2iEG4r2VQVpBJcJhTbo5PRaChd6mxd7J-cIWfub6r7QYBBgA1\u0026estsfed=1\u0026uaid=ebe91e586a8d4a3ead199b70813e8398\u0026signup=1\u0026lw=1\u0026fl=easi2\u0026fci=https%3a%2f%2fportal.microsoftonline.com.orgid.com","urlMsaLogout":"https://login.live.com/logout.srf?iframed_by=https%3a%2f%2flogin.windows.net","urlOtherIdpForget":"https://login.live.com/forgetme.srf?iframed_by=https%3a%2f%2flogin.windows.net","showCantAccessAccountLink":true,"urlGitHubFed":"https://login.live.com/oauth20_authorize.srf?scope=openid+profile+email+offline_access\u0026response_type=code\u0026client_id=51483342-085c-4d86-bf88-cf50c7252078\u0026response_mode=form_post\u0026redirect_uri=https%3a%2f%2flogin.windows.net%2fcommon%2ffederation%2foauth2msa\u0026state=rQQIARAA42Kw0skoKSkottLXL8gvKknM0cvNTC7KL85PK8nPy8nMS9VLzs_Vyy9Kz0wBsYqEuAQi5F6-7s2y81orObug0a55xixGzviczDKwylWMyoSN07_AyPiCkfEWk6B_UbpnSnixW2pKalFiSWZ-3gUWgVcsPAbMVhwcrAKMEgwKDD9YGBexAm2dtsxowcGCaNcJ5he4LuxkZjjFqu8TmeLtnlLqmlgalm5plJvu61tc6u6T7KWt7ZWe4mGaHWJcYFqQnxiYGxJqa2xlOIFNaAIb0yk2hg9sjB3sDLPYGQ5wMm7gYTzAy_CDb_ubhfd-T_z31uMVv05RebaJk2myRbphSkR2iEG4r2VQVpBJcJhTbo5PRaChd6mxd7J-cIWfub6r7QYBBgA1\u0026estsfed=1\u0026uaid=ebe91e586a8d4a3ead199b70813e8398\u0026fci=https%3a%2f%2fportal.microsoftonline.com.orgid.com\u0026idp_hint=github.com","arrExternalTrustedRealmFederatedIdps":[],"fShowSignInWithGitHubOnlyOnCredPicker":true,"fEnableShowResendCode":true,"iShowResendCodeDelay":900.... Truncated ....
```

References: 
- https://github.com/meljith-lab/mcon1/blob/821445cc974234cc6ce7367bc7fbcc4d6eb8aea5/yournuclei/shipped100-210609-054716.yaml

**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.3319.102 Safari/537.36' 'https://msoid.dropbox.com/?M_id=1%27&type=product'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)