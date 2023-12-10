### Possible phone numbers extractor (extract-possible-phonenumbers) found on https://blog.dropbox.com

----
**Details**: **extract-possible-phonenumbers** matched at https://blog.dropbox.com

**Protocol**: HTTP

**Full URL**: https://blog.dropbox.com

**Timestamp**: Sat Dec 9 00:00:40 +0000 UTC 2023

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
Host: blog.dropbox.com
User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux i686 on x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/53.0.2820.59 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Accept-Ranges: bytes
Age: 8
Cache-Control: max-age=0
Content-Type: text/html;charset=utf-8
Date: Sat, 09 Dec 2023 00:00:38 GMT
Expires: Sat, 09 Dec 2023 00:00:38 GMT
Server: Apache
Vary: Accept-Encoding
Via: 1.1 cb33d1722582b68ec8b5fec11b890e08.cloudfront.net (CloudFront)
X-Amz-Cf-Id: F28RqWJ6KXwhpMZWkHJGft7CBmJwY9FwgpGrSGYIvXnqopr-EBMOWQ==
X-Amz-Cf-Pop: MSP50-P1
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Dispatcher: dispatcher1uswest1
X-Frame-Options: SAMEORIGIN
X-Vhost: dropbox-prod.adobemsbasic.com

<!doctype html>
    
    
    
    
    <html lang="en" xml:lang="en" data-cms-lang="en-us">
    <head>
        <meta charset="utf-8"/>

<title>Work in Progress | Dropbox Blog</title>



<link rel="canonical" href="https://blog.dropbox.com/"/>



<meta name="quotasDisabled" content="true"/>
<meta name="pricingDisabled" content="true"/>



<meta name="primary_color" content="coconut"/>
<meta name="secondary_color" content="orchid plum"/>



<link rel="icon" href="https://aem.dropbox.com/cms/content/dam/dropbox/aem/favicon32.ico" type="image/x-icon"/>
<link rel="alternate" type="application/rss+xml" title="RSS Feed for Dropbox blog" href="https://blog.dropbox.com/feed/"/>




 
<script>
    window.utag_cfg_ovrd = window.utag_cfg_ovrd || {};
    window.utag_cfg_ovrd.noview = true;
    window.utag_data = window.utag_data || {};
    window.utag_data.evidon_enabled = true;
    if(window.utag_data.consent_categories == undefined){
        window.utag_data.consent_categories = "";
    }
</script>
<script src="https://www.dropbox.com/pithos/privacy_consent,top_frame_marketing_tracker,ux_analytics" async="true"></script>



<meta property="og:url" content="https://blog.dropbox.com/"/>
<meta property="og:type" content="article"/>
<meta property="og:title" content="Work in Progress: by Dropbox"/>

<meta property="og:image" content="https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2019/02/social_card_wip.png"/>


<meta name="twitter:card" content="summary_large_image"/>



<meta content="width=device-width,initial-scale=1.0,user-scalable=no" name="viewport"/>



    <link rel="alternate" hreflang="en-us" href="https://blog.dropbox.com/"/>









<!--/* Calling the tealium utag sync to avoid adobe target flickering */ -->



    
         
          <!-- CMS-5456 : Optimizing target calls -->
                
         
    

<!-- /* Calling the tealium utag sync to avoid adobe target flickering */  -->

    
        <script type="text/javascript">
            var attr = "tealium_event$cms".split(",");
            var utag_data = window.utag_data || {}
            attr.forEach(function (item) {
                if (item && item.indexOf("$") > -1)
                    utag_data[item.split("$")[0]] = item.split("$")[1];
            })
        </script>
        <script type="text/javascript">
            (function (a, b, c, d) {
                a = "\/\/tags.tiqcdn.com\/utag\/dropbox\/blog\/prod\/utag.js";
                b = document;
                c = 'script';
                d = b.createElement(c);
                d.src = a;
                d.type = 'text/java' + c;
                d.async = true;
                a = b.getElementsByTagName(c)[0];
                a.parentNode.insertBefore(d, a);
            })();
        </script>
    




<!-- blog-collection-page-horizontal-scroll -->
<style>
body.new-blog-collection__page .u01-header__color-panel {
    transition: none;
}
@media screen and (min-width: 1300px) {
	body.new-blog-collection__page {

		margin: 0;
		padding: 0;
	}

	body.new-blog-collection__page .u01-header {
		transform: translateY(-100%);
	}

    body.new-blog-collection__page .u01-header.visible {
        transform: translateY(0);
        transition: .6s cubic-bezier(0.25, 0, 0, 1);
    }

	body.new-blog-collection__page .u01-header,
	body.new-blog-collection__page .u01-header__header,
	body.new-blog-collection__page .u01-header__color-panel {
		background-color: white;
	}
	body.new-blog-collection__page .u01-header__logo-img--glyph path {
		fill: #000000;
	}
	body.new-blog-collection__page .u01-header__logo-img--word path {
		fill: #000000;
	}
	body.new-blog-collection__page .u03-navigation__list-link:link,
	body.new-blog-collection__page .u03-navigation__list-link:visited,
	body.new-blog-collection__page .u03-navigation__list-link:hover,
	body.new-blog-collection__page .u03-navigation__list-link:active,
	body.new-blog-collection__page .u03-navigation__list-link:focus,
	body.new-blog-collection__page .u03-navigation__list-nolink:link,
	body.new-blog-collection__page .u03-navigation__list-nolink:visited,
	body.new-blog-collection__page .u03-navigation__list-nolink:hover,
	body.new-blog-collection__page .u03-navigation__list-nolink:active,
	body.new-blog-collection__page .u03-navigation__list-nolink:focus {
		color: #000000;
	}
	body.new-blog-collection__page.u03-navigation__dropdown--op.... Truncated ....
```

**Extra Information**

**Extracted results:**

- 0 0 207 25
- 0 1.452
- 2.794 2.904
- 264-1.254
- 308 1.386
- 14-9358
- 894-1.364
- 0-2.618-1.386
- 4.378 0-6
- 3.432 0 5
- 4.972 0-7
- 6-1123-45
- 2.618-1.936
- 2.97 0 4
- 6.754 4.708
- 3-2023
- 16.99 0
- 15-6.512
- 2.442 0-3
- 0 2.816-2.244
- 352 9.592
- 4.29-6.292
- 02 6.47
- 2.97 2.772
- 3.938 3.982
- 74 1.078-4
- 49-5.41-8
- 902 1.034
- 1.012 2.772
- 3.784-2.926
- 7.04 4.114
- 8.38 4.114
- 5.893-6.204
- 3.85 3.872
- 88-1.76 2
- 12.12-3.146
- 968-5.654
- 1.496 0-2
- 13.528.374
- 574 2.112
- 574801
- 916-1.364
- 286 2.464
- 4.136 5.94
- 5.17 4.884
- 4.246-6.38
- 1.672 4.312
- 7.282-7.678
- 0-1.584-1.21
- 2.618 0 3
- 10.274
- 0-1.474.946-2
- 0 5.654
- 55-2.112 1
- 6.424-6.16
- 0 1.43 1.078
- 86218
- 618-2.816
- 4.51-7.238
- 5.082 0-6
- 17.0057 5.008
- 3.784 3.894
- 1.386 1.958
- 594 2.948
- 8.51 1.06
- 3.366 0-4
- 0-2.266
- 11.7737 12.088
- 400116
- 3.982-3.894
- 0 2.442 1.342
- 792-1.804
- 0-3.916 2.64
- 14.7977 2.2
- 8.5-5.41
- 34 17.3
- 088 2.904
- 3.63 1.958
- 71.048 4.07
- 11.416
- 3.52 0-2
- 2.42-2.992
- 4.84-2.992
- 14.5817 12.184
- 324 2.178
- 3.124-3.652
- 1.562-2.948
- 442.682-2
- 622-1.562
- 3.366 8.602
- 0-3.916 1.386
- 4.026-6.028
- 2.794.792
- 0 7.04 2.882
- 16.9817 9.4
- 86256
- 12.45 2.376
- 792-3.652
- 3.718 0 6
- 11.1737 0.183999
- 0.0616876 5
- 950-47
- 044-2.75
- 1.386 0 2
- 3.564 4.092
- 286 2.64
- 6.094 6.688
- 2.10092
- 73255
- 13.9577
- 65974
- 396 3.168
- 18 4.356
- 28-7684-4
- 2.354 0-3
- 2.156 0-2
- 15.4217 5.872
- 604257
- 0 7.194 2.42
- 684 0 71
- 11.154
- 1.43 3.652
- 968 5.786
- 17.465 0
- 4.004-3.828
- 484-2.948
- 308 5.786
- 3-6297-476
- 4.994-2.816
- 578-1.144
- 6.666 4.312
- 2.288 0 3
- 11.9657 2.248
- 3.982-2.442
- 1.606 14.234
- 2.134-3.278
- 66 4.026-1
- 012-1.188
- 8.5-5.41-8
- 3.718 8.448
- 4.444 12.65
- 464-2.09
- 726 2.046
- 5.324 5.566
- 308 4.312
- 55-1.364-2
- 1.188-3.982
- 02 17.3
- 8.51 24.51
- 7.194 6.666
- 4272-92
- 3.916-3.784
- 2.134 2.046
- 7.084-6.424
- 6.754 7.238
- 0 1.012 1.122
- 2.882-8.602
- 15-2.398-7
- 2.376 0-3
- 8.49 5.42
- 6.402-6.072
- 1316279-6384
- 18 1.122-4
- 2.794-4.444
- 6.82 6.754
- 14.407 0
- 8.5 5.42 8
- 2.332 3.278
- 61 3.74
- 16627
- 6.512-7.238
- 576-3.278
- 462 2.904
- 88-4.818-2
- 3511506841
- 6.666 7.194
- 0 4.048-2.596
- 134.506 2
- 134 2.024
- 442 1.606
- 084-2.552
- 8.49 5.41
- 2.002 3.256
- 308 1.914
- 4.862 0-7
- 98-3.278 4
- 0 2.464-1.034
- 1.826 0 2
- 88-3.102-2
- 2.068 0-3
- 7.04 6.512
- 3.674 0-2
- 9-9813
- 8.5-5.42
- 0-4.224 2.948
- 1.496 3.41
- 094 2.376
- 454.902 0
- 15.5417 8.416
- 19.682-3.19
- 1.408-3.344
- 772 1.452
- 11.0297 14.224
- 1.012 2.662
- 6.578-2.97
- 594.682.792
- 3.916 3.982
- 3.894-3.784
- 54717485-2
- 528 3.344
- 13.8617 4.6
- 0 4.268-2.75
- 170.688 7
- 22.503 3.608
- 386 1.056
- 3.014 0-3
- 838-1.364
- 1.672.132-2
- 264-5.654
- 4.136 4.048
- 49-5.42-8
- 14.76.374
- 25.471 3.85
- 19.4537 7.792
- 0 6.116 1.496
- 1200-628
- 08714011
- 000000
- 3.63-8.58
- 3.938 1.518
- 816-2.09
- 1.496-2.926
- 13.9337 9.664
- 81137
- 0 2.42 1.364
- 0 2.772-2.266
- 403-5265
- 7654-6770-4
- 3.322-1.738
- 0052-440
- 13.772 18.304
- 4.136 2.926
- 3.894 0 5
- 376 1.936
- 34 6.47
- 2.42 8.58
- 154-3.102
- 4.092 5.962
- 454.308-3
- 286-1.914
- 3.41 4.114
- 0 0 20 15
- 25.48-5.42
- 3.366-8.448
- 5.324 7.766
- 1.386-1.738
- 854377
- 528-2.112
- 7.084-4.554
- 14.1497 0.183999
- 0.0616876 8
- 0-2.552-1.364
- 1.65 2.926
- 13.9577 14.224
- 61 1.254 5
- 136 2.926
- 772.638-2
- 0 0 34 31
- 564 1.518
- 42 3.3-2
- 1.562 0-1
- 1.21 3.916
- 68.936.506 69
- 354 0-1
- 682 3.388
- 0 0 135 2
- 3 2023
- 2.2 0 2.948
- 6.688 4.202
- 3.74 0 2



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux i686 on x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/53.0.2820.59 Safari/537.36' 'https://blog.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)