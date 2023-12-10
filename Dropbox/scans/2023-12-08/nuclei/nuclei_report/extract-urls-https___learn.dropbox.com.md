### Urls extractor (extract-urls) found on https://learn.dropbox.com

----
**Details**: **extract-urls** matched at https://learn.dropbox.com

**Protocol**: HTTP

**Full URL**: https://learn.dropbox.com

**Timestamp**: Sat Dec 9 00:01:13 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Urls extractor |
| Authors | cipher387 |
| Tags | osint, juicy-info |
| Severity | info |
| Description | Extract urls from web page body |

**Request**
```http
GET / HTTP/1.1
Host: learn.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 6.3; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2225.0 Safari/537.36
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
Age: 214608
Cache-Control: public,max-age=0,must-revalidate
Cache-Status: "Netlify Edge"; hit
Content-Type: text/html; charset=UTF-8
Date: Sat, 09 Dec 2023 00:01:09 GMT
Etag: "9114711161082dc806acc0e8e1af1687-df"
Server: Netlify
Vary: Accept-Encoding
Via: 1.1 0befec97ec8a388fe199ea682db0cdc0.cloudfront.net (CloudFront)
X-Amz-Cf-Id: 7tHedEWXq6C65l668aWyKplBqDH7RCO4dqVE34D6YJUmYb376F9tkA==
X-Amz-Cf-Pop: CDG50-P4
X-Cache: Miss from cloudfront
X-Nf-Request-Id: 01HH5Y1G161V76DCDCT09BPK9G

<!DOCTYPE html><html lang="en-US"><head nonce="d2Zaun2DUii7VjQ4Imu3CYnIn3h3+cZALvvEescFCjo="><meta property="csp-nonce" content="d2Zaun2DUii7VjQ4Imu3CYnIn3h3+cZALvvEescFCjo="/><meta http-equiv="Content-Security-Policy" content="default-src &#x27;self&#x27; *.wistia.com *.wistia.net;base-uri &#x27;self&#x27;;style-src  https://fonts.googleapis.com &#x27;self&#x27; &#x27;unsafe-inline&#x27; blob: fast.wistia.com;script-src https://www.google-analytics.com scripts.demandbase.com/ https://c.contentsquare.net/ platform.cloud.coveo.com www.youtube.com embedwistia-a.akamaihd.net *.wistia.com *.wistia.net c.evidon.com tag.demandbase.com t.contentsquare.net iabmap.evidon.com https://*.dropbox.com https://*.dropboxstatic.com tags.tiqcdn.com/utag/dropbox/ tags.tiqcdn.com/utag/tiqapp/ https://cfl.dropboxstatic.com/static/pithos/lang/ https://www.knotch-cdn.com/ktag/latest/ktag.min.js https://aq-swa-api.knotch.it/ https://units.knotch.it/ &#x27;self&#x27; &#x27;unsafe-eval&#x27; &#x27;unsafe-inline&#x27; ;media-src blob: &#x27;self&#x27; data: embedwistia-a.akamaihd.net *.wistia.com *.wistia.net videos.ctfassets.net;font-src &#x27;self&#x27; data: *.wistia.com;img-src &#x27;self&#x27; embedwistia-a.akamaihd.net www.google-analytics.com https://scripts.demandbase.com/ https://c.contentsquare.net/ images.ctfassets.net downloads.ctfassets.net videos.ctfassets.net c.evidon.com l.evidon.com *.wistia.com *.wistia.net www.youtube.com dpiprodesntls.112.2o7.net match.prod.bidr.io id.rlcdn.com segments.company-target.com data:;frame-src https://consent.dropbox.com &#x27;self&#x27; www.youtube.com fast.wistia.com fast.wistia.net https://s.company-target.com;worker-src blob: &#x27;self&#x27;;prefetch-src &#x27;self&#x27;;connect-src &#x27;self&#x27; platform.cloud.coveo.com embedwistia-a.akamaihd.net *.litix.io *.wistia.com www.youtube.com images.ctfassets.net videos.ctfassets.net sessions.bugsnag.com notify.bugsnag.com configs.knotch.com optoutapi.evidon.com https://www.google-analytics.com https://www.dropbox.com https://cfl.dropboxstatic.com/static/pithos/lang/ https://c.contentsquare.net/ https://cognito-identity.us-east-1.amazonaws.com api.company-target.com https://preview.contentful.com https://aq-swa-api.knotch.it/ dpiprodesntls.112.2o7.net https://tag-logger.demandbase.com https://*.dropbox.com/log/ux_analytics https://x6exz9z8i0.execute-api.us-east-1.amazonaws.com;"/><script src="https://www.dropbox.com/pithos/ux_analytics" async="" defer=""></script><meta name="viewport" content="width=device-width"/><meta charSet="utf-8"/><title data-testid="Head-title">Dropbox training and self-guided courses | Dropbox learn</title><link rel="preconnect" href="https://dropbox.com"/><link rel="preload" href="/fonts/SharpGroteskDBMedium20.woff2" as="font" crossorigin="" type="font/woff2"/><link rel="preload" href="/fonts/SharpGroteskDBMedium22.woff2" as="font" crossorigin="" type="font/woff2"/><link rel="preload" href="/fonts/SharpGroteskDBBook20.woff2" as="font" crossorigin="" type="font/woff2"/><link rel="preload" href="/fonts/AtlasGrotesk-Regular.woff2" as="font" crossorigin="" type="font/woff2"/><link rel="preload" href="/fonts/AtlasGrotesk-Medium.woff2" as="font" crossorigin="" type="font/woff2"/><meta property="og:title" content="Dropbox training and self-guided courses | Dropbox learn"/><meta property="og:description" content="Learn how to use Dropbox. Browse our catalog of free self-guided courses and virtual instructor led training sessions. Start a Dropbox training course today."/><meta name="twitter:title" content="Dropbox training and self-guided courses | Dropbox learn"/><meta name="twitter:description" content="Learn how to use Dropbox. Browse our catalog of free self-guided courses and virtual instructor led training sessions. Start a Dropbox training course today."/><meta name="robots" content="index,follow"/><meta name="canonical" content="https://learn.dropbox.com"/><meta name="description" content="Learn how to use Dropbox. Browse our catalog of free self-guided courses and virtual instructor led training sessions. Start a Dropbox training course today."/><meta name="content_type" content="pageLanding"/><link href="https://learn.dropbox.com/fr" rel="alternate" hrefLang="fr"/><link href="https://learn.dropbox.com/de" rel="alternate" hrefLang="de"/><link href="https://learn.dropbox.com/it" rel="alternate" hrefLang="it"/><link href="https://learn.dropbox.com/ja" rel="alternate" hrefLang="ja"/><link href="https://learn.dropbox.com/pt-br" rel="alternate" hrefLang="pt-br"/><link href="https:/.... Truncated ....
```

**Extra Information**

**Extracted results:**

- https://www.dropbox.com/
- https://www.dropbox.com/business?trigger=_footer
- https://schema.org
- https://schema.org/
- https://embed-ssl.wistia.com/deliveries/9e469790867de66d4f4ae1c9cfd0fc0441ec0663.webp?image_crop_resized=900x450
- https://scripts.demandbase.com/
- https://dropbox.com
- https://www.dropbox.com/downloading
- https://help.dropbox.com/
- https://www.dropboxforum.com/
- https://learn.dropbox.com/fr
- https://www.dropbox.com/referrals?trigger=_footer
- https://learn.dropbox.com
- https://www.dropbox.com
- https://preview.contentful.com
- https://www.dropbox.com/install?trigger=_footer
- https://www.dropbox.com/security?trigger=_footer
- https://blog.dropbox.com/
- https://learn.dropbox.com/it
- https://learn.dropbox.com/pt-br
- https://www.dropbox.com/pro?trigger=_footer
- https://learn.dropbox.com/ja
- https://www.dropbox.com/plus?trigger=_footer
- https://help.dropbox.com/security/cookies
- https://www.dropbox.com/privacy?trigger=_footer
- https://www.dropbox.com/sitemap?trigger=_footer
- https://aq-swa-api.knotch.it/
- https://tag-logger.demandbase.com
- https://cognito-identity.us-east-1.amazonaws.com
- https://help.dropbox.com/accounts-billing/security/cookies
- https://units.knotch.it/
- https://s.company-target.com;worker-src
- https://help.dropbox.com/installs-integrations/desktop/locate-dropbox-folder
- https://help.dropbox.com/installs-integrations/desktop/s-mode
- https://cfl.dropboxstatic.com/static/pithos/lang/
- https://consent.dropbox.com
- http://www.dropbox.com
- https://c.contentsquare.net/
- https://images.ctfassets.net/zh1yxk5yn2r7/33cKbUcUgjCOB3aPxkIMGq/14cdd574f957e960f0972f73a80a892e/hoop.png
- https://www.dropbox.com/mobile?trigger=_footer
- https://www.dropbox.com/plans?trigger=_footer
- https://www.dropbox.com/features?trigger=_footer
- https://www.dropbox.com/news?trigger=_footer
- https://www.dropbox.com/developers?trigger=_footer
- http://schema.org
- https://www.google-analytics.com
- https://learn.dropbox.com/de
- https://investors.dropbox.com/
- https://www.knotch-cdn.com/ktag/latest/ktag.min.js
- https://jobs.dropbox.com/
- https://www.dropbox.com/support
- https://www.dropbox.com/pithos/ux_analytics
- https://www.dropbox.com/about
- https://www.dropbox.com/login
- https://fonts.googleapis.com
- https://x6exz9z8i0.execute-api.us-east-1.amazonaws.com;
- https://images.ctfassets.net/zh1yxk5yn2r7/2z2Foc0s6DPlQV1aTtWO3b/b0c0e0a58102dd90281f7b1df860a370/Dropbox.svg
- https://learn.dropbox.com/es
- https://www.dropbox.com/enterprise?trigger=_footer



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.3; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2225.0 Safari/537.36' 'https://learn.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)