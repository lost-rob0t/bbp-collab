### OSINT Extração de UUID (osint-extractor-uuid) found on https://www.dropbox.com

----
**Details**: **osint-extractor-uuid** matched at https://www.dropbox.com

**Protocol**: HTTP

**Full URL**: https://www.dropbox.com

**Timestamp**: Sat Dec 9 00:01:56 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | OSINT Extração de UUID |
| Authors | mrcl0wn / osint brazuca |
| Tags | uuid, consulta, osint |
| Severity | info |
| Description | Extração de UUID via expressão regular |

**Request**
```http
GET / HTTP/1.1
Host: www.dropbox.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2227.1 Safari/537.36
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
Content-Security-Policy: base-uri 'self' ; child-src https://www.dropbox.com/static/serviceworker/ blob: ; connect-src https://* ws://127.0.0.1:*/ws wss://dsimports.dropbox.com/ ; default-src 'none' ; font-src https://* data: ; form-action 'self' https://www.dropbox.com/ https://dl-web.dropbox.com/ https://photos.dropbox.com/ https://paper.dropbox.com/ https://showcase.dropbox.com/ https://www.hellofax.com/ https://app.hellofax.com/ https://www.hellosign.com/ https://app.hellosign.com/ https://docsend.com/ https://www.docsend.com/ https://help.dropbox.com/ https://navi.dropbox.jp/ https://a.sprig.com/ https://selfguidedlearning.dropboxbusiness.com/ https://instructorledlearning.dropboxbusiness.com/ https://sales.dropboxbusiness.com/ https://accounts.google.com/ https://api.login.yahoo.com/ https://login.yahoo.com/ https://experience.dropbox.com/ https://pal-test.adyen.com https://2e83413d8036243b-Dropbox-pal-live.adyenpayments.com/ ; frame-src https://* carousel: dbapi-6: dbapi-7: dbapi-8: dropbox-client: itms-apps: itms-appss: ; img-src https://* data: blob: ; media-src https://* blob: ; object-src 'self' https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ ; report-uri https://www.dropbox.com/csp_log?policy_name=metaserver-whitelist ; script-src 'unsafe-eval' https://www.dropbox.com/static/api/ https://www.dropbox.com/page_success/ https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ https://accounts.google.com/gsi/client https://canny.io/sdk.js 'nonce-A3sE2QzxEb6JBaS+iJI7' ; style-src https://* 'unsafe-inline' 'unsafe-eval' ; worker-src https://www.dropbox.com/static/serviceworker/ https://www.dropbox.com/encrypted_folder_download/service_worker.js blob:
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 00:01:48 GMT
Referrer-Policy: strict-origin-when-cross-origin
Server: envoy
Set-Cookie: gvc=NDMzNjgzNjc0NDY4ODUzMTYxMjg1ODg5NzY3MjIyNjAyMzc1NTk%3D; expires=Thu, 07 Dec 2028 00:01:48 GMT; HttpOnly; Path=/; Secure
Set-Cookie: t=xFbqt7tfMIYOtsc9X0gOV7Zl; Domain=dropbox.com; expires=Tue, 08 Dec 2026 00:01:47 GMT; HttpOnly; Path=/; Secure
Set-Cookie: __Host-js_csrf=xFbqt7tfMIYOtsc9X0gOV7Zl; expires=Tue, 08 Dec 2026 00:01:47 GMT; Path=/; Secure
Set-Cookie: locale=en; Domain=dropbox.com; expires=Thu, 07 Dec 2028 00:01:48 GMT; Path=/; Secure
Strict-Transport-Security: max-age=31536000; includeSubDomains
Strict-Transport-Security: max-age=31536000; includeSubDomains
Vary: Accept-Encoding
X-Content-Type-Options: nosniff
X-Dropbox-Request-Id: 35243dd9b06543a28a43b328e3a8d6e8
X-Dropbox-Response-Origin: far_remote
X-Frame-Options: DENY
X-Permitted-Cross-Domain-Policies: none
X-Xss-Protection: 1; mode=block

<!DOCTYPE html><html class="maestro maestro--responsive global-header" lang="en" xml:lang="en" xmlns="http://www.w3.org/1999/xhtml"><head><script nonce="A3sE2QzxEb6JBaS+iJI7">
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
window._csp_external_script_nonce = "R3LvcD1AVM9RwNtMdlic"</script><link href="https://cfl.dropboxstatic.com" rel="preconnect" /><link href="https://cfl.dropboxstatic.com/static/metaserver/static/images/favicon-vfl8lUR9B.ico" rel="shortcut icon" /><title>Dropbox.com</title><meta content="all" name="robots" /><link href="https://www.dropbox.com/" rel="canonical" /><link href="https://www.dropbox.com/da_DK/" hreflang="da-dk" rel="alternate" /><link href="https://www.dropbox.com/de/" hreflang="de-de" rel="alternate" /><link href="https://www.dropbox.com/" hreflang="en" rel="alternate" /><link href="https://www.dropbox.com/en_GB/" hreflang="en-gb" rel="alternate" /><link href="https://www.dropbox.com/es/" hreflang="es" rel="alternate" /><link href="https://www.dropbox.com/es_ES/" hreflang="es-es" rel="alternate" /><link href="https://www.dropbox.com/fr/" hreflang="fr" rel="alternate" /><link href="https://www.dropbox.com/fr_CA/" hreflang="fr-ca" rel="alternate" /><link href="https://www.dropbox.com/id/" hreflang="id-id" rel="alternate" /><link href="https://www.dropbox.com/it/" hreflang="it-it" rel="alternate" /><link href="https://www.dropbox.com/ja/" hreflang="ja-jp" rel="alternate" /><link href="https://www.dropbox.com/ko/" hreflang="ko-kr" rel="alternate" /><link href="https://www.dropbox.com/ms/" hreflang="ms-my" rel="alternate" /><link href="https://www.dropbox.com/nb_NO/" hreflang="nb-no" rel="alternate" /><link href="https://www.dropbox.com/nl_NL/" hreflang="nl-nl" rel="alternate" /><link href="https://www.dropbox.com/pl/" hreflang="pl-pl" rel="alternate" /><link href="https://www.dropbox.com/pt_BR/" hreflang="pt-br" rel="alternate" /><link href="https://www.dropbox.com/ru/" hreflang="ru-ru" rel="alternat.... Truncated ....
```

**Extra Information**

**Extracted results:**

- d587e174-e284-42e8-a18c-85c0d8e57e9e
- 27f665ce-74c5-4746-8b8c-61cd9e34aadd
- 80fdd51d-16da-4e7e-ba93-2b7ae408d2e4
- 048eb124-e2f8-43ad-a0b3-71acc76a2635
- 8AFFAA35-0217-4EF9-83C8-C62CF9EBCFB3
- 2008b1f6-a8b4-4303-aeb9-4c2c4bf78484
- bacc4706-0999-4aba-aecf-2289a6f0b33c
- 612f13ad-7264-48ac-9856-b60829cfc557
- 0eaff5fa-ffc5-41dd-bba1-4f05c5e32205
- e5339d6c-dcc7-477d-984b-7b2a039ca239
- 522e2ebf-a0ca-4b4b-9c0b-e399442719de
- 6e90bbc3-9cdb-4a09-af60-aed4cb16cbca
- 7e823734-e1e2-4676-bd8d-4e0887d1f3d4
- 411f20bf-600b-42f8-a5a5-508c48fc55f7
- 1545245b-6903-4636-9586-7e18dcb1085d
- 8871a3c9-3bb8-4abf-9ac5-d0ab2412b349
- b7cced4c-f6a4-4375-9eb9-28e53ea24d7a
- 311cb1d7-b5a5-4a01-8b7e-df63eb2c922c
- 68CECE5D-F360-8653-CA80-3CF99353DDD2
- 88a257c5-602b-48c0-bf49-e65aa2df21dd
- c6fb8e66-f6a0-4286-a8e2-5039067bd74b
- f718921a-2979-4312-b5ad-e40509c5efc2
- a1e675f4-8266-43ca-bb51-3b138d145ce3
- 5292c821-d047-4218-a4e1-72b01148e8ce
- de40db5c-8700-4100-9822-4ee6feff8e9f
- f9aee885-ea7b-4b1f-81fd-3e908dadc578
- d6f1841b-b694-417d-9d20-877aad41b4d9
- be7c9ef3-bc5a-424c-8892-02c70f18657b
- d39e724d-e9b4-4bf9-b448-6b92200606bf
- 419899FA-7FAF-5C1D-C027-BC34963E3A4F



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2227.1 Safari/537.36' 'https://www.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)