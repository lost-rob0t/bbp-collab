### Possible phone numbers extractor (extract-possible-phonenumbers) found on https://learn-stage.dropbox.com

----
**Details**: **extract-possible-phonenumbers** matched at https://learn-stage.dropbox.com

**Protocol**: HTTP

**Full URL**: https://learn-stage.dropbox.com

**Timestamp**: Sat Dec 9 00:01:12 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Possible phone numbers extractor |
| Authors | cipher387 |
| Tags | osint, juicy-info |
| Severity | info |
| Description | Extract possible phone numbers from web page body |

**Request**
```http
GET / HTTP/1.1
Host: learn-stage.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.67 Safari/537.36
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
Age: 6271
Cache-Control: public,max-age=0,must-revalidate
Cache-Status: "Netlify Edge"; hit
Content-Type: text/html; charset=UTF-8
Date: Sat, 09 Dec 2023 00:01:09 GMT
Etag: "e3df5ab4b117186065460f0339ab6dec-df"
Server: Netlify
Vary: Accept-Encoding
Via: 1.1 338cc9ab91d22cdfee3da5b2b53c3110.cloudfront.net (CloudFront)
X-Amz-Cf-Id: ddEpb-RrIiJu15Ub3ZnEit7SsaGGfDvUGuE2x28PdbI5mW_dsfs17A==
X-Amz-Cf-Pop: MRS52-C1
X-Cache: Miss from cloudfront
X-Nf-Request-Id: 01HH5Y1G292EG7QYREN7ARZKD7

<!DOCTYPE html><html lang="en-US"><head nonce="ldmsdeT+o7MbroYGQAq1SnjnBWjFdIqhizqOT0gUXZs="><meta property="csp-nonce" content="ldmsdeT+o7MbroYGQAq1SnjnBWjFdIqhizqOT0gUXZs="/><meta http-equiv="Content-Security-Policy" content="default-src &#x27;self&#x27; *.wistia.com *.wistia.net;base-uri &#x27;self&#x27;;style-src  https://fonts.googleapis.com &#x27;self&#x27; &#x27;unsafe-inline&#x27; blob: fast.wistia.com;script-src https://www.google-analytics.com scripts.demandbase.com/ https://c.contentsquare.net/ platform.cloud.coveo.com www.youtube.com embedwistia-a.akamaihd.net *.wistia.com *.wistia.net c.evidon.com tag.demandbase.com t.contentsquare.net iabmap.evidon.com https://*.dropbox.com https://*.dropboxstatic.com tags.tiqcdn.com/utag/dropbox/ tags.tiqcdn.com/utag/tiqapp/ https://cfl.dropboxstatic.com/static/pithos/lang/ https://www.knotch-cdn.com/ktag/latest/ktag.min.js https://aq-swa-api.knotch.it/ https://units.knotch.it/ &#x27;self&#x27; &#x27;unsafe-eval&#x27; &#x27;unsafe-inline&#x27; ;media-src blob: &#x27;self&#x27; data: embedwistia-a.akamaihd.net *.wistia.com *.wistia.net videos.ctfassets.net;font-src &#x27;self&#x27; data: *.wistia.com;img-src &#x27;self&#x27; embedwistia-a.akamaihd.net www.google-analytics.com https://scripts.demandbase.com/ https://c.contentsquare.net/ images.ctfassets.net downloads.ctfassets.net videos.ctfassets.net c.evidon.com l.evidon.com *.wistia.com *.wistia.net www.youtube.com dpiprodesntls.112.2o7.net match.prod.bidr.io id.rlcdn.com segments.company-target.com data:;frame-src https://consent.dropbox.com &#x27;self&#x27; www.youtube.com fast.wistia.com fast.wistia.net https://s.company-target.com;worker-src blob: &#x27;self&#x27;;prefetch-src &#x27;self&#x27;;connect-src &#x27;self&#x27; platform.cloud.coveo.com embedwistia-a.akamaihd.net *.litix.io *.wistia.com www.youtube.com images.ctfassets.net videos.ctfassets.net sessions.bugsnag.com notify.bugsnag.com configs.knotch.com optoutapi.evidon.com https://www.google-analytics.com https://www.dropbox.com https://cfl.dropboxstatic.com/static/pithos/lang/ https://c.contentsquare.net/ https://cognito-identity.us-east-1.amazonaws.com api.company-target.com https://preview.contentful.com https://aq-swa-api.knotch.it/ dpiprodesntls.112.2o7.net https://tag-logger.demandbase.com https://*.dropbox.com/log/ux_analytics https://ryojru1h6h.execute-api.us-east-1.amazonaws.com;"/><script src="https://www.dropbox.com/pithos/ux_analytics" async="" defer=""></script><meta name="viewport" content="width=device-width"/><meta charSet="utf-8"/><title data-testid="Head-title">Dropbox training and self-guided courses | Dropbox learn</title><link rel="preconnect" href="https://dropbox.com"/><link rel="preload" href="/fonts/SharpGroteskDBMedium20.woff2" as="font" crossorigin="" type="font/woff2"/><link rel="preload" href="/fonts/SharpGroteskDBMedium22.woff2" as="font" crossorigin="" type="font/woff2"/><link rel="preload" href="/fonts/SharpGroteskDBBook20.woff2" as="font" crossorigin="" type="font/woff2"/><link rel="preload" href="/fonts/AtlasGrotesk-Regular.woff2" as="font" crossorigin="" type="font/woff2"/><link rel="preload" href="/fonts/AtlasGrotesk-Medium.woff2" as="font" crossorigin="" type="font/woff2"/><meta property="og:title" content="Dropbox training and self-guided courses | Dropbox learn"/><meta property="og:description" content="Learn how to use Dropbox. Browse our catalog of free self-guided courses and virtual instructor led training sessions. Start a Dropbox training course today."/><meta name="twitter:title" content="Dropbox training and self-guided courses | Dropbox learn"/><meta name="twitter:description" content="Learn how to use Dropbox. Browse our catalog of free self-guided courses and virtual instructor led training sessions. Start a Dropbox training course today."/><meta name="robots" content="index,follow"/><meta name="canonical" content="https://learn.dropbox.com"/><meta name="description" content="Learn how to use Dropbox. Browse our catalog of free self-guided courses and virtual instructor led training sessions. Start a Dropbox training course today."/><meta name="content_type" content="pageLanding"/><link href="https://learn-stage.dropbox.com/fr" rel="alternate" hrefLang="fr"/><link href="https://learn-stage.dropbox.com/de" rel="alternate" hrefLang="de"/><link href="https://learn-stage.dropbox.com/it" rel="alternate" hrefLang="it"/><link href="https://learn-stage.dropbox.com/ja" rel="alternate" hrefLang="ja"/><link href="https://learn-stage.dropbox.com/pt-br" rel="alternate" hrefLang=.... Truncated ....
```

**Extra Information**

**Extracted results:**

- 05.626
- 36140
- 14557
- 58102
- 90281
- 10.688
- 59.534
- 274130
- 21.131
- 98013
- 42.542
- 14832
- 35.942
- 38.187
- 49.264
- 45.302
- 38.955
- 34.083
- 42.969
- 42902
- 04.465
- 02.067
- 58.711
- 20.343
- 163-01
- 41.914
- 59.504
- 36.034
- 32.467
- 49.765
- 660789
- 18961
- 29801183
- 75464
- 28.521
- 452335
- 41.417
- 2023-11-27
- 07.075
- 58.250
- 07888
- 631815
- 34.022
- 42.613
- 11.717
- 2023-10-02
- 13592
- 15.635
- 11.765
- 36.052
- 04.979
- 2021-11-05
- 170465
- 50.689
- 50.776
- 04.481
- 52.490
- 93779214
- 24.675
- 05.102
- +1-888-888-8888
- 56.957
- 42.434
- 35.518
- 2021-02-11
- 2022-10-13
- 3120151
- 097137
- 2023-09-26
- 383478219
- 23.702
- 11.718
- 17.683
- 16.992
- 59.556
- 87706
- 2021-02-17
- 55.419
- 19.643
- 31462
- 31.974
- 2023-10-06
- 44.628
- 2023-11-16
- 30.266
- 469790867
- 04.947
- 76903
- 2023-11-30
- 23.331
- 46.830
- 67326
- 54.554
- 22.970
- 07.438
- 09908
- 31.578
- 101336
- 5544973
- 31.331
- 25.726
- 54.548
- 46695
- 34951
- 29.288
- 10.712
- 14894
- 40.030
- 55790
- 04.088
- 23.305
- 26799
- 23584
- 12.070
- 26.972
- 22.879
- 05.852
- 2023-11-15
- 14427
- 30603
- 57.058
- 08.259
- 14831
- 565820
- 19179
- 35.350



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.67 Safari/537.36' 'https://learn-stage.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)