### Possible crypto addresses (long strings) extractor (extract-possible-crypto-addresses) found on https://mentoring.dropbox.com

----
**Details**: **extract-possible-crypto-addresses** matched at https://mentoring.dropbox.com

**Protocol**: HTTP

**Full URL**: https://mentoring.dropbox.com

**Timestamp**: Sat Dec 9 00:01:16 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Possible crypto addresses (long strings) extractor |
| Authors | cipher387 |
| Tags | osint, juicy-info, cryptocyrrency |
| Severity | info |
| Description | Extract possible crypto addresses (long strings) from web page body |

**Request**
```http
GET / HTTP/1.1
Host: mentoring.dropbox.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_2) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1944.0 Safari/537.36
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
Cache-Control: no-store
Content-Security-Policy: frame-ancestors teams.microsoft.com *.teams.microsoft.com 'self';
Content-Security-Policy-Report-Only: default-src 'none'; font-src 'self' data: https://d28ysuyw2f6yxp.cloudfront.net https://mentor-global-assets.chronus.com https://fonts.gstatic.com/ https://*.fontawesome.com https://chronus.com/ https://www.slant.co/ https://at.alicdn.com https://use.typekit.net https://zip.co/ https://github.com/google/fonts/blob/master/apache/opensans; img-src * data:; object-src 'self'; script-src 'self' 'unsafe-eval' 'unsafe-inline' data: https://d28ysuyw2f6yxp.cloudfront.net *.google-analytics.com *.googletagmanager.com https://ajax.googleapis.com *.pendo.io https://pendo-static-6184273133961216.storage.googleapis.com https://pendo-io-static.storage.googleapis.com https://js-agent.newrelic.com *.nr-data.net https://cdn.segment.com/ *.mxpnl.com https://mentor-global-assets.chronus.com; style-src 'self' 'unsafe-eval' 'unsafe-inline' data: https://d28ysuyw2f6yxp.cloudfront.net https://mentor-global-assets.chronus.com https://fonts.googleapis.com/ *.pendo.io https://pendo-static-6184273133961216.storage.googleapis.com; connect-src 'self' wss: data: *.nr-data.net *.google-analytics.com *.googletagmanager.com *.pendo.io https://pendo-static-6184273133961216.storage.googleapis.com https://api.segment.io/ https://cdn.segment.com/ *.mixpanel.com https://d28ysuyw2f6yxp.cloudfront.net; frame-src 'self' data: *; frame-ancestors teams.microsoft.com *.teams.microsoft.com 'self'; base-uri 'self'; form-action 'self'; child-src 'self' app.pendo.io; manifest-src 'self'; media-src 'self' data:; prefetch-src 'self' data: https://d28ysuyw2f6yxp.cloudfront.net; worker-src 'self'; report-uri /log_csp_violation
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 00:01:14 GMT
Etag: W/"430d13110ad358b425a83aaec0f0f18c"
Pragma: no-cache
Referrer-Policy: strict-origin-when-cross-origin
Set-Cookie: AWSALB=PEz2YGcCWySSObDUk+53GdcQ/tr1pWCbZjvgFHW5PzBvIZNdIpOkdXMxsFbbTs3TzfufuajSYhpHICaG7lY+wP2s7otlD8XPmsY6TekZ4E57go2V9SOBLiNMiI/b; Expires=Sat, 16 Dec 2023 00:01:14 GMT; Path=/
Set-Cookie: AWSALBCORS=PEz2YGcCWySSObDUk+53GdcQ/tr1pWCbZjvgFHW5PzBvIZNdIpOkdXMxsFbbTs3TzfufuajSYhpHICaG7lY+wP2s7otlD8XPmsY6TekZ4E57go2V9SOBLiNMiI/b; Expires=Sat, 16 Dec 2023 00:01:14 GMT; Path=/; SameSite=None; Secure
Set-Cookie: uniq_token=664112ba-6396-4072-8a79-e5820a6175fb; path=/; expires=Mon, 09 Dec 2024 00:01:14 GMT; Secure; HttpOnly
Set-Cookie: _mentor_session=bf4f108f3939daf4eb9eba84a6f2c944; domain=.dbxmentoring.chronus.com; path=/; secure; HttpOnly; SameSite=None
Status: 200 OK
Strict-Transport-Security: max-age=63072000
Vary: Accept-Encoding
Via: 1.1 a5527e17f7fd24342408a5722f47d30c.cloudfront.net (CloudFront)
X-Amz-Cf-Id: uGVqOXqHYHwkKZ0Cyw8A7X-cJMvXq5tDoWZNgrE9Bj2Ylc_tw17k8g==
X-Amz-Cf-Pop: MRS52-P1
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Frame-Options: SAMEORIGIN
X-Permitted-Cross-Domain-Policies: none
X-Request-Id: a50346dc-7a92-4a44-bf4e-530923c0b8b4
X-Robots-Tag: noindex
X-Runtime: 0.079130
X-Xss-Protection: 1; mode=block

<!DOCTYPE html>
<html lang="en" xml:lang="en" xmlns="https://www.w3.org/1999/xhtml">
  <head>
    
    <link rel="preconnect" href="https://d28ysuyw2f6yxp.cloudfront.net/" crossorigin/>
<link rel="preconnect" href="https://www.google-analytics.com/"/>
<link rel="preconnect" href="https://chronus-mentor.s3.amazonaws.com/"/>
<link rel="preconnect" href="https://mentor-global-assets.chronus.com/" crossorigin/>
<link rel="preconnect" href="https://mentor-global-assets.chronus.com/"/>
    <meta charset="utf-8">
<script type="text/javascript">window.NREUM||(NREUM={});NREUM.info={"beacon":"bam.nr-data.net","errorBeacon":"bam.nr-data.net","licenseKey":"fe0883d790","applicationID":"75707","transactionName":"Jg5cFUVcX1pSEUpXEAIAXAhNUkdfWA0WFxENDkU=","queueTime":1,"applicationTime":70,"agent":"","atts":"HkNHQw1IEWJFAgNeCwYuQAhQWl0UDUEKTAoAE0FDGxF8RFA8LHxAX1MKUwcfEWRYDwBLQF9DXA5DE19ZUAQAXEIMDxBNFWFWR0IGFkxPLCUQWxVSBgYEV1NcAUhWU1gFHgdXA1dIWgRRBB9UBAMKBAQAVVpaB1UQHEo="}</script>
<script type="text/javascript">(window.NREUM||(NREUM={})).init={privacy:{cookies_enabled:true},ajax:{deny_list:["bam.nr-data.net"]}};(window.NREUM||(NREUM={})).loader_config={xpid:"VgcAWV5ADwYHVFY=",licenseKey:"fe0883d790",applicationID:"75707"};;/*! For license information please see nr-loader-full-1.248.0.min.js.LICENSE.txt */
(()=>{var e,t,r={234:(e,t,r)=>{"use strict";r.d(t,{P_:()=>g,Mt:()=>v,C5:()=>s,DL:()=>A,OP:()=>S,lF:()=>R,Yu:()=>w,Dg:()=>m,CX:()=>c,GE:()=>x,sU:()=>j});var n=r(8632),i=r(9567);const a={beacon:n.ce.beacon,errorBeacon:n.ce.errorBeacon,licenseKey:void 0,applicationID:void 0,sa:void 0,queueTime:void 0,applicationTime:void 0,ttGuid:void 0,user:void 0,account:void 0,product:void 0,extra:void 0,jsAttributes:{},userAttributes:void 0,atts:void 0,transactionName:void 0,tNamePlain:void 0},o={};function s(e){if(!e)throw new Error("All info objects require an agent identifier!");if(!o[e].... Truncated ....
```

**Extra Information**

**Extracted results:**

- this.onAggregateImported
- hiddenOnLargeScreenInline-block
- ChrAnalyticsUtils.setDimensions
- mixpanelSuperProperties
- hero-unit-inner-content
- i._A.MutationObserver
- window.location.origin
- mixpanel.track_pageview
- .cui-skip-to-main-content-link
- unhandledPromiseRejection
- this.desiredFeatures.add
- --design-editor-canvas-image-height
- org_or_program_header_name
- language_selection_redirect_path
- data-terms-or-policy
- mentor-global-assets.chronus.com
- storeSupportabilityMetrics
- this.generateTraceHeader
- mentoring_area_new_ux_phase_one_data
- visibleOnLargeScreen
- d.traceContextParentHeader
- multiChoiceTypeOptionsLimit
- g.parentNode.insertBefore
- .distributed_tracing
- cjs-mobile-modal-cancel
- js-agent.newrelic.com
- commentsDisplayLimit
- fillAllFieldsToProceed
- allow_google_signals
- this.shouldImportAgg
- t.traceContextParentHeader
- visibleOnMobileInline
- visibleOnLargeScreenInline-block
- fillAppropriateValues
- Object.getPrototypeOf
- l._A.addEventListener
- this.generateTraceContextStateHeader
- hiddenOnTabInline-block
- newMessageNotification
- CustomDimensionsForEvent
- cors_use_tracecontext_headers
- this.sharedAggregator
- changeCurrentStateOfFilters
- document.createDocumentFragment
- document.createTextNode
- appearanceChannelStatus
- people.clear_charges
- f.getElementsByTagName
- hiddenOnMobileAndTabInline-block
- BAEKAAEALAAAAAABAAEAAAICTAEAOw
- chr-common-libraries-
- noDateForRepeatingSlot
- window.location.href
- my_programs_listing_link
- cjs-progress-banner-close-all
- session_replay.mask_input_option
- h.setCustomAttribute
- this.excludeNewrelicHeader
- this.useNewrelicHeaderForCors
- --design-editor-canvas-image-width
- exclude_newrelic_header
- hiddenOnWebInline-block
- hiddenOnMobileInline-block
- track_level_connection_status
- cjs-progress-status-list
- chronus-app-android-app-store.png
- .0.min.js.LICENSE.txt
- document.visibilityState
- visibleOnLargeScreenInline
- youHaveUnsavedChanges
- truncate-with-ellipsis
- cjs-datepicker-description
- xxx-yxxx-xxxxxxxxxxxx
- setApplicationVersion
- explicit_preference_configured
- chronus-app-overview-pages-style-guide--
- chronus-app-ios-app-store.png
- ...D.ajax.block_internal
- setApplicationVersion.
- s.parentNode.removeChild
- chatOnlineStatusCacheExpiryInMs
- cjs_sr_announcer_element
- session_replay.block_selector
- e.cors_use_tracecontext_headers
- program_logo_or_banner
- www.google-analytics.com
- f._A.MutationObserver
- this.agentIdentifier
- cjs_program_listing_dropdown
- cjs-terms-or-privacy-policy-modal-trigger
- pSEUpXEAIAXAhNUkdfWA0WFxENDkU
- extraSmallTimeFormat
- requiredFieldMissing
- cui-skip-to-main-content-link
- Ddbxmentoring.chronus.com
- Object.getOwnPropertyDescriptors
- Object.defineProperty
- d.traceContextStateHeader
- --program-header-img-height
- fullCalendarParamHash
- chat_room_or_sender_name
- ChrAnalyticsUtils.getPageUrl
- useNewrelicHeaderForCors
- hiddenOnMobileAndTab
- has_opted_out_tracking
- Object.prototype.hasOwnProperty.call
- h.setApplicationVersion
- o.traceContextParentHeader
- Array.prototype.slice.call
- cors_use_newrelic_header
- Object.prototype.hasOwnProperty
- generateTraceContextStateHeader
- contentTypeRestricted
- data-label-for-tracking
- img-responsive-block
- MKUwcfEWRYDwBLQF9DXA
- generateTracePayload
- rich_mail_experiment_data
- has_opted_in_tracking
- filter-loading-results
- window.addEventListener
- e.cors_use_newrelic_header
- base-jquery-libraries-c
- IEWJFAgNeCwYuQAhQWl0UDUEKTAoAE0FDGxF
- .state.sessionReplayMode
- dbxmentoring.chronus.com
- dIWgRRBB9UBAMKBAQAVVpaB
- this.useTraceContextHeadersForCors
- visibleOnMobileInline-block
- cjs_date_picker_for_profile_question
- datePickerTranslations
- minLimitGreaterThanMaxLimit
- Navigation.redirectOnLogoAndBannerClick
- addSameSiteNoneToCookies
- globalThis.navigator
- x.jsAttributes.isWorker
- excludeNewrelicHeader
- this.loadCaptureCalled
- cjs_ios_app_store_link
- visibleOnTabInline-block
- sidebar_logo_or_banner
- StepstoenableAJAX.pdf
- problemsPerformingOperation
- invalidEmailFormatError
- authenticate_in_teams_popup_window
- e.mask_input_options
- document.addEventListener
- useTraceContextHeadersForCors
- profileQuestionSeperator
- fullCalendarTranslations
- work_on_behalf_status
- h.setCurrentRouteName
- this.parsedOrigin.sameOrigin
- visibleOnWebInline-block
- chooseFutureAvailability
- ChrAnalytics.subscribe
- clear_opt_in_out_tracking
- session_replay.mask_selector
- this.desiredFeatures
- chronus_header_wrapper
- 9ZUAQAXEIMDxBNFWFWR0IGFkxPLCUQWxVSBgYEV
- generateTraceContextParentHeader
- n.traceContextParentHeader
- removeEventListener-end
- cjs_program_name_in_header
- window.document.documentMode
- cjs_programs_listing_header
- TermsAndPolicy.handleTermsAndPolicyForNonLoggedinPages
- addEventListener-end
- hiddenOnLargeScreenInline
- cjs_side_navigation_logo_or_banner
- sideBarLeftPlaceholder
- cui-powered-by-label
- MIXPANEL_CUSTOM_LIB_URL
- privacy.cookies_enabled
- a.generateTracePayload
- dateRangePickerForProfileQuestion
- this.shouldGenerateTrace
- o.traceContextStateHeader
- allow_ad_personalization_signals
- sk-spinner-double-bounce
- ...this.desiredFeatures
- monthNamesInDefaultLocale
- page_loading_result_id
- no-horizontal-padding
- --logo-or-banner-max-width
- hiddenOnMobileInline
- endDateBeforeStartDate
- www.googletagmanager.com
- cjs_mobile_programs_pane
- background-position-y
- e.exclude_newrelic_header
- this.importAggregator
- iBgdoJZEjQKTgYTpZgCTYQ
- n._A.removeEventListener
- t.traceContextStateHeader
- calendarTranslations
- ChrAnalyticsUtils.setDimensionMapping
- n._A.addEventListener
- r.pathname.startsWith
- hiddenOnMobileAndTabInline
- current_path_for_quick_access
- tooManyRequestsDelay
- e.removeEventListener
- r.allowed_origins.length
- noMeridiemTimeFormat
- org_level_connection_status
- document.createElement
- session_trace.enabled
- meetingSlotTimeinMinutes
- trackingCodes.forEach
- cjs_android_play_store_link
- document.head.appendChild
- this.isAllowedOrigin
- page_loading_results
- document.getElementsByTagName
- this.generateTraceContextParentHeader
- jsCommonTranslations
- OverViewPage.updatePlayStoreLink



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_2) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1944.0 Safari/537.36' 'https://mentoring.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)