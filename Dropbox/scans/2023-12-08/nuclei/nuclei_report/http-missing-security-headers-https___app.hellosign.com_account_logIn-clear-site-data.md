### HTTP Missing Security Headers (http-missing-security-headers:clear-site-data) found on https://app.hellosign.com

----
**Details**: **http-missing-security-headers:clear-site-data** matched at https://app.hellosign.com

**Protocol**: HTTP

**Full URL**: https://app.hellosign.com/account/logIn

**Timestamp**: Sat Dec 9 14:54:33 +0000 UTC 2023

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
Host: app.hellosign.com
User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/34.0.1866.237 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Cache-Control: private
Content-Security-Policy: base-uri 'none'; connect-src 'self' https://client-api.arkoselabs.com https://cdn.arkoselabs.com https://www.google-analytics.com https://stats.g.doubleclick.net https://heapanalytics.com https://api.sprig.com/sdk/ https://sentry.io https://dpiprodesntls.112.2o7.net/b/ss/dpi.prod.esntls/1/JS-2.22.0/ https://www.dropbox.com/amplitude_proxy/ingest_lenient https://*.dropbox.com/log/ux_analytics; frame-ancestors 'self'; object-src 'none'; script-src https: https://api.userleap.com 'nonce-pElc/Im8LoQWDsPQYRfip+yz' 'unsafe-inline' 'strict-dynamic'; style-src 'self' https://cdn.arkoselabs.com https://code.ionicframework.com https://*.marketo.com https://fonts.googleapis.com https://cdn.hellosign.com 'unsafe-inline'; report-uri https://app.hellosign.com/csp_report; upgrade-insecure-requests
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 14:54:33 GMT
P3p: CP="NOP3PPOLICY"
Referrer-Policy: origin-when-cross-origin
Server: Apache
Set-Cookie: AWSALB=l9OxcPzL1QJNTBl1vHXhteeMYDsIepmKwkjSCAO+0k/PRmzYMDm3jYBuhEKGXymTn2dOM1HsSj8qOzvGZ0BREXA2ebuhAkKkyw57EuEthcMJ1cS0De8X5N3MibFL; Expires=Sat, 16 Dec 2023 14:54:33 GMT; Path=/
Set-Cookie: AWSALBCORS=l9OxcPzL1QJNTBl1vHXhteeMYDsIepmKwkjSCAO+0k/PRmzYMDm3jYBuhEKGXymTn2dOM1HsSj8qOzvGZ0BREXA2ebuhAkKkyw57EuEthcMJ1cS0De8X5N3MibFL; Expires=Sat, 16 Dec 2023 14:54:33 GMT; Path=/; SameSite=None; Secure
Set-Cookie: hf_ref_lt=aHR0cHM6Ly9hcHAuaGVsbG9zaWduLmNvbSpbXSpodHRwczovL2FwcC5oZWxsb3NpZ24uY29tL2FjY291bnQvbG9nSW4=; expires=Mon, 08-Jan-2024 14:54:33 GMT; Max-Age=2592000; path=/; domain=hellosign.com
Strict-Transport-Security: max-age=31536000
Vary: Accept-Encoding
X-Content-Security-Policy: base-uri 'none'; connect-src 'self' https://client-api.arkoselabs.com https://cdn.arkoselabs.com https://www.google-analytics.com https://stats.g.doubleclick.net https://heapanalytics.com https://api.sprig.com/sdk/ https://sentry.io https://dpiprodesntls.112.2o7.net/b/ss/dpi.prod.esntls/1/JS-2.22.0/ https://www.dropbox.com/amplitude_proxy/ingest_lenient https://*.dropbox.com/log/ux_analytics; frame-ancestors 'self'; object-src 'none'; script-src https: https://api.userleap.com 'nonce-pElc/Im8LoQWDsPQYRfip+yz' 'unsafe-inline' 'strict-dynamic'; style-src 'self' https://cdn.arkoselabs.com https://code.ionicframework.com https://*.marketo.com https://fonts.googleapis.com https://cdn.hellosign.com 'unsafe-inline'; report-uri https://app.hellosign.com/csp_report; upgrade-insecure-requests
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Ua-Compatible: IE=Edge
X-Webkit-Csp: base-uri 'none'; connect-src 'self' https://client-api.arkoselabs.com https://cdn.arkoselabs.com https://www.google-analytics.com https://stats.g.doubleclick.net https://heapanalytics.com https://api.sprig.com/sdk/ https://sentry.io https://dpiprodesntls.112.2o7.net/b/ss/dpi.prod.esntls/1/JS-2.22.0/ https://www.dropbox.com/amplitude_proxy/ingest_lenient https://*.dropbox.com/log/ux_analytics; frame-ancestors 'self'; object-src 'none'; script-src https: https://api.userleap.com 'nonce-pElc/Im8LoQWDsPQYRfip+yz' 'unsafe-inline' 'strict-dynamic'; style-src 'self' https://cdn.arkoselabs.com https://code.ionicframework.com https://*.marketo.com https://fonts.googleapis.com https://cdn.hellosign.com 'unsafe-inline'; report-uri https://app.hellosign.com/csp_report; upgrade-insecure-requests

<!doctype html>
<html 
lang="en"
>
    <head>
        <meta charset="utf-8">
        <meta http-equiv="x-ua-compatible" content="ie=edge">
        <title>Log In | Dropbox Sign</title>
        <link rel="canonical" href="/account/login"></link>

        <meta name="viewport" content="width=device-width, initial-scale=1">

        <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<meta http-equiv="X-Ua-Compatible" content="IE=Edge" />
        <meta name="title" property="title" content="Log In | Dropbox Sign" />
<meta name="robots" property="robots" content="index,follow" />
<meta name="format-detection" property="format-detection" content="telephone=no" />
        <link rel="preconnect" href="https://fonts.gstatic.com"><link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Taviraj:regular,500&amp;subset=latin,latin-ext" media="all">        <link rel="stylesheet" type="text/css" media="screen" href="https://cdn.hellosign.com/1.170.0/css/../build/hellospa.css" />
        <link rel="apple-touch-icon" href="https://cdn.hellosign.com/1.170.0/images/icons/hs/apple-touch-icon.png" />        <link rel="shortcut icon" href="https://cdn.hellosign.com/1.170.0/images/dropbox-sign-favicon.ico" />        <script type="text/javascript" nonce="pElc/Im8LoQWDsPQYRfip+yz">
    var cookieDomain = location.hostname.split(".").slice(-2).join(".");
    document.cookie = "hs_consent_banner_enabled=true; Domain="+cookieDomain;

    if (!window.dropbox) { window.dropbox = {}; }
    if (!window.dropbox.privacyConsent) { window.dropbox.privacyConsent = {}; }

    window.dropbox.privacyConsent.autoInit = {
        thirdPartyConfig: {
            c.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/34.0.1866.237 Safari/537.36' 'https://app.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)