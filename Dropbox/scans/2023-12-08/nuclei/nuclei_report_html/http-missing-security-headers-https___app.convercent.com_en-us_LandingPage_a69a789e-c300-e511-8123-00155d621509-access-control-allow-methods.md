### HTTP Missing Security Headers (http-missing-security-headers:access-control-allow-methods) found on https://integrity.dropbox.com

----
**Details**: **http-missing-security-headers:access-control-allow-methods** matched at https://integrity.dropbox.com

**Protocol**: HTTP

**Full URL**: https://app.convercent.com/en-us/LandingPage/a69a789e-c300-e511-8123-00155d621509

**Timestamp**: Sat Dec 9 14:55:18 +0000 UTC 2023

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
Host: integrity.dropbox.com
User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/55.0.2919.83 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Cache-Control: private
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 14:55:17 GMT
Set-Cookie: ApplicationGatewayAffinityCORS=51409ad02208160ab3b747af3242ec74; Path=/; SameSite=None; Secure
Set-Cookie: ApplicationGatewayAffinity=51409ad02208160ab3b747af3242ec74; Path=/
Set-Cookie: ASP.NET_SessionId=k5zitgqtbiiks45nrkoup22o; path=/; secure; HttpOnly; SameSite=Lax
Set-Cookie: ASP.NET_SessionId=k5zitgqtbiiks45nrkoup22o; path=/; secure; HttpOnly; SameSite=Lax
Set-Cookie: __RequestVerificationToken=fUHkXvnwgoOeZPfThLOWwjuUi7m0tY-Vh57NVQ8HAngznTy2KSdp9O5dYl56kMi4XhdqzpI2_C9qGWbWXhMSv6_6NootcavqBXeO2Qox2kY1; path=/; secure; HttpOnly
Strict-Transport-Security: max-age=86400;includeSubDomains
Vary: Accept-Encoding
X-Frame-Options: SAMEORIGIN
X-Frame-Options: SAMEORIGIN
X-Ua-Compatible: IE=Edge



<!DOCTYPE html>
<html lang="en">
<head "">
	
<!-- OneTrust Cookies Consent Notice start -->
<script src="https://cdn.cookielaw.org/scripttemplates/otSDKStub.js" data-document-language="true" type="text/javascript" charset="UTF-8" data-domain-script="303afb82-bcff-4a9c-a161-ee881fe4485e"></script>
<script type="text/javascript">
	function OptanonWrapper() { }
</script>
<!-- OneTrust Cookies Consent Notice end -->

	<title>Dropbox Ethics &amp; Compliance Hotline - Powered by Convercent</title>
	<meta charset="utf-8" />
<meta http-equiv="pragma" content="no-cache" />
<meta http-equiv="expires" content="12/9/2022 2:55:17 PM" />
<meta http-equiv="cache-control" content="private, max-age=1, no-cache, must-revalidate, proxy-revalidate, no-transform" />
<meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, shrink-to-fit=no, viewport-fit=cover" />
<meta name="description" content="" />
<meta name="author" content="" />
<meta name="robots" content="noindex" />
<meta name="msapplication-TileColor" content="#FFFFFF" />
<meta name="msapplication-TileImage" content="/Themes/Convercent/Images/tileicon.png" />
<meta name="msapplication-navbutton-color" content="#7b2881" />
<meta name="application-name" content="Convercent" />
<link rel="shortcut icon" href="/Themes/Convercent/Images/favicon.ico" type="image/x-icon" />


	<link href="/bundles_anonymous/themes/?v=w16kdNzi39CnnzJYB08a3UeCfDSwu_BL_CxPqZZ503s1" rel="stylesheet"/>

	<link href="/bundles_anonymous/custom/?v=mSAXkfD1PW__lhDL3pBrsSMQlrUYGWvctvVepDgISwE1" rel="stylesheet"/>


	<link href="/Themes/Convercent/Styles/Fonts/glyph-icons.css" rel="stylesheet" />
	<link href="/Areas/Darwin/Themes/Convercent/CSS/glyph-icon-extensions.css" rel="stylesheet" />

	<!--[if lt IE 9]>
		<script src="/Scripts/lib/html5.js"></script>
	<![endif]-->
	<script src="/bundles_anonymous/scripts/?v=d9GkALuaywWs3wbuWVkzf_Q4bOC4Yh-Mw0naK9fHKLQ1"></script>


	

</head>
<body>
	<input name="__RequestVerificationToken" type="hidden" value="KpXC0QcCw3NNNnTauH8He7uyreKzwgBJCftRorLKwSuuPVxDDI-3UERNLnNzyf9auecB8HoexwJ890MjkcP98TyoO7e1y3ed9_3UYN3GyCs1" />
	

<link rel="stylesheet" href="/Themes/Convercent/Styles/Modules/ActionRow/ActionRow.css"/>
<link rel="stylesheet" href="/Themes/Convercent/Styles/landingPage/landingPage.css"/>

<div class="l-top">
	<div class="l-containter">
		<div class="translation cf">


<link href="/Areas/Anonymous/Themes/Convercent/_landingPageLanguageMenu.css" rel="stylesheet" />

<div class="dropdown control-group langsel pull-right">
	<div style="position: relative">
		<a class="dropdown-toggle" dir="ltr" href="#" id="selectedlangelement">
			<span id="font-icon" class="icon-Globe" style="all: initial; color:#007573; font-size: 16px; vertical-align: baseline;"></span>
			<span class="langsel-culture">
				English (United States)
			</span>
			<span class="caret"></span>
		</a>
		<div class="language-menu">
			<ul class="pull-right" id="languageslist">
					<li>
						<a href="/af-za/Anonymous/IssueIntake/LandingPage/a69a789e-c300-e511-8123-00155d621509">
							<span class="langsel-culture">
								<span dir="auto">Afrikaans (Suid-Afrika)</span>
							</span>
						</a>
					</li>
					<li>
						<a href="/ms-my/Anonymous/IssueIntake/LandingPage/a69a789e-c300-e511-8123-00155d621509">
							<span class="langsel-culture">
								<span dir="auto">Bahasa Melayu (Malaysia)</span>
							</span>
						</a>
					</li>
					<li>
						<a href="/cs-cz/Anonymous/IssueIntake/LandingPage/a69a789e-c300-e511-8123-00155d621509">
							<span class="langsel-culture">
								<span dir="auto">čeština (Česká republika)</span>
							</span>
						</a>
					</li>
					<li>
						<a href="/da-dk/Anonymous/IssueIntake/LandingPage/a69a789e-c300-e511-8123-00155d621509">
							<span class="langsel-culture">
								<span dir="auto">dansk (Danmark)</span>
							</span>
						</a>
					</li>
					<li>
						<a href="/de-de/Anonymous/IssueIntake/LandingPage/a69a789e-c300-e511-8123-00155d621509">
							<span class="langsel-culture">
								<span dir="auto">Deutsch (Deutschland)</span>
							</span>
						</a>
					</li>.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/55.0.2919.83 Safari/537.36' 'https://integrity.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)