### Possible phone numbers extractor (extract-possible-phonenumbers) found on https://www.dropbox.com

----
**Details**: **extract-possible-phonenumbers** matched at https://www.dropbox.com

**Protocol**: HTTP

**Full URL**: https://www.dropbox.com

**Timestamp**: Sat Dec 9 00:02:01 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Possible phone numbers extractor |
| Authors | cipher387 |
| Tags | osint, juicy-info |
| Severity | info |
| Description | Extract possible phone numbers from web page body |

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

- 21.6934 7.75786
- 9.90375 8.97678
- 67530
- 79959
- 22.1465 18.6925
- 10.5588
- 41.5424 13.2924
- 28.2692 14.6993
- 83.8346 10.6951
- 71.3631 7.04932
- 26.1258 17.5177
- 1702080107901
- 7.70077 20.2234
- 69.1327 17.5177
- 18657
- 1702080107899
- 58.9851 14.6993
- 62.0443 10.6545
- 18.2854
- 18552376726
- 4706-0999-4
- 99353
- 63.0819 4.25851
- 47.6171 10.8303
- 47.6171 8.30233
- 0 0 93 22
- 48.7909 4.23092
- 23.8248 10.7755
- 27.1152 13.4206
- 0-4286
- 6211234
- 60829
- 210019893730
- 47.6171 11.1161
- 4-4375-9
- 19699.0
- 06543
- 50.9075 15.3849
- 13.1942 3.77605
- 55.9697 8.52216
- 15.1865
- 1702080108
- 85.7321 13.0709
- 0.285156
- 14.9242 15.6304
- 88.3798 4.55302
- 70.1438 8.35003
- 55.926 6.78302
- 30.1634 17.5177
- 0.478516 4
- 29.3687 14.0994
- 23.8248 6.51492
- 5-4746-8
- 45.5499 17.5672
- 46.3278 7.04932
- 2-4676
- 75.0427 7.04932
- 76.2184 10.8192
- 8.7974
- 1545245
- 47.6171 13.4463
- 6903-4636-9586
- 14.9242 4.91332
- 82.8859 17.1956
- 50.9075 6.56753
- 42.7661 7.04932
- 11.1161
- 33.1898 13.4426
- 57357
- 13.1942 14.9151
- 71.2978 14.6993
- 43.5215 17.5672
- 7.70076 0.320312
- 57.8695 17.5177
- 44.536 14.6993
- 6.08687
- 66.8534 15.2995
- 73.1703 17.5177
- 10.9622
- 556856
- 17.6436 4.55228
- 360-8653
- 92.4175 17.1956
- 30.1634 7.04932
- 38.252
- 14.9659 17.1956
- 9.90375 5.82472
- 4-8266-43
- 73.1703 4.23092
- 11.1269
- 10.6984
- 88.6666
- 56.6327 5.1366
- 13.1942 9.87184
- 9.90375 12.9444
- 8700-4100-9822
- 1702080107
- 42.1765 16.6635
- 33.1898 10.8192
- 20-877
- 22.1465 9.50633
- 11.3877
- 23.8248 11.1269
- 76.904 4.23092
- 66.8534 10.7755
- 0.285583
- 18.9493 7.75786
- 6.22439 1.57357
- 79.0027
- 4.39197
- 14.9242 24.8164
- 66.8534 11.1269
- 32.0141 7.04932
- 14.9659
- 10000
- 87.6517 10.6731
- 76.2184 11.1278
- 79.3777 4.55302
- 59.0288 7.04932
- 10.844
- 27.1152 11.1278
- 23.8248 15.2995
- 341760
- 22.1465 20.2234
- 65.3347 10.932
- 3.57601 4.39197
- 76.2184 13.4426
- 65.3347 6.34398
- 42.7224 14.6993
- 3.57601
- 2-5039067
- 62.0443 13.4682
- 57.1715 14.6993
- 0.478516 14
- 2425540
- 33.9405 17.5177
- 73.1702 14.6993
- 17.1956
- 79.0027 17.1956
- 58.0462 4.23656
- 83.1948
- 0.285583 1
- 30.1634 4.23092
- 200-1920
- 7.70076 9.50633
- 52.6793
- 38.252 4.56791
- 41.03 4.56791
- 32205
- 823734
- 419899
- 79.5089 15.2995
- 75.0645 14.6993
- 73.192 7.04932
- 19.8788 4.39197
- 92.1748
- 10.8192
- 41.5424 11.0502
- 8.35455 4.39197
- 35243
- 41.3608 6.94227
- +1 855-237-6726
- 33.1898 8.43822
- 18.0641 7.44987
- 9.79235
- 79.5089 11.1269
- 26.5165 4.23092
- 60.0561 4.23656
- 18.5731 5.42593
- 718921
- 93575
- 7.70076 18.6925
- 70.1438 11.1278
- 36.4802 11.1269
- 047-4218
- 55.9697 10.9622
- 62.0443 8.32431
- 41.493
- 50.9075 11.1967
- 18.2854 8.70383
- 10.0622 1.57357
- 8.39945 14.3772
- 57779
- 91332
- 11.1278
- 21.544
- 42.0442 5.31105
- 40509
- 694-417
- 78484
- 1702080107906
- 0 0 30 25
- 14.9242 14.0994
- 46.4152 14.6993
- 35-0217-4
- 10.7755
- 79.5089 6.55884
- 22.2466
- 34963
- 33.897 4.23092
- 33.1898 11.1278
- 2979-4312
- 8892-02
- 4336836744688531612
- 8588976722260237559
- 60.8862 14.6993
- 60.7769 7.04932
- 55.5505
- 36.4802 6.55884
- 32.0141 14.6993
- 1.4988290398126465
- 55.8155 14.8834
- 65.3347 15.1468
- 66.8534 6.51492
- 62.0443 10.9622
- 56.5002 16.5079
- 48.5484 17.5672
- 28.3345 7.04932
- 040850
- 29.3687 4.91332
- 76.9474 17.5177
- 10.2386 17.1956
- 1.7777777777777777
- 01148
- 92200606
- 85.7762 8.38529
- 57.2152 7.04932
- 10.8083
- 399442719
- 70.1438 13.4206
- 55.9697 13.3363
- 27.1152 8.35003
- 7264-48
- 1702080107821
- 327630330
- 22.1465 0.320312
- 30.1416 14.6993
- 23.0654
- 17.1884
- 44.6016 7.04932
- 6.31261
- 4-4303
- 45.5499 4.23092
- 43.4553 4.23092
- 41.5424 8.45621
- 6.19913 14.3772
- 1702080107902
- 69.5234 4.23092
- 63.2144 17.5177
- 36.4802 15.2995
- 284-42
- 76.2184 8.43822
- 59.9678 17.5177



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2227.1 Safari/537.36' 'https://www.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)