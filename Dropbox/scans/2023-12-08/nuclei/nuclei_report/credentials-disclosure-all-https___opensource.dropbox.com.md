### credentials-disclosure-all (credentials-disclosure-all) found on https://opensource.dropbox.com

----
**Details**: **credentials-disclosure-all** matched at https://opensource.dropbox.com

**Protocol**: HTTP

**Full URL**: https://opensource.dropbox.com

**Timestamp**: Sat Dec 9 00:01:21 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | credentials-disclosure-all |
| Authors | w9w |
| Tags |  |
| Severity | medium |
| Description | Matching patterns in the body. |

**Request**
```http
GET / HTTP/1.1
Host: opensource.dropbox.com
User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2227.0 Safari/537.36
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
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 00:01:21 GMT
Last-Modified: Thu, 21 Jul 2022 07:33:59 GMT
Server: nginx
Strict-Transport-Security: max-age=31536000; includeSubDomains
Vary: Accept-Encoding
X-Cached: HIT
X-Dropbox-Request-Id: 31d16c74499cd855910b350164206ed3

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Dropbox Open Source</title>
    <link rel="shortcut icon" href="/static/images/favicon.ico"/>
    <link href="css/reset.css" media="screen" rel="stylesheet" type="text/css" />
    <link href="//fonts.googleapis.com/css?family=Open+Sans:400,300,700" rel="stylesheet" type="text/css">
    <link href="css/styles.css" media="screen" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <div id="wrapper">
      <section id="header">
        <div><a href="https://www.dropbox.com"><img src="assets/logo.png" width="64" /></a><div>
        <h1>Dropbox Open Source</h1>
        <p>Dropbox loves open source! We participate in the open source community by using open source software internally and open sourcing our own projects.</p>
        <div class="underline"></div>
      </section>
      <section id="libraries" class="category">
        <h2>Libraries</h2>
        <ul class="repositories">
          <li>
            <div class="language">CoffeeScript</div>
            <h3><a href="https://github.com/dropbox/amqp-coffee">amqp-coffee</a></h3>
            <p class="description">An AMQP 0.9.1 client for Node.js.</p>
            <p><a href="https://github.com/dropbox/amqp-coffee">View on GitHub</a></p>
          </li>
          <li>
            <h3><a href="https://github.com/dropbox/djinni">Djinni</a></h3>
            <p class="description">Generates cross-language type declarations and interface bindings.</p>
            <p><a href="https://github.com/dropbox/djinni">View on GitHub</a></p>
          </li>
          <li>
            <div class="language">Go</div>
            <h3><a href="https://github.com/dropbox/godropbox">godropbox</a></h3>
            <p class="description">Common libraries for writing Go services/applications.</p>
            <p><a href="https://github.com/dropbox/godropbox">View on GitHub</a></p>
          </li>
          <li>
            <div class="language">Python</div>
            <h3><a href="https://github.com/dropbox/hydra">hydra</a></h3>
            <p class="description">A multi-process MongoDB collection copier.</p>
            <p><a href="https://github.com/dropbox/hydra">View on GitHub</a> &bull; <a href="https://tech.dropbox.com/2013/09/scaling-mongodb-at-mailbox/">Blog post</a></p>
          </li>
          <li>
            <div class="language">C++</div>
            <h3><a href="https://github.com/dropbox/json11">json11</a></h3>
            <p class="description">A tiny JSON library for C++11.</p>
            <p><a href="https://github.com/dropbox/json11">View on GitHub</a></p>
          </li>
          <li>
            <div class="language">C++</div>
            <h3><a href="https://github.com/dropbox/lopper">lopper</a></h3>
            <p class="description">A light-weight C++ library for vectorizing image-processing code.</p>
            <p><a href="https://github.com/dropbox/lopper">View on GitHub</a></p>
          </li>
          <li>
            <div class="language">C++</div>
            <h3><a href="https://github.com/dropbox/miniutf">miniutf</a></h3>
            <p class="description">A C++ library for basic Unicode manipulation.</p>
            <p><a href="https://github.com/dropbox/miniutf">View on GitHub</a></p>
          </li>
          <li>
            <div class="language">Python</div>
            <h3><a href="https://github.com/dropbox/pygerduty">pygerduty</a></h3>
            <p class="description">A Python library for PagerDuty.</p>
            <p><a href="https://github.com/dropbox/pygerduty">View on GitHub</a></p>
          </li>
          <li>
            <div class="language">Python</div>
            <h3><a href="https://github.com/dropbox/pynsot">pynsot</a></h3>
            <p class="description">A Python client for NSoT REST API.</p>
            <p><a href="https://github.com/dropbox/pynsot">View on GitHub</a></p>
          </li>
          <li>
            <div class="language">C++</div>
            <h3><a href="https://github.com/dropbox/pyston">pyston</a></h3>
            <p class="description">An open-source Python implementation using JIT techniques.</p>
            <p><a href="https://github.com/dropbox/pyston">View on GitHub</a></p>
          </li>
          <li>
            <div class="language">Python</div>
            <h3><a href="https://github.com/dropbox/pytest-flakefinder">pytest-flakefinder</a></h3>
            <p class="description">Runs tests multiple times to expose flakiness.</p>
            <p><a href="https://github.com/dropbox/pytest-flakefinder">View on GitHub</a></p>
          </li>
          <li>
            <div class="language">Python</div>
            <h3><a href="https://github.com/dropbox/pyxl">pyxl</a></h3>
            <.... Truncated ....
```

**Extra Information**

**Extracted results:**

- basic Unicode



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2227.0 Safari/537.36' 'https://opensource.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)