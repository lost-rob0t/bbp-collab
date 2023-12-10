### HTTP Missing Security Headers (http-missing-security-headers:access-control-max-age) found on https://docs.helloworks.com

----
**Details**: **http-missing-security-headers:access-control-max-age** matched at https://docs.helloworks.com

**Protocol**: HTTP

**Full URL**: https://docs.helloworks.com/reference/getting-started

**Timestamp**: Sat Dec 9 14:55:00 +0000 UTC 2023

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
Host: docs.helloworks.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_8_4) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/49.0.2656.18 Safari/537.36
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
Age: 896
Alt-Svc: h3=":443"; ma=86400
Cache-Control: s-maxage=900
Cf-Cache-Status: HIT
Cf-Ray: 832e162eaced0159-CDG
Content-Language: en
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 14:55:00 GMT
Render-Cf-Cache: private, max-age=0, no-transform
Rndr-Id: a5066bd2-44ad-48f6
Server: cloudflare
Strict-Transport-Security: max-age=31536000
Vary: Accept-Encoding
X-Content-Type-Options: nosniff
X-Dns-Prefetch-Control: off
X-Download-Options: noopen
X-Frame-Options: Deny
X-Render-Origin-Server: Render
X-Xss-Protection: 1; mode=block

<!DOCTYPE html><html lang="en" style="" data-color-mode="light" class=" useReactApp isRefPage "><head><script src="https://cdn.readme.io/public/js/force-firefox-anchor-jump.js?1702068049020"></script><meta charset="utf-8"><meta http-equiv="X-UA-Compatible" content="IE=edge"><meta name="readme-deploy" content="4.549.0"><meta name="readme-subdomain" content="helloworks"><meta name="readme-version" content="3.3"><title ng-bind="pageTitle">Getting Started</title><meta name="description" property="og:description" content="This page will help you get started with Dropbox Forms API."><meta name="viewport" content="width=device-width, initial-scale=1.0"><meta name="twitter:card" content="summary_large_image"><meta name="title" property="og:title" content="Getting Started"><meta property="og:site_name" content="HelloWorks"><link id="favicon" rel="shortcut icon" href="https://files.readme.io/4c94731-small-Size32.png" type="image/png"><link rel="canonical" href="https://docs.helloworks.com/reference/getting-started"><script src="https://cdn.jsdelivr.net/npm/cash-dom@8.1.5/dist/cash.min.js"></script><link data-parent-chunk="main" rel="prefetch" as="style" href="https://cdn.readme.io/public/hub/web/routes-PageNotFound.1ada8671884e2a5b981e.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="https://cdn.readme.io/public/hub/web/routes-Changelog.ac251fcf6a16ffcca181.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="https://cdn.readme.io/public/hub/web/routes-Discuss.7130e638c898bc38ef51.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="https://cdn.readme.io/public/hub/web/SuperHub.6649da77b8a94b511d14.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="https://cdn.readme.io/public/hub/web/routes-Tutorials.6bbecc829930002d126a.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="https://cdn.readme.io/public/hub/web/CustomPage.a1623b056ecdeb4ea8ba.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="https://cdn.readme.io/public/hub/web/routes-Landing.ef4a0f66c25406693cb6.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="https://cdn.readme.io/public/hub/web/Header.e0370f3d67c17f35fcdb.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="https://cdn.readme.io/public/hub/web/routes-Doc.d1a9b4aa8bad2f43855a.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="https://cdn.readme.io/public/hub/web/routes-Doc-SuperHubEditor.70ddf33e550ed8ae27e3.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="https://cdn.readme.io/public/hub/web/routes-Reference.54541fde55ccb4d497f7.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="https://cdn.readme.io/public/hub/web/6445.cd913ab8f7b56dd3b3a0.css">
<link data-parent-chunk="main" rel="prefetch" as="style" href="https://cdn.readme.io/public/hub/web/ui-styles.9d464e23eab3990199d5.css">
<link data-chunk="New" rel="preload" as="style" href="https://cdn.readme.io/public/hub/web/New.b3b8595e99f4a9981db6.css">
<link data-chunk="routes-Tutorials" rel="preload" as="style" href="https://cdn.readme.io/public/hub/web/routes-Tutorials.6bbecc829930002d126a.css">
<link data-chunk="List" rel="preload" as="style" href="https://cdn.readme.io/public/hub/web/List.95cd63b7870b4453fc19.css">
<link data-chunk="Page" rel="preload" as="style" href="https://cdn.readme.io/public/hub/web/Page.b3b8595e99f4a9981db6.css">
<link data-chunk="routes-Discuss" rel="preload" as="style" href="https://cdn.readme.io/public/hub/web/routes-Discuss.7130e638c898bc38ef51.css">
<link data-chunk="Post" rel="preload" as="style" href="https://cdn.readme.io/public/hub/web/Post.a1623b056ecdeb4ea8ba.css">
<link data-chunk="routes-Changelog" rel="preload" as="style" href="https://cdn.readme.io/public/hub/web/routes-Changelog.ac251fcf6a16ffcca181.css">
<link data-chunk="Editor" rel="preload" as="style" href="https://cdn.readme.io/public/hub/web/Editor.4e2d61d01f0abe840dee.css">
<link data-chunk="routes-Suggestions-ngz-Header" rel="preload" as="style" href="https://cdn.readme.io/public/hub/web/routes-Suggestions-ngz-Header.0f3cc7b3c9b6779eaadb.css">
<link data-chunk="CustomPage" rel="preload" as="style" href="https://cdn.readme.io/public/hub/web/CustomPage.a1623b056ecdeb4ea8ba.css">
<link data-chunk="routes-PageNotFound" rel="preload" as="style" href="https://cdn.readme.io/public/hub/web/routes-PageNotFound.1ada8671884e2a5b981e.css">
<link data-chunk="routes-R.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_8_4) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/49.0.2656.18 Safari/537.36' 'https://docs.helloworks.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)