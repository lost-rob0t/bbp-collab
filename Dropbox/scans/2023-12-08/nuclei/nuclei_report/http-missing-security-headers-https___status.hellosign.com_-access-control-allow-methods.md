### HTTP Missing Security Headers (http-missing-security-headers:access-control-allow-methods) found on https://status.hellofax.com

----
**Details**: **http-missing-security-headers:access-control-allow-methods** matched at https://status.hellofax.com

**Protocol**: HTTP

**Full URL**: https://status.hellosign.com/

**Timestamp**: Sat Dec 9 14:55:59 +0000 UTC 2023

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
Host: status.hellofax.com
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
Accept-Ranges: bytes
Access-Control-Allow-Origin: *
Atl-Traceid: 78d66b531c9b427491522536333ef8cc
Cache-Control: max-age=3, public
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 14:55:58 GMT
Etag: W/"33612f2d19eb5c677377ce868935ab8d"
Link: <https://dka575ofm4ao0.cloudfront.net/assets/vendor/bowser-1643ca34a6d589b2d4d42163a891e4512d5d7657125e09bb5f3d44288114e6bd.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/register_subscription_form-589b657fec607087fc5c740c568270907310bc4f6aaa20256e70f01b103025ca.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/status_common-c1b99d73ee7ab0fea796bd170723c1daac1381095a7dd7501a38ce6f333d86b3.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/vendor/highstock.min-9de8c325692300efdf4b01e93caaa5668693434b74882c25c3b13d58b2d583cb.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/0.6bb03ffda3ffadfa27a1.css>; rel=preload; as=style; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/status/status_manifest-cc9fd99d26ea5cca6f3352190ad1a451683d356cd9a12bb1c7d57870bed73318.css>; rel=preload; as=style; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/jquery-3.5.1.min-729e416557a365062a8a20f0562f18aa171da57298005d392312670c706c68de.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/status_manifest-fe51120c5309a42b8fe23d0af40c6d1ddf533e0e24ebfb16557e15cd82189121.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/common-c3ca024b93f2e64d6f01.chunk.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/globals-3e964b59fb236dbfabd1.chunk.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/runtime-845beefc293f0b2f3a9a.js>; rel=preload; as=script; nopush
Nel: {"failure_fraction": 0.001, "include_subdomains": true, "max_age": 600, "report_to": "endpoint-1"}
Referrer-Policy: strict-origin-when-cross-origin
Report-To: {"endpoints": [{"url": "https://dz8aopenkvv6s.cloudfront.net"}], "group": "endpoint-1", "include_subdomains": true, "max_age": 600}
Server: AtlassianEdge
Strict-Transport-Security: max-age=259200
Vary: Accept-Encoding
Via: 1.1 468eeec33a1dbb9d71a79cbde5838d78.cloudfront.net (CloudFront)
X-Amz-Cf-Id: yR2Fg6tVYP66UZ_FEcJ8dwdqgeJlYE1fmzwXWTqLHF3IeCKULpaFjA==
X-Amz-Cf-Pop: CDG52-P1
X-Cache: Hit from cloudfront
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Edge-Cache-Ttl: 3
X-Permitted-Cross-Domain-Policies: none
X-Pollinator-Metadata-Service: status-page-web-pages
X-Runtime: 0.760042
X-Statuspage-Skip-Logging: true
X-Statuspage-Version: a7b5d580f11e475f053998d3a95134154d95445a
X-Xss-Protection: 1; mode=block

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <!-- force IE browsers in compatibility mode to use their most aggressive rendering engine -->

    <meta charset="utf-8">
    <title>Dropbox Sign, Fax, and Forms Status</title>
    <meta name="description" content="Welcome to Dropbox Sign, Fax, and Forms&#39;s home for real-time and historical data on system performance.">

    <!-- Mobile viewport optimization -->
    <meta name="HandheldFriendly" content="True">
    <meta name="MobileOptimized" content="320">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0">

    <!-- Time this page was rendered - http://purl.org/dc/terms/issued -->
    <meta name="issued" content="1702133758">

    <!-- Mobile IE allows us to activate ClearType technology for smoothing fonts for easy reading -->
    <meta http-equiv="cleartype" content="on">

    <!-- Le fonts -->
<style>
  @font-face {
    font-family: 'proxima-nova';
    src: url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaLight-f0b2f7c12b6b87c65c02d3c1738047ea67a7607fd767056d8a2964cc6a2393f7.eot?host=status.hellosign.com');
    src: url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaLight-f0b2f7c12b6b87c65c02d3c1738047ea67a7607fd767056d8a2964cc6a2393f7.eot?host=status.hellosign.com#iefix') format('embedded-opentype'),
         url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaLight-e642ffe82005c6208632538a557e7f5dccb835c0303b06f17f55ccf567907241.woff?host=status.hellosign.com') format('woff'),
         url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaLight-0f094da9b301d03292f97db5544142a16f9f2ddf50af91d44753d9310c194c5f.ttf?host=status.hellosign.com') format('truetype');
    font-weight:300;
    font-style:normal;
  }
   
  @font-face {
    font-family: 'proxima-nova';
    src: url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegular-366d17769d864aa72f27defaddf591e460a1de4984bb24dacea57a9fc1d14878.eot?host=status.hellosign.com');
    src: url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegular-366d17769d864aa72f27defaddf591e460a1de4984bb24dacea57a9fc1d14878.eot?host=status.hellosign.com#iefix') format('embedded-opentype'),
   .... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36' 'https://status.hellofax.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)