### Apache Detection (apache-detect) found on https://brandpartners.dropbox.com

----
**Details**: **apache-detect** matched at https://brandpartners.dropbox.com

**Protocol**: HTTP

**Full URL**: https://brandpartners.dropbox.com

**Timestamp**: Sat Dec 9 00:00:41 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Apache Detection |
| Authors | philippedelteil |
| Tags | tech, apache |
| Severity | info |
| Description | Some Apache servers have the version on the response header. The OpenSSL version can be also obtained |

**Request**
```http
GET / HTTP/1.1
Host: brandpartners.dropbox.com
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
Accept-Ranges: bytes
Age: 13
Cache-Control: max-age=0
Content-Type: text/html;charset=utf-8
Date: Sat, 09 Dec 2023 00:00:41 GMT
Expires: Sat, 09 Dec 2023 00:00:41 GMT
Server: Apache
Vary: Accept-Encoding
Via: 1.1 debce53763611e29dca055fee88e0812.cloudfront.net (CloudFront)
X-Amz-Cf-Id: wKO4vj18tg2k2up2YefUCjrIKjXnP6ltTRZysdSrstnN72eyU7_ZQA==
X-Amz-Cf-Pop: ORD56-P3
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Dispatcher: dispatcher1uswest1
X-Frame-Options: SAMEORIGIN
X-Vhost: dropbox-prod.adobemsbasic.com

<!doctype html>
    
    
    
    
    <html lang="en" xml:lang="en" data-cms-lang="en-us">
    <head>
        
<meta charset="utf-8"/>

<title>Dropbox Brand Partners - Dropbox</title>





<meta name="data-tags" content="Dropbox"/>

<meta name="page-id" content="brand_partner-en-us"/>


      <script>
            let path = window.location.href;
            if (path.endsWith("/")) {
                path = path.slice(0, -1);
            }
            let link = document.createElement("link");
            link.rel = "canonical";
            link.href = path;
            document.head.appendChild(link);
      </script>










<link rel="icon" href="https://aem.dropbox.com/cms/content/dam/dropbox/aem/favicon32.ico" type="image/x-icon"/>


 
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







<meta property="og:url" content="https://www.dropbox.com/content/dropbox/brand_partner/en-us"/>
<meta property="og:type" content="article"/>
<meta property="og:title" content="Dropbox Brand Partners"/>




<meta name="twitter:card" content="summary"/>



<meta content="width=device-width,initial-scale=1.0,user-scalable=no" name="viewport"/>



    <link rel="alternate" hreflang="en" href="https://www.dropbox.com/content/dropbox/brand_partner/en-us"/>
    <link rel="alternate" hreflang="configurations" href="https://www.dropbox.com/content/dropbox/brand_partner/configurations"/>




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
                a = "\/\/tags.tiqcdn.com\/utag\/dropbox\/main\/prod\/utag.js";
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
    




        













    
<link rel="stylesheet" href="https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-partner/clientlib-all.ae23646f86ecedb87961fd760702a4de.css" type="text/css">






    
<script type="text/javascript" src="https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-partner/clientlib-all.54e354595868bded1ef9ec17e659e327.js" defer></script>





    
<script type="text/javascript" src="https://aem.dropbox.com/cms/etc.clientlibs/clientlibs/social/thirdparty/handlebars.3a102a97671a524dc588fb10700ead22.js" defer></script>



    </head>
    <body class="home-page__page" data-article-uuid="c8cc010c-1da9-47e4-8f04-e31b7226dbbd">
          <div class="brand-partner__container">
        <!--/*<sly data-sly-include="partials/slidingoverlay.html"/>
        <script type="text/javascript">document.body.classList.add('loading');</script> -->
        








<!--/* Calling the tealium utag sync to avoid adobe target flickering */ -->



    
         
          <!-- CMS-5456 : Optimizing target calls -->
                
         
    

<!-- /* Calling the tealium utag sync to avoid adobe target flickering */  -->

    
        <script type="text/javascript">
            var attr = "tealium_event$cms".split(",");
            var utag_data = window.utag_data || {}
            attr.forEach(function (item) {
                if (item && item.indexOf("$") > -1)
                    utag_.... Truncated ....
```

**Extra Information**

**Extracted results:**

- Apache



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.2309.372 Safari/537.36' 'https://brandpartners.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)