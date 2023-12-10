### HTTP Missing Security Headers (http-missing-security-headers:clear-site-data) found on https://forum.dropbox.com

----
**Details**: **http-missing-security-headers:clear-site-data** matched at https://forum.dropbox.com

**Protocol**: HTTP

**Full URL**: https://www.dropboxforum.com/t5/English/ct-p/English

**Timestamp**: Sat Dec 9 14:55:08 +0000 UTC 2023

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
Host: forum.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.2117.157 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Cache-Control: no-cache, no-store, must-revalidate, private
Content-Type: text/html;charset=UTF-8
Date: Sat, 09 Dec 2023 14:55:08 GMT
Expires: Thu, 01 Jan 1970 00:00:00 GMT
Pragma: no-cache
Server: Apache
Set-Cookie: AWSALB=LzFQhwzm/2NxU5kyw0f1shsi2J2Um7Hx/l0sCSfGVWoMg/F9q8rDY8v0PHjT5ozbr/IHdY6wjeQFzi88J2WnsyL4HJoUQCN0oV+ySKnvQ5jp008bKafFgT4XS6fL; Expires=Sat, 16 Dec 2023 14:55:08 GMT; Path=/
Set-Cookie: AWSALBCORS=LzFQhwzm/2NxU5kyw0f1shsi2J2Um7Hx/l0sCSfGVWoMg/F9q8rDY8v0PHjT5ozbr/IHdY6wjeQFzi88J2WnsyL4HJoUQCN0oV+ySKnvQ5jp008bKafFgT4XS6fL; Expires=Sat, 16 Dec 2023 14:55:08 GMT; Path=/; SameSite=None; Secure
Set-Cookie: LithiumVisitor=~2dcl5CktJf7uYihdu~VQ9dn2tHAHspeI5xGDJgkqGwULIY3cjhMzwonD6dgxm6IUuVmFBZMqG9FYyCtSOtTZuoL6lPXx1UoNHRIAe7ow..; Path=/; HttpOnly; Max-Age=15780000; Secure; SameSite=None
Vary: Accept-Encoding
Via: 1.1 912fe8d927c37ab06a5ab9f3fd8505be.cloudfront.net (CloudFront)
X-Amz-Cf-Id: mdSV2xBQ0LwhAIAxkiZZ29u1xWNwAP3EFf0oQ2c8wc8eGyOC_jNCJg==
X-Amz-Cf-Pop: MRS52-P3
X-Cache: Miss from cloudfront
X-Frame-Options: SAMEORIGIN

<!DOCTYPE html><html prefix="og: http://ogp.me/ns#" dir="ltr" lang="en" class="no-js">
	<head>
	
	<title>
	Dropbox Community
</title>
	
	
	<link rel="preconnect" href="https://limuirs-cloudfront-live.prod.lia.aws.lcloud.com">
<link rel="preconnect" href="https://www.googletagmanager.com">




<link rel="preload" href="/html/assets/CustomIcons.ttf" as="font" type="font/ttf" crossorigin>
<link rel="preload" href="/html/assets/AtlasGrotesk-Regular.woff" as="font" type="font/woff" crossorigin>
<link rel="preload" href="/html/assets/SharpGrotesk-Bold.woff" as="font"  type="font/woff" crossorigin>
<link rel="preload" href="/html/assets/SharpGrotesk-Regular.woff" as="font" type="font/woff" crossorigin>
<link rel="preload" href="/html/assets/AtlasGrotesk-Light.woff" as="font" type="font/woff" crossorigin>
<link rel="preload" href="/html/assets/AtlasGrotesk-Bold.woff" as="font" type="font/woff" crossorigin>
<link rel="preload" href="/html/assets/SharpGroteskWide-Bold.woff" as="font" type="font/woff" crossorigin>
<link rel="preload" href="/html/assets/fonts/fontawesome-webfont.woff2?v=4.3.0" as="font" type="font/woff2" crossorigin>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Open+Sans&display=swap" rel="stylesheet">


<!-- hreflang -->



<link rel="alternate" hreflang="en" href="https://www.dropboxforum.com/t5/English/ct-p/English" />
<link rel="alternate" hreflang="de" href="https://www.dropboxforum.com/t5/Deutsch/ct-p/German" />
<link rel="alternate" hreflang="es" href="https://www.dropboxforum.com/t5/Español/ct-p/Spanish" />
<link rel="alternate" hreflang="fr" href="https://www.dropboxforum.com/t5/Français/ct-p/French" />
<link rel="alternate" hreflang="pt-br" href="https://www.dropboxforum.com/t5/Português/ct-p/Portuguese" />
<link rel="alternate" hreflang="ja" href="https://www.dropboxforum.com/t5/日本語/ct-p/Japanese" />
<link rel="alternate" hreflang="x-default" href="https://www.dropboxforum.com/t5/English/ct-p/English" />




<!--/hreflang -->


<!--UXlogger -->

<script src="https://www.dropbox.com/pithos/ux_analytics" async></script>

<!--/UXlogger -->



	
	
	
	<meta content="With the Dropbox Community you can connect with other users like you, get answers to your questions and discover how to work smarter with Dropbox." name="description"/><meta content="width=device-width, initial-scale=1.0" name="viewport"/><meta content="text/html; charset=UTF-8" http-equiv="Content-Type"/><link href="https://www.dropboxforum.com/t5/English/ct-p/English" rel="canonical"/>
	<meta content="https://www.dropboxforum.com/html/assets/maroonlogo.png" property="og:image"/><meta content="dropboxforum.com" property="og:site_name"/><meta content="website" property="og:type"/><meta content="https://www.dropboxforum.com/t5/English/ct-p/English" property="og:url"/><meta content="With the Dropbox Community you can connect with other users like you, get answers to your questions and discover how to work smarter with Dropbox." property="og:description"/><meta content="Dropbox Community" property="og:title"/>
	
	
		<link class="lia-link-navigation hidden live-links" title="New board topics in English" type="application/rss+xml" rel="alternate" id="link" href="/mxpez29397/rss/Category?category.id=English&amp;interaction.style=forum"></link>
	
		<link class="lia-link-navigation hidden live-links" title="All board posts in English" type="application/rss+xml" rel="alternate" id="link_0" href="/mxpez29397/rss/Category?category.id=English&amp;interaction.style=forum&amp;feeds.replies=true"></link>
	
		<link class="lia-link-navigation hidden live-links" title="New knowledge base articles in English" type="application/rss+xml" rel="alternate" id="link_1" href="/mxpez29397/rss/Category?category.id=English&amp;interaction.style=tkb"></link>
	
		<link class="lia-link-navigation hidden live-links" .... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.2117.157 Safari/537.36' 'https://forum.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)