### Possible phone numbers extractor (extract-possible-phonenumbers) found on https://investors.dropbox.com

----
**Details**: **extract-possible-phonenumbers** matched at https://investors.dropbox.com

**Protocol**: HTTP

**Full URL**: https://investors.dropbox.com

**Timestamp**: Sat Dec 9 00:01:09 +0000 UTC 2023

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
Host: investors.dropbox.com
User-Agent: Mozilla/5.0 (X11; OpenBSD i386) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.125 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Accept-Ranges: bytes
Cache-Control: public, max-age=0, s-maxage=2700
Content-Language: en
Content-Security-Policy: default-src 'self' bam-cell.nr-data.net bam.nr-data.net cm.everesttech.net thomsonreuterscorporategroupweb.sc.omtrdc.net *.demdex.net www.google-analytics.com www.googletagmanager.com www.adobetag.com *.facebook.net api.nasdaqomx.wallst.com www.google.com *.addthis.com *.addthisedge.com www.googleadservices.com thomsonreuterscorporategroupweb.d2.sc.omtrdc.net stats.g.doubleclick.net *.sharethis.com *.pixel.parsely.com www.recaptcha.net www.gstatic.com c212.net pixel.mathtag.com *.kscope.io *.globenewswire.com *.accesswire.com *.businesswire.com *.prnewswire.com *.c212.net *.youtube.com *.vimeo.com *.media-server.com ds-aksb-a.akamaihd.net media.corporate-ir.net *.unisonir.com http://cloudinary.com *.segment.com uninav.notified.com www.facebook.com *.dropbox.com; connect-src 'self' *.uni.wdc.west.com *.sharethis.com *.unisonir.com *.demdex.net bam-cell.nr-data.net bam.nr-data.net api.segment.io thomsonreuterscorporategroupweb.sc.omtrdc.net *.akamaihd.net uninav.notified.com *.kscope.io; font-src 'self' fonts.googleapis.com cloud.typography.com fonts.gstatic.com uninav.notified.com stackpath.bootstrapcdn.com *.kscope.io cdn.jsdelivr.net; frame-src 'self' s7.addthis.com tools.eurolandir.com www.google.com *.sharethis.com api.nasdaqomx.wallst.com *.demdex.net www.recaptcha.net cloudinary.com https://player.cloudinary.com http://login.notified.com https://www.slideshare.net https://consent.dropbox.com/ https://www.dropbox.com https://www.youtube.com/ *.facebook.com; object-src 'self'; script-src 'self' 'unsafe-inline' 'unsafe-eval' *.recaptcha.net js-agent.newrelic.com *.jquery.com *.gstatic.com bam-cell.nr-data.net bam.nr-data.net *.akamaihd.net uninav.notified.com assets.adobedtm.com https://media-library.cloudinary.com https://uninav.notified.com https://upload-widget.cloudinary.com https://www.google.com www.google.com; script-src-elem 'self' 'unsafe-inline' *.uni.wdc.west.com s7.addthis.com www.google.com www.googletagmanager.com www.google-analytics.com siteimproveanalytics.com cdn.parsely.com www.adobetag.com www.recaptcha.net www.gstatic.com *.sharethis.com ds-aksb-a.akamaihd.net sec.kscope.io *.unisonir.com js-agent.newrelic.com bam-cell.nr-data.net bam.nr-data.net code.jquery.com cdn.segment.com *.pendo.io *.notified.com intrado.kscope.io www.dropbox.com connect.facebook.net *.kscope.io cfl.dropboxstatic.com assets.adobedtm.com https://media-library.cloudinary.com https://uninav.notified.com https://upload-widget.cloudinary.com https://www.google.com; style-src 'self' 'unsafe-inline' uninav.notified.com fonts.googleapis.com https://uninav.notified.com maxcdn.bootstrapcdn.com stackpath.bootstrapcdn.com https://cdn.jsdelivr.net; style-src-elem 'self' 'unsafe-inline' fonts.googleapis.com *.uni.wdc.west.com *.sharethis.com www.google.com ajax.googleapis.com sec.kscope.io *.unisonir.com www.gstatic.com stackpath.bootstrapcdn.com maxcdn.bootstrapcdn.com https://uninav.notified.com *.pendo.io intrado.kscope.io *.kscope.io https://cdn.jsdelivr.net; form-action 'self' *.dropbox.com *.facebook.com; frame-ancestors 'self' www.dropbox.com
Content-Type: text/html; charset=UTF-8
Date: Sat, 09 Dec 2023 00:01:05 GMT
Etag: "1702078578"
Expect-Ct: max-age=0, report-uri="/report-expect-ct-violation"
Expires: Sat, 09 Dec 2023 00:01:05 GMT
Feature-Policy: accelerometer 'none';ambient-light-sensor 'none';autoplay 'self';camera 'none';encrypted-media 'none';fullscreen *;geolocation 'self';gyroscope 'none';magnetometer 'none';microphone 'none';midi 'none';payment 'none';picture-in-picture 'none';speaker 'self';sync-xhr 'self';usb 'none';vibrate 'none';vr 'none'
From-Origin: same
Last-Modified: Fri, 08 Dec 2023 23:36:18 GMT
Referrer-Policy: strict-origin-when-cross-origin
Strict-Transport-Security: max-age=31536000
Vary: Accept-Encoding
Via: 1.1 2f66f74411c5a2447c09372eb79e674e.cloudfront.net (CloudFront)
X-Age: 1476
X-Amz-Cf-Id: JWsCgD_KoI3mRCkXfGV0Kagp0P1PsxJtxONFJew7WchLZyp9XMo2sg==
X-Amz-Cf-Pop: CDG52-P6
X-Cache: Miss from cloudfront
X-Cache-Hits: 21
X-Content-Type-Options: nosniff
X-Drupal-Dynamic-Cache: UNCACHEABLE
X-Frame-Options: SAMEORIGIN
X-Request-Id: v-964a169c-9622-11ee-a157-03b1d9669105
X-Ua-Compatible: IE=edge
X-Xss-Protection: 1; mode=block

<!DOCTYPE html>
<html lang="en" dir="ltr" prefix="og: https://ogp.me/ns#">
  <head>
    <meta charset="utf-8" /><script type="text/javascript">(window.NREUM||(NREUM={})).init={ajax:{deny_list:["bam.nr-data.net"]}};(window.NREUM||(NREUM={})).loader_config={licenseKey:"761e715901",applicationID:"103445043"};;/*! For license information please see nr-loader-rum-1.248.0.min.js.LICENSE.txt */
(()=>{var e,t,n={234:(e,t,n)=>{"use strict";n.d(t,{P_:()=>h,Mt:()=>m,C5:()=>s,DL:()=>w,OP:()=>j,lF:()=>R,Yu:()=>_,Dg:()=>v,CX:()=>c,GE:()=>A,sU:()=>T});var r=n(8632),i=n(9567);const a={beacon:r.ce.beacon,errorBeacon:r.ce.errorBeacon,licenseKey:void 0,applicationID:void 0,sa:void 0,queueTime:void 0,applicationTime:void 0,ttGuid:void .... Truncated ....
```

**Extra Information**

**Extracted results:**

- 11.3877
- 961407
- 9428-6918
- 3.113 3.022
- 898335
- 103445043
- 79.5089 15.2995
- 57.8695 17.5177
- 23.8248 6.51492
- 14.9242 14.0994
- 60.8862 14.6993
- 45.5499 4.23092
- 10.2386 17.1956
- 256.032.505
- 11.1278
- 26.5165 4.23092
- 30.1416 14.6993
- 28.3345 7.04932
- 79.0027
- 36.4802 6.55884
- 57357
- 2949589
- 000051
- 0 0 0-3.284
- 79.156
- 34.091.648.27
- 47.6171 10.8303
- 73.192 7.04932
- 5.25-6.5
- 05-4931
- 9.341-9.341
- 333 3.852
- 0.478516 4
- 41.5424 8.45621
- 23.0654
- 18552376726
- 4.158-2.4
- 75.0645 14.6993
- 59.9678 17.5177
- 47.6171 11.1161
- 14.9659
- 10591
- 66.8534 11.1269
- 55.5505
- 27.1152 11.1278
- 8.39945 14.3772
- 7480076
- 7.70076 9.50633
- 55.8155 14.8834
- 33.1898 11.1278
- 22.2466
- 5.25 9.25
- 11.1161
- 76.2184 13.4426
- 083.749
- 88.6666
- +1 855-237-6726
- 3 2023
- 9.026 18.51
- 0-2.005 1.194
- 0-2.603.335-3
- 23.8248 11.1269
- 0 0 24 24
- 4-4024-922
- 24276188
- 23.8248 10.7755
- 9938-5
- 10781
- 6.689 6.689
- 6.53 6.53
- 0 0 1 4 17
- 303 1.25
- 9731613
- 75.0427 7.04932
- 881722
- 001 0 0
- 30.1634 17.5177
- 11.1269
- 52.6793
- 26.1258 17.5177
- 30.1634 7.04932
- 17.1956
- 6.5 6.25 6
- 34985-6369-4145
- 22.1465 0.320312
- 8-8 8.001 8
- 67302
- 13.1942 3.77605
- 18.5 16.5
- 0 0 1-1.486
- 2.28 6.585
- 0 0 0 20 12
- 4.39197
- 38.252 4.56791
- 10.8083
- 6-0268
- 19.148 7.358
- 76.2184 11.1278
- 28.2692 14.6993
- 18.0641 7.44987
- 0.285583 1
- 90300
- 840-27
- 0 0 1-1.889
- 3.198 0 0
- 33.9405 17.5177
- 333 3.851
- 4.59 4.747
- 557.519.896
- 14.9659 17.1956
- 18.9493 7.75786
- 9.90375 5.82472
- 9.90375 12.9444
- 12 6.5 12
- 65.3347 10.932
- 71.2978 14.6993
- 56.5002 16.5079
- 63.0819 4.25851
- 50.9075 15.3849
- 6.19913 14.3772
- 10581
- 2.006 2.006
- 0 0 93 22
- 1.7777777777777777
- 3.303 0 0
- 1-5905-4
- 0001467623-23
- 3.432 3.292
- 3.29 3.29
- 10.6984
- 55.9697 10.9622
- 3.57601
- 9.339 9.339
- 66.8534 10.7755
- 76.9474 17.5177
- 17.1884
- 55.9697 13.3363
- 47.6171 13.4463
- 46.4152 14.6993
- 33.1898 8.43822
- 33.1898 10.8192
- 91332
- 10.0622 1.57357
- 931183-4
- 13.1942 9.87184
- 62.0443 13.4682
- 42.7661 7.04932
- 27.1152 13.4206
- 6.08687
- 0 0 1-2.087
- 8.001 8.001
- 29.3687 4.91332
- 21.544
- 0 1.447-1.819
- 55.9697 8.52216
- 44.536 14.6993
- 6.31261
- 6.654 6.654
- 303.617-1
- 896.518
- 69.5234 4.23092
- 994 0-1
- 252.34
- 42.1765 16.6635
- 23.8248 15.2995
- 0 0 1 1.414
- 79.3777 4.55302
- 48.7909 4.23092
- 41.03 4.56791
- 8.7974
- 4706549
- 3.22 3.198
- 85.7762 8.38529
- 0.478516 14
- 22.1465 20.2234
- 76.904 4.23092
- 76.2184 10.8192
- 63.2144 17.5177
- 50.9075 6.56753
- 715901
- 65.3347 6.34398
- 673-371
- 90722
- 0 0 1-6.767
- 92.1748
- 41.5424 11.0502
- 36.4802 11.1269
- 33.1898 13.4426
- 8.35455 4.39197
- 809250
- 10566
- 355 2.313
- 10.844
- 46.3278 7.04932
- 432-42
- 39-132
- 6.995 6.5
- 69.1327 17.5177
- 30.1634 4.23092
- 32.0141 14.6993
- 42.7224 14.6993
- 79.0027 17.1956
- 62.0443 8.32431
- 271413
- 9893-3
- 5-4984-4472
- 6.585 0 0
- 0 2.604
- 14.9242 4.91332
- 2.003 2.003
- 3846860
- 7.70077 20.2234
- 73.1702 14.6993
- 10601
- 0 0 0 2.632
- 22.1465 18.6925
- 29.3687 14.0994
- 60.0561 4.23656
- 10.9622
- 19.8788 4.39197
- 3.283 3.283
- 0-1.25 15.903
- 0 0 30 25
- 41.493
- 15.1865
- 12.105 4 12
- 14.9242 15.6304
- 56.6327 5.1366
- 62.0443 10.9622
- 59.0288 7.04932
- 320423
- 0 0 0 20 7
- 249.248.427
- 10.5588
- 70.1438 13.4206
- 50.9075 11.1967
- 0 0 0 15.076
- 14.9242 24.8164
- 79.5089 6.55884
- 84206
- 89-436
- 5.004 0-6
- 92.4175 17.1956
- 66.8534 15.2995
- 88259801-8
- 0 0 0 5.026
- 252.335-6
- 83.1948
- 3.113.875 0
- 0 0 1-1.415
- 4 14.709 4
- 78025
- 65.3347 15.1468
- 11 0-11-11
- 3.277 3.277
- 6.22439 1.57357
- 82.8859 17.1956
- 70.1438 8.35003
- 38.252
- 994-759
- 10586
- 1-4.079 1.408
- 252.335
- 85.7321 13.0709
- 71.3631 7.04932
- 57.1715 14.6993
- 17.6436 4.55228
- 05908232-6344
- 341-5.007
- 10.8192
- 22.1465 9.50633
- 0.285156
- 18.2854
- 928702
- 0 1.018 4.386
- 1.247.335-6
- 5.004 0 6
- 1.248.0
- 57.2152 7.04932
- 41.5424 13.2924
- 3.287 3.287
- 55.926 6.78302
- 60.7769 7.04932
- 47.6171 8.30233
- 36.4802 15.2995
- 3.57601 4.39197
- 4500-807
- 3-2023
- 4816-4471-9
- 87.6517 10.6731
- 73.1703 4.23092
- 76.2184 8.43822
- 42.0442 5.31105
- 41.3608 6.94227
- 33.897 4.23092
- 32.0141 7.04932
- 6.25 6.5
- 7.70076 18.6925
- 329 1.248
- 6.038 0 9
- 21.6934 7.75786
- 18.5731 5.42593
- 0.285583
- 5 11.75
- 17.5 6.5
- 5092004
- 0 0 0 3.067
- 10.7755
- 6.32 6.32
- 45.5499 17.5672
- 43.4553 4.23092
- 88.3798 4.55302
- 66.8534 6.51492
- 43.5215 17.5672
- 44.6016 7.04932
- 22858
- 10776
- 8 8 0 0 0
- 73.1703 17.5177
- 1631992
- 9.323 9.323
- 3.292 0 0
- 3.32 3.32
- 88210229046
- 58.0462 4.23656
- 18.2854 8.70383
- 624-081
- 10596
- 519 3.303
- 1.79.156 1
- 70.1438 11.1278
- 58.9851 14.6993
- 13.1942 14.9151
- 7360-4
- 865.115
- 83.8346 10.6951
- 79.5089 11.1269
- 62.0443 10.6545
- 48.5484 17.5672
- 27.1152 8.35003
- 9.90375 8.97678
- 9.79235
- 417-41
- 7.70076 0.320312
- 2.004 2.004



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; OpenBSD i386) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.125 Safari/537.36' 'https://investors.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)