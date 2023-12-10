### Urls extractor (extract-urls) found on https://mentoring.dropbox.com

----
**Details**: **extract-urls** matched at https://mentoring.dropbox.com

**Protocol**: HTTP

**Full URL**: https://mentoring.dropbox.com

**Timestamp**: Sat Dec 9 00:01:16 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Urls extractor |
| Authors | cipher387 |
| Tags | osint, juicy-info |
| Severity | info |
| Description | Extract urls from web page body |

**Request**
```http
GET / HTTP/1.1
Host: mentoring.dropbox.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_2) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1944.0 Safari/537.36
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
Cache-Control: no-store
Content-Security-Policy: frame-ancestors teams.microsoft.com *.teams.microsoft.com 'self';
Content-Security-Policy-Report-Only: default-src 'none'; font-src 'self' data: https://d28ysuyw2f6yxp.cloudfront.net https://mentor-global-assets.chronus.com https://fonts.gstatic.com/ https://*.fontawesome.com https://chronus.com/ https://www.slant.co/ https://at.alicdn.com https://use.typekit.net https://zip.co/ https://github.com/google/fonts/blob/master/apache/opensans; img-src * data:; object-src 'self'; script-src 'self' 'unsafe-eval' 'unsafe-inline' data: https://d28ysuyw2f6yxp.cloudfront.net *.google-analytics.com *.googletagmanager.com https://ajax.googleapis.com *.pendo.io https://pendo-static-6184273133961216.storage.googleapis.com https://pendo-io-static.storage.googleapis.com https://js-agent.newrelic.com *.nr-data.net https://cdn.segment.com/ *.mxpnl.com https://mentor-global-assets.chronus.com; style-src 'self' 'unsafe-eval' 'unsafe-inline' data: https://d28ysuyw2f6yxp.cloudfront.net https://mentor-global-assets.chronus.com https://fonts.googleapis.com/ *.pendo.io https://pendo-static-6184273133961216.storage.googleapis.com; connect-src 'self' wss: data: *.nr-data.net *.google-analytics.com *.googletagmanager.com *.pendo.io https://pendo-static-6184273133961216.storage.googleapis.com https://api.segment.io/ https://cdn.segment.com/ *.mixpanel.com https://d28ysuyw2f6yxp.cloudfront.net; frame-src 'self' data: *; frame-ancestors teams.microsoft.com *.teams.microsoft.com 'self'; base-uri 'self'; form-action 'self'; child-src 'self' app.pendo.io; manifest-src 'self'; media-src 'self' data:; prefetch-src 'self' data: https://d28ysuyw2f6yxp.cloudfront.net; worker-src 'self'; report-uri /log_csp_violation
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 00:01:14 GMT
Etag: W/"430d13110ad358b425a83aaec0f0f18c"
Pragma: no-cache
Referrer-Policy: strict-origin-when-cross-origin
Set-Cookie: AWSALB=PEz2YGcCWySSObDUk+53GdcQ/tr1pWCbZjvgFHW5PzBvIZNdIpOkdXMxsFbbTs3TzfufuajSYhpHICaG7lY+wP2s7otlD8XPmsY6TekZ4E57go2V9SOBLiNMiI/b; Expires=Sat, 16 Dec 2023 00:01:14 GMT; Path=/
Set-Cookie: AWSALBCORS=PEz2YGcCWySSObDUk+53GdcQ/tr1pWCbZjvgFHW5PzBvIZNdIpOkdXMxsFbbTs3TzfufuajSYhpHICaG7lY+wP2s7otlD8XPmsY6TekZ4E57go2V9SOBLiNMiI/b; Expires=Sat, 16 Dec 2023 00:01:14 GMT; Path=/; SameSite=None; Secure
Set-Cookie: uniq_token=664112ba-6396-4072-8a79-e5820a6175fb; path=/; expires=Mon, 09 Dec 2024 00:01:14 GMT; Secure; HttpOnly
Set-Cookie: _mentor_session=bf4f108f3939daf4eb9eba84a6f2c944; domain=.dbxmentoring.chronus.com; path=/; secure; HttpOnly; SameSite=None
Status: 200 OK
Strict-Transport-Security: max-age=63072000
Vary: Accept-Encoding
Via: 1.1 a5527e17f7fd24342408a5722f47d30c.cloudfront.net (CloudFront)
X-Amz-Cf-Id: uGVqOXqHYHwkKZ0Cyw8A7X-cJMvXq5tDoWZNgrE9Bj2Ylc_tw17k8g==
X-Amz-Cf-Pop: MRS52-P1
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Frame-Options: SAMEORIGIN
X-Permitted-Cross-Domain-Policies: none
X-Request-Id: a50346dc-7a92-4a44-bf4e-530923c0b8b4
X-Robots-Tag: noindex
X-Runtime: 0.079130
X-Xss-Protection: 1; mode=block

<!DOCTYPE html>
<html lang="en" xml:lang="en" xmlns="https://www.w3.org/1999/xhtml">
  <head>
    
    <link rel="preconnect" href="https://d28ysuyw2f6yxp.cloudfront.net/" crossorigin/>
<link rel="preconnect" href="https://www.google-analytics.com/"/>
<link rel="preconnect" href="https://chronus-mentor.s3.amazonaws.com/"/>
<link rel="preconnect" href="https://mentor-global-assets.chronus.com/" crossorigin/>
<link rel="preconnect" href="https://mentor-global-assets.chronus.com/"/>
    <meta charset="utf-8">
<script type="text/javascript">window.NREUM||(NREUM={});NREUM.info={"beacon":"bam.nr-data.net","errorBeacon":"bam.nr-data.net","licenseKey":"fe0883d790","applicationID":"75707","transactionName":"Jg5cFUVcX1pSEUpXEAIAXAhNUkdfWA0WFxENDkU=","queueTime":1,"applicationTime":70,"agent":"","atts":"HkNHQw1IEWJFAgNeCwYuQAhQWl0UDUEKTAoAE0FDGxF8RFA8LHxAX1MKUwcfEWRYDwBLQF9DXA5DE19ZUAQAXEIMDxBNFWFWR0IGFkxPLCUQWxVSBgYEV1NcAUhWU1gFHgdXA1dIWgRRBB9UBAMKBAQAVVpaB1UQHEo="}</script>
<script type="text/javascript">(window.NREUM||(NREUM={})).init={privacy:{cookies_enabled:true},ajax:{deny_list:["bam.nr-data.net"]}};(window.NREUM||(NREUM={})).loader_config={xpid:"VgcAWV5ADwYHVFY=",licenseKey:"fe0883d790",applicationID:"75707"};;/*! For license information please see nr-loader-full-1.248.0.min.js.LICENSE.txt */
(()=>{var e,t,r={234:(e,t,r)=>{"use strict";r.d(t,{P_:()=>g,Mt:()=>v,C5:()=>s,DL:()=>A,OP:()=>S,lF:()=>R,Yu:()=>w,Dg:()=>m,CX:()=>c,GE:()=>x,sU:()=>j});var n=r(8632),i=r(9567);const a={beacon:n.ce.beacon,errorBeacon:n.ce.errorBeacon,licenseKey:void 0,applicationID:void 0,sa:void 0,queueTime:void 0,applicationTime:void 0,ttGuid:void 0,user:void 0,account:void 0,product:void 0,extra:void 0,jsAttributes:{},userAttributes:void 0,atts:void 0,transactionName:void 0,tNamePlain:void 0},o={};function s(e){if(!e)throw new Error("All info objects require an agent identifier!");if(!o[e].... Truncated ....
```

**Extra Information**

**Extracted results:**

- https://play.google.com/store/apps/details?id=com.chronus.mentorp&amp;referrer=utm_source%3Ddbxmentoring.chronus.com%26utm_medium%3Doverview_page
- https://www.google-analytics.com/
- https://d28ysuyw2f6yxp.cloudfront.net/assets/version-2/favicons/chronus-7a386ecc6895153f2e18a3d46ea66a8ede356332ef0441a32f03049c91cb07e7.ico
- https://d28ysuyw2f6yxp.cloudfront.net/assets/version-2/v3/manifests/base-libraries-4ba1e29abcadc6263088a66c1a87da105eb0c44cd0a5af958a0d46bcc07a5512.js
- https://www.google.com/support/bin/answer.py?answer=23852
- https://d28ysuyw2f6yxp.cloudfront.net/assets/version-2/v3/manifests/loggedin-user-f740705941770c4a7ecc395be52480e75d962383da330a7e080f83c1d162f329.js
- https://www.w3.org/1999/xhtml
- https://mentor-global-assets.chronus.com/
- https://www.googletagmanager.com/gtag/js?id=
- https://cdn.mxpnl.com/libs/mixpanel-2-latest.min.js
- https://itunes.apple.com/in/app/chronus-mobile/id920354077?mt=8
- https://chronus-mentor.s3.amazonaws.com/
- https://mentor-global-assets.chronus.com/images/chronus-app-android-app-store.png
- https://d28ysuyw2f6yxp.cloudfront.net/assets/version-2/v3/web-html-e8e4ef461b61239b8001c038bb66210dd9b40f3f8e1a57a153f075455a96e923.css
- https://d28ysuyw2f6yxp.cloudfront.net/assets/version-2/v3/manifests/chr-common-libraries-2e1d86cb80b7d4df8424946e836894129bc44ab47dc543ff0d1212caca45f03c.js
- https://app.frontify.com/d/sXZ1M2LmQvgw/chronus-app-overview-pages-style-guide--
- https://dbxmentoring.chronus.com/p/p1/
- https://mentor-global-assets.chronus.com/stylesheets/overview-page-2018-template-v2.css
- https://js-agent.newrelic.com/
- https://d28ysuyw2f6yxp.cloudfront.net/org_assets/programs/stylesheets/684/theme%20%286%29-b33fd5.css?1664356602?v=5
- https://chronus.com
- https://d28ysuyw2f6yxp.cloudfront.net/org_region_assets/programs/ckphotos/50270/original.jpeg?1631134799
- https://dbxmentoring.chronus.com/p/p1/membership_requests/new
- https://d28ysuyw2f6yxp.cloudfront.net/
- https://d28ysuyw2f6yxp.cloudfront.net/assets/version-2/webfont-non-latin-48b500c2394f3a6a26f5d40f8b4f596f328b10a5ae40904c645b772e2e6271fe.css
- https://d28ysuyw2f6yxp.cloudfront.net/assets/version-2/v3/manifests/base-jquery-libraries-c74f8392248406b6ee27f04fb548d85a7ce7ee24f9f8a750d922e2be2f87d98a.js
- https://d28ysuyw2f6yxp.cloudfront.net/assets/version-2/v3/manifests/nonloggedin-3b82775865be8101548533082c8fa081fa5c2fb4d0fe68caf91240c94b11e3ee.js
- https://d28ysuyw2f6yxp.cloudfront.net/org_region_assets/programs/logos/2080/original.png?1623711692
- https://mentor-global-assets.chronus.com/images/chronus-app-ios-app-store.png
- https://play.google.com/store/apps/details?id=com.chronus.mentorp&amp;referrer=utm_source%3Dchronus.com%26utm_medium%3Doverview
- https://mentor-global-assets.chronus.com/files/StepstoenableAJAX.pdf
- http://custom.transaction
- https://d28ysuyw2f6yxp.cloudfront.net/assets/version-2/v3/overview_pages-df6bfb247584d0e78f288c041ddc0bfeb94e76cf867ef179dae33f670c3a7bf4.css
- https://d28ysuyw2f6yxp.cloudfront.net/org_region_assets/programs/ckphotos/50295/original.png?1631215679



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_2) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1944.0 Safari/537.36' 'https://mentoring.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)