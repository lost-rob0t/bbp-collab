### Apple app site association for harvesting end points (apple-app-site-association) found on https://www.dropbox.com

----
**Details**: **apple-app-site-association** matched at https://www.dropbox.com

**Protocol**: HTTP

**Full URL**: https://www.dropbox.com/.well-known/apple-app-site-association

**Timestamp**: Sat Dec 9 08:58:25 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Apple app site association for harvesting end points |
| Authors | panch0r3d |
| Tags | misc, apple |
| Severity | info |

**Request**
```http
GET /.well-known/apple-app-site-association HTTP/1.1
Host: www.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.3319.102 Safari/537.36
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
Content-Type: application/json; charset=utf-8
Date: Sat, 09 Dec 2023 08:58:25 GMT
Referrer-Policy: strict-origin-when-cross-origin
Server: envoy
Set-Cookie: gvc=MTM0NTUyNDg0NDY3OTI0NzkwODA4MTA1MTk4NTg5MDQ0OTU5ODQ3; expires=Thu, 07 Dec 2028 08:58:25 GMT; HttpOnly; Path=/; Secure
Set-Cookie: t=gnwRcBseqV2MOrGb3iLyJQGW; Domain=dropbox.com; expires=Tue, 08 Dec 2026 08:58:25 GMT; HttpOnly; Path=/; Secure
Set-Cookie: __Host-js_csrf=gnwRcBseqV2MOrGb3iLyJQGW; expires=Tue, 08 Dec 2026 08:58:25 GMT; Path=/; Secure
Set-Cookie: locale=en; Domain=dropbox.com; expires=Thu, 07 Dec 2028 08:58:25 GMT; Path=/; Secure
Strict-Transport-Security: max-age=31536000; includeSubDomains
Strict-Transport-Security: max-age=31536000; includeSubDomains
Vary: Accept-Encoding
X-Content-Type-Options: nosniff
X-Dropbox-Is-Upstream-Batch: true
X-Dropbox-Request-Id: 5e3042789ad344929d6ba5d84474b81c
X-Dropbox-Response-Origin: far_remote
X-Frame-Options: SAMEORIGIN
X-Permitted-Cross-Domain-Policies: none
X-Server-Response-Time: 26
X-Xss-Protection: 1; mode=block


{
    "applinks": {
        "apps": [],
        "details": [
            {
                "appID": "8KM394JM3R.com.getdropbox.Dropbox",
                "paths": [
                    "/dl/*",
                    "/ga/*",
                    "/s/*",
                    "/sh/*",
                    "/spri/*",
                    "/scl/*",
                    "/l/dl/*",
                    "/l/ga/*",
                    "/l/login_via_email/*",
                    "/l/s/*",
                    "/l/sh/*",
                    "/l/spri/*",
                    "/l/scl/*",
                    "/family/join/*",
                    "NOT /transfer/",
                    "NOT /transfer/about",
                    "NOT /transfer/manage",
                    "/transfer/*"
                 ]
            },
            {
                "appID": "XGP696M5GC.com.dropbox.DropboxTest",
                "paths": [
                    "/dl/*",
                    "/ga/*",
                    "/s/*",
                    "/sh/*",
                    "/spri/*",
                    "/scl/*",
                    "/l/dl/*",
                    "/l/ga/*",
                    "/l/login_via_email/*",
                    "/l/s/*",
                    "/l/sh/*",
                    "/l/spri/*",
                    "/l/scl/*",
                    "/family/join/*",
                    "NOT /transfer/",
                    "NOT /transfer/about",
                    "NOT /transfer/manage",
                    "/transfer/*"
                 ]
            },
            {
                "appID": "8KM394JM3R.com.getdropbox.DropboxEMM",
                "paths": [
                    "/dl/*",
                    "/ga/*",
                    "/s/*",
                    "/sh/*",
                    "/spri/*",
                    "/scl/*",
                    "/l/dl/*",
                    "/l/ga/*",
                    "/l/login_via_email/*",
                    "/l/s/*",
                    "/l/sh/*",
                    "/l/spri/*",
                    "/l/scl/*",
                    "/family/join/*",
                    "NOT /transfer/",
 .... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.3319.102 Safari/537.36' 'https://www.dropbox.com/.well-known/apple-app-site-association'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)