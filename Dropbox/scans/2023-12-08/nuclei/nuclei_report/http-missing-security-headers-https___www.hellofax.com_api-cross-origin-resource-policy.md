### HTTP Missing Security Headers (http-missing-security-headers:cross-origin-resource-policy) found on https://api.hellofax.com

----
**Details**: **http-missing-security-headers:cross-origin-resource-policy** matched at https://api.hellofax.com

**Protocol**: HTTP

**Full URL**: https://www.hellofax.com/api

**Timestamp**: Sat Dec 9 14:54:33 +0000 UTC 2023

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
Host: api.hellofax.com
User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/55.0.2919.83 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 404 Not Found
Connection: close
Transfer-Encoding: chunked
Accept-Ranges: bytes
Cache-Control: private, max-age=0, must-revalidate
Content-Security-Policy: frame-ancestors 'self'
Content-Type: text/html
Date: Sat, 09 Dec 2023 14:54:33 GMT
Etag: W/"3bef04ab735286c62d1867c79140c349"
Last-Modified: Thu, 07 Dec 2023 19:30:22 GMT
Strict-Transport-Security: max-age=31536000; includeSubDomains
Vary: Accept-Encoding,x-wf-forwarded-proto
X-Cache: MISS, MISS
X-Cache-Hits: 0, 0
X-Cluster-Name: eu-west-1-prod-hosting-red
X-Frame-Options: SAMEORIGIN
X-Served-By: cache-iad-kjyo7100138-IAD, cache-dub4352-DUB
X-Timer: S1702133673.335883,VS0,VE146

<!DOCTYPE html><!-- This site was created in Webflow. https://www.webflow.com --><!-- Last Published: Thu Dec 07 2023 19:30:20 GMT+0000 (Coordinated Universal Time) --><html data-wf-domain="www.hellofax.com" data-wf-page="5e3b56847961de2e59d20717" data-wf-site="5d8276a79ed2c0d135ef444b"><head><meta charset="utf-8"/><title>Not Found</title><meta content="Not Found" property="og:title"/><meta content="Not Found" property="twitter:title"/><meta content="width=device-width, initial-scale=1" name="viewport"/><meta content="Webflow" name="generator"/><link href="https://assets-global.website-files.com/5d8276a79ed2c0d135ef444b/css/hellofax.webflow.38f162f77.min.css" rel="stylesheet" type="text/css"/><script src="https://use.typekit.net/vph1lkb.js" type="text/javascript"></script><script type="text/javascript">try{Typekit.load();}catch(e){}</script><script type="text/javascript">!function(o,c){var n=c.documentElement,t=" w-mod-";n.className+=t+"js",("ontouchstart"in o||o.DocumentTouch&&c instanceof DocumentTouch)&&(n.className+=t+"touch")}(window,document);</script><link href="https://assets-global.website-files.com/5d8276a79ed2c0d135ef444b/6357f2da07bc101f411020d8_dbx-fax-favicon.ico" rel="shortcut icon" type="image/x-icon"/><link href="https://assets-global.website-files.com/5d8276a79ed2c0d135ef444b/6357f2e1e465945a10d34d5a_dbx-fax-webclip.png" rel="apple-touch-icon"/><link href="https://app.hellosign.com/images/webflow/hellofax-fav.ico" rel="shortcut icon" type="image/x-icon">
<link href="https://app.hellosign.com/images/webflow/hellfoax-webclip.png" rel="apple-touch-icon">

<style>

._404-image {
filter: hue-rotate(200deg)
}
  * {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
  
/* resize fat nav on smaller desktop screen*/
@media (max-width: 1215px) and (min-width: 991px) {
	.fn-dropdown-list.products.w--open, .fn-dropdown-list.solutions.w--open {
    max-width: none;
    width: 95.5vw;
  }
  .fn-dropdown-list.products.w--open {
  	margin-left: -166px;
  }
 .fn-dropdown-list.solutions.w--open { 
    margin-left: -310px;
}
  .fn-dropdown-col {
  	width: 100%;
  }
 }

 .w-nav-overlay {
 	z-index: 2!important;
 }

 @media (min-width: 992px) {
      .fn-overlay.fn-overlay-show {
      display: block;
      opacity: 1;
      }
    }
    @media (max-width: 991px) {
      .fn-overlay.fn-overlay-show {
        display: none;
      }
    }
    
 .fn-nav-menu {
   -webkit-overflow-scrolling: touch;
   }
 
 @media screen and (max-width: 991px) {
.fn-dropdown-col.last {
    border-bottom-width: 0;
}
}
/*
@media (max-width: 1175px) and (min-width: 991px) {
  .menu-dropdown-toggle {
    padding: 22px 5px 15px;
  }
 }
  
@media (max-width: 1100px) and (min-width: 991px) {  
  .nav-link-solutions {
    display: none;
  }
 }
 @media (max-width: 1000px) and (min-width: 991px) {  
  .cta-primary .primary-menu .less-padding {
    width: 118px;
    font-size: 13px;
  }
 }
 */
</style>

<!-- Google Tag Manager -->
<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-PVPHMZ');</script>
<!-- End Google Tag Manager --></head><body><div class="fn-component-master"><div data-collapse="medium" data-animation="default" data-duration="400" data-doc-height="1" data-easing="ease" data-easing2="ease" role="banner" class="fn-component w-nav"><div class="fn-login-bar"><div class="fn-content-max login-flip"><a href="/blog/a-letter-from-our-ceo-were-joining-dropbox" class="fn-login-bar-message w-inline-block"><div>We&#x27;re joining Dropbox! <span class="semibold">Learn More</span></div></a><div data-delay="0" data-hover="false" class="fn-login-dropdown fn-dropdown-listen w-dropdown"><div class="fn-login-toggle w-dropdown-toggle"><div class="fn-login-toggle-text">Log In</div><img src="https://assets-global.website-files.com/58065afcec27c89278ba59f7/5cf95d8222a3cb128337f0e2_fn-dropdown-arrow.svg" alt="" class="fn-dropdown-arrow"/></div><nav class="fn-login-list fn-dropdown-list w-dropdown-list"><a da-action="hellosign" da-category="login" href="https://app.hellosign.com/account/logIn" class="fn-login-dropdown-link w-inline-block"><div class="text-block">HelloSign</div></a><a da-action="helloworks".... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/55.0.2919.83 Safari/537.36' 'https://api.hellofax.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)