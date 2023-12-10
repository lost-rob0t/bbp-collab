### Disclosed user ids in headers (user-id-headers) found on https://dropboxpartner.dropbox.com

----
**Details**: **user-id-headers** matched at https://dropboxpartner.dropbox.com

**Protocol**: HTTP

**Full URL**: https://www.dropbox.com/business/partners

**Timestamp**: Sat Dec 9 12:38:44 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Disclosed user ids in headers |
| Authors | panch0r3d |
| Tags |  |
| Severity | info |

**Request**
```http
GET / HTTP/1.1
Host: dropboxpartner.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64; rv:43.0) Gecko/20100101 Firefox/43.0
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
Content-Security-Policy: base-uri 'self' ; child-src https://www.dropbox.com/static/serviceworker/ blob: ; connect-src https://* ws://127.0.0.1:*/ws wss://dsimports.dropbox.com/ ; default-src 'none' ; font-src https://* data: ; form-action 'self' https://www.dropbox.com/ https://dl-web.dropbox.com/ https://photos.dropbox.com/ https://paper.dropbox.com/ https://showcase.dropbox.com/ https://www.hellofax.com/ https://app.hellofax.com/ https://www.hellosign.com/ https://app.hellosign.com/ https://docsend.com/ https://www.docsend.com/ https://help.dropbox.com/ https://navi.dropbox.jp/ https://a.sprig.com/ https://selfguidedlearning.dropboxbusiness.com/ https://instructorledlearning.dropboxbusiness.com/ https://sales.dropboxbusiness.com/ https://accounts.google.com/ https://api.login.yahoo.com/ https://login.yahoo.com/ https://experience.dropbox.com/ https://pal-test.adyen.com https://2e83413d8036243b-Dropbox-pal-live.adyenpayments.com/ https://www.salesforce.com/ https://app-sj01.marketo.com/ https://*:* ; frame-src https://* carousel: dbapi-6: dbapi-7: dbapi-8: dropbox-client: itms-apps: itms-appss: https://*:* ; img-src https://* data: blob: ; media-src https://* blob: ; object-src 'self' https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ ; report-uri https://www.dropbox.com/csp_log?policy_name=metaserver-whitelist ; script-src 'unsafe-eval' https://www.dropbox.com/static/api/ https://www.dropbox.com/page_success/ https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ https://accounts.google.com/gsi/client https://canny.io/sdk.js https://www.google.com/recaptcha/ https://www.gstatic.com/recaptcha/ 'unsafe-inline' ; style-src https://* 'unsafe-inline' 'unsafe-eval' ; worker-src https://www.dropbox.com/static/serviceworker/ https://www.dropbox.com/encrypted_folder_download/service_worker.js blob:
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 12:38:43 GMT
Referrer-Policy: strict-origin-when-cross-origin
Server: envoy
Set-Cookie: gvc=ODQ0NzY2Njc5NTczNjIzOTA5NzAyNzEzOTI4MzM2MjM1MTc3MDQ%3D; expires=Thu, 07 Dec 2028 12:38:43 GMT; HttpOnly; Path=/; Secure
Set-Cookie: t=prnwO2nMVx3q0v0pdXRWQOKG; Domain=dropbox.com; expires=Tue, 08 Dec 2026 12:38:43 GMT; HttpOnly; Path=/; Secure
Set-Cookie: __Host-js_csrf=prnwO2nMVx3q0v0pdXRWQOKG; expires=Tue, 08 Dec 2026 12:38:43 GMT; Path=/; Secure
Set-Cookie: locale=en; Domain=dropbox.com; expires=Thu, 07 Dec 2028 12:38:43 GMT; Path=/; Secure
Strict-Transport-Security: max-age=31536000; includeSubDomains
Strict-Transport-Security: max-age=31536000; includeSubDomains
Vary: Accept-Encoding
X-Content-Type-Options: nosniff
X-Dropbox-Request-Id: 94b975c94e4644cbba9aef345eaff1fe
X-Dropbox-Response-Origin: far_remote
X-Frame-Options: DENY
X-Permitted-Cross-Domain-Policies: none
X-Xss-Protection: 1; mode=block

<!DOCTYPE html><html class="maestro maestro--responsive global-header" lang="en" xml:lang="en" xmlns="http://www.w3.org/1999/xhtml"><head><script nonce="3YHkT3er92nGCVnvRKv1">
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
window._csp_external_script_nonce = "GpG+2abrhdU9xaEBiTuD"</script><link href="https://cfl.dropboxstatic.com" rel="preconnect" /><link href="https://cfl.dropboxstatic.com/static/metaserver/static/images/favicon-vfl8lUR9B.ico" rel="shortcut icon" /><title>Dropbox Partners Program</title><meta content="all" name="robots" /><link href="https://www.dropbox.com/business/partners" rel="canonical" /><link href="https://www.dropbox.com/da_DK/business/partners" hreflang="da-dk" rel="alternate" /><link href="https://www.dropbox.com/de/business/partners" hreflang="de-de" rel="alternate" /><link href="https://www.dropbox.com/business/partners" hreflang="en" rel="alternate" /><link href="https://www.dropbox.com/en_GB/business/partners" hreflang="en-gb" rel="alternate" /><link href="https://www.dropbox.com/es/business/partners" hreflang="es" rel="alternate" /><link href="https://www.dropbox.com/es_ES/business/partners" hreflang="es-es" rel="alternate" /><link href="https://www.dropbox.com/fr/business/partners" hreflang="fr" rel="alternate" /><link href="https://www.dropbox.com/fr_CA/business/partners" hreflang="fr-ca" rel="alternate" /><link href="https://www.dropbox.com/id/business/partners" hreflang="id-id" rel="alternate" /><link href="https://www.dropbox.com/it/business/partners" hreflang="it-it" rel="alternate" /><link href="https://www.dropbox.com/ja/business/partners" hreflang="ja-jp" rel="alternate" /><link href="https://www.dropbox.com/ko/business/partners" hreflang="ko-kr" rel="alternate" /><link href="https://www.dropbox.com/ms/business/partners" hreflang="ms-my" rel="alternat.... Truncated ....
```

**Extra Information**

**Extracted results:**

- accounts.google.com/ https://api.login.yahoo.com/ https://login.yahoo.com/ https://experience.dropbox.com/ https://pal-test.adyen.com https://2e83413d8036243b-Dropbox-pal-live.adyenpayments.com/ https://www.salesforce.com/ https://app-sj01.marketo.com/ https://*:* ; frame-src https://* carousel: dbapi-6: dbapi-7: dbapi-8: dropbox-client: itms-apps: itms-appss: https://*:* ; img-src https://* data: blob: ; media-src https://* blob: ; object-src 'self' https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ ; report-uri https://www.dropbox.com/csp_log?policy_name=metaserver-whitelist ; script-src 'unsafe-eval' https://www.dropbox.com/static/api/ https://www.dropbox.com/page_success/ https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ https://accounts.google.com/gsi/client https://canny.io/sdk.js https://www.google.com/recaptcha/ https://www.gstatic.com/recaptcha/ 'unsafe-inline' ; style-src https://* 'unsafe-inline' 'unsafe-eval' ; worker-src https://www.dropbox.com/static/serviceworker/ https://www.dropbox.com/encrypted_folder_download/service_worker.js blob:



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64; rv:43.0) Gecko/20100101 Firefox/43.0' 'https://dropboxpartner.dropbox.com/'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)