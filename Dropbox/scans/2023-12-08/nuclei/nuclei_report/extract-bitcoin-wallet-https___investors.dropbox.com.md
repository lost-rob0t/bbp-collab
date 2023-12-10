### Bitcoin wallets addresses extractor (extract-bitcoin-wallet) found on https://investors.dropbox.com

----
**Details**: **extract-bitcoin-wallet** matched at https://investors.dropbox.com

**Protocol**: HTTP

**Full URL**: https://investors.dropbox.com

**Timestamp**: Sat Dec 9 00:01:06 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Bitcoin wallets addresses extractor |
| Authors | cipher387 |
| Tags | osint, juicy-info, cryptocyrrency |
| Severity | info |
| Description | Extract bitcoin wallets addresses from web page body |

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

- 3xCFkBQXGlbCgVQaXNXXhdCXlxZUBc9e



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; OpenBSD i386) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.125 Safari/537.36' 'https://investors.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)