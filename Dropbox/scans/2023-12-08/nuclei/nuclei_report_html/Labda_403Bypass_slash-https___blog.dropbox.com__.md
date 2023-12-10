### Labda 403 bypass (Labda_403Bypass_slash) found on https://blog.dropbox.com

----
**Details**: **Labda_403Bypass_slash** matched at https://blog.dropbox.com

**Protocol**: HTTP

**Full URL**: https://blog.dropbox.com//

**Timestamp**: Sat Dec 9 00:00:33 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Labda 403 bypass |
| Authors | labda |
| Tags | bypass, web, 403, forbidden |
| Severity |  |
| Description | Bypasses 403 Forbidden |

**Request**
```http
GET // HTTP/1.1
Host: blog.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/95.0.4638.54 Safari/537.36
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
Cache-Control: max-age=0
Content-Type: text/html;charset=utf-8
Date: Sat, 09 Dec 2023 00:00:33 GMT
Expires: Sat, 09 Dec 2023 00:00:33 GMT
Server: Apache
Vary: Accept-Encoding
Via: 1.1 873527676a354c5998cad133525df9c0.cloudfront.net (CloudFront)
X-Amz-Cf-Id: Ht_xDotxQfV4T23I72IBOTioR32NQs9-EkgDx3rcvxmBUFHLqJs40g==
X-Amz-Cf-Pop: MSP50-P1
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Dispatcher: dispatcher2uswest1
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
	body.new-blog-collection__page.u03-navigation__dropdown--open .u03-.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/95.0.4638.54 Safari/537.36' 'https://blog.dropbox.com//'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)