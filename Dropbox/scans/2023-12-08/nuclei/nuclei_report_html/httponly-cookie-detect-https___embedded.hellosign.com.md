### HttpOnly Cookie - Detect (httponly-cookie-detect) found on https://embedded.hellosign.com

----
**Details**: **httponly-cookie-detect** matched at https://embedded.hellosign.com

**Protocol**: HTTP

**Full URL**: https://embedded.hellosign.com

**Timestamp**: Sat Dec 9 00:00:54 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | HttpOnly Cookie - Detect |
| Authors | mr. bobo hp |
| Tags | misconfig, http, cookie, generic |
| Severity | info |
| Description | Checks whether cookies in the HTTP response contain the HttpOnly attribute. If the HttpOnly flag is set, it means that the cookie is HTTP-only<br> |
| CVSS-Metrics | [CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:N](https://www.first.org/cvss/calculator/3.0#CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:N) |
| CVSS-Score | 0.00 |

**Request**
```http
GET / HTTP/1.1
Host: embedded.hellosign.com
User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux i686 on x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/53.0.2820.59 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 404 Not Found
Connection: close
Content-Length: 46
Access-Control-Allow-Headers: Authorization, Origin, X-Requested-With, Content-Type, Accept
Access-Control-Allow-Methods: GET, POST, OPTIONS
Access-Control-Allow-Origin: *
Cache-Control: private
Content-Security-Policy: base-uri 'none'; connect-src 'self' https://www.google-analytics.com https://heapanalytics.com https://api.sprig.com/sdk/ https://sentry.io https://ekr.zdassets.com https://hellosign.zendesk.com wss://hellosign.zendesk.com https://www.dropbox.com/amplitude_proxy/ingest_lenient; frame-ancestors 'self'; object-src 'none'; script-src https: 'report-sample' 'nonce-rpWer3ibZbi4CQ50isl1e8o/' 'unsafe-inline' 'strict-dynamic'; style-src 'self' https://fonts.googleapis.com https://heapanalytics.com https://cdn.hellosign.com 'unsafe-inline'; report-uri https://app.hellosign.com/csp_report; upgrade-insecure-requests
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 00:00:54 GMT
P3p: CP="NOP3PPOLICY"
Referrer-Policy: origin-when-cross-origin
Server: Apache
Set-Cookie: AWSALB=pfKp2KJ5p06Dpz07HHNu9OQ67Y6BjUgXqS/xMS19PZ74aCyVX/Jgfyrvom4Ul0Q8qJV76Kq8ydxIk+bN1bDEpI3pQDcZ9MaJAo+/RgKa25UTeF27fmeNcepFweZB; Expires=Sat, 16 Dec 2023 00:00:53 GMT; Path=/
Set-Cookie: AWSALBCORS=pfKp2KJ5p06Dpz07HHNu9OQ67Y6BjUgXqS/xMS19PZ74aCyVX/Jgfyrvom4Ul0Q8qJV76Kq8ydxIk+bN1bDEpI3pQDcZ9MaJAo+/RgKa25UTeF27fmeNcepFweZB; Expires=Sat, 16 Dec 2023 00:00:53 GMT; Path=/; SameSite=None; Secure
Set-Cookie: __Host-hf_user=b9f42e4e658c74be2b6334a910e549ac41b938f8c61fca1f10b5a8f6da2a3d1a:9e6760c174078a3bfa0201ea705848dabdafe017; path=/; secure; httponly; samesite=none
Set-Cookie: hf_ref=KltdKmh0dHBzOi8vZW1iZWRkZWQuaGVsbG9zaWduLmNvbS8=; expires=Mon, 08-Jan-2024 00:00:54 GMT; Max-Age=2592000; path=/; domain=hellosign.com
Set-Cookie: hf_ref_lt=KltdKmh0dHBzOi8vZW1iZWRkZWQuaGVsbG9zaWduLmNvbS8=; expires=Mon, 08-Jan-2024 00:00:54 GMT; Max-Age=2592000; path=/; domain=hellosign.com
Set-Cookie: hs_embedded_puuid=23215fb74688c478a17c866446747e8bb3aaa679; expires=Tue, 06-Dec-2033 00:00:54 GMT; Max-Age=315360000; path=/; domain=hellosign.com
Status: 404 Not Found
Strict-Transport-Security: max-age=31536000
X-Content-Security-Policy: base-uri 'none'; connect-src 'self' https://www.google-analytics.com https://heapanalytics.com https://api.sprig.com/sdk/ https://sentry.io https://ekr.zdassets.com https://hellosign.zendesk.com wss://hellosign.zendesk.com https://www.dropbox.com/amplitude_proxy/ingest_lenient; frame-ancestors 'self'; object-src 'none'; script-src https: 'report-sample' 'nonce-rpWer3ibZbi4CQ50isl1e8o/' 'unsafe-inline' 'strict-dynamic'; style-src 'self' https://fonts.googleapis.com https://heapanalytics.com https://cdn.hellosign.com 'unsafe-inline'; report-uri https://app.hellosign.com/csp_report; upgrade-insecure-requests
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Ua-Compatible: IE=Edge
X-Webkit-Csp: base-uri 'none'; connect-src 'self' https://www.google-analytics.com https://heapanalytics.com https://api.sprig.com/sdk/ https://sentry.io https://ekr.zdassets.com https://hellosign.zendesk.com wss://hellosign.zendesk.com https://www.dropbox.com/amplitude_proxy/ingest_lenient; frame-ancestors 'self'; object-src 'none'; script-src https: 'report-sample' 'nonce-rpWer3ibZbi4CQ50isl1e8o/' 'unsafe-inline' 'strict-dynamic'; style-src 'self' https://fonts.googleapis.com https://heapanalytics.com https://cdn.hellosign.com 'unsafe-inline'; report-uri https://app.hellosign.com/csp_report; upgrade-insecure-requests

<h2>
    Sorry, that page doesn't exist!
</h2>
```

References: 
- https://stackoverflow.com/questions/4316539/how-do-i-test-httponly-cookie-flag

**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux i686 on x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/53.0.2820.59 Safari/537.36' 'https://embedded.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)