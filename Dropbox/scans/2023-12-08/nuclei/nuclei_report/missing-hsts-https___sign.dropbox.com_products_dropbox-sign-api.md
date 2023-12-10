### Strict Transport Security Not Enforced (missing-hsts) found on https://api.hellosign.com

----
**Details**: **missing-hsts** matched at https://api.hellosign.com

**Protocol**: HTTP

**Full URL**: https://sign.dropbox.com/products/dropbox-sign-api

**Timestamp**: Sat Dec 9 08:23:09 +0000 UTC 2023

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
Host: api.hellosign.com
User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36
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
Age: 1374
Content-Security-Policy: frame-ancestors 'self'
Content-Type: text/html
Date: Sat, 09 Dec 2023 08:23:08 GMT
Vary: Accept-Encoding
Via: 1.1 ab98259c2b5c7fba2ccac74c507f520c.cloudfront.net (CloudFront)
X-Amz-Cf-Id: LF7rqlr_94ir_BCcM-73qF5VtwypxSE5z3zuaahqlQ0TrQjtFUU0kA==
X-Amz-Cf-Pop: MRS52-C2
X-Cache: Miss from cloudfront
X-Cache-Hits: 1, 1
X-Cluster-Name: eu-west-1-prod-hosting-red
X-Frame-Options: SAMEORIGIN
X-Lambda-Id: e90539c4-db94-4cc2-b38e-85f0b941b157
X-Served-By: cache-iad-kjyo7100129-IAD, cache-dub4348-DUB
X-Timer: S1702110189.935084,VS0,VE1

<!DOCTYPE html><!-- Last Published: Thu Dec 07 2023 19:29:24 GMT+0000 (Coordinated Universal Time) --><html data-wf-domain="www.dropboxsign.com" data-wf-page="649a06c9b3d68c4dc56bb34f" data-wf-site="64412cfef2e5476af2f044bd" lang="en"><head><meta charset="utf-8"/><title>eSignature API from Dropbox Sign (Formerly HelloSign)</title><meta content="Dropbox Sign&#x27;s eSignature API gives you a Quickstart Guide, SDKs, and super clean documentation to get you up and signing in no time. SOC2 and HIPAA compliant esignatures." name="description"/><meta content="eSignature API from Dropbox Sign (Formerly HelloSign)" property="og:title"/><meta content="Dropbox Sign&#x27;s eSignature API gives you a Quickstart Guide, SDKs, and super clean documentation to get you up and signing in no time. SOC2 and HIPAA compliant esignatures." property="og:description"/><meta content="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/65654a0f0106669b38b4b3b9_Screenshot%202023-11-27%20at%205.59.04%E2%80%AFPM.png" property="og:image"/><meta content="eSignature API from Dropbox Sign (Formerly HelloSign)" property="twitter:title"/><meta content="Dropbox Sign&#x27;s eSignature API gives you a Quickstart Guide, SDKs, and super clean documentation to get you up and signing in no time. SOC2 and HIPAA compliant esignatures." property="twitter:description"/><meta content="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/65654a0f0106669b38b4b3b9_Screenshot%202023-11-27%20at%205.59.04%E2%80%AFPM.png" property="twitter:image"/><meta property="og:type" content="website"/><meta content="summary_large_image" name="twitter:card"/><meta content="width=device-width, initial-scale=1" name="viewport"/><link href="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/css/dropbox-sign.ac62ad978.css" rel="stylesheet" type="text/css"/><script type="text/javascript">!function(o,c){var n=c.documentElement,t=" w-mod-";n.className+=t+"js",("ontouchstart"in o||o.DocumentTouch&&c instanceof DocumentTouch)&&(n.className+=t+"touch")}(window,document);</script><link href="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/6441320af2e547320ef091a6_favicon.png" rel="shortcut icon" type="image/x-icon"/><link href="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/6441320df020d65e5a8250be_webclip.png" rel="apple-touch-icon"/><!-- Marketo Forms -->
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
<link rel="canonical" href="https://sign.dropbox.com/products/dropbox-sign-api"/>

<!-- Hreflangs -->
<link rel="alternate" hreflang="en" href="https://sign.dropbox.com/products/dropbox-sign-api"/>
<link rel="alternate" hreflang="da-dk" href="https://sign.dropbox.com/da-DK/products/dropbox-sign-api"/>
<link rel="alternate" hreflang="de-de" href="https://sign.dropbox.com/de-DE/products/dropbox-sign-api"/>
<link rel="alternate" hreflang="en-gb" href="https://sign.dropbox.com/en-GB/products/dropbox-sign-api"/>
<link rel="alternate" hreflang="fr-fr" href="https://sign.dropbox.com/fr-FR/products/dropbox-sign-api"/>
<link rel="alternate" hreflang="nb-no" href="https://sign.dropbox.com/nb-NO/products/dropbox-sign-api"/>
<link rel="alternate" hreflang="sv-se" href="https://sign.dropbox.com/sv-SE/products/dropbox-sign-api"/>
<link rel="alternate" hreflang="es-la" href="https://sign.dropbox.com/es-LA/products/dropbox-sign-api"/>
<link rel="alt.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36' 'https://api.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)