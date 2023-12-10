### Display Via Header (display-via-header) found on https://enterprise.dropbox.com

----
**Details**: **display-via-header** matched at https://enterprise.dropbox.com

**Protocol**: HTTP

**Full URL**: https://enterprise.dropbox.com

**Timestamp**: Sat Dec 9 08:23:33 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Display Via Header |
| Authors | geeknik |
| Tags | misc, generic |
| Severity | info |

**Request**
```http
GET / HTTP/1.1
Host: enterprise.dropbox.com
User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/34.0.1847.137 Safari/4E423F
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 403 Forbidden
Connection: close
Transfer-Encoding: chunked
Content-Type: text/html; charset=UTF-8
Date: Sat, 09 Dec 2023 08:23:33 GMT
Etag: W/"2442-5eb808d5432c0"
Last-Modified: Fri, 21 Oct 2022 00:30:43 GMT
Server: Apache
Vary: Accept-Encoding
Via: 1.1 5c0d26cafc949da4f2fa947ea21b4f74.cloudfront.net (CloudFront)
X-Amz-Cf-Id: p2BhvQj-MkYUV0MIhUGag7ABIndur8Rp5r5UjnJ3q_CPRxia89Vzxw==
X-Amz-Cf-Pop: CDG52-P1
X-Cache: Error from cloudfront
X-Dispatcher: dispatcher2uswest1
X-Vhost: catch-all

<html>
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <title>TURN AROUND!</title>
    <meta name="viewport" content="width=device-width">
    <!--[if gte IE 9]>
    <style type="text/css">
    .gradient {
    filter: none;
    }
    </style>
    <![endif]-->
    <style type="text/css">
      *, *:after, *:before {
        -webkit-box-sizing: border-box;
        -moz-box-sizing: border-box;
        -ms-box-sizing: border-box;
        box-sizing: border-box; 
      }

      html {
        background: #ccc;
        font: bold 14px/20px "Trajan Pro", "Times New Roman", Times, serif;
        color: #430400;
        text-shadow: 0 1px 0 rgba(255, 255, 255, 0.15); 
      }

      .error-page-wrap {
        width: 310px;
        height: 310px;
        margin: 155px auto; }
        .error-page-wrap:before {
        box-shadow: 0 0 200px 150px #fff;
        width: 310px;
        height: 310px;
        border-radius: 50%;
        position: relative;
        z-index: -1;
        content: '';
        display: block; 
      }

      .error-page {
        width: 310px;
        height: 310px;
        border-radius: 50%;
        top: -310px;
        position: relative;
        text-align: center;
        background: #d36242;
        background: -moz-linear-gradient(top, #d36242 0%, darkred 100%);
        background: -webkit-gradient(linear, left top, left bottom, color-stop(0%, #d36242), color-stop(100%, darkred));
        background: -webkit-linear-gradient(top, #d36242 0%, darkred 100%);
        background: -o-linear-gradient(top, #d36242 0%, darkred 100%);
        background: -ms-linear-gradient(top, #d36242 0%, darkred 100%);
        background: linear-gradient(to bottom, #d36242 0%, darkred 100%);
        filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='$firstColor', endColorstr='$secondColor',GradientType=0 ); 
      }
      
      .error-page:before {
        width: 63px;
        height: 63px;
        content: '';
        z-index: -1;
        display: block;
        position: relative;
        top: -19px;
        left: 44px; 
      }
      
      .error-page:after {
        width: 310px;
        height: 17px;
        margin: 0 auto;
        top: 25px;
        content: '';
        z-index: -1;
        display: block;
        position: relative;
        background: -moz-radial-gradient(center, ellipse cover, rgba(0, 0, 0, 0.65) 0%, rgba(35, 26, 26, 0) 59%, rgba(60, 44, 44, 0) 100%);
        background: -webkit-gradient(radial, center center, 0px, center center, 100%, color-stop(0%, rgba(0, 0, 0, 0.65)), color-stop(59%, rgba(35, 26, 26, 0)), color-stop(100%, rgba(60, 44, 44, 0)));
        background: -webkit-radial-gradient(center, ellipse cover, rgba(0, 0, 0, 0.65) 0%, rgba(35, 26, 26, 0) 59%, rgba(60, 44, 44, 0) 100%);
        background: -o-radial-gradient(center, ellipse cover, rgba(0, 0, 0, 0.65) 0%, rgba(35, 26, 26, 0) 59%, rgba(60, 44, 44, 0) 100%);
        background: -ms-radial-gradient(center, ellipse cover, rgba(0, 0, 0, 0.65) 0%, rgba(35, 26, 26, 0) 59%, rgba(60, 44, 44, 0) 100%);
        background: radial-gradient(ellipse at center, rgba(0, 0, 0, 0.65) 0%, rgba(35, 26, 26, 0) 59%, rgba(60, 44, 44, 0) 100%);
        filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#a6000000', endColorstr='#003c2c2c',GradientType=1 ); 
      }
      
      .error-page h1 {
        color: rgba(255, 255, 255, 0.94);
        font-size: 100px;
        margin: 65px auto 0 auto;
        text-shadow: 0px 0 7px rgba(0, 0, 0, 0.5); 
      }
      
      .error-page h1:before {
        width: 260px;
        height: 1px;
        position: relative;
        margin: 0 auto;
        top: 70px;
        content: '';
        display: block;
        background: -moz-radial-gradient(center, ellipse cover, rgba(111, 25, 25, 0.65) 0%, rgba(75, 38, 38, 0) 70%, rgba(60, 44, 44, 0) 100%);
        background: -webkit-gradient(radial, center center, 0px, center center, 100%, color-stop(0%, rgba(111, 25, 25, 0.65)), color-stop(70%, rgba(75, 38, 38, 0)), color-stop(100%, rgba(60, 44, 44, 0)));
        background: -webkit-radial-gradient(center, ellipse cover, rgba(111, 25, 25, 0.65) 0%, rgba(75, 38, 38, 0) 70%, rgba(60, 44, 44, 0) 100%);
        background: -o-radial-gradient(center, ellipse cover, rgba(111, 25, 25, 0.65) 0%, rgba(75, 38, 38, 0) 70%, rgba(60, 44, 44, 0) 100%);
        background: -ms-radial-gradient(center, ellipse cover, rgba(111, 25, 25, 0.65) 0%, rgba(75, 38, 38, 0) 70%, rgba(60, 44, 44, 0) 100%);
        background: radial-gradient(ellipse at center,.... Truncated ....
```

**Extra Information**

**Extracted results:**

- Via: 1.1 5c0d26cafc949da4f2fa947ea21b4f74.cloudfront.net (CloudFront)


References: 
- https://developer.mozilla.org/en-us/docs/web/http/headers/via

**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/34.0.1847.137 Safari/4E423F' 'https://enterprise.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)