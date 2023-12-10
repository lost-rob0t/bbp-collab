### ElasticSearch Information Disclosure (elasticsearch) found on https://partners.dropbox.com

----
**Details**: **elasticsearch** matched at https://partners.dropbox.com

**Protocol**: HTTP

**Full URL**: https://partners.dropbox.com/?pretty

**Timestamp**: Sat Dec 9 13:04:19 +0000 UTC 2023

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
Host: partners.dropbox.com
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
Cache-Control: max-age=31536000
Content-Security-Policy: upgrade-insecure-requests; default-src 'self' ziftsolutions.ccindex.cn *.ziftsolutions.com *.staging.ziftone.com *.ziftone.com *.google-analytics.com *.wistia.com *.wistia.net blob: ; img-src 'self' http: https: ziftsolutions.ccindex.cn *.ziftsolutions.com s3.amazonaws.com *.google-analytics.com *.wistia.com *.wistia.net data: ; script-src 'self' 'unsafe-inline' 'unsafe-eval' https: checkout.stripe.com *.ziftsolutions.com *.ziftone.com *.getbee.io *.googleapis.com *.google-analytics.com *.zdassets.com *.googletagmanager.com *.google.com *.pendo.io browser-update.org static.zdassets.com s3.amazonaws.com *.zopim.com *.churnzero.net *.marketo.com *.wistia.com *.wistia.net data: ; connect-src 'self' https: ziftsolutions.ccindex.cn *.ziftsolutions.com *.ziftone.com *.zift123.com *.zendesk.com *.zdassets.com *.zopim.com wss://widget-mediator.zopim.com *.churnzero.net *.getbee.io *.google-analytics.com *.wistia.com *.wistia.net *.litix.io data: ; style-src 'self' 'unsafe-inline' blob: https: fast.wistia.com; font-src 'self' https: fast.wistia.com fast.wistia.net data:; media-src 'self' https: ziftsolutions.ccindex.cn *.ziftsolutions.com *.zift123.com *.ziftone.com *.looker.com *.ziftmarcom.com *.lenovo.com *.wistia.com *.wistia.net blob: data: ; object-src 'self' https: *.ziftsolutions.com *.ziftsolutions.com *.zift123.com *.ziftone.com *.looker.com *.ziftmarcom.com; frame-src 'self' https: *.onserro.com *.onserrodemo.com ziftsolutions.ccindex.cn *.ziftsolutions.com *.zift123.com *.staging.ziftone.com *.ziftone.com *.looker.com *.ziftmarcom.com *.getbee.io *.getbee.com; frame-ancestors 'self' https: *.onserro.com *.onserrodemo.com ziftsolutions.ccindex.cn *.ziftsolutions.com *.zift123.com *.ziftone.com *.looker.com *.ziftmarcom.com; worker-src 'self' blob: ;
Content-Type: text/html
Date: Sat, 09 Dec 2023 13:04:19 GMT
Etag: W/"652fd18c65e2698bf2453a4f1f1e7e70"
Expires: Sun, 03 Dec 2023 21:03:17 GMT
Last-Modified: Sun, 03 Dec 2023 21:03:19 GMT
Referrer-Policy: no-referrer-when-downgrade
Server: AmazonS3
Strict-Transport-Security: max-age=63072000; includeSubdomains; preload
Vary: Accept-Encoding
Via: 1.1 e3f435228cbc8657d81bd707948f5910.cloudfront.net (CloudFront), 1.1 0427e61e9a445e92793b25f38fbdcb74.cloudfront.net (CloudFront)
X-Amz-Cf-Id: gmecaYNws5Ggv8SpdP33DNwmL5C2dgo1GjOErCZqwpX8k95yiiUpHA==
X-Amz-Cf-Pop: DUB56-P1
X-Amz-Cf-Pop: CDG53-C1
X-Amz-Replication-Status: FAILED
X-Amz-Server-Side-Encryption: AES256
X-Amz-Version-Id: hsjCx8MwIiswBKs6YorJYPQq7lq4qCl8
X-Cache: Miss from cloudfront
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
    <script src="js/config.js?rel=1701637304623"></script>

<!--    <script src="https://kit.fontawesome.com/10033eaeb0.js?rel=1701637362117466411" crossorigin="anonymous"></script>-->
    <script src="https://kit.fontawesome.com/af436fe6a2.js?rel=1701637362117466411" crossorigin="anonymous"></script>

    <!-- Google Tag Manager -->
    <script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
            new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
        j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
        'https://www.googletagmanager.com/gtm.js?id='+i+dl+ GOOGLE_TM_KEY;f.parentNode.insertBefore(j,f);
    })(window,document,'script','dataLayer','GTM-WBP8BR5');</script>
    <!-- End Google Tag Manager -->

    <!-- Stripe Checkout - It looks like we are behind a couple versions of Stripe and their APIs have changed, consider upgrading -->
    <script src="https://checkout.stripe.com/checkout.js?rel=1701637362117466411"></script>
    <!-- End Stripe Checkout -->

    <script src="../common/lib/jquery/jquery-switch.js?rel=1701637362117466411"></script>

    <script src="../common/lib/third-party.js?v=20231106"></script> <!-- to use the constituent parts esp for performance profiling replace this line with code in third-party-js-for-dev.html -->
    <link href="css/third-party.min.css?v=20211121" rel="stylesheet" />

    <link rel="stylesheet" href="dist/css/base.min.css?rel=1701637304623"/>

    <style>
        .feedback-container { margin-top:15px; }
        .feedback-link { margin-left:20px; margin-top:-3px; }
        .messages-header { padding-top:.... Truncated ....
```

References: 
- https://www.elastic.co/blog/a-practical-introduction-to-elasticsearch
- https://discuss.elastic.co/t/how-to-find-elastic-search-version/8737

**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_2) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1944.0 Safari/537.36' 'https://partners.dropbox.com/?pretty'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)