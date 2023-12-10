### Nicknames extractor (extract-nickname) found on https://jobs.dropbox.com

----
**Details**: **extract-nickname** matched at https://jobs.dropbox.com

**Protocol**: HTTP

**Full URL**: https://jobs.dropbox.com

**Timestamp**: Sat Dec 9 00:01:12 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Nicknames extractor |
| Authors | cipher387 |
| Tags | osint, juicy-info |
| Severity | info |
| Description | Extract nicknames (words start with @) from web page body (extract the second parts of the emails as well, but this is additional unnecessary information. To extract full emails, use the emails.yaml template) |

**Request**
```http
GET / HTTP/1.1
Host: jobs.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 6.4; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2225.0 Safari/537.36
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
Date: Sat, 09 Dec 2023 00:01:09 GMT
Expires: Sat, 09 Dec 2023 00:01:09 GMT
Server: Apache
Vary: Accept-Encoding
Via: 1.1 9d1195da2196f119f0b70fe9bda25e10.cloudfront.net (CloudFront)
X-Amz-Cf-Id: O14thfYzyTu9CXrfSAT-TUrvOO5bIiIf7oTQO0_vF2Ry7ltKq5-mqg==
X-Amz-Cf-Pop: CDG50-P4
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Dispatcher: dispatcher2uswest1
X-Frame-Options: SAMEORIGIN
X-Vhost: dropbox-prod.adobemsbasic.com

<!doctype html>


    
    
    

    


    
    
    
    

    
    
    
    

    <html lang="en" xml:lang="en" data-cms-lang="en-us">
    <head>
        
<meta charset="utf-8"/>

<title>Join Us - Jobs - Dropbox</title>




<meta name="description" content="Join us at Dropbox and design your dream career from anywhere. We&#39;re building a company that works hard for its people. Apply now to work at Dropbox.
"/>


<meta name="page-id" content="en-us-jobs"/>


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







<meta property="og:url" content="https://www.dropbox.com/jobs"/>
<meta property="og:type" content="article"/>
<meta property="og:title" content="Join Us - Jobs"/>
<meta property="og:description" content="Join us at Dropbox and design your dream career from anywhere. We&#39;re building a company that works hard for its people. Apply now to work at Dropbox.
"/>
<meta property="og:image" content="https://aem.dropbox.com/cms/content/dam/dropbox/www/en-us/jobs/blog-pictures/Join-our-team.png/_jcr_content/renditions/Join-our-team.og.png"/>


<meta name="twitter:card" content="summary"/>



<meta content="width=device-width,initial-scale=1.0,user-scalable=no" name="viewport"/>



    <link rel="alternate" hreflang="id" href="https://www.dropbox.com/id/jobs"/>
    <link rel="alternate" hreflang="ms" href="https://www.dropbox.com/ms/jobs"/>
    <link rel="alternate" hreflang="da" href="https://www.dropbox.com/da_DK/jobs"/>
    <link rel="alternate" hreflang="de" href="https://www.dropbox.com/de/jobs"/>
    <link rel="alternate" hreflang="en-GB" href="https://www.dropbox.com/en_GB/jobs"/>
    <link rel="alternate" hreflang="en" href="https://www.dropbox.com/jobs"/>
    <link rel="alternate" hreflang="es-ES" href="https://www.dropbox.com/es_ES/jobs"/>
    <link rel="alternate" hreflang="es" href="https://www.dropbox.com/es/jobs"/>
    <link rel="alternate" hreflang="fr" href="https://www.dropbox.com/fr/jobs"/>
    <link rel="alternate" hreflang="it" href="https://www.dropbox.com/it/jobs"/>
    <link rel="alternate" hreflang="nl" href="https://www.dropbox.com/nl_NL/jobs"/>
    <link rel="alternate" hreflang="no" href="https://www.dropbox.com/nb_NO/jobs"/>
    <link rel="alternate" hreflang="pl" href="https://www.dropbox.com/pl/jobs"/>
    <link rel="alternate" hreflang="pt-BR" href="https://www.dropbox.com/pt_BR/jobs"/>
    <link rel="alternate" hreflang="ru" href="https://www.dropbox.com/ru/jobs"/>
    <link rel="alternate" hreflang="sv" href="https://www.dropbox.com/sv_SE/jobs"/>
    <link rel="alternate" hreflang="th" href="https://www.dropbox.com/th_TH/jobs"/>
    <link rel="alternate" hreflang="zh-CN" href="https://www.dropbox.com/zh_CN/jobs"/>
    <link rel="alternate" hreflang="zh-TW" href="https://www.dropbox.com/zh_TW/jobs"/>
    <link rel="alternate" hreflang="ja" href="https://www.dropbox.com/ja/jobs"/>
    <link rel="alternate" hreflang="ko" href="https://www.dropbox.com/ko/jobs"/>




<!--/* Calling the tealium utag sync to avoid adobe target flickering */ -->



    
         
          <!-- CMS-5456 : Optimizing target calls -->
                
                 <script src="https://tags.tiqcdn.com/utag/dropbox/main/prod/utag.sync.js"></script>
                
         
    

<!-- /* Calling the tealium utag sync to avoid adobe target flickering */  -->

    
        <script type="text/javascript">
            var attr = "tealium_event$cms".split(",");
            var utag_data = window.utag_data || {}
            attr.f.... Truncated ....
```

**Extra Information**

**Extracted results:**

- @media



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.4; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2225.0 Safari/537.36' 'https://jobs.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)