### Monero wallets addresses extractor (extract-monero-wallet) found on https://www.dropbox.com

----
**Details**: **extract-monero-wallet** matched at https://www.dropbox.com

**Protocol**: HTTP

**Full URL**: https://www.dropbox.com

**Timestamp**: Sat Dec 9 00:02:00 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Monero wallets addresses extractor |
| Authors | cipher387 |
| Tags | osint, juicy-info, cryptocyrrency |
| Severity | info |
| Description | Extract monero wallets addresses from web page body |

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

- 4MS1oZXJvLTE5MjB4MTA4MC5tcDQaoAEKM2Ryb3Bib3gtd2FycC9jb21wb25lbnRzL3dhcnAvZHdnL2R3Z19oZWFkbGluZV
- 4c3RhdGljLmNvbS93YXJwL2NvbnZlcnNpb24vZHJvcGJveC93YXJwL2VuLXVzL2Ryb3Bib3gvcHJvZmVzc2lvbmFscy11aS
- 4c3RhdGljLmNvbS93YXJwL2NvbnZlcnNpb24vZHJvcGJveC93YXJwL2VuLXVzL2Ryb3Bib3gvNC41QitfZ3JhcGhpdGViZy
- 8gb2YgS2luZyBDaGlsZHJlbgrTIwpU4oCcQ3JlYXRpdmUgZ3Jvd3RoIGhhcHBlbnMgd2hlbiB5b3UgZG9u4oCZdCBoYXZlI
- 4NTUyMzc2NzI2Ghl1bmF2X2NvbnRhY3RfcGhvbmVfbnVtYmVyEsYBCgdHZXQgYXBwGi9kd2dfdW5pdmVyc2FsX25hdl9wbG
- 4ECiFTdGF5IGluIGNvbnRyb2wgb2Ygc2hhcmVkIGNvbnRlbnQqzwE8cD5UcmFja2FibGUgbGlua3Mgc2hvdyB3aGVuIHNvb
- 4L3dhcnAvZW4tdXMvZGFzaC9kYngtaGVhZGVyLWJsdXItMTkyMHgxMDgwLm1wNBqcAQozZHJvcGJveC13YXJwL2NvbXBvbm
- 4gdHJlbWVuZG91c2x5IGhlbHBmdWwgZm9yIHNvY2lhbCBtZWRpYS4gSSBjYW4gaG9wIG9uIGFueXRpbWUgYW5kIHB1bGwgd
- 8vd3d3LmRyb3Bib3guY29tL2ZlYXR1cmVzL2NvbnRlbnQtY29sbGFib3JhdGlvbhoVdW5hdl93aHlfY29ubmVjdHRlYW1zE
- 4GhR1bmF2X3Byb2R1Y3RfZHJvcGJveCItU3RvcmUsIHNoYXJlLCBhbmQgYWNjZXNzIGZpbGVzIGFjcm9zcyBkZXZpY2VzKp
- 8cD5XaXRoIERyb3Bib3gsIHlvdSBnZXQgYSBmdWxsIHN1aXRlIG9mIHRvb2xzIGRlc2lnbmVkIHRvIGhlbHAgeW91IGNyZW
- 4L3dhcnAvZW4tdXMvZHJvcGJveC9kcm9wYm94LW9uZS1ob21lcGFnZS1oZXJvLXVpLTAxLWdyYXBoaXRlMjAwLTE5MjB4MT
- 4PyoIZ3JhcGhpdGUyHWR3Z19oZWFkbGluZV9wbGFuay1mMDFhYzVlYjE5QghzdGFuZGFyZBrQNQo3ZHJvcGJveC13YXJwL2
- 4gb25lIHBsYWNlLjwvcD4ajBsKEEZvciBwZXJzb25hbCB1c2UabgpjChxHZXQgRHJvcGJveCBmb3IgcGVyc29uYWwgdXNlE
- 4wWlNPRE5FYUZWa2JXWldhbmxmYmxFaUxDSjJZWEpwWVc1MGN5STZJbXhsYjE5c1lYVnVZMmhmYzNkcGRHTm9PazlPSW4wL
- 4c3RhdGljLmNvbS93YXJwL2NvbnZlcnNpb24vZHJvcGJveC93YXJwL2ljb25zL2Ryb3Bib3gtc2lnbi1sb2dvLnN2Zz9pZD
- 4ejV2b3BrbF9kNDZVY19tWF83MVA4djNHYmNQbDVFbW5RblZuSnFwdUpfZjI3aEg4VF9kM1pOeUZSTWlMQ1FlYWRodmVTal
- 4oCZcyBpbXBvcnRhbnQgdG8geW91IGFuZCB5b3VyIGZhbWlseSBzaGFyZWFibGUgYW5kIHNhZmUgaW4gb25lIHBsYWNlLiB
- 8vZXhwZXJpZW5jZS5kcm9wYm94LmNvbS9kcm9wLWluLXZpZGVvLXNlcmllcy9raW5nLWNoaWxkcmVuKkFpbmRleF9kd2dfc
- 4gYmFja3VwEh5odHRwczovL3d3dy5kcm9wYm94LmNvbS9iYWNrdXAaFXVuYXZfd2h5X2Fsd2F5c2JhY2t1cBJpCg9TaWduI
- 4OTItMDJjNzBmMTg2NTdiJndpZHRoPTgyOCZvdXRwdXRfdHlwZT1qcGcYvAYgtBMqowFodHRwczovL2Zqb3JkLmRyb3Bib3
- 4L2RtZXAvZW4tdXMvYXNzZXRzL2FydGljbGVzL2N1c3RvbWVyLXN1Y2Nlc3Mtc3Rvcmllcy9jcmVhdGl2aXR5LWV4cGxvcm
- 4gdGhlcmUgdGhhdCB5b3UgcmVhbGx5IGxpa2Uu4oCdEgxTYWhpciBaYXZlcmkqqwEKmwEKE1JlYWQgdGhlIGZ1bGwgc3Rvc
- 4gc2VhcmNoIHlvdXIgZmF2b3JpdGUgYXBwcywgZW1haWxzLCBhbmQgbXVjaCBtb3JlIGluIHNlY29uZHMuPC9wPiJiChJHZ
- 4NGItN2IyYTAzOWNhMjM5CrIJCglTb2x1dGlvbnMaMWR3Z191bml2ZXJzYWxfbmF2X3BsYW5rLTRmMzZmNmIzNDVfX3NvbH
- 4zMTEzMzNaX3Byb2RfcHVibGlzaGVyX2RlZmF1bHQsbG9jYWxlOmVuLVVTLHBhdGg6L2NvbnRlbnQvZHJvcGJveC93YXJwL
- 4aWkzVU1MLVU3aTVYUkNFRGlfYUN5eXJWeGZPSmxLV2k5UG5fR3Byb1ltNHFON2FWa2NtdDJiampRWmpvbUE1VlpsdXNtZV
- 4c3RhdGljLmNvbS93YXJwL2NvbnZlcnNpb24vZHJvcGJveC93YXJwL2VuLXVzL2Rhc2gvZGJ4LWRhc2gtbHAtaGVhZGVyLW
- 4oCcRHJvcGJveCBlYXNpbHkgYWxsb3dzIG1lIHRvIHRyYW5zZmVyIHdoYXTigJlzIGluIG15IG1pbmQgdG8gYW5vdGhlciB
- 4ZHJvcGJveC13YXJwL2NvbXBvbmVudHMvd2FycC9kd2cvZHdnX3VuaXZlcnNhbF9uYXZfcGxhbmsSFGR3Z191bml2ZXJzYW
- 4c3RhdGljLmNvbS93YXJwL2NvbnZlcnNpb24vZHJvcGJveC93YXJwL2VuLXVzL2Ryb3Bib3gvZHJvcGJveC1vbmUtaG9tZX
- 8xMTk4NzY4NzAzsgJTEh5DbG91ZCBzdG9yYWdlIHlvdSBjYW4gY291bnQgb24qCGdyYXBoaXRlMh1kd2dfaGVhZGxpbmVfc
- 8vZXhwZXJpZW5jZS5kcm9wYm94LmNvbS9yZXNvdXJjZXMvc3VuZGFuY2Utc3VjY2Vzcy1zdG9yeSpBaW5kZXhfZHdnX3F1b
- 4c3RhdGljLmNvbS93YXJwL2NvbnZlcnNpb24vZHJvcGJveC9leHBlcmllbmNlL2VuLXVzL2Ryb3AtaW4tdmlkZW8tc2VyaW
- 8vd3d3LmRyb3Bib3guY29tL2J1c2luZXNzL3BhcnRuZXJzKjJkd2dfZm9vdGVyX3BsYW5rLTBlN2IzY2YzMDlfX3Jlc2Vsb
- 4cGVyaW1lbnRhbC9zdXNpX21vZGFsX3BsYW5rEhBzdXNpX21vZGFsX3BsYW5rogSoAxABGpoDCogDTUlJQklqQU5CZ2txaG



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2227.1 Safari/537.36' 'https://www.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)