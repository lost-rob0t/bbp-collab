### Pull back base64 encoded strings in the url body (handy for javascript and html files) (base-64-strings) found on https://spaces.dropbox.com

----
**Details**: **base-64-strings** matched at https://spaces.dropbox.com

**Protocol**: HTTP

**Full URL**: https://www.dropbox.com/login?cont=/spaces

**Timestamp**: Sat Dec 9 09:13:35 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Pull back base64 encoded strings in the url body (handy for javascript and html files) |
| Authors | panch0r3d |
| Tags |  |
| Severity | info |

**Request**
```http
GET / HTTP/1.1
Host: spaces.dropbox.com
User-Agent: Mozilla/5.0 (X11; CrOS x86_64 12239.92.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/76.0.3809.136 Safari/537.36
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
Content-Security-Policy: base-uri 'self' ; child-src https://www.dropbox.com/static/serviceworker/ blob: ; connect-src https://* ws://127.0.0.1:*/ws wss://dsimports.dropbox.com/ ; default-src 'none' ; font-src https://* data: ; form-action 'self' https://www.dropbox.com/ https://dl-web.dropbox.com/ https://photos.dropbox.com/ https://paper.dropbox.com/ https://showcase.dropbox.com/ https://www.hellofax.com/ https://app.hellofax.com/ https://www.hellosign.com/ https://app.hellosign.com/ https://docsend.com/ https://www.docsend.com/ https://help.dropbox.com/ https://navi.dropbox.jp/ https://a.sprig.com/ https://selfguidedlearning.dropboxbusiness.com/ https://instructorledlearning.dropboxbusiness.com/ https://sales.dropboxbusiness.com/ https://accounts.google.com/ https://api.login.yahoo.com/ https://login.yahoo.com/ https://experience.dropbox.com/ https://pal-test.adyen.com https://2e83413d8036243b-Dropbox-pal-live.adyenpayments.com/ ; frame-src https://* carousel: dbapi-6: dbapi-7: dbapi-8: dropbox-client: itms-apps: itms-appss: ; img-src https://* data: blob: ; media-src https://* blob: ; object-src 'self' https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ ; report-uri https://www.dropbox.com/csp_log?policy_name=metaserver-whitelist ; script-src 'unsafe-eval' https://www.dropbox.com/static/api/ https://www.dropbox.com/page_success/ https://cfl.dropboxstatic.com/static/ https://www.dropboxstatic.com/static/ https://accounts.google.com/gsi/client https://canny.io/sdk.js 'nonce-R3NNbltuAmqo+IVosB/A' ; style-src https://* 'unsafe-inline' 'unsafe-eval' ; worker-src https://www.dropbox.com/static/serviceworker/ https://www.dropbox.com/encrypted_folder_download/service_worker.js blob:
Content-Security-Policy: report-uri https://www.dropbox.com/csp_log?policy_name=metaserver-dynamic ; script-src 'unsafe-eval' 'strict-dynamic' 'nonce-R3NNbltuAmqo+IVosB/A' 'nonce-2Sn+hNMLjFvy4WX7Qnoc'
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 09:13:34 GMT
Referrer-Policy: strict-origin-when-cross-origin
Server: envoy
Set-Cookie: gvc=MjYwNTcyNzk3MTc1MzY0NTkzNDc0NTQzNDI5ODk5ODc4ODYwNjE1; expires=Thu, 07 Dec 2028 09:13:35 GMT; HttpOnly; Path=/; SameSite=None; Secure
Set-Cookie: __Host-logged-out-session=ChDONiOOyns6B80IiiCFIvoPEL%2Ff0KsGGi5BSVlwSm9sZEJ0a1BlZlBUWW5NOUVSZzlGS3VOU2dINi1rcUxlU1J0UXhGNmxB; HttpOnly; Path=/; SameSite=None; Secure
Set-Cookie: locale=en; Domain=dropbox.com; expires=Thu, 07 Dec 2028 09:13:35 GMT; Path=/; SameSite=None; Secure
Strict-Transport-Security: max-age=31536000; includeSubDomains
Strict-Transport-Security: max-age=31536000; includeSubDomains
Vary: Accept-Encoding
X-Content-Type-Options: nosniff
X-Dropbox-Request-Id: 6220cc049376497db17ab691b89295ab
X-Dropbox-Response-Origin: far_remote
X-Frame-Options: SAMEORIGIN
X-Permitted-Cross-Domain-Policies: none
X-Server-Response-Time: 295
X-Xss-Protection: 1; mode=block

<!DOCTYPE html><html class="media-desktop" lang="en" xml:lang="en" xmlns="http://www.w3.org/1999/xhtml" xmlns:fb="http://ogp.me/ns/fb#"><head><script nonce="R3NNbltuAmqo+IVosB/A">
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
window._csp_external_script_nonce = "2Sn+hNMLjFvy4WX7Qnoc"</script><meta content="IE=edge, chrome=1" http-equiv="X-UA-Compatible" /><meta content="origin-when-cross-origin" name="referrer" /><link href="https://www.dropbox.com/login" rel="canonical" /><head><script nonce="R3NNbltuAmqo+IVosB/A">
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
window._csp_external_script_nonce = "2Sn+hNMLjFvy4WX7Qnoc"</script><link href="https://cfl.dropboxstatic.com" rel="preconnect" /><link href="https://cfl.dropboxstatic.com" rel="dns-prefetch" /><link href="https://consent.dropbox.com" rel="preconnect" /><link href="https://consent.dropbox.com" rel="dns-prefetch" /><link href="https://accounts.google.com" rel="preconnect" /><link href="https://accounts.google.com" rel="dns-prefetch" /><link href="https://cfl.dropboxstatic.com/static/metaserver/static/images/favicon-vfl8lUR9B.ico" rel="shortcut icon" /><link href="https://cfl.dropboxstatic.com/static/metaserver/static/css/main-vflT4Sd9a.css" rel="stylesheet" type="text/css" /><style type="text/css">@media only screen and (max-width: 980px){.unsub-page-content{padding:10px 30px} .unsub-page-content p{padding-top:10px} }</style><script type="text/javascript" nonce=".... Truncated ....
```

**Extra Information**

**Extracted results:**

- aHR0cHM6Ly9zaWduLmRyb3Bib3guY29tLyo6ZHdnX2Zvb3Rlcl9wbGFuay0wZTdiM2NmMzA5X18wbnVtYmVydHJhZGVtYXJraGVsbG9zaWduLS0xNRKlAQoHRG9jU2VuZBJoaHR0cHM6Ly93d3cuZG9jc2VuZC5jb20vP3V0bV9tZWRpdW09UmVmZXJyYWwmdXRtX3NvdXJjZT1Ecm9wYm94JTIwV2ViJTIwUmVmZXJyYWwmdXRtX2NhbXBhaWduPWRieC1mb290ZXIaBl9ibGFuayooZHdnX2Zvb3Rlcl9wbGFuay0wZTdiM2NmMzA5X19kb2NzZW5kLS0xNhJCCgVQbGFucxIRL3BsYW5zP3RyaWdnZXI9bnIqJmR3Z19mb290ZXJfcGxhbmstMGU3YjNjZjMwOV9fcGxhbnMtLTE3ElUKD1Byb2R1Y3QgdXBkYXRlcxIQL3Byb2R1Y3QtdXBkYXRlcyowZHdnX2Zvb3Rlcl9wbGFuay0wZTdiM2NmMzA5X19wcm9kdWN0LXVwZGF0ZXMtLTE4Cu4FCgdTdXBwb3J0ElYKC0hlbHAgY2VudGVyEhlodHRwczovL2hlbHAuZHJvcGJveC5jb20vKixkd2dfZm9vdGVyX3BsYW5rLTBlN2IzY2YzMDlfX2hlbHAtY2VudGVyLS0xORJDCgpDb250YWN0IHVzEggvY29udGFjdCorZHdnX2Zvb3Rlcl9wbGFuay0wZTdiM2NmMzA5X19jb250YWN0LXVzLS0yMBJKCg9Qcml2YWN5ICYgdGVybXMSBi90ZXJtcyovZHdnX2Zvb3Rlcl9wbGFuay0wZTdiM2NmMzA5X19wcml2YWN5LS10ZXJtcy0tMjESewoNQ29va2llIHBvbGljeRI6aHR0cHM6Ly9oZWxwLmRyb3Bib3guY29tL2FjY291bnRzLWJpbGxpbmcvc2VjdXJpdHkvY29va2llcyouZHdnX2Zvb3Rlcl9wbGFuay0wZTdiM2NmMzA5X19jb29raWUtcG9saWN5LS0yMhJpChpDb29raWVzICYgQ0NQQSBwcmVmZXJlbmNlcxIPI21hbmFnZS1jb29raWVzKjpkd2dfZm9vdGVyX3BsYW5rLTBlN2IzY2YzMDlfX2Nvb2tpZXMtLWNjcGEtcHJlZmVyZW5jZXMtLTIzEk8KDUFJIHByaW5jaXBsZXMSDi9haS1wcmluY2lwbGVzKi5kd2dfZm9vdGVyX3BsYW5rLTBlN2IzY2YzMDlfX2FpLXByaW5jaXBsZXMtLTI0ElsKB1NpdGVtYXASJmh0dHBzOi8vZXhwZXJpZW5jZS5kcm9wYm94LmNvbS9zaXRlbWFwKihkd2dfZm9vdGVyX3BsYW5rLTBlN2IzY2YzMDlfX3NpdGVtYXAtLTI1EmQKEkxlYXJuaW5nIHJlc291cmNlcxIZaHR0cHM6Ly9sZWFybi5kcm9wYm94LmNvbSozZHdnX2Zvb3Rlcl9wbGFuay0wZTdiM2NmMzA5X19sZWFybmluZy1yZXNvdXJjZXMtLTI2CtAECglDb21tdW5pdHkSSAoEQmxvZxIZaHR0cHM6Ly9ibG9nLmRyb3Bib3guY29tLyolZHdnX2Zvb3Rlcl9wbGFuay0wZTdiM2NmMzA5X19ibG9nLS0yNxJdCgpEZXZlbG9wZXJzEiJodHRwczovL3d3dy5kcm9wYm94LmNvbS9kZXZlbG9wZXJzKitkd2dfZm9vdGVyX3BsYW5rLTBlN2IzY2YzMDlfX2RldmVsb3BlcnMtLTI4EmwKEENvbW11bml0eSBmb3J1bXMSHWh0dHBzOi8vd3d3LmRyb3Bib3hmb3J1bS5jb20vGgZfYmxhbmsqMWR3Z19mb290ZXJfcGxhbmstMGU3YjNjZjMwOV9fY29tbXVuaXR5LWZvcnVtcy0tMjkSPwoJUmVmZXJyYWxzEgYvcmVmZXIqKmR3Z19mb290ZXJfcGxhbmstMGU3YjNjZjMwOV9fcmVmZXJyYWxzLS0zMBJyChFSZXNlbGxlciBwYXJ0bmVycxIpaHR0cHM6Ly93d3cuZHJvcGJveC5jb20vYnVzaW5lc3MvcGFydG5lcnMqMmR3Z19mb290ZXJfcGxhbmstMGU3YjNjZjMwOV9fcmVzZWxsZXItcGFydG5lcnMtLTMxEncKFEludGVncmF0aW9uIHBhcnRuZXJzEihodHRwczovL3d3dy5kcm9wYm94LmNvbS9hcHAtaW50ZWdyYXRpb25zKjVkd2dfZm9vdGVyX3BsYW5rLTBlN2IzY2YzMDlfX2ludGVncmF0aW9uLXBhcnRuZXJzLS0zMgqiAwoHQ29tcGFueRI9CghBYm91dCB1cxIGL2Fib3V0Kilkd2dfZm9vdGVyX3BsYW5rLTBlN2IzY2YzMDlfX2Fib3V0LXVzLS0zMxJHCgRKb2JzEhhodHRwczovL2pvYnMuZHJvcGJveC5jb20qJWR3Z19mb290ZXJfcGxhbmstMGU3YjNjZjMwOV9fam9icy0tMzQSaQoSSW52ZXN0b3IgcmVsYXRpb25zEh5odHRwczovL2ludmVzdG9ycy5kcm9wYm94LmNvbS8qM2R3Z19mb290ZXJfcGxhbmstMGU3YjNjZjMwOV9faW52ZXN0b3ItcmVsYXRpb25zLS0zNRIxCgNFU0cSBC9lc2cqJGR3Z19mb290ZXJfcGxhbmstMGU3YjNjZjMwOV9fZXNnLS0zNhJxCg5GaW5kIGEgcGFydG5lchIuaHR0cHM6Ly9leHBlcmllbmNlLmRyb3Bib3guY29tL3BhcnRuZXItbG9jYXRvciovZHdnX2Zvb3Rlcl9wbGFuay0wZTdiM2NmMzA5X19maW5kLWEtcGFydG5lci0tMzcQARgBIAEyG2R3Z19mb290ZXJfcGxhbmstMGU3YjNjZjMwOToMZ3JhcGhpdGUtNjAwQghzdGFuZGFyZBpVCjpkcm9wYm94LXdhcnAvY29tcG9uZW50cy93YXJwL2R3Zy9kd2dfbG9jYWxlX3NlbGVjdG9yX3BsYW5rEhRkd2dfbG9jYWxlX3NlbGVjdG9yX7IDAFIA



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; CrOS x86_64 12239.92.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/76.0.3809.136 Safari/537.36' 'https://spaces.dropbox.com/'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)