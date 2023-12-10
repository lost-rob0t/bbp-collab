### Allowed Options Method (options-method) found on https://investors.dropbox.com

----
**Details**: **options-method** matched at https://investors.dropbox.com

**Protocol**: HTTP

**Full URL**: https://investors.dropbox.com

**Timestamp**: Sat Dec 9 10:41:11 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Allowed Options Method |
| Authors | pdteam |
| Tags | misc, generic |
| Severity | info |

**Request**
```http
OPTIONS / HTTP/1.1
Host: investors.dropbox.com
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
Allow: GET, POST
Cache-Control: private, no-cache, must-revalidate
Content-Language: en
Content-Security-Policy: default-src 'self' bam-cell.nr-data.net bam.nr-data.net cm.everesttech.net thomsonreuterscorporategroupweb.sc.omtrdc.net *.demdex.net www.google-analytics.com www.googletagmanager.com www.adobetag.com *.facebook.net api.nasdaqomx.wallst.com www.google.com *.addthis.com *.addthisedge.com www.googleadservices.com thomsonreuterscorporategroupweb.d2.sc.omtrdc.net stats.g.doubleclick.net *.sharethis.com *.pixel.parsely.com www.recaptcha.net www.gstatic.com c212.net pixel.mathtag.com *.kscope.io *.globenewswire.com *.accesswire.com *.businesswire.com *.prnewswire.com *.c212.net *.youtube.com *.vimeo.com *.media-server.com ds-aksb-a.akamaihd.net media.corporate-ir.net *.unisonir.com http://cloudinary.com *.segment.com uninav.notified.com www.facebook.com *.dropbox.com; connect-src 'self' *.uni.wdc.west.com *.sharethis.com *.unisonir.com *.demdex.net bam-cell.nr-data.net bam.nr-data.net api.segment.io thomsonreuterscorporategroupweb.sc.omtrdc.net *.akamaihd.net uninav.notified.com *.kscope.io; font-src 'self' fonts.googleapis.com cloud.typography.com fonts.gstatic.com uninav.notified.com stackpath.bootstrapcdn.com *.kscope.io cdn.jsdelivr.net; frame-src 'self' s7.addthis.com tools.eurolandir.com www.google.com *.sharethis.com api.nasdaqomx.wallst.com *.demdex.net www.recaptcha.net cloudinary.com https://player.cloudinary.com http://login.notified.com https://www.slideshare.net https://consent.dropbox.com/ https://www.dropbox.com https://www.youtube.com/ *.facebook.com; object-src 'self'; script-src 'self' 'unsafe-inline' 'unsafe-eval' *.recaptcha.net js-agent.newrelic.com *.jquery.com *.gstatic.com bam-cell.nr-data.net bam.nr-data.net *.akamaihd.net uninav.notified.com assets.adobedtm.com https://media-library.cloudinary.com https://uninav.notified.com https://upload-widget.cloudinary.com https://www.google.com www.google.com; script-src-elem 'self' 'unsafe-inline' *.uni.wdc.west.com s7.addthis.com www.google.com www.googletagmanager.com www.google-analytics.com siteimproveanalytics.com cdn.parsely.com www.adobetag.com www.recaptcha.net www.gstatic.com *.sharethis.com ds-aksb-a.akamaihd.net sec.kscope.io *.unisonir.com js-agent.newrelic.com bam-cell.nr-data.net bam.nr-data.net code.jquery.com cdn.segment.com *.pendo.io *.notified.com intrado.kscope.io www.dropbox.com connect.facebook.net *.kscope.io cfl.dropboxstatic.com assets.adobedtm.com https://media-library.cloudinary.com https://uninav.notified.com https://upload-widget.cloudinary.com https://www.google.com; style-src 'self' 'unsafe-inline' uninav.notified.com fonts.googleapis.com https://uninav.notified.com maxcdn.bootstrapcdn.com stackpath.bootstrapcdn.com https://cdn.jsdelivr.net; style-src-elem 'self' 'unsafe-inline' fonts.googleapis.com *.uni.wdc.west.com *.sharethis.com www.google.com ajax.googleapis.com sec.kscope.io *.unisonir.com www.gstatic.com stackpath.bootstrapcdn.com maxcdn.bootstrapcdn.com https://uninav.notified.com *.pendo.io intrado.kscope.io *.kscope.io https://cdn.jsdelivr.net; form-action 'self' *.dropbox.com *.facebook.com; frame-ancestors 'self' www.dropbox.com
Content-Type: text/html; charset=UTF-8
Date: Sat, 09 Dec 2023 10:41:11 GMT
Expect-Ct: max-age=0, report-uri="/report-expect-ct-violation"
Expires: Sat, 09 Dec 2023 10:41:11 GMT
Feature-Policy: accelerometer 'none';ambient-light-sensor 'none';autoplay 'self';camera 'none';encrypted-media 'none';fullscreen *;geolocation 'self';gyroscope 'none';magnetometer 'none';microphone 'none';midi 'none';payment 'none';picture-in-picture 'none';speaker 'self';sync-xhr 'self';usb 'none';vibrate 'none';vr 'none'
From-Origin: same
Referrer-Policy: strict-origin-when-cross-origin
Strict-Transport-Security: max-age=31536000
Vary: Accept-Encoding
Via: 1.1 8ef3b122b1955c9b50019a917f1a6a58.cloudfront.net (CloudFront)
X-Age: 0
X-Amz-Cf-Id: Ks0AZj8sSDc_yZ70x9Dv5UYceM6DW9PgERCAzHroYeXT_ePSGe4BPA==
X-Amz-Cf-Pop: CDG52-P6
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Request-Id: v-783de5d6-967f-11ee-a388-37abc0761b98
X-Ua-Compatible: IE=edge
X-Xss-Protection: 1; mode=block


```

**Extra Information**

**Extracted results:**

- GET, POST



**CURL command**
```sh
curl -X 'OPTIONS' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.67 Safari/537.36' 'https://investors.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)