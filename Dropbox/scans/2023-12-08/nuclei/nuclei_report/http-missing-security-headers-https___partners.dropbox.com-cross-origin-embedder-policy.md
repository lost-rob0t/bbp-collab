### HTTP Missing Security Headers (http-missing-security-headers:cross-origin-embedder-policy) found on https://partners.dropbox.com

----
**Details**: **http-missing-security-headers:cross-origin-embedder-policy** matched at https://partners.dropbox.com

**Protocol**: HTTP

**Full URL**: https://partners.dropbox.com

**Timestamp**: Sat Dec 9 14:55:35 +0000 UTC 2023

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
Host: partners.dropbox.com
User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/55.0.2919.83 Safari/537.36
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
Age: 4290396
Cache-Control: max-age=31536000
Content-Security-Policy: upgrade-insecure-requests; default-src 'self' ziftsolutions.ccindex.cn *.ziftsolutions.com *.staging.ziftone.com *.ziftone.com *.google-analytics.com *.wistia.com *.wistia.net blob: ; img-src 'self' http: https: ziftsolutions.ccindex.cn *.ziftsolutions.com s3.amazonaws.com *.google-analytics.com *.wistia.com *.wistia.net data: ; script-src 'self' 'unsafe-inline' 'unsafe-eval' https: checkout.stripe.com *.ziftsolutions.com *.ziftone.com *.getbee.io *.googleapis.com *.google-analytics.com *.zdassets.com *.googletagmanager.com *.google.com *.pendo.io browser-update.org static.zdassets.com s3.amazonaws.com *.zopim.com *.churnzero.net *.marketo.com *.wistia.com *.wistia.net data: ; connect-src 'self' https: ziftsolutions.ccindex.cn *.ziftsolutions.com *.ziftone.com *.zift123.com *.zendesk.com *.zdassets.com *.zopim.com wss://widget-mediator.zopim.com *.churnzero.net *.getbee.io *.google-analytics.com *.wistia.com *.wistia.net *.litix.io data: ; style-src 'self' 'unsafe-inline' blob: https: fast.wistia.com; font-src 'self' https: fast.wistia.com fast.wistia.net data:; media-src 'self' https: ziftsolutions.ccindex.cn *.ziftsolutions.com *.zift123.com *.ziftone.com *.looker.com *.ziftmarcom.com *.lenovo.com *.wistia.com *.wistia.net blob: data: ; object-src 'self' https: *.ziftsolutions.com *.ziftsolutions.com *.zift123.com *.ziftone.com *.looker.com *.ziftmarcom.com; frame-src 'self' https: *.onserro.com *.onserrodemo.com ziftsolutions.ccindex.cn *.ziftsolutions.com *.zift123.com *.staging.ziftone.com *.ziftone.com *.looker.com *.ziftmarcom.com *.getbee.io *.getbee.com; frame-ancestors 'self' https: *.onserro.com *.onserrodemo.com ziftsolutions.ccindex.cn *.ziftsolutions.com *.zift123.com *.ziftone.com *.looker.com *.ziftmarcom.com; worker-src 'self' blob: ;
Content-Type: text/html
Date: Fri, 20 Oct 2023 23:08:59 GMT
Etag: W/"90ea6b1ea1fc39a4386362d992001728"
Expires: Sun, 15 Oct 2023 20:02:53 GMT
Last-Modified: Sun, 15 Oct 2023 20:02:55 GMT
Referrer-Policy: no-referrer-when-downgrade
Server: AmazonS3
Strict-Transport-Security: max-age=63072000; includeSubdomains; preload
Vary: Accept-Encoding
Via: 1.1 33388636a7cb2afa812b276d900f88d4.cloudfront.net (CloudFront), 1.1 d6ca02594f64feaa0041e70bddff61ee.cloudfront.net (CloudFront)
X-Amz-Cf-Id: LNa_GIAdNEYrWX6aD02QMoBptnEy68qit_hqJRAcbmdjb2d22Q0HeA==
X-Amz-Cf-Pop: DUB56-P1
X-Amz-Cf-Pop: CDG53-C1
X-Amz-Replication-Status: FAILED
X-Amz-Server-Side-Encryption: AES256
X-Amz-Version-Id: KCz9a_zDHhhG20xie757mUmkE27UdbLZ
X-Cache: Hit from cloudfront
X-Content-Type-Options: nosniff
X-Xss-Protection: 1; mode=block

<!DOCTYPE html>
<html lang="en" id="ng-app" ng-app="ziftAppModule">
<head>

    <title ng-bind="(pageTitle ? pageTitle + ' - ' : '') + (siteBrand && siteBrand.marcomName ? siteBrand.marcomName : isPartnerPortalDomain ? '' : 'Partner portal')"></title>

    <meta charset="utf-8">
    <meta name="description" content="Zift" />
    <meta name="author" content="Zift Solutions Inc." />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
    <link rel="shortcut icon" brand-favicon />
    <link rel="canonical" href="{{canonicalUrl}}" />
    <!-- no clickjacking, bro -->
    <script>if (top != self && top.location.hostname != self.location.hostname) top.location=location</script>
    <script src="js/config.js?rel=1697400087592"></script>

<!--    <script src="https://kit.fontawesome.com/10033eaeb0.js?rel=1697400139832120762" crossorigin="anonymous"></script>-->
    <script src="https://kit.fontawesome.com/af436fe6a2.js?rel=1697400139832120762" crossorigin="anonymous"></script>

    <!-- Google Tag Manager -->
    <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
            new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
        j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
        'https://www.googletagmanager.com/gtm.js?id='+i+dl+ GOOGLE_TM_KEY;f.parentNode.insertBefore(j,f);
    })(window,document,'script','dataLayer','GTM-WBP8BR5');</script>
    <!-- End Google Tag Manager -->

    <!-- Stripe Checkout - It looks like we are behind a couple versions of Stripe and their APIs have changed, consider upgrading -->
    <script src="https://checkout.stripe.com/checkout.js?rel=1697400139832120762"></script>
    <!-- End Stripe Checkout -->

    <script src="../common/lib/jquery/jquery-switch.js?rel=1697400139832120762"></script>

    <script src="../common/lib/third-party.js?v=20220211"></script> <!-- to use the constituent parts esp for performance profiling replace this line with code in third-party-js-for-dev.html -->
    <link href="css/third-party.min.css?v=20211121" rel="stylesheet" />

    <link rel="stylesheet" href="dist/css/base.min.css?rel=1697400087592"/>

    <style>
        .feedback-container { margin-top:15px; }
        .feedback-link { margin-left:20px; margin-top:-3px; }
        .messages-header {.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/55.0.2919.83 Safari/537.36' 'https://partners.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)