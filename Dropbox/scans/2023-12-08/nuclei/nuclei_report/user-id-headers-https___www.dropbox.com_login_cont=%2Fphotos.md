### Disclosed user ids in headers (user-id-headers) found on https://photos.dropbox.com

----
**Details**: **user-id-headers** matched at https://photos.dropbox.com

**Protocol**: HTTP

**Full URL**: https://www.dropbox.com/login?cont=%2Fphotos

**Timestamp**: Sat Dec 9 12:39:01 +0000 UTC 2023

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
Host: photos.dropbox.com
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
Content-Security-Policy: base-uri 'self' ; child-src https://www.dropbox.com/static/serviceworker/ blob: ; connect-src https://* ws://127.0.0.1:*/ws wss://dsimports.dropbox.com/ ; default-src 'none' ; font-src https://* data: ; form-action 'self' https://www.dropbox.com/ https://dl-web.dropbox.com/ https://photos.dropbox.com/ https://paper.dropbox.com/ https://showcase.dropbox.com/ https://www.hellofax.com/ https://app.hellofax.com/ https://www.hellosign.com/ https://app.hellosign.com/ https://docsend.com/ https://www.docsend.com/ https://help.dropbox.com/ https://navi.dropbox.jp/ https://a.sprig.com/ https://selfguidedlearning.dropboxbusiness.com/ https://instructorledlearning.dropboxbusiness.com/ https://sales.dropboxbusiness.com/ https://accounts.google.com/ https://api.login.yahoo.com/ https://login.yahoo.com/ https://experience.dropbox.com/ https://pal-test.adyen.com https://2e83413d8036243b-Dropbox-pal-live.adyenpayments.com/ ; frame-src https://* carousel: dbapi-6: dbapi-7: dbapi-8: dropbox-client: itms-apps: itms-appss: ; img-src https://* data: blob: ; media-src https://* blob: ; object-src 'self' https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ ; report-uri https://www.dropbox.com/csp_log?policy_name=metaserver-whitelist ; script-src 'unsafe-eval' https://www.dropbox.com/static/api/ https://www.dropbox.com/page_success/ https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ https://accounts.google.com/gsi/client https://canny.io/sdk.js https://www.google.com/recaptcha/ https://www.gstatic.com/recaptcha/ 'unsafe-inline' ; style-src https://* 'unsafe-inline' 'unsafe-eval' ; worker-src https://www.dropbox.com/static/serviceworker/ https://www.dropbox.com/encrypted_folder_download/service_worker.js blob:
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 12:39:01 GMT
Referrer-Policy: strict-origin-when-cross-origin
Server: envoy
Set-Cookie: __Host-logged-out-session=ChC84WfzpiVyv+hYHtd7QhYNEOS%2F0asGGi5BSWJTTkN5dFZQX09RNHB6THh5eGxJUFVESkhGYnBhMVFqLXE5eDI0OE5UOFBB; HttpOnly; Path=/; Secure
Set-Cookie: locale=en; Domain=dropbox.com; expires=Thu, 07 Dec 2028 12:39:01 GMT; Path=/; Secure
Strict-Transport-Security: max-age=31536000; includeSubDomains
Strict-Transport-Security: max-age=31536000; includeSubDomains
Vary: Accept-Encoding
X-Content-Type-Options: nosniff
X-Dropbox-Request-Id: 7eabb934c5674bd69963eb3000ea5721
X-Dropbox-Response-Origin: far_remote
X-Frame-Options: SAMEORIGIN
X-Permitted-Cross-Domain-Policies: none
X-Server-Response-Time: 314
X-Xss-Protection: 1; mode=block

<!DOCTYPE html><html class="media-desktop" lang="en" xml:lang="en" xmlns="http://www.w3.org/1999/xhtml" xmlns:fb="http://ogp.me/ns/fb#"><head><script nonce="sdXeBzSpf5Afbc5MbKPf">
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
window._csp_external_script_nonce = "eGXG0v1vuvYFR6FzduZe"</script><meta content="IE=edge, chrome=1" http-equiv="X-UA-Compatible" /><meta content="origin-when-cross-origin" name="referrer" /><link href="https://www.dropbox.com/login" rel="canonical" /><head><script nonce="sdXeBzSpf5Afbc5MbKPf">
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
window._csp_external_script_nonce = "eGXG0v1vuvYFR6FzduZe"</script><link href="https://cfl.dropboxstatic.com" rel="preconnect" /><link href="https://cfl.dropboxstatic.com" rel="dns-prefetch" /><link href="https://consent.dropbox.com" rel="preconnect" /><link href="https://consent.dropbox.com" rel="dns-prefetch" /><link href="https://accounts.google.com" rel="preconnect" /><link href="https://accounts.google.com" rel="dns-prefetch" /><link href="https://cfl.dropboxstatic.com/static/metaserver/static/images/favicon-vfl8lUR9B.ico" rel="shortcut icon" /><link href="https://cfl.dropboxstatic.com/static/metaserver/static/css/main-vflT4Sd9a.css" rel="stylesheet" type="text/css" /><style type="text/css">@media only screen and (max-width: 980px){.unsub-page-content{padding:10px 30px} .unsub-page-content p{padding-top:10px} }</style><script type="text/javascript" nonce="sdXeBzSpf5Afbc5MbKPf">window.ST=+new Date();</script><link href="https://cfl.dropboxstatic.com/static/metaserver/static/images/logo_catalog/dropbox_webclip_60_vis.png" rel="apple-touch-icon" /><link href="https://cfl.dropboxstatic.com/static/metaserver/static/images/logo_catalog/dropbox_webclip_76_vis.png" rel="apple-touch-i.... Truncated ....
```

**Extra Information**

**Extracted results:**

- accounts.google.com/ https://api.login.yahoo.com/ https://login.yahoo.com/ https://experience.dropbox.com/ https://pal-test.adyen.com https://2e83413d8036243b-Dropbox-pal-live.adyenpayments.com/ ; frame-src https://* carousel: dbapi-6: dbapi-7: dbapi-8: dropbox-client: itms-apps: itms-appss: ; img-src https://* data: blob: ; media-src https://* blob: ; object-src 'self' https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ ; report-uri https://www.dropbox.com/csp_log?policy_name=metaserver-whitelist ; script-src 'unsafe-eval' https://www.dropbox.com/static/api/ https://www.dropbox.com/page_success/ https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ https://accounts.google.com/gsi/client https://canny.io/sdk.js https://www.google.com/recaptcha/ https://www.gstatic.com/recaptcha/ 'unsafe-inline' ; style-src https://* 'unsafe-inline' 'unsafe-eval' ; worker-src https://www.dropbox.com/static/serviceworker/ https://www.dropbox.com/encrypted_folder_download/service_worker.js blob:



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64; rv:43.0) Gecko/20100101 Firefox/43.0' 'https://photos.dropbox.com/'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)