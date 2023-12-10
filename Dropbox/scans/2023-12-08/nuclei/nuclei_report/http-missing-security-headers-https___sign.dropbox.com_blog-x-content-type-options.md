### HTTP Missing Security Headers (http-missing-security-headers:x-content-type-options) found on https://www.blog.hellosign.com

----
**Details**: **http-missing-security-headers:x-content-type-options** matched at https://www.blog.hellosign.com

**Protocol**: HTTP

**Full URL**: https://sign.dropbox.com/blog

**Timestamp**: Sat Dec 9 14:56:14 +0000 UTC 2023

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
Host: www.blog.hellosign.com
User-Agent: Mozilla/5.0 (Windows NT 6.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2228.0 Safari/537.36
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
Age: 24964
Content-Security-Policy: frame-ancestors 'self'
Content-Type: text/html
Date: Sat, 09 Dec 2023 14:56:14 GMT
Vary: Accept-Encoding
Via: 1.1 3e2d48e2701d85ed2900b5e1e8df2e24.cloudfront.net (CloudFront)
X-Amz-Cf-Id: DTUicr74AkBZbS5pnh8PMKf5iGj62-YgD_vdSPDSBTDtmnHfkAyirw==
X-Amz-Cf-Pop: MRS52-C2
X-Cache: Miss from cloudfront
X-Cache-Hits: 0, 44
X-Cluster-Name: eu-west-1-prod-hosting-red
X-Frame-Options: SAMEORIGIN
X-Lambda-Id: 088b0194-55a9-427f-a114-0ba5b2109e5b
X-Served-By: cache-iad-kcgs7200120-IAD, cache-dub4350-DUB
X-Timer: S1702133774.056508,VS0,VE0

<!DOCTYPE html><!-- Last Published: Thu Dec 07 2023 19:29:24 GMT+0000 (Coordinated Universal Time) --><html data-wf-domain="www.dropboxsign.com" data-wf-page="649a06c9b3d68c4dc56bb2ae" data-wf-site="64412cfef2e5476af2f044bd" lang="en"><head><meta charset="utf-8"/><title>Home - Dropbox Sign Blog</title><meta content="A Dropbox Sign blog about eSignature fundamentals, workflow management, HR and Sales tips, product news, and developer content." name="description"/><meta content="Home - Dropbox Sign Blog" property="og:title"/><meta content="A Dropbox Sign blog about eSignature fundamentals, workflow management, HR and Sales tips, product news, and developer content." property="og:description"/><meta content="https://assets-global.website-files.com/6446df33610093270e7fb677/6488525492750615c6e86487_647933635c48893bd960ac8d_IMG_2979.jpeg" property="og:image"/><meta content="Home - Dropbox Sign Blog" property="twitter:title"/><meta content="A Dropbox Sign blog about eSignature fundamentals, workflow management, HR and Sales tips, product news, and developer content." property="twitter:description"/><meta content="https://assets-global.website-files.com/6446df33610093270e7fb677/6488525492750615c6e86487_647933635c48893bd960ac8d_IMG_2979.jpeg" property="twitter:image"/><meta property="og:type" content="website"/><meta content="summary_large_image" name="twitter:card"/><meta content="width=device-width, initial-scale=1" name="viewport"/><link href="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/css/dropbox-sign.ac62ad978.css" rel="stylesheet" type="text/css"/><script type="text/javascript">!function(o,c){var n=c.documentElement,t=" w-mod-";n.className+=t+"js",("ontouchstart"in o||o.DocumentTouch&&c instanceof DocumentTouch)&&(n.className+=t+"touch")}(window,document);</script><link href="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/6441320af2e547320ef091a6_favicon.png" rel="shortcut icon" type="image/x-icon"/><link href="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/6441320df020d65e5a8250be_webclip.png" rel="apple-touch-icon"/><!-- Marketo Forms -->
<script src="//lp.dropboxbusiness.com/js/forms2/js/forms2.min.js"></script>
<!-- End Marketo Forms -->

<!-- Automatically append - Dropbox to every meta title -->
<script>
  document.addEventListener("DOMContentLoaded", function() {
    var metaTitle = document.querySelector("title");
    metaTitle.innerHTML = metaTitle.innerHTML + " - Dropbox";
  });
</script>

<!-- uxa script -->
<script src="https://www.dropbox.com/pithos/ux_analytics,top_frame_marketing_tracker" async></script>

<!-- Tealium (MKT-1453) -->
<script type="text/javascript">
  (function (a, b, c, d) {
    a = `https://tags.tiqcdn.com/utag/dropbox/hellosign/${
      window.location.hostname === "sign.dropbox.com" ? "prod" : "dev"
    }/utag.js`;
    b = document;
    c = "script";
    d = b.createElement(c);
    d.src = a;
    d.type = "text/java" + c;
    d.async = true;
    a = b.getElementsByTagName(c)[0];
    a.parentNode.insertBefore(d, a);
  })();
</script>
<!-- End Tealium -->


<link rel="preload" href="https://mar-cdn.hellosign.com/ls/main.7f51e88ecd1550aa45cf.css" as="style" onload="this.onload=null;this.rel='stylesheet'"><!-- [Attributes by Finsweet] CMS Filter -->
<script async src="https://cdn.jsdelivr.net/npm/@finsweet/attributes-cmsfilter@1/cmsfilter.js"></script>

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [{
    "@type": "ListItem",
      "position": 1,
      "name": "Dropbox Sign",
      "item": "http://sign.dropbox.com/"
    },{
    "@type": "ListItem",
      "position": 2,
      "name": "Blog",
      "item": "/blog"
  }]      
}
</script></head><body><div class="page-wrapper"><div class="global-styles w-embed"><style>

/* Make text look crisper and more legible in all browsers */
body {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-smoothing: antialiased;
  text-rendering: optimizeLegibility;
}

/* Focus state style for keyboard navigation for the focusable elements */
*[tabindex]:focus-visible,
  input[type="file"]:focus-visible {
   outline: 0.125rem solid #4d65ff;
   /*outline-offset: 0.125rem;*/
}

/*a:-webkit-any-link:focus-visible {
    outline: 0.125rem solid #4d65ff;
}*/

/* Get rid of top margin on first element in any rich text element */
.w-richtext > :not(div):first-child, .w-richtext > d.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2228.0 Safari/537.36' 'https://www.blog.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)