### HTTP Missing Security Headers (http-missing-security-headers:access-control-max-age) found on https://spa.hellosign.com

----
**Details**: **http-missing-security-headers:access-control-max-age** matched at https://spa.hellosign.com

**Protocol**: HTTP

**Full URL**: https://sign.dropbox.com:443/es-ES/

**Timestamp**: Sat Dec 9 14:55:58 +0000 UTC 2023

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
Host: spa.hellosign.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2227.1 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Transfer-Encoding: chunked
Age: 24953
Content-Security-Policy: frame-ancestors 'self'
Content-Type: text/html
Date: Sat, 09 Dec 2023 14:55:57 GMT
Vary: Accept-Encoding,Accept-Encoding
Via: 1.1 979084a90b32fe3f5fdc377fb6e67b76.cloudfront.net (CloudFront), 1.1 8e72609f76eedcc790a085684fec9340.cloudfront.net (CloudFront)
X-Amz-Cf-Id: 2_wLvHCXzvlPgn69nbryBtKRAiAjFc3MUzch50Pt7uszy2C7kZTVXw==
X-Amz-Cf-Pop: IAD89-P1
X-Amz-Cf-Pop: MRS52-C2
X-Cache: Miss from cloudfront
X-Cache-Hits: 60
X-Cluster-Name: us-east-1-prod-hosting-red
X-Frame-Options: SAMEORIGIN
X-Lambda-Id: 1069dfb0-7ec0-4c05-8668-eb5f06b4c9a4
X-Served-By: cache-iad-kjyo7100115-IAD
X-Server: Smartling
X-Sl-Norewrite: 1
X-Sl-Notranslate: 1
X-Timer: S1702133758.878541,VS0,VE0

<!DOCTYPE html><!-- Last Published: Thu Dec 07 2023 19:29:24 GMT+0000 (Coordinated Universal Time) --><html data-wf-domain="www.dropboxsign.com" data-wf-page="649a06c9b3d68c4dc56bb270" data-wf-site="64412cfef2e5476af2f044bd" lang="es-ES"><head><meta charset="UTF-8" /><title>Acuerdos de firma electrónica de Dropbox Sign — Trabaja mejor</title><meta content="Dropbox Sign (anteriormente HelloSign) es la forma más sencilla de enviar, recibir y gestionar firmas electrónicas legalmente vinculantes. Puedes probarlo gratis." name="description" /><meta content="Acuerdos de firma electrónica de Dropbox Sign — Trabaja mejor" property="og:title" /><meta content="Dropbox Sign (anteriormente HelloSign) es la forma más sencilla de enviar, recibir y gestionar firmas electrónicas legalmente vinculantes. Puedes probarlo gratis." property="og:description" /><meta content="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/648a230bf374dfde400bf582_Container2.png" property="og:image" /><meta content="Dropbox Sign eSignature Agreements — Work Smarter" property="twitter:title" /><meta content="Dropbox Sign (formerly HelloSign) is the easiest way to send, receive and manage legally binding electronic signatures. Try it free!" property="twitter:description" /><meta content="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/648a230bf374dfde400bf582_Container2.png" property="twitter:image" /><meta property="og:type" content="website" /><meta content="summary_large_image" name="twitter:card" /><meta content="width=device-width, initial-scale=1" name="viewport" /><link href="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/css/dropbox-sign.ac62ad978.css" rel="stylesheet" type="text/css" /><script type="text/javascript">!function(o,c){var n=c.documentElement,t=" w-mod-";n.className+=t+"js",("ontouchstart"in o||o.DocumentTouch&&c instanceof DocumentTouch)&&(n.className+=t+"touch")}(window,document);</script><link href="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/6441320af2e547320ef091a6_favicon.png" rel="shortcut icon" type="image/x-icon" /><link href="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/6441320df020d65e5a8250be_webclip.png" rel="apple-touch-icon" /><!-- Marketo Forms -->
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
<script src="https://www.dropbox.com/pithos/ux_analytics,top_frame_marketing_tracker" async=""></script>

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


<link rel="preload" href="https://mar-cdn.hellosign.com/ls/main.7f51e88ecd1550aa45cf.css" as="style" onload="this.onload=null;this.rel='stylesheet'" /><!-- Canonical -->
<link rel="canonical" href="https://sign.dropbox.com/es-ES" />

<!-- Hreflangs -->
<link rel="alternate" hreflang="en" href="https://sign.dropbox.com/" />
<link rel="alternate" hreflang="da-dk" href="https://sign.dropbox.com/da-DK/" />
<link rel="alternate" hreflang="de-de" href="https://sign.dropbox.com/de-DE/" />
<link rel="alternate" hreflang="en-gb" href="https://sign.dropbox.com/en-GB/" />
<link rel="alternate" hreflang="fr-fr" href="https://sign.dropbox.com/fr-FR/" />
<link rel="alternate" hreflang="nb-no" href="https://sign.dropbox.com/nb-NO/" />
<link rel="alternate" hreflang="sv-se" href="https://sign.dropbox.com/sv-SE/" />
<link rel="alternate" hreflang="es-la" href="https://sign.dropbox.com/es-LA/" />
<link rel="alternate" hreflang="es-es" href="https://sign.dropbox.com/es-ES/" />
<link rel="alternate" hreflang="id-id" href="https://sign.dropbox.com/id-ID/" />
<link rel="alt.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2227.1 Safari/537.36' 'https://spa.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)