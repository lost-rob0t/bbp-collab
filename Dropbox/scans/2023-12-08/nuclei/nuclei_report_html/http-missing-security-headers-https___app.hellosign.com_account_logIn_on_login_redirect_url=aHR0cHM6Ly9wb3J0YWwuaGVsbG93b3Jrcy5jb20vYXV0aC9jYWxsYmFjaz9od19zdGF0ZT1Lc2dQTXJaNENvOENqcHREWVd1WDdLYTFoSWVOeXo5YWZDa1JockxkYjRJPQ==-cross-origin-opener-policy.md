### HTTP Missing Security Headers (http-missing-security-headers:cross-origin-opener-policy) found on https://portal.helloworks.com

----
**Details**: **http-missing-security-headers:cross-origin-opener-policy** matched at https://portal.helloworks.com

**Protocol**: HTTP

**Full URL**: https://app.hellosign.com/account/logIn?on_login_redirect_url=aHR0cHM6Ly9wb3J0YWwuaGVsbG93b3Jrcy5jb20vYXV0aC9jYWxsYmFjaz9od19zdGF0ZT1Lc2dQTXJaNENvOENqcHREWVd1WDdLYTFoSWVOeXo5YWZDa1JockxkYjRJPQ==

**Timestamp**: Sat Dec 9 14:55:42 +0000 UTC 2023

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
Host: portal.helloworks.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.1916.47 Safari/537.36
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
Content-Security-Policy: base-uri 'none'; connect-src 'self' https://client-api.arkoselabs.com https://cdn.arkoselabs.com https://www.google-analytics.com https://stats.g.doubleclick.net https://heapanalytics.com https://api.sprig.com/sdk/ https://sentry.io https://dpiprodesntls.112.2o7.net/b/ss/dpi.prod.esntls/1/JS-2.22.0/ https://www.dropbox.com/amplitude_proxy/ingest_lenient https://*.dropbox.com/log/ux_analytics; frame-ancestors 'self'; object-src 'none'; script-src https: https://api.userleap.com 'nonce-dSUhMVKgs0F/xkVbB0FDCEX/' 'unsafe-inline' 'strict-dynamic'; style-src 'self' https://cdn.arkoselabs.com https://code.ionicframework.com https://*.marketo.com https://fonts.googleapis.com https://cdn.hellosign.com 'unsafe-inline'; report-uri https://app.hellosign.com/csp_report; upgrade-insecure-requests
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 14:55:42 GMT
P3p: CP="NOP3PPOLICY"
Referrer-Policy: origin-when-cross-origin
Server: Apache
Set-Cookie: AWSALB=sf93YgKj6CN4POHLYtBlVX3zlpADmPmG3mNrPwNq7OVXv3Q19mM78YQfKF8YdnnADf1zyWEvq4FUnlsHoHTahnGfUlHhsYMzkhqERm6hbIlRS/JAkdORGw2gqOAy; Expires=Sat, 16 Dec 2023 14:55:42 GMT; Path=/
Set-Cookie: AWSALBCORS=sf93YgKj6CN4POHLYtBlVX3zlpADmPmG3mNrPwNq7OVXv3Q19mM78YQfKF8YdnnADf1zyWEvq4FUnlsHoHTahnGfUlHhsYMzkhqERm6hbIlRS/JAkdORGw2gqOAy; Expires=Sat, 16 Dec 2023 14:55:42 GMT; Path=/; SameSite=None; Secure
Set-Cookie: hf_user=ddc1ad69ec662aaebf7dc5c328a813bd9319b40df0201a35b445adc7adf26730:2694db2ee44f45d7d35ae7e5a505dd3c015d33be; path=/; domain=app.hellosign.com; secure; httponly
Set-Cookie: hf_ref=aHR0cHM6Ly9wb3J0YWwuaGVsbG93b3Jrcy5jb20vYXV0aCpbXSpodHRwczovL2FwcC5oZWxsb3NpZ24uY29tL2FjY291bnQvbG9nSW4/b25fbG9naW5fcmVkaXJlY3RfdXJsPWFIUjBjSE02THk5d2IzSjBZV3d1YUdWc2JHOTNiM0pyY3k1amIyMHZZWFYwYUM5allXeHNZbUZqYXo5b2QxOXpkR0YwWlQxTGMyZFFUWEphTkVOdk9FTnFjSFJFV1ZkMVdEZExZVEZvU1dWT2VYbzVZV1pEYTFKb2NreGtZalJKUFE9PQ==; expires=Mon, 08-Jan-2024 14:55:42 GMT; Max-Age=2592000; path=/; domain=hellosign.com
Set-Cookie: hf_ref_lt=aHR0cHM6Ly9wb3J0YWwuaGVsbG93b3Jrcy5jb20vYXV0aCpbXSpodHRwczovL2FwcC5oZWxsb3NpZ24uY29tL2FjY291bnQvbG9nSW4/b25fbG9naW5fcmVkaXJlY3RfdXJsPWFIUjBjSE02THk5d2IzSjBZV3d1YUdWc2JHOTNiM0pyY3k1amIyMHZZWFYwYUM5allXeHNZbUZqYXo5b2QxOXpkR0YwWlQxTGMyZFFUWEphTkVOdk9FTnFjSFJFV1ZkMVdEZExZVEZvU1dWT2VYbzVZV1pEYTFKb2NreGtZalJKUFE9PQ==; expires=Mon, 08-Jan-2024 14:55:42 GMT; Max-Age=2592000; path=/; domain=hellosign.com
Set-Cookie: hs_puuid=9a27d621c2ae41dffeb4010563f4cda29c670e26; expires=Tue, 06-Dec-2033 14:55:42 GMT; Max-Age=315360000; path=/; domain=hellosign.com
Set-Cookie: deferred_login_redirect_url=https://portal.helloworks.com/auth/callback?hw_state=KsgPMrZ4Co8CjptDYWuX7Ka1hIeNyz9afCkRhrLdb4I=; expires=Sat, 09-Dec-2023 16:25:42 GMT; Max-Age=5400; path=/; domain=hellosign.com
Strict-Transport-Security: max-age=31536000
Vary: Accept-Encoding
X-Content-Security-Policy: base-uri 'none'; connect-src 'self' https://client-api.arkoselabs.com https://cdn.arkoselabs.com https://www.google-analytics.com https://stats.g.doubleclick.net https://heapanalytics.com https://api.sprig.com/sdk/ https://sentry.io https://dpiprodesntls.112.2o7.net/b/ss/dpi.prod.esntls/1/JS-2.22.0/ https://www.dropbox.com/amplitude_proxy/ingest_lenient https://*.dropbox.com/log/ux_analytics; frame-ancestors 'self'; object-src 'none'; script-src https: https://api.userleap.com 'nonce-dSUhMVKgs0F/xkVbB0FDCEX/' 'unsafe-inline' 'strict-dynamic'; style-src 'self' https://cdn.arkoselabs.com https://code.ionicframework.com https://*.marketo.com https://fonts.googleapis.com https://cdn.hellosign.com 'unsafe-inline'; report-uri https://app.hellosign.com/csp_report; upgrade-insecure-requests
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Ua-Compatible: IE=Edge
X-Webkit-Csp: base-uri 'none'; connect-src 'self' https://client-api.arkoselabs.com https://cdn.arkoselabs.com https://www.google-analytics.com https://stats.g.doubleclick.net https://heapanalytics.com https://api.sprig.com/sdk/ https://sentry.io https://dpiprodesntls.112.2o7.net/b/ss/dpi.prod.esntls/1/JS-2.22.0/ https://www.dropbox.com/amplitude_proxy/ingest_lenient https://*.dropbox.com/log/ux_analytics; frame-ancestors 'self'; object-src 'none'; script-src https: https://api.userleap.com 'nonce-dSUhMVKgs0F/xkVbB0FDCEX/' 'unsafe-inline' 'strict-dynamic'; style-src 'self' https://cdn.arkoselabs.com https://code.ionicframework.com https://*.marketo.com https://fonts.googleapis.com https://cdn.hellosign.com 'unsafe-inline'; report-uri https://app.hellosign.com/csp_report; upgrade-insecure-requests

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
        <meta name="title" prop.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.1916.47 Safari/537.36' 'https://portal.helloworks.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)