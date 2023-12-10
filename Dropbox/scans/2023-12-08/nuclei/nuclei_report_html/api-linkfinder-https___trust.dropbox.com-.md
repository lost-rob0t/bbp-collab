### API Recon (api-linkfinder:relative_links) found on https://trust.dropbox.com

----
**Details**: **api-linkfinder:relative_links** matched at https://trust.dropbox.com

**Protocol**: HTTP

**Full URL**: https://trust.dropbox.com

**Timestamp**: Sat Dec 9 00:01:42 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | API Recon |
| Authors | nullenc0de |
| Tags | file |
| Severity | info |

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

- /_next/static/chunks/9314-98ffd26a7ed4cab
- com/css
- /_next/static/chunks/framework-64bcb7c567f48ca
- /_next/static/chunks/main-62ca16aaca3ac0f
- /_next/static/chunks/5314-16edfb8b71bad9dd
- //securityheaders
- //app
- io/api/share/835dbfe0-47b2-48d0-9680-132765266574/logo_og
- /_next/static/css/5458cdd3c66c8be
- com/sundance
- com/lonelyplanet
- image/png
- //status
- io/trust-center?utm_source=app&amp;utm_medium=web&amp;utm_content=sp_footer&amp;utm_date=231209&amp;utm_campaign=835dbfe0-47b2-48d0-9680-132765266574
- com/2kD35t4g
- //fonts
- /_next/static/chunks/1579-9c51320de
- com/ai-principles
- com/acceptable_use
- //3fbff9fa2e9e4c6991906aa26710df
- /_next/static/chunks/9003-3974cea0d3c70e
- /_next/static/chunks/3034-06253cd247561df
- /_next/static/chunks/7709-c7baf7ccf3a5dfac
- /_next/image?url=%2Fimages%2Fcertifications%2Fsoc.png&amp;w=128&amp;q=75
- /_next/static/chunks/2092-5c72d49feb99bd
- com/campaignmonitor
- application/json
- com/ssltest/analyze
- //logo
- com/transparency
- io/api/share/835dbfe0-47b2-48d0-9680-132765266574/favicon
- /_next/static/chunks/7010-a1865f537460653c
- /_next/static/ab7c9ffb1a47780993eba0478934ea103a82b1c8/_ssgManifest
- IDS/IPS
- image/x-icon
- /_next/static/chunks/8938-305a7993df8d
- //www
- com/security/privacy-policy-faq
- /_next/static/chunks/9325-51ba65533e49e
- //dropbox
- /images/certifications/ccpa
- /_next/image?url=%2Fimages%2Fcertifications%2Feu_us_dpf.png&amp;w=64&amp;q=75 1x, /_next/image?url=%2Fimages%2Fcertifications%2Feu_us_dpf.png&amp;w=128&amp;q=75 2x
- /_next/static/chunks/webpack-1fce48c46fa3e
- /_next/static/chunks/3592-8518f288022e3fa
- /_next/static/chunks/6693-a3c4decce5043b
- /_next/static/chunks/8100-78878bb3b1437d
- com/security/cookies
- com/documents/en/legal/dfb-data-processing-agreement
- /_next/static/chunks/2408-9f79e0afddf
- application/pdf
- com/dropbox
- com/security/supported-identity-providers
- //trust
- /_next/static/chunks/pages/_app-174f4b4c99dca51b
- /_next/static/chunks/28064ca8-29445a4535e
- /_next/static/chunks/ec5d7cc0-34c0236d2459579a
- //hstspreload
- use/access
- /cdn-cgi/challenge-platform/scripts/jsd/main
- //safebase
- data/indices
- //assets
- /_next/static/chunks/3222-abc43b6dc45bb9ee
- /_next/static/chunks/6771-44d6b8739e700b
- /api/share/835dbfe0-47b2-48d0-9680-132765266574/logo
- org/2000/svg
- com/privacy
- //help
- com/jamf
- //security
- /_next/static/chunks/3955-d3be8a1df7fe2cfe
- /_next/static/chunks/3431-53027e44bb65144a
- /_next/static/ab7c9ffb1a47780993eba0478934ea103a82b1c8/_buildManifest
- /images/safebase
- /_next/image?url=%2Fimages%2Fcertifications%2Feu_us_dpf.png&amp;w=128&amp;q=75
- com/terms
- /_next/static/chunks/3746-3ecdc7b9bdf8dc
- com/websec/www
- /_next/static/chunks/9136-8c63ffdba0570def
- /_next/static/chunks/pages/index-aefcfe08d097af
- com/gongchausa
- ISO/IEC
- /_next/static/css/705e1731ed9b3daf
- /_next/static/chunks/polyfills-c67a75d1b6f99dc
- /_next/static/chunks/1547-8b38d97bd246a02e
- /_next/static/chunks/2154-d9895cee3eb52e
- and/or
- /_next/static/css/b8afd5d51f53c19c
- /_next/static/chunks/382-a5dc848a1788f64a
- /images/certifications/gdpr
- /_next/image?url=%2Fimages%2Fcertifications%2Fsoc.png&amp;w=64&amp;q=75 1x, /_next/image?url=%2Fimages%2Fcertifications%2Fsoc.png&amp;w=128&amp;q=75 2x



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2224.3 Safari/537.36' 'https://trust.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)