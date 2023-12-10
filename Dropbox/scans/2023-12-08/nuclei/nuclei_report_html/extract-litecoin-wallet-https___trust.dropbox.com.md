### Litecoin wallets addresses extractor (extract-litecoin-wallet) found on https://trust.dropbox.com

----
**Details**: **extract-litecoin-wallet** matched at https://trust.dropbox.com

**Protocol**: HTTP

**Full URL**: https://trust.dropbox.com

**Timestamp**: Sat Dec 9 00:01:44 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Litecoin wallets addresses extractor |
| Authors | cipher387 |
| Tags | osint, juicy-info, cryptocyrrency |
| Severity | info |
| Description | Extract litecoin wallets addresses from web page body |

**Request**
```http
GET / HTTP/1.1
Host: trust.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2224.3 Safari/537.36
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
Cache-Control: private, no-cache, no-store, max-age=0, must-revalidate
Cf-Cache-Status: DYNAMIC
Cf-Ray: 8328f99bde2c9a0c-FRA
Content-Security-Policy: connect-src 'self' https://app.safebase.io https://*.google-analytics.com https://*.analytics.google.com https://analytics.google.com https://adservice.google.com https://stats.g.doubleclick.net https://api-js.mixpanel.com https://*.ingest.sentry.io https://storage.googleapis.com https://api-segment.safebase.io https://cdn-segment.safebase.io https://api.intercom.io https://api-iam.intercom.io https://api-ping.intercom.io https://nexus-websocket-a.intercom.io https://nexus-websocket-b.intercom.io wss://nexus-websocket-a.intercom.io wss://nexus-websocket-b.intercom.io https://uploads.intercomcdn.com https://uploads.intercomusercontent.com https://app.vitally.io https://api.vitally.io https://z9uyl8uax6-dsn.algolia.net https://z9uyl8uax6-1.algolianet.com https://z9uyl8uax6-2.algolianet.com https://z9uyl8uax6-3.algolianet.com https://connect.useparagon.com https://zeus.useparagon.com https://api.useparagon.com https://auth.split.io https://sdk.split.io https://streaming.split.io https://events.split.io https://telemetry.split.io https://auth-split.safebase.io https://events-split.safebase.io https://sdk-split.safebase.io https://streaming-split.safebase.io https://telemetry-split.safebase.io https://uploads.userpilot.io https://api.userpilot.io wss://api.userpilot.io https://find.userpilot.io https://find-x.userpilot.io https://find-y.userpilot.io https://find-z.userpilot.io https://find-w.userpilot.io wss://analytex.userpilot.io wss://analytex-us.userpilot.io wss://analytex-eu.userpilot.io wss://analytex-in.userpilot.io https://analytex.userpilot.io https://analytex-us.userpilot.io https://analytex-eu.userpilot.io https://analytex-in.userpilot.io https://reporting.userpilot.io wss://reporting.userpilot.io https://playground.userpilot.io https://consent.api.osano.com https://tattle.api.osano.com https://cmp.osano.com https://disclosure.api.osano.com https://embed.explo.co https://api.explo.co https://data.explo.co https://data1.explo.co https://analytics.explo.co https://api.statsig.com https://autocomplete.clearbit.com https://api.us.flatfile.io wss://api.us.flatfile.io https://canny.io https://api.canny.io https://edge.fullstory.com https://rs.fullstory.com https://www.loom.com https://*.hubspot.com https://*.hsforms.com https://*.hsforms.net https://*.hscollectedforms.net https://*.hubapi.com https://js.hs-banner.com https://js.hs-scripts.com https://js.hsleadflows.net https://js.hubspotfeedback.com https://js.hsadspixel.net;img-src 'self' blob: data: https://app.safebase.io https://s.gravatar.com https://*.googleusercontent.com https://*.wp.com https://img.icons8.com https://storage.googleapis.com/public.safebase.co/ https://www.google.com https://*.google-analytics.com https://www.googletagmanager.com https://www.gstatic.com https://www.google.ca https://www.google.ie https://stats.g.doubleclick.net https://analytics.google.com https://px.ads.linkedin.com https://px4.ads.linkedin.com https://p.adsymptotic.com https://js.intercomcdn.com https://static.intercomassets.com https://downloads.intercomcdn.com https://uploads.intercomusercontent.com https://gifs.intercomcdn.com  https://video-messages.intercomcdn.com https://messenger-apps.intercom.io https://*.intercom-attachments-5.com https://*.intercom-attachments-6.com https://*.intercom-attachments-9.com https://media.userpilot.io https://uploads.userpilot.io https://gifs.userpilot.io https://videos.userpilot.io https://logo.clearbit.com https://platform.securityscorecard.io https://rs.fullstory.com https://app.livestorm.co https://*.hsforms.com https://*.hsforms.net https://*.hubspot.com https://www.facebook.com/tr/;script-src 'self' 'report-sample' 'nonce-+2d5QoKiVVjQFy1jtQ7YWA==' 'strict-dynamic' https://app.safebase.io https://cdn-segment.safebase.io https://cdn.mxpnl.com https://*.google-analytics.com https://www.gstatic.com https://www.google.com https://www.googletagmanager.com https://embed.explo.co https://app.intercom.io https://widget.intercom.io https://js.intercomcdn.com https://cdn.vitally.io https://cdn.useparagon.com https://js.userpilot.io https://deploy.userpilot.io https://consent.api.osano.com https://tattle.api.osano.com https://cmp.osano.com https://disclosure.api.osano.com https://canny.io https://edge.fullstory.com https://rs.fullstory.com https://js.hs-analytics.net https://js.hs-banner.com https://*.hs-scripts.com https://static.hsappstatic.net https://js.hscollectedforms.net https://*.usemessages.com https://forms.hsforms.com https://js.hs-banner.com https://js.hs-scripts.com https://js.hsleadflows.net https://js.hubspotfeedback.com https://js.hsadspixel.net https://*.hscollectedforms.net https://app.svix.com;manifest-src 'self';media-src https://js.intercomcdn.com https://js.userpilot.io;default-src 'self';child-src 'self' blob: https://intercom-sheets.com https://www.intercom-reporting.com  https://www.youtube.com https://player.vime.... Truncated ....
```

**Extra Information**

**Extracted results:**

- ME1qazFaVEk1TUMxbE9HRTRMVFJpWm1ZdF



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2224.3 Safari/537.36' 'https://trust.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)