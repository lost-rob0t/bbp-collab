### HTTP Missing Security Headers (http-missing-security-headers:access-control-allow-origin) found on https://developers.dropbox.com

----
**Details**: **http-missing-security-headers:access-control-allow-origin** matched at https://developers.dropbox.com

**Protocol**: HTTP

**Full URL**: https://www.dropbox.com/developers

**Timestamp**: Sat Dec 9 14:54:58 +0000 UTC 2023

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
Host: developers.dropbox.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_2) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1944.0 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Transfer-Encoding: chunked
Accept-Encoding: identity,gzip
Cache-Control: no-cache, no-store
Content-Security-Policy: base-uri 'self' ; child-src https://www.dropbox.com/static/serviceworker/ blob: ; connect-src https://* ws://127.0.0.1:*/ws wss://dsimports.dropbox.com/ ; default-src 'none' ; font-src https://* data: ; form-action 'self' https://www.dropbox.com/ https://dl-web.dropbox.com/ https://photos.dropbox.com/ https://paper.dropbox.com/ https://showcase.dropbox.com/ https://www.hellofax.com/ https://app.hellofax.com/ https://www.hellosign.com/ https://app.hellosign.com/ https://docsend.com/ https://www.docsend.com/ https://help.dropbox.com/ https://navi.dropbox.jp/ https://a.sprig.com/ https://selfguidedlearning.dropboxbusiness.com/ https://instructorledlearning.dropboxbusiness.com/ https://sales.dropboxbusiness.com/ https://accounts.google.com/ https://api.login.yahoo.com/ https://login.yahoo.com/ https://experience.dropbox.com/ https://pal-test.adyen.com https://2e83413d8036243b-Dropbox-pal-live.adyenpayments.com/ ; frame-src https://* carousel: dbapi-6: dbapi-7: dbapi-8: dropbox-client: itms-apps: itms-appss: ; img-src https://* data: blob: ; media-src https://* blob: ; object-src 'self' https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ ; report-uri https://www.dropbox.com/csp_log?policy_name=metaserver-whitelist ; script-src 'unsafe-eval' https://www.dropbox.com/static/api/ https://www.dropbox.com/page_success/ https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ https://accounts.google.com/gsi/client https://canny.io/sdk.js https://www.google.com/recaptcha/ https://www.gstatic.com/recaptcha/ 'unsafe-inline' ; style-src https://* 'unsafe-inline' 'unsafe-eval' ; worker-src https://www.dropbox.com/static/serviceworker/ https://www.dropbox.com/encrypted_folder_download/service_worker.js blob:
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 14:54:57 GMT
Referrer-Policy: strict-origin-when-cross-origin
Server: envoy
Set-Cookie: gvc=MjQyMzg2MDA1MTUzMTIwNDk3OTcxMjM5NjU2NTc3NzM5NzkxMTY1; expires=Thu, 07 Dec 2028 14:54:57 GMT; HttpOnly; Path=/; Secure
Set-Cookie: t=KbpAmdqrdfT_ihjAygqhnmf7; Domain=dropbox.com; expires=Tue, 08 Dec 2026 14:54:57 GMT; HttpOnly; Path=/; Secure
Set-Cookie: __Host-js_csrf=KbpAmdqrdfT_ihjAygqhnmf7; expires=Tue, 08 Dec 2026 14:54:57 GMT; Path=/; Secure
Set-Cookie: locale=en; Domain=dropbox.com; expires=Thu, 07 Dec 2028 14:54:57 GMT; Path=/; Secure
Strict-Transport-Security: max-age=31536000; includeSubDomains
Strict-Transport-Security: max-age=31536000; includeSubDomains
Vary: Accept-Encoding
X-Content-Type-Options: nosniff
X-Dropbox-Request-Id: 2b7f24e4d33b4647b9cc53047127fec6
X-Dropbox-Response-Origin: far_remote
X-Frame-Options: DENY
X-Permitted-Cross-Domain-Policies: none
X-Xss-Protection: 1; mode=block

<!DOCTYPE html><html class="maestro maestro--responsive global-header" lang="en" xml:lang="en" xmlns="http://www.w3.org/1999/xhtml"><head><script nonce="yfxxNsLE57jGjdvt+tEz">
window._goch_ = {};
window.addEventListener('click', function(event) {
    'use strict';
    for (var elm = event.target; elm; elm = elm.parentElement) {
        if (elm.id &&
            window._goch_.hasOwnProperty(elm.id) &&
            window._goch_[elm.id].call(elm, event) === false) {
            event.preventDefault();
        }
    }
}, true);
window._csp_external_script_nonce = "3yqm77eCX9FV6x/z5wok"</script><link href="https://cfl.dropboxstatic.com" rel="preconnect" /><link href="https://cfl.dropboxstatic.com/static/metaserver/static/images/favicon-vfl8lUR9B.ico" rel="shortcut icon" /><title>DBX Platform for Developers - Dropbox</title><meta content="all" name="robots" /><link href="https://www.dropbox.com/developers" rel="canonical" /><link href="https://www.dropbox.com/da_DK/developers" hreflang="da-dk" rel="alternate" /><link href="https://www.dropbox.com/de/developers" hreflang="de-de" rel="alternate" /><link href="https://www.dropbox.com/developers" hreflang="en" rel="alternate" /><link href="https://www.dropbox.com/en_GB/developers" hreflang="en-gb" rel="alternate" /><link href="https://www.dropbox.com/es/developers" hreflang="es" rel="alternate" /><link href="https://www.dropbox.com/es_ES/developers" hreflang="es-es" rel="alternate" /><link href="https://www.dropbox.com/fr/developers" hreflang="fr" rel="alternate" /><link href="https://www.dropbox.com/fr_CA/developers" hreflang="fr-ca" rel="alternate" /><link href="https://www.dropbox.com/id/developers" hreflang="id-id" rel="alternate" /><link href="https://www.dropbox.com/it/developers" hreflang="it-it" rel="alternate" /><link href="https://www.dropbox.com/ja/developers" hreflang="ja-jp" rel="alternate" /><link href="https://www.dropbox.com/ko/developers" hreflang="ko-kr" rel="alternate" /><link href="https://www.dropbox.com/ms/developers" hreflang="ms-my" rel="alternate" /><link href="https://www.dropbox.com/nb_NO/developers" hreflang="nb-no" rel="alternate" /><link href="https://www.dropbox.com/nl_NL/developers" hreflang="nl-nl" rel=.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_2) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1944.0 Safari/537.36' 'https://developers.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)