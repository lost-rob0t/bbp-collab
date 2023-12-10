### HTTP Missing Security Headers (http-missing-security-headers:cross-origin-resource-policy) found on https://designstandards.dropbox.com

----
**Details**: **http-missing-security-headers:cross-origin-resource-policy** matched at https://designstandards.dropbox.com

**Protocol**: HTTP

**Full URL**: https://dropboxdesignstandards.com/

**Timestamp**: Sat Dec 9 14:54:54 +0000 UTC 2023

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
Host: designstandards.dropbox.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/37.0.2062.124 Safari/537.36
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
Age: 112644
Cache-Control: public, max-age=0, s-maxage=2678400, must-revalidate
Content-Type: text/html
Date: Fri, 08 Dec 2023 07:37:31 GMT
Etag: W/"526a51ecdda1951c8db77b8985024f81"
Last-Modified: Tue, 12 Sep 2023 15:48:35 GMT
Server: AmazonS3
Vary: Accept-Encoding
Via: 1.1 2ba5677785db2f66bc73820b2a261476.cloudfront.net (CloudFront)
X-Amz-Cf-Id: UGcvV9CtFpqxCX_lF-IAgqVRTiOFFwhO6lS6I17GV-6kmZF0dfvt4A==
X-Amz-Cf-Pop: CDG50-P2
X-Amz-Server-Side-Encryption: AES256
X-Cache: Hit from cloudfront

<!DOCTYPE html><html lang="en"><head><meta http-equiv="Content-Security-Policy" content="default-src &#x27;self&#x27;;base-uri &#x27;self&#x27;;style-src  https://fonts.googleapis.com &#x27;self&#x27; &#x27;unsafe-inline&#x27;;script-src https://www.googletagmanager.com https://www.google-analytics.com https://*.dropbox.com https://*.dropboxstatic.com platform.cloud.coveo.com fast.wistia.com https://www.googletagmanager.com/debug/bootstrap c.evidon.com tag.demandbase.com t.contentsquare.net iabmap.evidon.com &#x27;self&#x27; &#x27;unsafe-eval&#x27; &#x27;unsafe-inline&#x27; ;media-src videos.ctfassets.net assets.ctfassets.net blob:;font-src &#x27;self&#x27; assets.ctfassets.net data:;img-src &#x27;self&#x27; https://cfl.dropboxstatic.com embedwistia-a.akamaihd.net www.google-analytics.com www.googletagmanager.com images.ctfassets.net downloads.ctfassets.net c.evidon.com l.evidon.com *.wistia.com dpiprodesntls.112.2o7.net match.prod.bidr.io id.rlcdn.com segments.company-target.com data:;frame-src www.googletagmanager.com https://*.dev.corp.dropbox.com https://consent.dropbox.com &#x27;self&#x27;;worker-src blob:;prefetch-src &#x27;self&#x27;;connect-src &#x27;self&#x27; platform.cloud.coveo.com embedwistia-a.akamaihd.net *.litix.io *.wistia.com videos.ctfassets.net assets.ctfassets.net images.ctfassets.net downloads.ctfassets.net optoutapi.evidon.com https://www.google-analytics.com https://www.dropbox.com https://cognito-identity.us-west-2.amazonaws.com api.company-target.com https://preview.contentful.com http://localhost:5000/graphql ;"/><meta name="gtm_id" content="GTM-TWL269C"/><link rel="preconnect" href="https://images.ctfassets.net"/><link rel="preconnect" href="https://assets.ctfassets.net"/><meta name="viewport" content="width=device-width"/><meta charSet="utf-8"/><script>
                (function (a, s, y, n, c, h, i, d, e) {
                  
                  s.className += ' ' + y
                  h.start = 1 * new Date()
                  h.end = i = function () {
                    s.className = s.className.replace(RegExp(' ?' + y), '')
                  }
                  ;(a[n] = a[n] || []).hide = h
                  setTimeout(function () {
                    i()
                    h.end = null
                  }, c)
                  h.timeout = c
                })(window, document.documentElement, 'async-hide', 'dataLayer', 500,{})
              </script><link rel="shortcut icon" href="/favicon.ico"/><meta name="title" content="Welcome to the design standards."/><meta name="keywords" content=""/><meta name="description" content=""/><title>Welcome to the design standards.</title><meta name="contentful_space" content="w7shgyvrfdaa"/><meta name="contentful_environment" content="master"/><meta name="content_type" content="homepage"/><link rel="preload" href="//images.ctfassets.net/w7shgyvrfdaa/442g1arr1dBa5z0eMl2zXV/6ace0b94b51111150db894a9689b79b1/Homepage_Hero_05.jpg" imagesrcset="//images.ctfassets.net/w7shgyvrfdaa/442g1arr1dBa5z0eMl2zXV/6ace0b94b51111150db894a9689b79b1/Homepage_Hero_05.jpg?w=3840 3840w, //images.ctfassets.net/w7shgyvrfdaa/442g1arr1dBa5z0eMl2zXV/6ace0b94b51111150db894a9689b79b1/Homepage_Hero_05.jpg?w=3520 3520w, //images.ctfassets.net/w7shgyvrfdaa/442g1arr1dBa5z0eMl2zXV/6ace0b94b51111150db894a9689b79b1/Homepage_Hero_05.jpg?w=3200 3200w, //images.ctfassets.net/w7shgyvrfdaa/442g1arr1dBa5z0eMl2zXV/6ace0b94b51111150db894a9689b79b1/Homepage_Hero_05.jpg?w=2880 2880w, //images.ctfassets.net/w7shgyvrfdaa/442g1arr1dBa5z0eMl2zXV/6ace0b94b51111150db894a9689b79b1/Homepage_Hero_05.jpg?w=2560 2560w, //images.ctfassets.net/w7shgyvrfdaa/442g1arr1dBa5z0eMl2zXV/6ace0b94b51111150db894a9689b79b1/Homepage_Hero_05.jpg?w=2240 2240w, //images.ctfassets.net/w7shgyvrfdaa/442g1arr1dBa5z0eMl2zXV/6ace0b94b51111150db894a9689b79b1/Homepage_Hero_05.jpg?w=1920 1920w, //images.ctfassets.net/w7shgyvrfdaa/442g1arr1dBa5z0eMl2zXV/6ace0b94b51111150db894a9689b79b1/Homepage_Hero_05.jpg?w=1600 1600w, //images.ctfassets.net/w7shgyvrfdaa/442g1arr1dBa5z0eMl2zXV/6ace0b94b51111150db894a9689b79b1/Homepage_Hero_05.jpg?w=1440 1440w, //images.ctfassets.net/w7shgyvrfdaa/442g1arr1dBa5z0eMl2zXV/6ace0b94b51111150db894a9689b79b1/Homepage_Hero_05.jpg?w=1280 1280w, //images.ctfassets.net/w7shgyvrfdaa/442g1arr1dBa5z0eMl2zXV/6ace0b94b51111150db894a9689b79b1/Homepage_Hero_05.jpg?w=960 960w, //images.ctfassets.net/w7shgyvrfdaa/442g1arr1dBa5z0eMl2zXV/6ace0b94b51111150db894a9689b79b1/Homepage_Hero_05.jpg?w=1280 640w" as="image"/><link rel="preload" href="//images.ctfassets.net/w.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/37.0.2062.124 Safari/537.36' 'https://designstandards.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)