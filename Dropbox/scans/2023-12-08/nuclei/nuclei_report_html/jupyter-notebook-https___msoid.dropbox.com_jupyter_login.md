### Jupyter Notebook (jupyter-notebook) found on https://msoid.dropbox.com

----
**Details**: **jupyter-notebook** matched at https://msoid.dropbox.com

**Protocol**: HTTP

**Full URL**: https://msoid.dropbox.com/jupyter/login

**Timestamp**: Sat Dec 9 15:41:49 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Jupyter Notebook |
| Authors | hakimkt, arafatansari |
| Tags | panel, jupyter, notebook, exposure |
| Severity | info |
| Description | JupyterHub is an open source tool that lets you host a distributed Jupyter Notebook environment.<br> |
| shodan-query | http.html:"JupyterHub" |

**Request**
```http
GET /jupyter/login HTTP/1.1
Host: msoid.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.67 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Cache-Control: no-store, no-cache
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 15:41:49 GMT
Expires: -1
Link: <https://aadcdn.msauth.net>; rel=preconnect; crossorigin
Link: <https://aadcdn.msauth.net>; rel=dns-prefetch
Link: <https://aadcdn.msftauth.net>; rel=dns-prefetch
P3p: CP="DSP CUR OTPi IND OTRi ONL FIN"
Pragma: no-cache
Set-Cookie: fpc=AhOvNzuds9JFh6sluqElQMc; expires=Mon, 08-Jan-2024 15:41:49 GMT; path=/; secure; HttpOnly
Set-Cookie: esctx=PAQABAAEAAAAmoFfGtYxvRrNriQdPKIZ-jHALvEesTt5HeBc7IHtHThVNtJx_9G_gZwWjaFxdMZS7hqLp_RN0i5_7k932G0BZ36o5Y2moIFvyF-UX2v_0SEd87XQRan4HCEiOJoMYtNwbg7WVplpTkHao1EssM0UkLpUKgvm9wpPv_X5XFbORcSjBoTdyXsWe2Yd-qB6sFwogAA; domain=.msoid.dropbox.com; path=/; secure; HttpOnly
Set-Cookie: x-ms-gateway-slice=estsfd; path=/; secure; httponly
Set-Cookie: stsservicecookie=estsfd; path=/; secure; httponly
Vary: Accept-Encoding
X-Content-Type-Options: nosniff
X-Dns-Prefetch-Control: on
X-Ms-Ests-Server: 2.1.16878.5 - NEULR1 ProdSlices
X-Ms-Request-Id: dbd5aafe-a851-4f48-a7b3-d721005f0c00
X-Xss-Protection: 0



<!-- Copyright (C) Microsoft Corporation. All rights reserved. -->
<!DOCTYPE html>
<html dir="ltr" class="" lang="en">
<head>
    <title>Sign in to your account</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=2.0, user-scalable=yes">
    <meta http-equiv="Pragma" content="no-cache">
    <meta http-equiv="Expires" content="-1">
    <link rel="preconnect" href="https://aadcdn.msauth.net" crossorigin>
<meta http-equiv="x-dns-prefetch-control" content="on">
<link rel="dns-prefetch" href="//aadcdn.msauth.net">
<link rel="dns-prefetch" href="//aadcdn.msftauth.net">

    <meta name="PageID" content="ConvergedError" />
    <meta name="SiteID" content="" />
    <meta name="ReqLC" content="9" />
    <meta name="LocLC" content="en" />

        <meta name="referrer" content="origin" />

        <meta name="format-detection" content="telephone=no" />

    <noscript>
        <meta http-equiv="Refresh" content="0; URL=" />
    </noscript>

    
    
<meta name="robots" content="none" />

<script type="text/javascript">//<![CDATA[
$Config={"iErrorDesc":0,"iErrorTitle":0,"strMainMessage":"We received a bad request.","strAdditionalMessage":"","strServiceExceptionMessage":"AADSTS900561: The endpoint only accepts POST requests. Received a GET request.","strTraceId":"dbd5aafe-a851-4f48-a7b3-d721005f0c00","iErrorCode":900561,"iHttpErrorCode":400,"iViewId":1,"urlCancel":"","strTimestamp":"2023-12-09T15:41:49Z","fShowIssuerHintErrorStrings":true,"urlLearnMoreRiskyApp":"https://go.microsoft.com/fwlink/?linkid=2133457","oResumePostParams":{},"iMaxStackForKnockoutAsyncComponents":10000,"fShowButtons":true,"urlCdn":"https://aadcdn.msauth.net/shared/1.0/","urlDefaultFavicon":"https://aadcdn.msauth.net/shared/1.0/content/images/favicon_a_eupayfgghqiai7k9sol6lg2.ico","urlFooterTOU":"https://www.microsoft.com/en/servicesagreement/","urlFooterPrivacy":"https://privacy.microsoft.com/en/privacystatement","iPawnIcon":0,"sPOST_Username":"","sFTName":"flowToken","dynamicTenantBranding":null,"staticTenantBranding":null,"oAppCobranding":{},"iBackgroundImage":2,"fApplicationInsightsEnabled":false,"iApplicationInsightsEnabledPercentage":0,"urlSetDebugMode":"https://login.windows.net/common/debugmode","fEnableCssAnimation":true,"fAllowGrayOutLightBox":true,"fIsRemoteNGCSupported":true,"desktopSsoConfig":{"isEdgeAnaheimAllowed":true,"iwaEndpointUrlFormat":"https://autologon.microsoftazuread-sso.com/{0}/winauth/sso?client-request-id=8314bfbe-b271-43f4-82db-de7efb2949c9","iwaSsoProbeUrlFormat":"https://autologon.microsoftazuread-sso.com/{0}/winauth/ssoprobe?client-request-id=8314bfbe-b271-43f4-82db-de7efb2949c9","iwaIFrameUrlFormat":"https://autologon.microsoftazuread-sso.com/{0}/winauth/iframe?client-request-id=8314bfbe-b271-43f4-82db-de7efb2949c9\u0026isAdalRequest=False","iwaRequestTimeoutInMs":10000,"startDesktopSsoOnPageLoad":false,"progressAnimationTimeout":10000,"isEdgeAllowed":false,"minDssoEdgeVersion":"17","isSafariAllowed":true,"redirectUri":"","isIEAllowedForSsoProbe":true,"edgeRedirectUri":"https://autologon.microsoftazuread-sso.com/common/winauth/sso/edgeredirect?client-request-id=8314bfbe-b271-43f4-82db-de7efb2949c9\u0026origin=login.windows.net\u0026is_redirected=1","isFlowTokenPassedInEdge":true},"iSessionPullType":2,"uiflavor":1001,"fOfflineAccountVisible":false,"fEnableUserStateFix":true,"fShowAccessPassPeek":true,"fUpdateSessionPollingLogic":true,"fEnableShowPickerCredObservable":true,"fFetchSessionsSkipDsso":true,"fUseNonMicrosoftDefaultBrandingForCiam":true,"fMergeComplexBrandingProperties":true,"fUseAltText":true,"fRemoveCustomCss":true,"fAddRtlCustomCssSupport":true,"fFixLightboxHeaderMargin":true,"fFixUICrashForApiRequestHandler":true,"fDeprecateBrandingProperties":true,"fFixDynamicTenantBranding":true,"fShowUpdatedKoreanPrivacyFooter":tr.... Truncated ....
```

References: 
- https://www.exploit-db.com/ghdb/7970

**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.67 Safari/537.36' 'https://msoid.dropbox.com/jupyter/login'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)