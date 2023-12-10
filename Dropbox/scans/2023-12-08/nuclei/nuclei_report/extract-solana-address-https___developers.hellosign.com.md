### Solana addresses extractor (extract-solana-address) found on https://developers.hellosign.com

----
**Details**: **extract-solana-address** matched at https://developers.hellosign.com

**Protocol**: HTTP

**Full URL**: https://developers.hellosign.com

**Timestamp**: Sat Dec 9 00:00:50 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Solana addresses extractor |
| Authors | cipher387 |
| Tags | osint, juicy-info, cryptocyrrency |
| Severity | info |
| Description | Solana addresses from web page body (not universal, can also find addresses of other cryptocurrencies) |

**Request**
```http
GET / HTTP/1.1
Host: developers.hellosign.com
User-Agent: Mozilla/5.0 (Windows NT 6.2; WOW64) AppleWebKit/537.36 (KHTML like Gecko) Chrome/44.0.2403.155 Safari/537.36
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
Age: 99
Cache-Control: public, max-age=0, must-revalidate
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 00:00:48 GMT
Etag: "340cda8a867afc4f31c4f08c4f38f624"
Last-Modified: Wed, 06 Dec 2023 23:39:36 GMT
Server: openresty/1.21.4.2
Strict-Transport-Security: max-age=31536000
Vary: Accept-Encoding
Via: 1.1 7c246f3a389d2701a9bf150d0e576cd0.cloudfront.net (CloudFront)
X-Amz-Cf-Id: -udoZr6DYh8iMS9OS0zcNGRsvB9qPNa0UbyRPAmPKkJs7IjDR4amRQ==
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

**Extra Information**

**Extracted results:**

- uMzQzLDYuMTQyLDAuMDAxLDguNDg1bDY5Ljc1NSw2
- DcsNiw2LDZoMTE3LjQ4MmMzLjMxMywwLDYtMi42
- signatureRequestCreateEmbeddedWithTemp
- KGgoAAAANSUhEUgAAAAQAAAADCAYAAAC
- NzQtMC4zMzRjLTAuMDM1LTAuMTE3LTAuMDc1LTAuMjMx
- tMC4xNzgtMC4yNTgtMC4yNjJjLTAuMDctMC4wNjgtMC4
- MDgtMC41MjYsMy4yMzMtMS4zNTdjMC44MTctMC44MzQs
- jMS4xNzEsMS4xNzEsMi43MDcsMS43NTcsNC4yND
- cDovL3d3dy53My5vcmcvMjAwMC9zdmci
- KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAAN
- DNjLTAuMDk2LTAuMDE5LTAuMTg4LTAuMDM2LTAuMjg5L
- LDQuNjM1LTEwLjM1NCwxMC4zNTRMNi41ND
- NTYsNi45NTYsMTUyLjQ1NnoiLz4KCTxwYXRo
- KGgoAAAANSUhEUgAAAAcAAAAHCAMAAADzjKfhAAAACVB
- LTAuMDMtMC4xNTQtMC4wNDYtMC4yMzQtMC4wNzJjLTAu
- xMC4zNTRsLTAuMDkxLTQwLjc4Mmg2LjEzNSAgdjQwLjg
- 2LDZ2MjY4LjM1NgoJCWwtNTkuNTEzLTU5LjUxMmMtMi4
- KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAAH
- LDcuMzA2LTE2LjMyLDE2LjMyLTE2LjMybDQxLjEz
- BMVEW7AAC7AACxAAC7AAC7AAAAAAC4AAC5AAD
- Ljc4NGMtMC4wMjQtMC4xMTMtMC4wNDctMC4yMjMtMC4w
- DEtMC4wNDMtMC4xMjEtMC4wNjFjLTAuMDc
- MDk1LTAuMDMzLTAuMTktMC4wNjUtMC4y
- GMtMC4xMjMtMC4wMzQtMC4yNDYtMC4wNTktMC4zNjktM
- DMuMjc5YzAsNS43MTcsNC42MzUsMTAuMzU
- aimedDraftCreateEmbeddedWithTemp
- SU1FB9sJFhQXEbhTg7YAAAAZdEVYdENvbW1
- tMC4yMDJjLTAuMDkzLTAuMDgzLTAuMTk2LTAuMTU4LTA
- wLjEyLTAuMDEyLTAuMTg2LTAuMDEyTDYzLjc3LDEuMzA
- LDEwLjM1NCwxMC4zNTRsNTUuNjE2LDAuMDY1YzUuNzE5
- TJjLTAuMDQ4LTAuMTE5LTAuMTA3LTAuMj
- tMC4xLTAuMTM5LTAuMTk1LTAuMjA5LTAuMjkyQzk3LjY
- GMwLjE3NCwwLjg2MywwLjU5NiwxLjY5MSwxLj
- 7b25ddb5754b9795e2ede9355e243fea



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.2; WOW64) AppleWebKit/537.36 (KHTML like Gecko) Chrome/44.0.2403.155 Safari/537.36' 'https://developers.hellosign.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)