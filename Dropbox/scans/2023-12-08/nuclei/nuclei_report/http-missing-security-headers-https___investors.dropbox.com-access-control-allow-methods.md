### HTTP Missing Security Headers (http-missing-security-headers:access-control-allow-methods) found on https://investors.dropbox.com

----
**Details**: **http-missing-security-headers:access-control-allow-methods** matched at https://investors.dropbox.com

**Protocol**: HTTP

**Full URL**: https://investors.dropbox.com

**Timestamp**: Sat Dec 9 14:55:15 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | HTTP Missing Security Headers |
| Authors | socketz, geeknik, g4l1t0, convisoappsec, kurohost, dawid-czarnecki |
| Tags | misconfig, generic |
| Severity | info |
| Description | It searches for missing security headers, but obviously, could be so less generic and could be useless for Bug Bounty. |

**Request**
```http
GET / HTTP/1.1
Host: investors.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 10.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36
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
Date: Sat, 09 Dec 2023 14:55:15 GMT
Etag: "1702133404"
Expect-Ct: max-age=0, report-uri="/report-expect-ct-violation"
Expires: Sat, 09 Dec 2023 14:55:15 GMT
Feature-Policy: accelerometer 'none';ambient-light-sensor 'none';autoplay 'self';camera 'none';encrypted-media 'none';fullscreen *;geolocation 'self';gyroscope 'none';magnetometer 'none';microphone 'none';midi 'none';payment 'none';picture-in-picture 'none';speaker 'self';sync-xhr 'self';usb 'none';vibrate 'none';vr 'none'
From-Origin: same
Last-Modified: Sat, 09 Dec 2023 14:50:04 GMT
Referrer-Policy: strict-origin-when-cross-origin
Strict-Transport-Security: max-age=31536000
Vary: Accept-Encoding
Via: 1.1 670b7fc2dd3052d71cc169230b289e08.cloudfront.net (CloudFront)
X-Age: 310
X-Amz-Cf-Id: Fr9Psm4UZDu3pwXRL35z-sTTI2ERl5MJzKCxKn-GJQThJ1O07AHDjQ==
X-Amz-Cf-Pop: CDG52-P6
X-Cache: Miss from cloudfront
X-Cache-Hits: 3
X-Content-Type-Options: nosniff
X-Drupal-Dynamic-Cache: UNCACHEABLE
X-Frame-Options: SAMEORIGIN
X-Request-Id: v-3ccd4532-96a2-11ee-a609-93f637f8ec46
X-Ua-Compatible: IE=edge
X-Xss-Protection: 1; mode=block

<!DOCTYPE html>
<html lang="en" dir="ltr" prefix="og: https://ogp.me/ns#">
  <head>
    <meta charset="utf-8" /><script type="text/javascript">(window.NREUM||(NREUM={})).init={ajax:{deny_list:["bam.nr-data.net"]}};(window.NREUM||(NREUM={})).loader_config={licenseKey:"761e715901",applicationID:"103445043"};;/*! For license information please see nr-loader-rum-1.248.0.min.js.LICENSE.txt */
(()=>{var e,t,n={234:(e,t,n)=>{"use strict";n.d(t,{P_:()=>h,Mt:()=>m,C5:()=>s,DL:()=>w,OP:()=>j,lF:()=>R,Yu:()=>_,Dg:()=>v,CX:()=>c,GE:()=>A,sU:()=>T});var r=n(8632),i=n(9567);const a={beacon:r.ce.beacon,errorBeacon:r.ce.errorBeacon,licenseKey:void 0,applicationID:void 0,sa:void 0,queueTime:void 0,applicationTime:void 0,ttGuid:void 0,.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36' 'https://investors.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)