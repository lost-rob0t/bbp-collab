### HTTP Missing Security Headers (http-missing-security-headers:referrer-policy) found on https://learn.dropbox.com

----
**Details**: **http-missing-security-headers:referrer-policy** matched at https://learn.dropbox.com

**Protocol**: HTTP

**Full URL**: https://learn.dropbox.com

**Timestamp**: Sat Dec 9 14:55:22 +0000 UTC 2023

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
Host: learn.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.2309.372 Safari/537.36
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
Age: 279645
Cache-Control: public,max-age=0,must-revalidate
Cache-Status: "Netlify Edge"; hit
Content-Type: text/html; charset=UTF-8
Date: Sat, 09 Dec 2023 14:55:21 GMT
Etag: "9114711161082dc806acc0e8e1af1687-df"
Server: Netlify
Vary: Accept-Encoding
Via: 1.1 4bc6e08d9495b312ae3b91e801107f80.cloudfront.net (CloudFront)
X-Amz-Cf-Id: xR8cj9_werrKhCkkgTCSWgwp9i_aFLius8csO904L41pFUiZD-Q9WQ==
X-Amz-Cf-Pop: CDG50-P4
X-Cache: Miss from cloudfront
X-Nf-Request-Id: 01HH7H6TSP1CXM2FVGQPXDQZ6A

<!DOCTYPE html><html lang="en-US"><head nonce="d2Zaun2DUii7VjQ4Imu3CYnIn3h3+cZALvvEescFCjo="><meta property="csp-nonce" content="d2Zaun2DUii7VjQ4Imu3CYnIn3h3+cZALvvEescFCjo="/><meta http-equiv="Content-Security-Policy" content="default-src &#x27;self&#x27; *.wistia.com *.wistia.net;base-uri &#x27;self&#x27;;style-src  https://fonts.googleapis.com &#x27;self&#x27; &#x27;unsafe-inline&#x27; blob: fast.wistia.com;script-src https://www.google-analytics.com scripts.demandbase.com/ https://c.contentsquare.net/ platform.cloud.coveo.com www.youtube.com embedwistia-a.akamaihd.net *.wistia.com *.wistia.net c.evidon.com tag.demandbase.com t.contentsquare.net iabmap.evidon.com https://*.dropbox.com https://*.dropboxstatic.com tags.tiqcdn.com/utag/dropbox/ tags.tiqcdn.com/utag/tiqapp/ https://cfl.dropboxstatic.com/static/pithos/lang/ https://www.knotch-cdn.com/ktag/latest/ktag.min.js https://aq-swa-api.knotch.it/ https://units.knotch.it/ &#x27;self&#x27; &#x27;unsafe-eval&#x27; &#x27;unsafe-inline&#x27; ;media-src blob: &#x27;self&#x27; data: embedwistia-a.akamaihd.net *.wistia.com *.wistia.net videos.ctfassets.net;font-src &#x27;self&#x27; data: *.wistia.com;img-src &#x27;self&#x27; embedwistia-a.akamaihd.net www.google-analytics.com https://scripts.demandbase.com/ https://c.contentsquare.net/ images.ctfassets.net downloads.ctfassets.net videos.ctfassets.net c.evidon.com l.evidon.com *.wistia.com *.wistia.net www.youtube.com dpiprodesntls.112.2o7.net match.prod.bidr.io id.rlcdn.com segments.company-target.com data:;frame-src https://consent.dropbox.com &#x27;self&#x27; www.youtube.com fast.wistia.com fast.wistia.net https://s.company-target.com;worker-src blob: &#x27;self&#x27;;prefetch-src &#x27;self&#x27;;connect-src &#x27;self&#x27; platform.cloud.coveo.com embedwistia-a.akamaihd.net *.litix.io *.wistia.com www.youtube.com images.ctfassets.net videos.ctfassets.net sessions.bugsnag.com notify.bugsnag.com configs.knotch.com optoutapi.evidon.com https://www.google-analytics.com https://www.dropbox.com https://cfl.dropboxstatic.com/static/pithos/lang/ https://c.contentsquare.net/ https://cognito-identity.us-east-1.amazonaws.com api.company-target.com https://preview.contentful.com https://aq-swa-api.knotch.it/ dpiprodesntls.112.2o7.net https://tag-logger.demandbase.com https://*.dropbox.com/log/ux_analytics https://x6exz9z8i0.execute-api.us-east-1.amazonaws.com;"/><script src="https://www.dropbox.com/pithos/ux_analytics" async="" defer=""></script><meta name="viewport" content="width=device-width"/><meta charSet="utf-8"/><title data-testid="Head-title">Dropbox training and self-guided courses | Dropbox learn</title><link rel="preconnect" href="https://dropbox.com"/><link rel="preload" href="/fonts/SharpGroteskDBMedium20.woff2" as="font" crossorigin="" type="font/woff2"/><link rel="preload" href="/fonts/SharpGroteskDBMedium22.woff2" as="font" crossorigin="" type="font/woff2"/><link rel="preload" href="/fonts/SharpGroteskDBBook20.woff2" as="font" crossorigin="" type="font/woff2"/><link rel="preload" href="/fonts/AtlasGrotesk-Regular.woff2" as="font" crossorigin="" type="font/woff2"/><link rel="preload" href="/fonts/AtlasGrotesk-Medium.woff2" as="font" crossorigin="" type="font/woff2"/><meta property="og:title" content="Dropbox training and self-guided courses | Dropbox learn"/><meta property="og:description" content="Learn how to use Dropbox. Browse our catalog of free self-guided courses and virtual instructor led training sessions. Start a Dropbox training course today."/><meta name="twitter:title" content="Dropbox training and self-guided courses | Dropbox learn"/><meta name="twitter:description" content="Learn how to use Dropbox. Browse our catalog of free self-guided courses and virtual instructor led training sessions. Start a Dropbox training course today."/><meta name="robots" content="index,follow"/><meta name="canonical" content="https://learn.dropbox.com"/><meta name="description" content="Learn how to use Dropbox. Browse our catalog of free self-guided courses and virtual instructor led training sessions. Start a Dropbox training course today."/><meta name="content_type" content="pageLanding"/><link href="https://learn.dropbox.com/fr" rel="alternate" hrefLang="fr"/><link href="https://learn.dropbox.com/de" rel="alternate" hrefLang="de"/><link href="https://learn.dropbox.com/it" rel="alternate" hrefLang="it"/><link href="https://learn.dropbox.com/ja" rel="alternate" hrefLang="ja"/><link href="https://learn.dropbox.com/pt-br" rel="alternate" hrefLang="pt-br"/><link href="https:/.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.2309.372 Safari/537.36' 'https://learn.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)