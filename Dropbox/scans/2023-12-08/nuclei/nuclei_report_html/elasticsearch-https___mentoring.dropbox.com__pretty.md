### ElasticSearch Information Disclosure (elasticsearch) found on https://mentoring.dropbox.com

----
**Details**: **elasticsearch** matched at https://mentoring.dropbox.com

**Protocol**: HTTP

**Full URL**: https://mentoring.dropbox.com/?pretty

**Timestamp**: Sat Dec 9 13:04:04 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | ElasticSearch Information Disclosure |
| Authors | shine, c-sh0 |
| Tags | elastic, unauth, elasticsearch |
| Severity | low |

**Request**
```http
GET /?pretty HTTP/1.1
Host: mentoring.dropbox.com
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
Transfer-Encoding: chunked
Cache-Control: no-store
Content-Security-Policy: frame-ancestors teams.microsoft.com *.teams.microsoft.com 'self';
Content-Security-Policy-Report-Only: default-src 'none'; font-src 'self' data: https://d28ysuyw2f6yxp.cloudfront.net https://mentor-global-assets.chronus.com https://fonts.gstatic.com/ https://*.fontawesome.com https://chronus.com/ https://www.slant.co/ https://at.alicdn.com https://use.typekit.net https://zip.co/ https://github.com/google/fonts/blob/master/apache/opensans; img-src * data:; object-src 'self'; script-src 'self' 'unsafe-eval' 'unsafe-inline' data: https://d28ysuyw2f6yxp.cloudfront.net *.google-analytics.com *.googletagmanager.com https://ajax.googleapis.com *.pendo.io https://pendo-static-6184273133961216.storage.googleapis.com https://pendo-io-static.storage.googleapis.com https://js-agent.newrelic.com *.nr-data.net https://cdn.segment.com/ *.mxpnl.com https://mentor-global-assets.chronus.com; style-src 'self' 'unsafe-eval' 'unsafe-inline' data: https://d28ysuyw2f6yxp.cloudfront.net https://mentor-global-assets.chronus.com https://fonts.googleapis.com/ *.pendo.io https://pendo-static-6184273133961216.storage.googleapis.com; connect-src 'self' wss: data: *.nr-data.net *.google-analytics.com *.googletagmanager.com *.pendo.io https://pendo-static-6184273133961216.storage.googleapis.com https://api.segment.io/ https://cdn.segment.com/ *.mixpanel.com https://d28ysuyw2f6yxp.cloudfront.net; frame-src 'self' data: *; frame-ancestors teams.microsoft.com *.teams.microsoft.com 'self'; base-uri 'self'; form-action 'self'; child-src 'self' app.pendo.io; manifest-src 'self'; media-src 'self' data:; prefetch-src 'self' data: https://d28ysuyw2f6yxp.cloudfront.net; worker-src 'self'; report-uri /log_csp_violation
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 13:04:04 GMT
Etag: W/"8298fa15c604985217cbdb3b9845b13b"
Pragma: no-cache
Referrer-Policy: strict-origin-when-cross-origin
Set-Cookie: AWSALB=6hNYc5i7KWMjAsec6PXfvvZXqnLyr6oNQRMcgoQQtI+fQJhET32kIeHWvfWy+iWXn2vK8rmuCdWLysTIG17oAWkmXzMzYgErZPs2rHl2oxrG0YiloG9cMGFFCPlX; Expires=Sat, 16 Dec 2023 13:04:04 GMT; Path=/
Set-Cookie: AWSALBCORS=6hNYc5i7KWMjAsec6PXfvvZXqnLyr6oNQRMcgoQQtI+fQJhET32kIeHWvfWy+iWXn2vK8rmuCdWLysTIG17oAWkmXzMzYgErZPs2rHl2oxrG0YiloG9cMGFFCPlX; Expires=Sat, 16 Dec 2023 13:04:04 GMT; Path=/; SameSite=None; Secure
Set-Cookie: uniq_token=f6c3abe7-5129-4dc0-8f51-33c7e8622ce2; path=/; expires=Mon, 09 Dec 2024 13:04:04 GMT; Secure; HttpOnly
Set-Cookie: _mentor_session=05ca29959805b497c4c7ed20682e4763; domain=.dbxmentoring.chronus.com; path=/; secure; HttpOnly; SameSite=None
Status: 200 OK
Strict-Transport-Security: max-age=63072000
Vary: Accept-Encoding
Via: 1.1 f1f5d974f7fdb5d7a316f8977e43daae.cloudfront.net (CloudFront)
X-Amz-Cf-Id: wrnv1d_tAJyIj9hjPJPcJOK6-YW1nD7dSF7lw-7mS4Sok-hMrE6bvg==
X-Amz-Cf-Pop: MRS52-P1
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Frame-Options: SAMEORIGIN
X-Permitted-Cross-Domain-Policies: none
X-Request-Id: 53ad06a5-ccab-49a1-b670-86c12f647774
X-Robots-Tag: noindex
X-Runtime: 0.075567
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
<script type="text/javascript">window.NREUM||(NREUM={});NREUM.info={"beacon":"bam.nr-data.net","errorBeacon":"bam.nr-data.net","licenseKey":"fe0883d790","applicationID":"75707","transactionName":"Jg5cFUVcX1pSEUpXEAIAXAhNUkdfWA0WFxENDkU=","queueTime":1,"applicationTime":67,"agent":"","atts":"HkNHQw1IEWJFAgNeCwYuQAhQWl0UDUEKTAoAE0FDGxF8RFA8LHxAX1MKUwcfEWRYDwBLQF9DXA5DE19ZUAQAXEIMDxBNFWFWR0IGFkxPLCUQWxUGAFdTU1NZV0gCUQBVHgcPVlJIWlRSUR9ZAVACBFFVUQ9VUlUQHEo="}</script>
<script type="text/javascript">(window.NREUM||(NREUM={})).init={privacy:{cookies_enabled:true},ajax:{deny_list:["bam.nr-data.net"]}};(window.NREUM||(NREUM={})).loader_config={xpid:"VgcAWV5ADwYHVFY=",licenseKey:"fe0883d790",applicationID:"75707"};;/*! For license information please see nr-loader-full-1.248.0.min.js.LICENSE.txt */
(()=>{var e,t,r={234:(e,t,r)=>{"use strict";r.d(t,{P_:()=>g,Mt:()=>v,C5:()=>s,DL:()=>A,OP:()=>S,lF:()=>R,Yu:()=>w,Dg:()=>m,CX:()=>c,GE:()=>x,sU:()=>j});var n=r(8632),i=r(9567);const a={beacon:n.ce.beacon,errorBeacon:n.ce.errorBeacon,licenseKey:void 0,applicationID:void 0,sa:void 0,queueTime:void 0,applicationTime:void 0,ttGuid:void 0,user:void 0,account:void 0,product:void 0,extra:void 0,jsAttributes:{},userAttributes:void 0,atts:void 0,transactionName:void 0,tNamePlain:void 0},o={};function s(e){if(!e)throw new Error("All info objects require an agent identifier!");if(!o[e].... Truncated ....
```

References: 
- https://www.elastic.co/blog/a-practical-introduction-to-elasticsearch
- https://discuss.elastic.co/t/how-to-find-elastic-search-version/8737

**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36' 'https://mentoring.dropbox.com/?pretty'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)