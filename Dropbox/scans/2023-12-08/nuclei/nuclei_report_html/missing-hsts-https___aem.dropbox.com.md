### Strict Transport Security Not Enforced (missing-hsts) found on https://aem.dropbox.com

----
**Details**: **missing-hsts** matched at https://aem.dropbox.com

**Protocol**: HTTP

**Full URL**: https://aem.dropbox.com

**Timestamp**: Sat Dec 9 08:22:59 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Strict Transport Security Not Enforced |
| Authors | dawid czarnecki |
| Tags | misc |
| Severity | info |
| Description | Checks if the HSTS is enabled by looking for Strict Transport Security response header. |

**Request**
```http
GET / HTTP/1.1
Host: aem.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 404 Not Found
Connection: close
Access-Control-Allow-Headers: Content-Type, origin, accept
Access-Control-Allow-Methods: GET, OPTIONS
Access-Control-Allow-Origin: *
Content-Type: text/html;charset=utf-8
Date: Sat, 09 Dec 2023 08:22:59 GMT
Server: Apache
Timing-Allow-Origin: https://www.dropbox.com
Vary: Accept-Encoding
Via: 1.1 a769201928d4a671d76c2aeb231718ae.cloudfront.net (CloudFront)
X-Aem-Error-Pass: true
X-Amz-Cf-Id: NcuJ2WuwIu-4oUKyHSzKfpdNJgUUkpxKkBturtb8x3K1aQQ3Oottnw==
X-Amz-Cf-Pop: CDG52-P1
X-Cache: Error from cloudfront
X-Content-Type-Options: nosniff
X-Dispatcher: dispatcher2uswest1
X-Frame-Options: SAMEORIGIN
X-Vhost: dropbox-prod.adobemsbasic.com

<!doctype html>


    
    
    

    


    
    
    
    

    
    
    
    

    <html lang="en" xml:lang="en" data-cms-lang="en-us">
    <head>
        
<meta charset="utf-8"/>

<title>Not found - Dropbox</title>







<meta name="page-id" content="error-404"/>


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




<meta name="uxAnalyticsEnabled" content="true"/>





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







<meta property="og:url" content="https://www.dropbox.com/error/404"/>
<meta property="og:type" content="article"/>
<meta property="og:title" content="Not found"/>




<meta name="twitter:card" content="summary_large_image"/>



<meta content="width=device-width,initial-scale=1.0,user-scalable=no" name="viewport"/>



    <link rel="alternate" hreflang="en" href="https://www.dropbox.com/error/404"/>




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
    




        

        













    
<link rel="stylesheet" href="https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-birch/clientlib-all.7b04b1e8f59eb5a4d57448a46b55d224.css" type="text/css">






    
<script type="text/javascript" src="https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-birch/clientlib-all.8f6f4970ee6de530b4a25b2038be8db2.js" defer></script>


    </head>
    <body class="birch-page__page    stormcrow-animate   " data-article-uuid="2959daba-33ea-4877-8c35-a1e7f1d8dbbf">

        

        
        <input type="hidden" id="wcmRunmode" name="wcmRunmode" value="publish,prod"/>
        

        <!-- Stormcrow Rule for EMEA Cookie Banner -->

    <div data-stormcrow-feature="emea_cookie_countries">
        <div data-stormcrow-variant="OFF" class="stormcrow-variant stormcrow-variant--hidden stormcrow-variant--first">
        </div>
        <div data-stormcrow-variant="ON" class="stormcrow-variant stormcrow-variant--hidden">
        </div>
    </div>


<!-- Stormcrow Rule for EMEA Cookie Banner -->








    


        


    






















<!-- Business Notification -->

<header class="u01-header__header     ">
    <div class="u01-header__logo logo--long">
        <a href="/" class="u01-header__logo-link">
            
            <svg width="40" height="40" viewBox="0 0 40 40" xmlns="http://www.w3.org/2000/svg" class="u01-header__logo-img u01-header__logo-i.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36' 'https://aem.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)