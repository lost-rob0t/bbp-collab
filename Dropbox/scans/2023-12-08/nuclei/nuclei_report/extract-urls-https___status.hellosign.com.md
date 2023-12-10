### Urls extractor (extract-urls) found on https://status.hellosign.com

----
**Details**: **extract-urls** matched at https://status.hellosign.com

**Protocol**: HTTP

**Full URL**: https://status.hellosign.com

**Timestamp**: Sat Dec 9 00:01:43 +0000 UTC 2023

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
Host: status.hellosign.com
User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.2309.372 Safari/537.36
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
Atl-Traceid: 3bd457ebbdb84f78abebbdf2b64529d9
Cache-Control: max-age=3, public
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 00:01:35 GMT
Etag: W/"a8dbf4faf0cda1c7fd6f87cbe2daafac"
Link: <https://dka575ofm4ao0.cloudfront.net/assets/register_subscription_form-589b657fec607087fc5c740c568270907310bc4f6aaa20256e70f01b103025ca.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/status_common-c1b99d73ee7ab0fea796bd170723c1daac1381095a7dd7501a38ce6f333d86b3.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/vendor/highstock.min-9de8c325692300efdf4b01e93caaa5668693434b74882c25c3b13d58b2d583cb.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/0.6bb03ffda3ffadfa27a1.css>; rel=preload; as=style; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/status/status_manifest-cc9fd99d26ea5cca6f3352190ad1a451683d356cd9a12bb1c7d57870bed73318.css>; rel=preload; as=style; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/jquery-3.5.1.min-729e416557a365062a8a20f0562f18aa171da57298005d392312670c706c68de.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/status_manifest-fe51120c5309a42b8fe23d0af40c6d1ddf533e0e24ebfb16557e15cd82189121.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/common-c3ca024b93f2e64d6f01.chunk.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/globals-3e964b59fb236dbfabd1.chunk.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/runtime-845beefc293f0b2f3a9a.js>; rel=preload; as=script; nopush
Nel: {"failure_fraction": 0.001, "include_subdomains": true, "max_age": 600, "report_to": "endpoint-1"}
Referrer-Policy: strict-origin-when-cross-origin
Report-To: {"endpoints": [{"url": "https://dz8aopenkvv6s.cloudfront.net"}], "group": "endpoint-1", "include_subdomains": true, "max_age": 600}
Server: AtlassianEdge
Strict-Transport-Security: max-age=259200
Vary: Accept-Encoding
Via: 1.1 53f1fabf09e106b6477c73343225c058.cloudfront.net (CloudFront)
X-Amz-Cf-Id: YnxOcMq2ARP1jVHPOSBfTKQDl-4Cng_HEYUNAuWmoLz3zdNi5HdjNA==
X-Amz-Cf-Pop: CDG52-P1
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Edge-Cache-Ttl: 3
X-Permitted-Cross-Domain-Policies: none
X-Pollinator-Metadata-Service: status-page-web-pages
X-Runtime: 0.104732
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
    <meta name="issued" content="1702080011">

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
         url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegular-2ee4c449a9ed716f1d88207bd1094e21b69e2818b5cd36b28ad809dc1924ec54.woff?host=status.hel.... Truncated ....
```

**Extra Information**

**Extracted results:**

- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaLight-f0b2f7c12b6b87c65c02d3c1738047ea67a7607fd767056d8a2964cc6a2393f7.eot?host=status.hellosign.com#iefix
- https://polyfill.io/v3/polyfill.min.js?features=default
- https://dka575ofm4ao0.cloudfront.net/assets/vendor/highstock.min-9de8c325692300efdf4b01e93caaa5668693434b74882c25c3b13d58b2d583cb.js
- https://www.recaptcha.net/recaptcha/enterprise.js?onload=onloadCallback&render=explicit
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegular-366d17769d864aa72f27defaddf591e460a1de4984bb24dacea57a9fc1d14878.eot?host=status.hellosign.com
- https://status.hellosign.com/history.atom
- https://www.atlassian.com/legal/product-specific-terms#statuspage-specific-terms
- https://dka575ofm4ao0.cloudfront.net/packs/common-c3ca024b93f2e64d6f01.chunk.js
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaSemibold-09566917307251d22021a3f91fc646f3e45f8d095209bcd2cded8a1979f06e54.eot?host=status.hellosign.com#iefix
- https://dka575ofm4ao0.cloudfront.net/assets/jquery-3.5.1.min-729e416557a365062a8a20f0562f18aa171da57298005d392312670c706c68de.js
- https://dka575ofm4ao0.cloudfront.net/packs/0.6bb03ffda3ffadfa27a1.css
- https://www.atlassian.com/legal/cloud-terms-of-service
- https://dka575ofm4ao0.cloudfront.net/packs/runtime-845beefc293f0b2f3a9a.js
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaLight-0f094da9b301d03292f97db5544142a16f9f2ddf50af91d44753d9310c194c5f.ttf?host=status.hellosign.com
- https://dka575ofm4ao0.cloudfront.net/assets/status/status_manifest-cc9fd99d26ea5cca6f3352190ad1a451683d356cd9a12bb1c7d57870bed73318.css
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegular-2ee4c449a9ed716f1d88207bd1094e21b69e2818b5cd36b28ad809dc1924ec54.woff?host=status.hellosign.com
- https://status.hellosign.com/incidents/hnxbs18s5q4q
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaBold-c8dc577ff7f76d2fc199843e38c04bb2e9fd15889421358d966a9f846c2ed1cd.woff?host=status.hellosign.com
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegularIt-9e43859f8015a4d47d9eaf7bafe8d1e26e3298795ce1f4cdb0be0479b8a4605e.ttf?host=status.hellosign.com
- https://twitter.com/DropboxSupport
- http://purl.org/dc/terms/issued
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaLight-e642ffe82005c6208632538a557e7f5dccb835c0303b06f17f55ccf567907241.woff?host=status.hellosign.com
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegular-a40a469edbd27b65b845b8000d47445a17def8ba677f4eb836ad1808f7495173.ttf?host=status.hellosign.com
- https://policies.google.com/privacy
- https://dka575ofm4ao0.cloudfront.net/packs/globals-3e964b59fb236dbfabd1.chunk.js
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaLight-f0b2f7c12b6b87c65c02d3c1738047ea67a7607fd767056d8a2964cc6a2393f7.eot?host=status.hellosign.com
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaSemibold-86724fb2152613d735ba47c3f47a9ad2424b898bea4bece213dacee40344f966.woff?host=status.hellosign.com
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaBold-622ea489d20e12e691663f83217105e957e2d3d09703707d40155a29c06cc9d9.eot?host=status.hellosign.com
- https://subscriptions.statuspage.io/slack_authentication/kickoff?page_code=djw9397fmqd1
- https://dka575ofm4ao0.cloudfront.net/assets/status_manifest-fe51120c5309a42b8fe23d0af40c6d1ddf533e0e24ebfb16557e15cd82189121.js
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegularIt-0bf83a850b45e4ccda15bd04691e3c47ae84fec3588363b53618bd275a98cbb7.eot?host=status.hellosign.com#iefix
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaSemibold-cf3e4eb7fbdf6fb83e526cc2a0141e55b01097e6e1abfd4cbdc3eda75d183f74.ttf?host=status.hellosign.com
- https://status.hellosign.com/history.rss
- https://www.w3.org/TR/wai-aria-practices-1.1/examples/tabs/tabs-1/tabs.html
- https://www.dropbox.com/privacy
- https://www.atlassian.com/software/statuspage?utm_campaign=status.hellosign.com&amp;utm_content=SP-notifications&amp;utm_medium=powered-by&amp;utm_source=inapp
- https://dka575ofm4ao0.cloudfront.net/assets/register_subscription_form-589b657fec607087fc5c740c568270907310bc4f6aaa20256e70f01b103025ca.js
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegularIt-0bf83a850b45e4ccda15bd04691e3c47ae84fec3588363b53618bd275a98cbb7.eot?host=status.hellosign.com
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaSemibold-09566917307251d22021a3f91fc646f3e45f8d095209bcd2cded8a1979f06e54.eot?host=status.hellosign.com
- https://status.hellosign.com
- https://www.googletagmanager.com/gtag/js?id=UA-168991564-2
- https://www.atlassian.com/legal/privacy-policy
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaBold-27177fe9242acbe089276ee587feef781446667ffe9b6fdc5b7fe21ad73e12f3.ttf?host=status.hellosign.com
- https://policies.google.com/terms
- https://faq.hellosign.com/
- https://community.atlassian.com/t5/Statuspage-articles/Attention-SMS-notifications-will-be-disabled-on-August-1st-2023/ba-p/2424398
- https://dka575ofm4ao0.cloudfront.net/assets/status_common-c1b99d73ee7ab0fea796bd170723c1daac1381095a7dd7501a38ce6f333d86b3.js
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegular-366d17769d864aa72f27defaddf591e460a1de4984bb24dacea57a9fc1d14878.eot?host=status.hellosign.com#iefix
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaBold-622ea489d20e12e691663f83217105e957e2d3d09703707d40155a29c06cc9d9.eot?host=status.hellosign.com#iefix
- https://www.hellosign.com
- https://dka575ofm4ao0.cloudfront.net/assets/vendor/bowser-1643ca34a6d589b2d4d42163a891e4512d5d7657125e09bb5f3d44288114e6bd.js
- https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegularIt-0c394ec7a111aa7928ea470ec0a67c44ebdaa0f93d1c3341abb69656cc26cbdd.woff?host=status.hellosign.com



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.2309.372 Safari/537.36' 'https://status.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)