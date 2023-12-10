### CSP Not Enforced (missing-csp) found on https://status.dropbox.com

----
**Details**: **missing-csp** matched at https://status.dropbox.com

**Protocol**: HTTP

**Full URL**: https://status.dropbox.com

**Timestamp**: Sat Dec 9 08:24:44 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | CSP Not Enforced |
| Authors | geeknik |
| Tags | misc |
| Severity | info |
| Description | Checks if there is a CSP header |

**Request**
```http
GET / HTTP/1.1
Host: status.dropbox.com
User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/34.0.1847.137 Safari/4E423F
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
Atl-Traceid: 27654c067d694e2c9549852b06e2b55c
Cache-Control: max-age=3, public
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 08:24:42 GMT
Etag: W/"d39d00cd35c49635275489d3fad3bac4"
Link: <https://dka575ofm4ao0.cloudfront.net/assets/register_subscription_form-589b657fec607087fc5c740c568270907310bc4f6aaa20256e70f01b103025ca.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/status_common-c1b99d73ee7ab0fea796bd170723c1daac1381095a7dd7501a38ce6f333d86b3.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/0.6bb03ffda3ffadfa27a1.css>; rel=preload; as=style; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/status/status_manifest-cc9fd99d26ea5cca6f3352190ad1a451683d356cd9a12bb1c7d57870bed73318.css>; rel=preload; as=style; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/jquery-3.5.1.min-729e416557a365062a8a20f0562f18aa171da57298005d392312670c706c68de.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/status_manifest-fe51120c5309a42b8fe23d0af40c6d1ddf533e0e24ebfb16557e15cd82189121.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/common-c3ca024b93f2e64d6f01.chunk.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/globals-3e964b59fb236dbfabd1.chunk.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/runtime-845beefc293f0b2f3a9a.js>; rel=preload; as=script; nopush
Nel: {"failure_fraction": 0.001, "include_subdomains": true, "max_age": 600, "report_to": "endpoint-1"}
Referrer-Policy: strict-origin-when-cross-origin
Report-To: {"endpoints": [{"url": "https://dz8aopenkvv6s.cloudfront.net"}], "group": "endpoint-1", "include_subdomains": true, "max_age": 600}
Server: AtlassianEdge
Strict-Transport-Security: max-age=63072000; preload
Vary: Accept,Accept-Encoding
Via: 1.1 ce22e0407d9b4f91724feba4d5aa25c2.cloudfront.net (CloudFront)
X-Amz-Cf-Id: nMzO34ccJV06cifPR_hc-0hv4SsiFpkkS1n-Wi8VsvwNjNf2Ro1Kow==
X-Amz-Cf-Pop: MRS52-C1
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Edge-Cache-Ttl: 3
X-Permitted-Cross-Domain-Policies: none
X-Pollinator-Metadata-Service: status-page-web-pages
X-Runtime: 0.104628
X-Statuspage-Skip-Logging: true
X-Statuspage-Version: a7b5d580f11e475f053998d3a95134154d95445a
X-Xss-Protection: 1; mode=block

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <!-- force IE browsers in compatibility mode to use their most aggressive rendering engine -->

    <meta charset="utf-8">
    <title>Dropbox Status</title>
    <meta name="description" content="Welcome to Dropbox&#39;s home for real-time and historical data on system performance.">

    <!-- Mobile viewport optimization -->
    <meta name="HandheldFriendly" content="True">
    <meta name="MobileOptimized" content="320">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0">

    <!-- Time this page was rendered - http://purl.org/dc/terms/issued -->
    <meta name="issued" content="1702109793">

    <!-- Mobile IE allows us to activate ClearType technology for smoothing fonts for easy reading -->
    <meta http-equiv="cleartype" content="on">

    <!-- Le fonts -->
<style>
  @font-face {
    font-family: 'proxima-nova';
    src: url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaLight-f0b2f7c12b6b87c65c02d3c1738047ea67a7607fd767056d8a2964cc6a2393f7.eot?host=status.dropbox.com');
    src: url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaLight-f0b2f7c12b6b87c65c02d3c1738047ea67a7607fd767056d8a2964cc6a2393f7.eot?host=status.dropbox.com#iefix') format('embedded-opentype'),
         url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaLight-e642ffe82005c6208632538a557e7f5dccb835c0303b06f17f55ccf567907241.woff?host=status.dropbox.com') format('woff'),
         url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaLight-0f094da9b301d03292f97db5544142a16f9f2ddf50af91d44753d9310c194c5f.ttf?host=status.dropbox.com') format('truetype');
    font-weight:300;
    font-style:normal;
  }
   
  @font-face {
    font-family: 'proxima-nova';
    src: url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegular-366d17769d864aa72f27defaddf591e460a1de4984bb24dacea57a9fc1d14878.eot?host=status.dropbox.com');
    src: url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegular-366d17769d864aa72f27defaddf591e460a1de4984bb24dacea57a9fc1d14878.eot?host=status.dropbox.com#iefix') format('embedded-opentype'),
         url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegular-2ee4c449a9ed716f1d88207bd1094e21b69e2818b5cd36b28ad809dc1924ec54.woff?host=status.dropbox.com') format('woff'),
         url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegular-a40a469edbd27b65b845b8000d47445a17def8ba677f4eb836ad1808f7495173.ttf?host=status.dropbox.com') form.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/34.0.1847.137 Safari/4E423F' 'https://status.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)