### HTTP Missing Security Headers (http-missing-security-headers:clear-site-data) found on https://transfers.dropbox.com

----
**Details**: **http-missing-security-headers:clear-site-data** matched at https://transfers.dropbox.com

**Protocol**: HTTP

**Full URL**: https://www.dropbox.com/

**Timestamp**: Sat Dec 9 14:56:08 +0000 UTC 2023

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
Host: transfers.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 10.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/40.0.2214.93 Safari/537.36
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
Content-Security-Policy: base-uri 'self' ; child-src https://www.dropbox.com/static/serviceworker/ blob: ; connect-src https://* ws://127.0.0.1:*/ws wss://dsimports.dropbox.com/ ; default-src 'none' ; font-src https://* data: ; form-action 'self' https://www.dropbox.com/ https://dl-web.dropbox.com/ https://photos.dropbox.com/ https://paper.dropbox.com/ https://showcase.dropbox.com/ https://www.hellofax.com/ https://app.hellofax.com/ https://www.hellosign.com/ https://app.hellosign.com/ https://docsend.com/ https://www.docsend.com/ https://help.dropbox.com/ https://navi.dropbox.jp/ https://a.sprig.com/ https://selfguidedlearning.dropboxbusiness.com/ https://instructorledlearning.dropboxbusiness.com/ https://sales.dropboxbusiness.com/ https://accounts.google.com/ https://api.login.yahoo.com/ https://login.yahoo.com/ https://experience.dropbox.com/ https://pal-test.adyen.com https://2e83413d8036243b-Dropbox-pal-live.adyenpayments.com/ ; frame-src https://* carousel: dbapi-6: dbapi-7: dbapi-8: dropbox-client: itms-apps: itms-appss: ; img-src https://* data: blob: ; media-src https://* blob: ; object-src 'self' https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ ; report-uri https://www.dropbox.com/csp_log?policy_name=metaserver-whitelist ; script-src 'unsafe-eval' https://www.dropbox.com/static/api/ https://www.dropbox.com/page_success/ https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ https://accounts.google.com/gsi/client https://canny.io/sdk.js 'nonce-EKeQfOqN1dO//9TrSq34' ; style-src https://* 'unsafe-inline' 'unsafe-eval' ; worker-src https://www.dropbox.com/static/serviceworker/ https://www.dropbox.com/encrypted_folder_download/service_worker.js blob:
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 14:56:07 GMT
Referrer-Policy: strict-origin-when-cross-origin
Server: envoy
Set-Cookie: gvc=MTY3OTE5NTAxODU0Nzg3MzU5NjIzODA3NDQ0MzEyMTA2MjIxNDM2; expires=Thu, 07 Dec 2028 14:56:07 GMT; HttpOnly; Path=/; Secure
Set-Cookie: t=X_I42cdaqxU9c95Vi3S4uGFu; Domain=dropbox.com; expires=Tue, 08 Dec 2026 14:56:07 GMT; HttpOnly; Path=/; Secure
Set-Cookie: __Host-js_csrf=X_I42cdaqxU9c95Vi3S4uGFu; expires=Tue, 08 Dec 2026 14:56:07 GMT; Path=/; Secure
Set-Cookie: locale=en; Domain=dropbox.com; expires=Thu, 07 Dec 2028 14:56:07 GMT; Path=/; Secure
Strict-Transport-Security: max-age=31536000; includeSubDomains
Strict-Transport-Security: max-age=31536000; includeSubDomains
Vary: Accept-Encoding
X-Content-Type-Options: nosniff
X-Dropbox-Request-Id: 3056a006870c45b490c792959aeae8f5
X-Dropbox-Response-Origin: far_remote
X-Frame-Options: DENY
X-Permitted-Cross-Domain-Policies: none
X-Xss-Protection: 1; mode=block

<!DOCTYPE html><html class="maestro maestro--responsive global-header" lang="en" xml:lang="en" xmlns="http://www.w3.org/1999/xhtml"><head><script nonce="EKeQfOqN1dO//9TrSq34">
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
window._csp_external_script_nonce = "2jL/VV1xfGGPZ18I6sjP"</script><link href="https://cfl.dropboxstatic.com" rel="preconnect" /><link href="https://cfl.dropboxstatic.com/static/metaserver/static/images/favicon-vfl8lUR9B.ico" rel="shortcut icon" /><title>Dropbox.com</title><meta content="all" name="robots" /><link href="https://www.dropbox.com/" rel="canonical" /><link href="https://www.dropbox.com/da_DK/" hreflang="da-dk" rel="alternate" /><link href="https://www.dropbox.com/de/" hreflang="de-de" rel="alternate" /><link href="https://www.dropbox.com/" hreflang="en" rel="alternate" /><link href="https://www.dropbox.com/en_GB/" hreflang="en-gb" rel="alternate" /><link href="https://www.dropbox.com/es/" hreflang="es" rel="alternate" /><link href="https://www.dropbox.com/es_ES/" hreflang="es-es" rel="alternate" /><link href="https://www.dropbox.com/fr/" hreflang="fr" rel="alternate" /><link href="https://www.dropbox.com/fr_CA/" hreflang="fr-ca" rel="alternate" /><link href="https://www.dropbox.com/id/" hreflang="id-id" rel="alternate" /><link href="https://www.dropbox.com/it/" hreflang="it-it" rel="alternate" /><link href="https://www.dropbox.com/ja/" hreflang="ja-jp" rel="alternate" /><link href="https://www.dropbox.com/ko/" hreflang="ko-kr" rel="alternate" /><link href="https://www.dropbox.com/ms/" hreflang="ms-my" rel="alternate" /><link href="https://www.dropbox.com/nb_NO/" hreflang="nb-no" rel="alternate" /><link href="https://www.dropbox.com/nl_NL/" hreflang="nl-nl" rel="alternate" /><link href="https://www.dropbox.com/pl/" hreflang="pl-pl" rel="alternate" /><link href="https://www.dropbox.com/pt_BR/" hreflang="pt-br" rel="alternate" /><link href="https://www.dropbox.com/ru/" hreflang="ru-ru" rel="alternate".... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/40.0.2214.93 Safari/537.36' 'https://transfers.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)