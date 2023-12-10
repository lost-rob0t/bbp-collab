### HTTP Missing Security Headers (http-missing-security-headers:x-frame-options) found on https://developers.hellosign.com

----
**Details**: **http-missing-security-headers:x-frame-options** matched at https://developers.hellosign.com

**Protocol**: HTTP

**Full URL**: https://developers.hellosign.com

**Timestamp**: Sat Dec 9 14:54:56 +0000 UTC 2023

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
Host: developers.hellosign.com
User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/55.0.2919.83 Safari/537.36
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
Age: 54
Cache-Control: public, max-age=0, must-revalidate
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 14:54:56 GMT
Etag: "340cda8a867afc4f31c4f08c4f38f624"
Last-Modified: Wed, 06 Dec 2023 23:39:36 GMT
Server: openresty/1.21.4.2
Strict-Transport-Security: max-age=31536000
Vary: Accept-Encoding
Via: 1.1 7154e2f13d02d1cc12281ca90f1bd47e.cloudfront.net (CloudFront)
X-Amz-Cf-Id: IZNERNc1q9YGCEr3kSWNgqLHoy1f6q52M3lwY0Y-hsBCBhIE4ZJXkA==
X-Amz-Cf-Pop: IAD66-C1
X-Amz-Id-2: pE/CP9ayOWVJahgUULNO5yNgsTQ0KmMpezkFxhzSolp/54n72WH7hoXEYXjrRkM2yFzfzJBnSmM=
X-Amz-Request-Id: 90KGN59BZ837P621
X-Amz-Server-Side-Encryption: AES256
X-Cache: Hit from cloudfront

<!DOCTYPE html><html lang="en-US"><head><meta charSet="utf-8"/><meta http-equiv="x-ua-compatible" content="ie=edge"/><meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no, viewport-fit=cover"/><script>window._onRedoclyRouteChange = function (cb) {
    window.__redoclyRouteChangeListenres = window.__redoclyRouteChangeListenres || [];
    window.__redoclyRouteChangeListenres.push(cb);
  }
  window._onRedoclyLoginResult = function(cb) {
    window.__redoclyLoginResultListenres =  window.__redoclyLoginResultListenres || [];
    window.__redoclyLoginResultListenres.push(cb);
  }</script><style data-href="/styles.bd4d38a2835753fb419e.css" data-identity="gatsby-global-css">.ps{-ms-overflow-style:none;overflow:hidden!important;overflow-anchor:none;touch-action:auto;-ms-touch-action:auto}.ps__rail-x{bottom:0;height:15px}.ps__rail-x,.ps__rail-y{display:none;opacity:0;position:absolute;transition:background-color .2s linear,opacity .2s linear;-webkit-transition:background-color .2s linear,opacity .2s linear}.ps__rail-y{right:0;width:15px}.ps--active-x>.ps__rail-x,.ps--active-y>.ps__rail-y{background-color:transparent;display:block}.ps--focus>.ps__rail-x,.ps--focus>.ps__rail-y,.ps--scrolling-x>.ps__rail-x,.ps--scrolling-y>.ps__rail-y,.ps:hover>.ps__rail-x,.ps:hover>.ps__rail-y{opacity:.6}.ps .ps__rail-x.ps--clicking,.ps .ps__rail-x:focus,.ps .ps__rail-x:hover,.ps .ps__rail-y.ps--clicking,.ps .ps__rail-y:focus,.ps .ps__rail-y:hover{background-color:#eee;opacity:.9}.ps__thumb-x{bottom:2px;height:6px;transition:background-color .2s linear,height .2s ease-in-out;-webkit-transition:background-color .2s linear,height .2s ease-in-out}.ps__thumb-x,.ps__thumb-y{background-color:#aaa;border-radius:6px;position:absolute}.ps__thumb-y{right:2px;transition:background-color .2s linear,width .2s ease-in-out;-webkit-transition:background-color .2s linear,width .2s ease-in-out;width:6px}.ps__rail-x.ps--clicking .ps__thumb-x,.ps__rail-x:focus>.ps__thumb-x,.ps__rail-x:hover>.ps__thumb-x{background-color:#999;height:11px}.ps__rail-y.ps--clicking .ps__thumb-y,.ps__rail-y:focus>.ps__thumb-y,.ps__rail-y:hover>.ps__thumb-y{background-color:#999;width:11px}@supports (-ms-overflow-style:none){.ps{overflow:auto!important}}@media (-ms-high-contrast:none),screen and (-ms-high-contrast:active){.ps{overflow:auto!important}}.beta-badge{background:rgba(0,179,230,.12);border-radius:12px;color:#000;padding:2px 8px;text-align:center}.beta-badge.operation{font-size:14px;line-height:1.5;margin-left:10px;vertical-align:super}.beta-badge.field{align-self:baseline;font-size:12px;margin-bottom:12px}.beta-disclaimer{background-color:#f5f7fa;border-radius:4px;color:#000;font-size:16px;margin:12px 0;padding:8px 12px}.add-style-to-screenshot-column+table th:nth-child(2){min-width:25%;width:60%}.zoomable-image{cursor:zoom-in}.img-modal{background-color:#000;background-color:rgba(0,0,0,.5);height:100%;left:0;padding-top:100px;position:fixed;top:0;width:100%;z-index:25}.img-modal-content{-webkit-animation-duration:.6s;animation-duration:.6s;-webkit-animation-name:zoom;animation-name:zoom;cursor:zoom-out;display:block;margin:auto;max-height:95%;max-width:75%}@-webkit-keyframes zoom{0%{-webkit-transform:scale(0);transform:scale(0)}to{-webkit-transform:scale(1);transform:scale(1)}}@keyframes zoom{0%{-webkit-transform:scale(0);transform:scale(0)}to{-webkit-transform:scale(1);transform:scale(1)}}.sdk-compare{margin-bottom:10px}.sdk-compare p{margin-top:0}.before-code-comparison{height:20px}.before-code-comparison+.code-snippets-tabs .snippets-tabs-headers .tab-header{border:none;border-radius:4px;box-shadow:none;font-weight:600;line-height:1;min-width:120px;outline:none;padding:8px 10px!important;text-align:center;text-decoration:none;width:auto}.before-code-comparison+.code-snippets-tabs .snippets-tabs-headers .tab-header.active{background-color:#e4e7eb}.before-code-comparison+.code-snippets-tabs .snippets-tabs-contents .tab-content{border-radius:0;margin-top:0}.before-code-comparison+.code-snippets-tabs .gatsby-highlight pre[class*=language-],pre[class*=language-]{border-radius:0 0 4px 4px}.wrap-me+code.wrap-sign-url{display:inline-block;max-width:100%;white-space:normal;word-break:break-all}.endpoints-dropdown{-webkit-appearance:none;appearance:none;background:url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvM.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/55.0.2919.83 Safari/537.36' 'https://developers.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)