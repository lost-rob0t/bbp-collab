### OSINT Extração de URLS (osint-extractor-url) found on https://app.helloworks.com

----
**Details**: **osint-extractor-url** matched at https://app.helloworks.com

**Protocol**: HTTP

**Full URL**: https://app.helloworks.com

**Timestamp**: Sat Dec 9 00:00:33 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | OSINT Extração de URLS |
| Authors | mrcl0wn / osint brazuca |
| Tags | url, consulta, osint |
| Severity | info |
| Description | Extração de URLS via expressão regular |

**Request**
```http
GET / HTTP/1.1
Host: app.helloworks.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.1916.47 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Content-Length: 3132
Cache-Control: max-age=0, private, must-revalidate
Content-Type: text/html; charset=utf-8
Cross-Origin-Window-Policy: deny
Date: Sat, 09 Dec 2023 00:00:33 GMT
Server: nginx
Set-Cookie: AWSALB=uIF+//9YBwq8lVRgZ+fVK5CsYV8THL0h0Wj/9opPdgTQl3IA8PNFeLW9EeqH478omdXLDc5ec7I7tJ3YsmAZSMEWw/xPhKbgLJ6d+3DvFVl8VK7t/jA94BOG/XZA; Expires=Sat, 16 Dec 2023 00:00:33 GMT; Path=/
Set-Cookie: AWSALBCORS=uIF+//9YBwq8lVRgZ+fVK5CsYV8THL0h0Wj/9opPdgTQl3IA8PNFeLW9EeqH478omdXLDc5ec7I7tJ3YsmAZSMEWw/xPhKbgLJ6d+3DvFVl8VK7t/jA94BOG/XZA; Expires=Sat, 16 Dec 2023 00:00:33 GMT; Path=/; SameSite=None; Secure
Strict-Transport-Security: max-age=31536000; includeSubDomains;
X-Content-Type-Options: nosniff
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Frame-Options: SAMEORIGIN
X-Frame-Options: DENY
X-Permitted-Cross-Domain-Policies: none
X-Request-Id: F58AxaMCa2dUyuAh_AYi
X-Xss-Protection: 1; mode=block

<!DOCTYPE html>
<html lang="en">
  <head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale = 1.0">

<title>Dropbox Forms</title>
<meta name="author" content="Dropbox Sign">
<meta name="description" content="The world&#39;s first workflow platform converting complex PDFs into beautiful simple workflows that reduce errors and increase completion rates. Build multi-form workflows that are mobile-first, with drag-and-drop functionality, and see document completion rates increase.">
<meta name="subject" content="Workflow Automation">
<meta name="copyright" content="Dropbox Sign">
<link rel="shortcut icon" href="https://cdn.helloworks.com/2023-12-01-151408-45e6bb2/assets/favicon-backdrop.png">

<meta property="og:title" content="Dropbox Forms">
<meta property="og:description" content="The world&#39;s first workflow platform converting complex PDFs into beautiful simple workflows that reduce errors and increase completion rates. Build multi-form workflows that are mobile-first, with drag-and-drop functionality, and see document completion rates increase.">
<meta property="og:type" content="website">
<meta property="og:image" content="https://cdn.helloworks.com/2023-12-01-151408-45e6bb2/assets/logo-lockup-backdrop.png">
<meta property="og:site_name" content="Dropbox Forms">
<meta property="og:locale" content="en">

<meta name="twitter:card" content="summary">
<meta name="twitter:site" content="@DropboxSign">
<meta name="twitter:creator" content="@DropboxSign">
<meta name="twitter:name" content="Dropbox Forms">
<meta name="twitter:description" content="The world&#39;s first workflow platform converting complex PDFs into beautiful simple workflows that reduce errors and increase completion rates. Build multi-form workflows that are mobile-first, with drag-and-drop functionality, and see document completion rates increase.">
<meta name="twitter:image" content="https://cdn.helloworks.com/2023-12-01-151408-45e6bb2/assets/logo-lockup-backdrop.png">
<meta name="twitter:image:alt" content="Dropbox Forms">

<meta name="apple-mobile-web-app-capable" content="yes">
    <link rel="stylesheet" href="https://cdn.helloworks.com/2023-12-01-151408-45e6bb2/tokens/style.css">
      <script type="text/javascript" src="/js/jquery-3.5.0.min.js"></script>
      <link rel="stylesheet" href="/css/bootstrap.min.css">
    <style>
      .btn-primary {
          background-color: var(--hw-color-button-primary-bg);
          border-width: 0;
          border-radius: var(--hw-corner-button-primary);
      }

      .btn-primary:hover {
          background-color: var(--hw-color-button-primary-bg-hover);
      }

      .btn-primary:not(:disabled):not(.disabled):active {
          background-color: var(--hw-color-button-primary-bg-pressed);
          border-width: 0;
      }
    </style>
    <style>
    .alert {
      margin: 20px 0;
      float: left;
      width: 100%;
    }
    </style>
  </head>

  <body>
    <div class="container">


      <main role="main">

      </main>
    </div> <!-- /container -->
  </body>
</html>
```

**Extra Information**

**Extracted results:**

- https://cdn.helloworks.com/2023-12-01-151408-45e6bb2/assets/favicon-backdrop.png
- https://cdn.helloworks.com/2023-12-01-151408-45e6bb2/assets/logo-lockup-backdrop.png
- https://cdn.helloworks.com/2023-12-01-151408-45e6bb2/tokens/style.css



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.1916.47 Safari/537.36' 'https://app.helloworks.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)