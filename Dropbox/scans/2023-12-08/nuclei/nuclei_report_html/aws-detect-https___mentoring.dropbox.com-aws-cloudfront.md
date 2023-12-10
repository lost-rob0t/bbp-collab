### AWS Service - Detect (aws-detect:aws-cloudfront) found on https://mentoring.dropbox.com

----
**Details**: **aws-detect:aws-cloudfront** matched at https://mentoring.dropbox.com

**Protocol**: HTTP

**Full URL**: https://mentoring.dropbox.com

**Timestamp**: Sat Dec 9 09:08:58 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | AWS Service - Detect |
| Authors | 6mile |
| Tags | tech, aws, amazon, alb, cloudfront, codebuild, gateway, xray, captcha, dynamodb, kms |
| Severity | info |
| Description | Detect if AWS is being used in the application. |
| CWE-ID | [CWE-200](https://cwe.mitre.org/data/definitions/200.html) |
| CVSS-Score | 0.00 |

**Request**
```http
GET / HTTP/1.1
Host: mentoring.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36
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
Date: Sat, 09 Dec 2023 09:08:58 GMT
Etag: W/"9f386fb110fbee363aec4ef48d3b0804"
Pragma: no-cache
Referrer-Policy: strict-origin-when-cross-origin
Set-Cookie: AWSALB=Bf/FjzyAJubGYIFVRkicb2WferD0l0mDbp7Bl3ztHF3J9NXKHfjHIy/krNBbzXrX+/tIlLHZAHMaBmWwkpCSHx287TskZEktmK7lY+EbBoG6AEZM3etBI2O6h6Lk; Expires=Sat, 16 Dec 2023 09:08:57 GMT; Path=/
Set-Cookie: AWSALBCORS=Bf/FjzyAJubGYIFVRkicb2WferD0l0mDbp7Bl3ztHF3J9NXKHfjHIy/krNBbzXrX+/tIlLHZAHMaBmWwkpCSHx287TskZEktmK7lY+EbBoG6AEZM3etBI2O6h6Lk; Expires=Sat, 16 Dec 2023 09:08:57 GMT; Path=/; SameSite=None; Secure
Set-Cookie: uniq_token=e31119fb-bd0c-48d7-b4d3-c238f63f72bd; path=/; expires=Mon, 09 Dec 2024 09:08:57 GMT; Secure; HttpOnly
Set-Cookie: _mentor_session=62d3c147723f1b2ec3b3e62d0c59f1fb; domain=.dbxmentoring.chronus.com; path=/; secure; HttpOnly; SameSite=None
Status: 200 OK
Strict-Transport-Security: max-age=63072000
Vary: Accept-Encoding
Via: 1.1 54ba4737103cb6263e414e602fbbe752.cloudfront.net (CloudFront)
X-Amz-Cf-Id: ZsLLMjlNWf0z1E3MDJIXjhiOwOMdYFwuSFYkORjZ-EzaD3j4gTuPhQ==
X-Amz-Cf-Pop: MRS52-P1
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Frame-Options: SAMEORIGIN
X-Permitted-Cross-Domain-Policies: none
X-Request-Id: e17845c5-d494-4c98-a55b-b63658d023e9
X-Robots-Tag: noindex
X-Runtime: 0.113830
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
<script type="text/javascript">window.NREUM||(NREUM={});NREUM.info={"beacon":"bam.nr-data.net","errorBeacon":"bam.nr-data.net","licenseKey":"fe0883d790","applicationID":"75707","transactionName":"Jg5cFUVcX1pSEUpXEAIAXAhNUkdfWA0WFxENDkU=","queueTime":1,"applicationTime":105,"agent":"","atts":"HkNHQw1IEWJFAgNeCwYuQAhQWl0UDUEKTAoAE0FDGxF8RFA8LHxAX1MKUwcfEWRYDwBLQF9DXA5DE19ZUAQAXEIMDxBNFWFWR0IGFkxPLCUQWxVWAgEPV1BbV0gFBlgDHgdVDltIWVdQAx8DAQAFAw8HVQpRAFgQHEo="}</script>
<script type="text/javascript">(window.NREUM||(NREUM={})).init={privacy:{cookies_enabled:true},ajax:{deny_list:["bam.nr-data.net"]}};(window.NREUM||(NREUM={})).loader_config={xpid:"VgcAWV5ADwYHVFY=",licenseKey:"fe0883d790",applicationID:"75707"};;/*! For license information please see nr-loader-full-1.248.0.min.js.LICENSE.txt */
(()=>{var e,t,r={234:(e,t,r)=>{"use strict";r.d(t,{P_:()=>g,Mt:()=>v,C5:()=>s,DL:()=>A,OP:()=>S,lF:()=>R,Yu:()=>w,Dg:()=>m,CX:()=>c,GE:()=>x,sU:()=>j});var n=r(8632),i=r(9567);const a={beacon:n.ce.beacon,errorBeacon:n.ce.errorBeacon,licenseKey:void 0,applicationID:void 0,sa:void 0,queueTime:void 0,applicationTime:void 0,ttGuid:void 0,user:void 0,account:void 0,product:void 0,extra:void 0,jsAttributes:{},userAttributes:void 0,atts:void 0,transactionName:void 0,tNamePlain:void 0},o={};function s(e){if(!e)throw new Error("All info objects require an agent identifier!");if(!o[e.... Truncated ....
```

References: 
- https://github.com/6mile/cloud-headers

**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36' 'https://mentoring.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)