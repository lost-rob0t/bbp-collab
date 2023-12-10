### HTTP Missing Security Headers (http-missing-security-headers:access-control-max-age) found on https://invoice.dropbox.com

----
**Details**: **http-missing-security-headers:access-control-max-age** matched at https://invoice.dropbox.com

**Protocol**: HTTP

**Full URL**: https://invoice.dropbox.com

**Timestamp**: Sat Dec 9 14:55:15 +0000 UTC 2023

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
Host: invoice.dropbox.com
User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/34.0.1847.137 Safari/4E423F
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
Age: 39
Cache-Control: no-cache, no-store, max-age=0, must-revalidate
Content-Type: text/html
Date: Sat, 09 Dec 2023 14:54:37 GMT
Etag: W/"4b0f5c2f50f7a22b3ce3d619e48b7327"
Expires: -1
Last-Modified: Mon, 30 Oct 2023 14:58:05 GMT
Pragma: no-cache
Server: AmazonS3
Vary: Accept-Encoding
Via: 1.1 1713affce12abff65dc8b74f1260c722.cloudfront.net (CloudFront)
X-Amz-Cf-Id: jeqTROC4dfw85ipTK4nQljq9TL49P6GCUvWzKwv8pOsN38mvhIbe3Q==
X-Amz-Cf-Pop: CDG52-P2
X-Cache: Hit from cloudfront

<!doctype html><html lang="en" class="dig-Theme--VIS"><head><meta charset="utf-8"/><link rel="icon" href="/favicon.ico"/><meta name="viewport" content="user-scalable=no,initial-scale=1,maximum-scale=1,minimum-scale=1,width=device-width,height-device-height"/><meta name="theme-color" content="#000000"/><meta name="description" content="Dropbox Invoice helps you manage your clients, send invoices, collect payments, and integrates with your accounting tools"/><link rel="apple-touch-icon" href="/logo192.png"/><link rel="manifest" href="/manifest.json"/><link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Lato:wght@400;700&family=Roboto+Condensed:wght@400;700&family=Roboto:wght@400;500;700&family=Source+Serif+4:opsz,wght@8..60,400;8..60,500;8..60,700&display=swap" rel="stylesheet"><title>Dropbox Invoice</title><style>body{width:var(--full-inner-width);overflow-x:hidden;overflow-y:auto;animation:none}</style><link href="/static/css/2.d290f05b.chunk.css" rel="stylesheet"><link href="/static/css/main.69a2d04a.chunk.css" rel="stylesheet"></head><body><noscript>You need to enable JavaScript to run this app.</noscript><div id="root"></div><script>!function(e){function r(r){for(var n,i,a=r[0],c=r[1],l=r[2],s=0,p=[];s<a.length;s++)i=a[s],Object.prototype.hasOwnProperty.call(o,i)&&o[i]&&p.push(o[i][0]),o[i]=0;for(n in c)Object.prototype.hasOwnProperty.call(c,n)&&(e[n]=c[n]);for(f&&f(r);p.length;)p.shift()();return u.push.apply(u,l||[]),t()}function t(){for(var e,r=0;r<u.length;r++){for(var t=u[r],n=!0,a=1;a<t.length;a++){var c=t[a];0!==o[c]&&(n=!1)}n&&(u.splice(r--,1),e=i(i.s=t[0]))}return e}var n={},o={1:0},u=[];function i(r){if(n[r])return n[r].exports;var t=n[r]={i:r,l:!1,exports:{}};return e[r].call(t.exports,t,t.exports,i),t.l=!0,t.exports}i.e=function(e){var r=[],t=o[e];if(0!==t)if(t)r.push(t[2]);else{var n=new Promise((function(r,n){t=o[e]=[r,n]}));r.push(t[2]=n);var u,a=document.createElement("script");a.charset="utf-8",a.timeout=120,i.nc&&a.setAttribute("nonce",i.nc),a.src=function(e){return i.p+"static/js/"+({}[e]||e)+"."+{3:"0939ac98",4:"333e78b5"}[e]+".chunk.js"}(e);var c=new Error;u=function(r){a.onerror=a.onload=null,clearTimeout(l);var t=o[e];if(0!==t){if(t){var n=r&&("load"===r.type?"missing":r.type),u=r&&r.target&&r.target.src;c.message="Loading chunk "+e+" failed.\n("+n+": "+u+")",c.name="ChunkLoadError",c.type=n,c.request=u,t[1](c)}o[e]=void 0}};var l=setTimeout((function(){u({type:"timeout",target:a})}),12e4);a.onerror=a.onload=u,document.head.appendChild(a)}return Promise.all(r)},i.m=e,i.c=n,i.d=function(e,r,t){i.o(e,r)||Object.defineProperty(e,r,{enumerable:!0,get:t})},i.r=function(e){"undefined"!=typeof Symbol&&Symbol.toStringTag&&Object.defineProperty(e,Symbol.toStringTag,{value:"Module"}),Object.defineProperty(e,"__esModule",{value:!0})},i.t=function(e,r){if(1&r&&(e=i(e)),8&r)return e;if(4&r&&"object"==typeof e&&e&&e.__esModule)return e;var t=Object.create(null);if(i.r(t),Object.defineProperty(t,"default",{enumerable:!0,value:e}),2&r&&"string"!=typeof e)for(var n in e)i.d(t,n,function(r){return e[r]}.bind(null,n));return t},i.n=function(e){var r=e&&e.__esModule?function(){return e.default}:function(){return e};return i.d(r,"a",r),r},i.o=function(e,r){return Object.prototype.hasOwnProperty.call(e,r)},i.p="/",i.oe=function(e){throw console.error(e),e};var a=this.webpackJsonpfreddie=this.webpackJsonpfreddie||[],c=a.push.bind(a);a.push=r,a=a.slice();for(var l=0;l<a.length;l++)r(a[l]);var f=c;t()}([])</script><script src="/static/js/2.30c584b7.chunk.js"></script><script src="/static/js/main.3a1b7a69.chunk.js"></script></body></html>
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/34.0.1847.137 Safari/4E423F' 'https://invoice.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)