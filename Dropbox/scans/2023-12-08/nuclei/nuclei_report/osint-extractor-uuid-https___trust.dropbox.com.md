### OSINT Extração de UUID (osint-extractor-uuid) found on https://trust.dropbox.com

----
**Details**: **osint-extractor-uuid** matched at https://trust.dropbox.com

**Protocol**: HTTP

**Full URL**: https://trust.dropbox.com

**Timestamp**: Sat Dec 9 00:01:43 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | OSINT Extração de UUID |
| Authors | mrcl0wn / osint brazuca |
| Tags | uuid, consulta, osint |
| Severity | info |
| Description | Extração de UUID via expressão regular |

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

- a1106706-af0c-41ce-b15c-35147a721b41
- d78e37b4-3cb3-4588-b1e3-a976e2bfc730
- ff5fc564-d713-4e3c-98a6-0318490fde65
- 1f0bd979-1753-4816-b548-b08c79caa697
- 3715f476-6732-4dff-a174-d09ba7025191
- 3c238e7b-c522-450f-86be-12372ff0b0d4
- e01f428e-70c8-4460-9d40-7229aea984ab
- 382f924d-54f3-43a8-a9df-c39e6c959958
- f4951085-df2e-4fac-9d43-60b796478b2e
- 0d553957-8301-444e-a66f-3a7715270242
- 2295dac0-4666-4503-8305-18da8472661f
- 6f1a7448-fb4d-4d7e-895f-2beb1c49564c
- 6f99a885-6c87-42f0-bf97-69a281edde17
- 9d9c6a4d-f335-4a92-ad43-ab4aae24bf0e
- 9ee7eb7d-253e-4372-85fb-34017d46f92e
- 45220873-6e51-4dbb-b1b1-37d66ee9ef95
- 7bfa66da-33ab-49de-8391-e329738a1ae9
- 176a2871-a5a2-4c04-974f-d88be6486c55
- 4f5e1d9d-df3a-4fe4-9642-30ecbd6de704
- ae049d80-d542-4ddc-bb4f-9adf6c1eaf66
- c669d178-0855-495c-9ca9-3e5546c7727b
- 0f25c6f9-ffe7-4cc7-97de-7d784ba1f96f
- 3ed0e483-a60b-44b4-9920-3a200e691d19
- 64c9680b-ef79-4c92-baa0-13b541954bef
- ad55ffde-2431-4f72-b8cf-fbe7c37b83f3
- ef061e5b-a2f4-469e-92bc-ab973e3d7842
- 835dbfe0-47b2-48d0-9680-132765266574
- 092e78c8-b5c8-4428-ac96-c357c088ef66
- 5eeb9c41-2fc0-4961-aafb-3ac64badd8e1
- 919c72da-bcee-440f-bf74-487936712330
- f8feb4d4-b79d-47f3-9dd7-06c479a49dfe
- 4459b4a1-c6ee-446b-8dce-9d132e28c73f
- 26715457-a875-4de9-a848-a586aa08e8d9
- f7d895be-22d8-4c2c-bf38-ce09e8d1f4a0
- fc265e31-7459-4a4d-8c74-a648a134266b
- a0c2d606-48f6-4519-8db5-9029a98328d6
- ddee6fb4-ffcc-40bc-892c-ca344768d1ff
- 56583ca0-6561-4cf3-a150-8c0c45d214cf
- 6a6c21a3-9441-4222-953e-fa6d17a8c5a4
- 7945038b-bd78-4f1e-973f-371063be657a
- a5bb6b4d-c23b-4d4f-9da1-bedf5dc74ff5
- ebb9d0ce-15da-4d04-aadc-fe1cd5b827c6
- fa7a4923-3f51-431c-9eb6-3f88989ea858
- 2aafaddd-5329-45e2-a37e-cf6979191ad4
- 54c702e6-3bd6-496c-a8db-72de85317206
- 93bffca9-f4aa-4338-90fb-ae179376a6a2
- af119565-5dc2-4aec-bab6-21f9cf5ae315
- dc3faa9c-5613-4462-9bd8-121b965a6106
- f737ac65-fa6f-4918-954d-afefcc446461
- 80064615-c657-408c-8d94-2e5e96c4299e
- 92ff33fd-666e-49f9-8cc7-c8a3ba9fd4d7
- 38b62117-19f2-4e4e-b679-9421b66c114e
- 3a4ee4e4-b5b6-44d0-a530-abf7cadef428
- 4ea65d1e-79fb-47cf-95a8-bdb24d2d6a4b
- 98a98389-38a4-4205-9db9-821319f78044
- af8eb7bc-d4b7-4e13-a4b7-6f05e2744c22
- bd5d76c7-29b5-45c0-ad10-1413f6210538
- 4064ac33-7b48-407b-aed7-ce02971d1ec1
- 4b596933-d401-447e-ac9a-c752ff660221
- d04f3376-ffef-40fd-badb-d9b4d9e6b8ab
- ed9ba78d-8785-4345-9252-deb96405dd03
- fd95db16-e6d4-4ee7-9f24-038c6e13f81f
- 35332dc4-c893-4b2a-b032-bda1bcc9f77c
- 5b478567-b88b-4489-a822-d8d52dc767f2
- 63f59def-eb18-4135-95a1-addeb7463801
- 82bfe5ad-1b71-455d-98c3-8dc70c033318
- c4223a81-5840-4e11-ac9f-2b812794a67e
- d9b5efd5-6ec5-436d-8844-58658944869d
- e4e84d80-25cf-4c34-b518-d3e093f54f28
- 1fcaa8c0-7ef1-4e10-8b80-736a826c6b37
- 1a0dc64a-1178-440c-8a61-4d4d70c89ea2
- c9dbed6a-478e-416c-a180-d1d67ee669df
- cb8070bb-9efc-4a4f-a5c8-dd5cb6ab8ab4
- b05bcec1-da7e-4885-9603-a39fd73a1cdc
- b100824b-e986-45ec-861b-95d490dac04c
- 9acdbc12-55fe-409e-a6ab-4febbb90c8c0
- a26c76c4-6568-4a97-a75b-5cc628e0a407
- a8d0e8ff-4701-4d1c-a4bd-107c5351e890
- bb383d4c-2d21-426a-9c69-7a80a4d2fbb0
- 2a8c3762-0970-4a72-88cd-a86b29f9ef12
- 98c0e7d7-4916-4bdc-8f2a-519ef2a315f6
- 94db1991-6c00-43ba-8215-32828b3cd186
- 0a25420b-a29c-4544-900e-5b9e21c24818
- b62613cc-082d-49ea-bfa5-16362db4933f
- 4745c791-3414-4061-9b04-b516052b00f8
- 568cc045-e9e1-4296-ac6b-1dd0b56dd53a
- 6ea252c9-f877-470a-95c7-df4703d099c0
- 7103fdad-d6ac-45f6-b28d-e71f32884b7f
- 9162b815-d8af-49f2-8c26-4ddb72f42f48
- a6f735cc-ee1e-4026-94a5-5a4ea9538137
- 032f8803-47c0-4627-beeb-e5e72eef265c
- 2895b7a4-3e67-4740-be44-fbd30f21faef
- f8a6e2f1-82d6-4ec9-9836-4b737f74a89a



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2224.3 Safari/537.36' 'https://trust.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)