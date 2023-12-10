### credentials-disclosure-all (credentials-disclosure-all) found on https://sign-staging.dropbox.com

----
**Details**: **credentials-disclosure-all** matched at https://sign-staging.dropbox.com

**Protocol**: HTTP

**Full URL**: https://sign-staging.dropbox.com

**Timestamp**: Sat Dec 9 00:01:33 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | credentials-disclosure-all |
| Authors | w9w |
| Tags |  |
| Severity | medium |
| Description | Matching patterns in the body. |

**Request**
```http
GET / HTTP/1.1
Host: sign-staging.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2224.3 Safari/537.36
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
Age: 55895
Content-Security-Policy: frame-ancestors 'self' https://*.webflow.com http://*.webflow.com http://*.webflow.io http://webflow.com https://webflow.com
Content-Type: text/html
Date: Sat, 09 Dec 2023 00:01:32 GMT
Vary: Accept-Encoding
Via: 1.1 5107abe805c079f90ed2ab4c60ef887a.cloudfront.net (CloudFront)
X-Amz-Cf-Id: fSzClhUBIe90f433iphvKxUIZpiQbIa1EE2DSGlFa-1ToqFYbYm0pQ==
X-Amz-Cf-Pop: MRS52-P2
X-Cache: Miss from cloudfront
X-Cache-Hits: 1
X-Frame-Options: SAMEORIGIN
X-Lambda-Id: bd8c5765-d097-4942-bd2e-0e529e00b35c
X-Served-By: cache-mrs10522-MRS
X-Timer: S1702080093.650747,VS0,VE1

<!DOCTYPE html><!-- Last Published: Fri Dec 08 2023 00:45:45 GMT+0000 (Coordinated Universal Time) --><html data-wf-domain="dropbox-sign.webflow.io" data-wf-page="649a06c9b3d68c4dc56bb270" data-wf-site="64412cfef2e5476af2f044bd" lang="en"><head><meta charset="utf-8"/><title>Dropbox Sign eSignature Agreements — Work Smarter</title><meta content="Dropbox Sign (formerly HelloSign) is the easiest way to send, receive and manage legally binding electronic signatures. Try it free!" name="description"/><meta content="Dropbox Sign eSignature Agreements — Work Smarter" property="og:title"/><meta content="Dropbox Sign (formerly HelloSign) is the easiest way to send, receive and manage legally binding electronic signatures. Try it free!" property="og:description"/><meta content="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/648a230bf374dfde400bf582_Container2.png" property="og:image"/><meta content="Dropbox Sign eSignature Agreements — Work Smarter" property="twitter:title"/><meta content="Dropbox Sign (formerly HelloSign) is the easiest way to send, receive and manage legally binding electronic signatures. Try it free!" property="twitter:description"/><meta content="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/648a230bf374dfde400bf582_Container2.png" property="twitter:image"/><meta property="og:type" content="website"/><meta content="summary_large_image" name="twitter:card"/><meta content="width=device-width, initial-scale=1" name="viewport"/><link href="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/css/dropbox-sign.ac62ad978.css" rel="stylesheet" type="text/css"/><script type="text/javascript">!function(o,c){var n=c.documentElement,t=" w-mod-";n.className+=t+"js",("ontouchstart"in o||o.DocumentTouch&&c instanceof DocumentTouch)&&(n.className+=t+"touch")}(window,document);</script><link href="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/6441320af2e547320ef091a6_favicon.png" rel="shortcut icon" type="image/x-icon"/><link href="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/6441320df020d65e5a8250be_webclip.png" rel="apple-touch-icon"/><!-- Marketo Forms -->
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


<link rel="preload" href="https://mar-cdn.hellosign.com/ls/main.7f51e88ecd1550aa45cf.css" as="style" onload="this.onload=null;this.rel='stylesheet'"><!-- Canonical -->
<link rel="canonical" href="https://sign.dropbox.com"/>

<!-- Hreflangs -->
<link rel="alternate" hreflang="en" href="https://sign.dropbox.com/"/>
<link rel="alternate" hreflang="da-dk" href="https://sign.dropbox.com/da-DK/"/>
<link rel="alternate" hreflang="de-de" href="https://sign.dropbox.com/de-DE/"/>
<link rel="alternate" hreflang="en-gb" href="https://sign.dropbox.com/en-GB/"/>
<link rel="alternate" hreflang="fr-fr" href="https://sign.dropbox.com/fr-FR/"/>
<link rel="alternate" hreflang="nb-no" href="https://sign.dropbox.com/nb-NO/"/>
<link rel="alternate" hreflang="sv-se" href="https://sign.dropbox.com/sv-SE/"/>
<link rel="alternate" hreflang="es-la" href="https://sign.dropbox.com/es-LA/"/>
<link rel="alternate" hreflang="es-es" href="https://sign.dropbox.com/es-ES/"/>
<link rel="alternate" hreflang="id-id" href="https://sign.dropbox.com/id-ID/"/>
<link rel="alternate" hreflang="it-it" href="https://sign.dropbox.com/it-IT/"/>
<link rel="alternate" hreflang="ja-jp" href="https://sign.dropbox.com/ja-JP/"/>
<link rel="alternate" hreflang="ko-kr" href="https://sign.dropbox.com/ko-KR/"/>
<link rel="alternate" .... Truncated ....
```

**Extra Information**

**Extracted results:**

- api_link_click



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2224.3 Safari/537.36' 'https://sign-staging.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)