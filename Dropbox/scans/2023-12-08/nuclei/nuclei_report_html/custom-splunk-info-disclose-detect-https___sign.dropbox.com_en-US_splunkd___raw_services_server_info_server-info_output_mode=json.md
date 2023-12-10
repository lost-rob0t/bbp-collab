### Custom Splunk Info Disclosure (custom-splunk-info-disclose-detect) found on https://sign.dropbox.com

----
**Details**: **custom-splunk-info-disclose-detect** matched at https://sign.dropbox.com

**Protocol**: HTTP

**Full URL**: https://sign.dropbox.com/en-US/splunkd/__raw/services/server/info/server-info?output_mode=json

**Timestamp**: Sat Dec 9 10:20:18 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Custom Splunk Info Disclosure |
| Authors | pdteam |
| Tags | config, exposure |
| Severity | medium |

**Request**
```http
GET /en-US/splunkd/__raw/services/server/info/server-info?output_mode=json HTTP/1.1
Host: sign.dropbox.com
User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/34.0.1847.137 Safari/4E423F
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
Date: Sat, 09 Dec 2023 10:20:18 GMT
Etag: W/"f7c8a005000c9978cc2be432d0fede57"
Last-Modified: Thu, 07 Dec 2023 19:31:41 GMT
Vary: Accept-Encoding
Via: 1.1 e193dc7153d24abe4297798fbf91a678.cloudfront.net (CloudFront)
X-Amz-Cf-Id: naPOVE2XlDZQ-hUCyW8th41M-6wBb7Nyx02vTk03t1YcFfZ17GfakQ==
X-Amz-Cf-Pop: MRS52-C2
X-Cache: Error from cloudfront
X-Cache-Hits: 0, 0
X-Cluster-Name: eu-west-1-prod-hosting-red
X-Frame-Options: SAMEORIGIN
X-Served-By: cache-iad-kiad7000087-IAD, cache-dub4337-DUB
X-Timer: S1702117219.695822,VS0,VE197

<!DOCTYPE html><!-- Last Published: Thu Dec 07 2023 19:29:24 GMT+0000 (Coordinated Universal Time) --><html data-wf-domain="www.dropboxsign.com" data-wf-page="649a06c9b3d68c4dc56bb2a5" data-wf-site="64412cfef2e5476af2f044bd" lang="en"><head><meta charset="utf-8"/><title>Not Found</title><meta content="Not Found" property="og:title"/><meta content="Not Found" property="twitter:title"/><meta content="width=device-width, initial-scale=1" name="viewport"/><link href="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/css/dropbox-sign.ac62ad978.css" rel="stylesheet" type="text/css"/><script type="text/javascript">!function(o,c){var n=c.documentElement,t=" w-mod-";n.className+=t+"js",("ontouchstart"in o||o.DocumentTouch&&c instanceof DocumentTouch)&&(n.className+=t+"touch")}(window,document);</script><link href="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/6441320af2e547320ef091a6_favicon.png" rel="shortcut icon" type="image/x-icon"/><link href="https://assets-global.website-files.com/64412cfef2e5476af2f044bd/6441320df020d65e5a8250be_webclip.png" rel="apple-touch-icon"/><!-- Marketo Forms -->
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


<link rel="preload" href="https://mar-cdn.hellosign.com/ls/main.7f51e88ecd1550aa45cf.css" as="style" onload="this.onload=null;this.rel='stylesheet'"></head><body><div class="global-styles w-embed"><style>

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
.w-richtext > :not(div):first-child, .w-richtext > div:first-child > :first-child {
  margin-top: 0 !important;
}

/* Get rid of bottom margin on last element in any rich text element */
.w-richtext>:last-child, .w-richtext ol li:last-child, .w-richtext ul li:last-child {
	margin-bottom: 0 !important;
}

/* Prevent all click and hover interaction with an element */
.pointer-events-off {
	pointer-events: none;
}

/* Enables all click and hover interaction with an element */
.pointer-events-on {
  pointer-events: auto;
}

/* Create a class of .div-square which maintains a 1:1 dimension of a div */
.div-square::after {
	content: "";
	display: block;
	padding-bottom: 100%;
}

/* Make sure containers never lose their center alignment */
.container-medium,.container-small, .container-large {
	margin-right: auto !important;
  margin-left: auto !important;
}

/* 
Make the following elements inherit typography styles from the parent and not have hardcoded values. 
Important: You will not be able to style for example "All Links" in Designer with this CSS applied.
Uncomment this CSS to use it in the project. Leave this message for future hand-off.
*/

a,
.w-input,
.w-select,
.w-tab-link,
.w-nav-link,
.w-dropdown-btn,
.w-dropdown-toggle,
.w-dropdown-link {
  color: inherit;
  text-decoration: inherit;
  font-size: inherit;
}


/* Apply "..." after 3 lines of text */
.text-style-3lines {
	display: -webkit-box;
	overflow: hidden;
	-webkit-line-clamp: 3;
	-webki.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/34.0.1847.137 Safari/4E423F' 'https://sign.dropbox.com/en-US/splunkd/__raw/services/server/info/server-info?output_mode=json'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)