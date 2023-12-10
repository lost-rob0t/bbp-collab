### Possible phone numbers extractor (extract-possible-phonenumbers) found on https://status.dropbox.com

----
**Details**: **extract-possible-phonenumbers** matched at https://status.dropbox.com

**Protocol**: HTTP

**Full URL**: https://status.dropbox.com

**Timestamp**: Sat Dec 9 00:01:37 +0000 UTC 2023

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
Host: status.dropbox.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.1916.47 Safari/537.36
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
Atl-Traceid: 6201d1e9ff73427096af7ca1d6b794fa
Cache-Control: max-age=3, public
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 00:01:36 GMT
Etag: W/"d82d02e160ac8b3247245f26ce5199c3"
Link: <https://dka575ofm4ao0.cloudfront.net/assets/register_subscription_form-589b657fec607087fc5c740c568270907310bc4f6aaa20256e70f01b103025ca.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/status_common-c1b99d73ee7ab0fea796bd170723c1daac1381095a7dd7501a38ce6f333d86b3.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/0.6bb03ffda3ffadfa27a1.css>; rel=preload; as=style; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/status/status_manifest-cc9fd99d26ea5cca6f3352190ad1a451683d356cd9a12bb1c7d57870bed73318.css>; rel=preload; as=style; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/jquery-3.5.1.min-729e416557a365062a8a20f0562f18aa171da57298005d392312670c706c68de.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/status_manifest-fe51120c5309a42b8fe23d0af40c6d1ddf533e0e24ebfb16557e15cd82189121.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/common-c3ca024b93f2e64d6f01.chunk.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/globals-3e964b59fb236dbfabd1.chunk.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/runtime-845beefc293f0b2f3a9a.js>; rel=preload; as=script; nopush
Nel: {"failure_fraction": 0.001, "include_subdomains": true, "max_age": 600, "report_to": "endpoint-1"}
Referrer-Policy: strict-origin-when-cross-origin
Report-To: {"endpoints": [{"url": "https://dz8aopenkvv6s.cloudfront.net"}], "group": "endpoint-1", "include_subdomains": true, "max_age": 600}
Server: AtlassianEdge
Strict-Transport-Security: max-age=63072000; preload
Vary: Accept,Accept-Encoding
Via: 1.1 bf5c45d38bcbc855bc2d697c4a8787b2.cloudfront.net (CloudFront)
X-Amz-Cf-Id: zjkQ5NzwXUgbqm_nGcVx3UfXdRfULbxgu6paUnWxadbNKEQIUSuAtA==
X-Amz-Cf-Pop: MRS52-C1
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Edge-Cache-Ttl: 3
X-Permitted-Cross-Domain-Policies: none
X-Pollinator-Metadata-Service: status-page-web-pages
X-Runtime: 0.084504
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
    <meta name="issued" content="1702079818">

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

**Extra Information**

**Extracted results:**

- 27177
- 2023-09-20
- 2023-11-30
- 2023-09-14
- 2023-09-28
- 2023-11-01
- 3298795
- 2023-10-14
- 2023-11-23
- 2023-12-05
- 2023-10-11
- 03292
- 57870
- 365062
- 2023-10-02
- 2023-11-28
- 3352190
- 2023-09-17
- 2023-10-12
- 2023-11-08
- 2023-09-30
- 2023-11-07
- 44753
- 2023-09-21
- 2023-12-01
- 2023-11-03
- 16557
- 09566917307251
- 01097
- 16142
- 168991564-1
- 57298005
- 2023-11-05
- 2023-11-27
- 51120
- 2023-09-19
- 2023-10-06
- 40155
- 42163
- 2023-11-09
- 2023-09-10
- 2023-10-18
- 2023-10-22
- 2023-11-20
- 5544142
- 69656
- 2023-09-25
- 2023-09-29
- 04691
- 20190509-35
- 2023-10-13
- 2023-11-26
- 2023-10-24
- 2023-11-17
- 1702602000
- 73318
- 0 0 448 34
- 2023-09-22
- 2023-09-26
- 2023-10-21
- 2023-10-28
- 2023-11-16
- 2023-12-07
- 82005
- 17769
- 2152613
- 2023-09-16
- 1701912311000
- 1381095
- 2023-10-01
- 2023-12-04
- 170723
- 199843
- 15889421358
- 089276
- 44288114
- 2023-11-19
- 2023-12-08
- 43859
- 2023-09-27
- 2023-10-09
- 2023-10-23
- 2023-10-04
- 2023-11-21
- 82189121
- 3588363
- 83217105
- 2424398
- 2023-09-13
- 2023-10-26
- 2023-11-02
- 2023-11-06
- 20256
- 88207
- 451683
- 7657125
- 2023-09-18
- 2023-10-25
- 2023-11-12
- 2023-11-29
- 47445
- 2023-10-27
- 2023-10-30
- 2023-11-13
- 2023-10-29
- 10000
- 416557
- 392312670
- 6806922
- 2023-10-05
- 767056
- 22021
- 2023-09-24
- 2023-11-11
- 6208632538
- 2023-10-16
- 2023-12-06
- 000000
- 2023-10-08
- 2023-10-19
- 2023-10-17
- 2023-11-22
- 2023-11-24
- 2023-12-02
- 7495173
- 53618
- 2023-09-15
- 2023-10-07
- 607087
- 2023-10-31
- 2023-12-03
- 568270907310
- 103025
- 1702079818
- 14878
- 86724
- 2023-09-23
- 095209
- 781446667
- 2023-09-11
- 2023-10-03
- 691663
- 2023-11-10
- 2023-11-15
- 2023-11-18
- 567907241
- 09703707
- 16092
- 2023-10-15
- 2023-11-14
- 40344
- 637381
- 2023-10-10
- 2023-11-04
- 2023-11-25
- 1738047
- 00866
- 2023-09-12
- 2023-10-20



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.1916.47 Safari/537.36' 'https://status.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)