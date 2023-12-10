### DOM EventListener detection (addeventlistener-detect) found on https://learn.hellosign.com

----
**Details**: **addeventlistener-detect** matched at https://learn.hellosign.com

**Protocol**: HTTP

**Full URL**: https://learn.hellosign.com

**Timestamp**: Sat Dec 9 00:01:11 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | DOM EventListener detection |
| Authors | yavolo, dwisiswant0 |
| Tags | xss, misc |
| Severity | info |

**Request**
```http
GET / HTTP/1.1
Host: learn.hellosign.com
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
Cache-Control: no-cache, no-store, must-revalidate, private
Content-Language: en
Content-Security-Policy: frame-ancestors 'self'
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 00:01:10 GMT
Expires: Sat, 09 Dec 2023 00:01:10 GMT
P3p: CP="This is not a P3P policy!"
Pragma: no-cache
Server: gunicorn
Strict-Transport-Security: max-age=31536000; includeSubDomains
Vary: Accept-Encoding, Cookie
Via: 1.1 b36c56308a153045449f75b4b54bd908.cloudfront.net (CloudFront)
X-Amz-Cf-Id: SS8UoCpycvHocbdufH0wNeApaiDZauNjaTbcXnB3xLKetuT86US-kA==
X-Amz-Cf-Pop: MRS52-P5
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Ua-Compatible: IE=edge
X-Xss-Protection: 1

<!DOCTYPE html>











<!--[if IE 8]> <html class="no-js lt-ie9" lang="en-US" > <![endif]-->
<!--[if gt IE 8]><!-->
<html class="no-js" lang="en-US">
<!--<![endif]-->
<head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# skilljar: http://ogp.me/ns/fb/skilljar#" >
    
    
        
    

    <meta charset="utf-8"/>

    
        <link rel="search" type="application/opensearchdescription+xml" href="/domain/open-search" title="Skilljar">
    
    
        <link rel="shortcut icon" href="https://cc.sj-cdn.net/instructor/35mddemoc9wcl-hellosign/themes/3j0xkfgk7tvlr/favicon.1666702206.png"/>
    

    
    
        <link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800" rel="stylesheet">
    
    <meta name="viewport" id="viewport" content="width=device-width, initial-scale=1.0"/>
    
        <meta name="global-title" content="Dropbox Sign Learn"/>
    
    
    
    






    <meta property="og:title" content="Dropbox Sign Learn"/>
    <meta name="twitter:title" content="Dropbox Sign Learn"/>











    <meta property="og:image" content="https://cc.sj-cdn.net/instructor/35mddemoc9wcl-hellosign/catalog_page/p3atnmjsmxy1/tile-image.1654190718.png"/>
    <meta name="twitter:image" content="https://cc.sj-cdn.net/instructor/35mddemoc9wcl-hellosign/catalog_page/p3atnmjsmxy1/tile-image.1654190718.png"/>














<meta property="fb:app_id" content="571325372910940"/>


    <meta property="og:url" content="https://learn.hellosign.com/"/>



    <meta property="og:type" content="website"/>



    <meta property="og:site_name" content="HelloSign"/>





<meta name="twitter:card" content="summary_large_image"/>
<meta name="twitter:site" content="@skilljar"/>



    <title>Dropbox Sign Learn</title>

    
    
        
        
            <link rel="stylesheet" href="/static/css/sj_course_platform_v2.a9d3db617bd0.css"/>
        
        
        <link href="/static/js/vendor/prism/prism.47d40f251583.css" rel="stylesheet"/>
    

    
    
        
            
            <link rel="stylesheet" href="https://learn.hellosign.com/theme/3j0xkfgk7tvlr.css?v=4&amp;theme_version=2"/>
        
    

    
    

    
    

    <script>
        window.SKILLJAR_DASHBOARD_GLOBALS = {
            TIME_ZONE: 'America/Los_Angeles',
        };

    </script>

    
    <script>
        
        window.renderElement = function(tagName, attributes, children) {
            var elem = document.createElement(tagName);
            if (attributes) {
              Object.keys(attributes).forEach(function (attributeKey) {
                elem[attributeKey] = attributes[attributeKey];
              });
            }

            if (children) {
              children
                .filter(function(child) {
                  return !!child;
                })
                .forEach(function(child) {
                  elem.appendChild(child);
                });
            }

            return elem;
        }
    </script>

    
        
        <script src="/static/js/modernizr.min.9e840c2ca12e.js"></script>
    

    
    
        <script src="/static/js/jquery.min.8c8a019607b8.js"></script>
    

    <script src="/static/js/jquery.min.8c8a019607b8.js"></script>
    <script src="/static/js/vendor/prism/prism.d722a89f1d58.js"></script>
    <script src="/static/js/sanitize-html.0c819ce64fd6.js"></script>

    
        
            <script>
                console.sentryCaptureException = function() {};
                console.sentryCaptureMessage = function() {};
            </script>
        
    

    
        
            




<script>
(function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
})(window,document,'script','//www.google-analytics.com/analytics.js','ga');


    ga('create', {
        trackingId: 'UA\u002D40340039\u002D1',
        cookieDomain: 'auto',
        name: 'skilljarTracker',
        
        
    });



    
        ga('skilljarTracker.set', 'dimension1', 'false');
    
    
    ga('skilljarTracker.set', 'anonymizeIp', true);
    ga('skilljarTracker.send', 'pageview');

</script>




<!-- Google tag (gtag.js) -->

    <.... Truncated ....
```

References: 
- https://portswigger.net/web-security/dom-based/controlling-the-web-message-source

**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/55.0.2919.83 Safari/537.36' 'https://learn.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)