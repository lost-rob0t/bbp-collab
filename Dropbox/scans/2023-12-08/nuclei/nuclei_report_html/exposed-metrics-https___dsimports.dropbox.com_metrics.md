### Exposed metrics (exposed-metrics) found on https://dsimports.dropbox.com

----
**Details**: **exposed-metrics** matched at https://dsimports.dropbox.com

**Protocol**: HTTP

**Full URL**: https://dsimports.dropbox.com/metrics

**Timestamp**: Sat Dec 9 09:18:27 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Exposed metrics |
| Authors | dhiyaneshdk |
| Tags | config, exposure |
| Severity | low |

**Request**
```http
GET /metrics HTTP/1.1
Host: dsimports.dropbox.com
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
Transfer-Encoding: chunked
Content-Type: text/plain
Date: Sat, 09 Dec 2023 09:18:26 GMT
Nel: {"report_to":"heroku-nel","max_age":3600,"success_fraction":0.005,"failure_fraction":0.05,"response_headers":["Via"]}
Report-To: {"group":"heroku-nel","max_age":3600,"endpoints":[{"url":"https://nel.heroku.com/reports?ts=1702113506&sid=929419e7-33ea-4e2f-85f0-7d8b7cd5cbd6&s=ywya2llFJVcDeWnyRkVArHwe5tziZrlo4lAFgWZF4Ys%3D"}]}
Reporting-Endpoints: heroku-nel=https://nel.heroku.com/reports?ts=1702113506&sid=929419e7-33ea-4e2f-85f0-7d8b7cd5cbd6&s=ywya2llFJVcDeWnyRkVArHwe5tziZrlo4lAFgWZF4Ys%3D
Server: Cowboy
Set-Cookie: heroku-session-affinity=ACyDaANoA24IAabgK/D///8HYgABu2JiAA2OGWEBbAAAAAFtAAAABXdlYi4xakhi93mlI22m0BWz3XeIW2zPOPvx; Version=1; Expires=Sun, 10-Dec-2023 09:18:26 GMT; Max-Age=86400; Domain=dsimports.dropbox.com; Path=/
Set-Cookie: connect.sid=s%3APAM-RcYnvcjgxm9tCma78hRqQF1KlqHs.Qc9accrGABdMyQbbe5KYuZA%2F8LzUI95KXbLUJXdo7v4; Path=/; HttpOnly
Via: 1.1 vegur, 1.1 319d5f1e8660f76d5a2dceecbead5196.cloudfront.net (CloudFront)
X-Amz-Cf-Id: zxhtvWRBw5DOEElNGKYpygRbinTf3iOgYjSnCHbt9JcVG3SlZrbgzg==
X-Amz-Cf-Pop: MRS52-P6
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Frame-Options: SAMEORIGIN
X-Powered-By: Express
X-Request-Id: 3707be87-5b42-4ad8-a464-2a3bd9e36d0b
X-Xss-Protection: 0

# HELP http_request_duration_seconds duration histogram of http responses labeled with: status_code, method
# TYPE http_request_duration_seconds histogram
http_request_duration_seconds_bucket{le="0.003",status_code="404",method="GET"} 906
http_request_duration_seconds_bucket{le="0.03",status_code="404",method="GET"} 907
http_request_duration_seconds_bucket{le="0.1",status_code="404",method="GET"} 907
http_request_duration_seconds_bucket{le="0.3",status_code="404",method="GET"} 907
http_request_duration_seconds_bucket{le="1.5",status_code="404",method="GET"} 907
http_request_duration_seconds_bucket{le="10",status_code="404",method="GET"} 907
http_request_duration_seconds_bucket{le="+Inf",status_code="404",method="GET"} 907
http_request_duration_seconds_sum{status_code="404",method="GET"} 0.853027840000001
http_request_duration_seconds_count{status_code="404",method="GET"} 907
http_request_duration_seconds_bucket{le="0.003",status_code="404",method="POST"} 66
http_request_duration_seconds_bucket{le="0.03",status_code="404",method="POST"} 66
http_request_duration_seconds_bucket{le="0.1",status_code="404",method="POST"} 66
http_request_duration_seconds_bucket{le="0.3",status_code="404",method="POST"} 66
http_request_duration_seconds_bucket{le="1.5",status_code="404",method="POST"} 66
http_request_duration_seconds_bucket{le="10",status_code="404",method="POST"} 66
http_request_duration_seconds_bucket{le="+Inf",status_code="404",method="POST"} 66
http_request_duration_seconds_sum{status_code="404",method="POST"} 0.06329962400000001
http_request_duration_seconds_count{status_code="404",method="POST"} 66
http_request_duration_seconds_bucket{le="0.003",status_code="400",method="GET"} 1
http_request_duration_seconds_bucket{le="0.03",status_code="400",method="GET"} 1
http_request_duration_seconds_bucket{le="0.1",status_code="400",method="GET"} 1
http_request_duration_seconds_bucket{le="0.3",status_code="400",method="GET"} 1
http_request_duration_seconds_bucket{le="1.5",status_code="400",method="GET"} 1
http_request_duration_seconds_bucket{le="10",status_code="400",method="GET"} 1
http_request_duration_seconds_bucket{le="+Inf",status_code="400",method="GET"} 1
http_request_duration_seconds_sum{status_code="400",method="GET"} 0.00121132
http_request_duration_seconds_count{status_code="400",method="GET"} 1
http_request_duration_seconds_bucket{le="0.003",status_code="404",method="DELETE"} 1
http_request_duration_seconds_bucket{le="0.03",status_code="404",method="DELETE"} 1
http_request_duration_seconds_bucket{le="0.1",status_code="404",method="DELETE"} 1
http_request_duration_seconds_bucket{le="0.3",status_code="404",method="DELETE"} 1
http_request_duration_seconds_bucket{le="1.5",status_code="404",method="DELETE"} 1
http_request_duration_seconds_bucket{le="10",status_code="404",method="DELETE"} 1
http_request_duration_seconds_bucket{le="+Inf",status_code="404",method="DELETE"} 1
http_request_duration_seconds_sum{status_code="404",method="DELETE"} 0.000673476
http_request_duration_seconds_count{status_code="404",method="DELETE"} 1
http_request_duration_seconds_bucket{le="0.003",status_code="204",method="OPTIONS"} 26
http_request_duration_seconds_bucket{le="0.03",status_code="204",method="OPTIONS"} 26
http_request_duration_seconds_bucket{le="0.1",status_code="204",method="OPTIONS"} 26
http_request_duration_seconds_bucket{le="0.3",status_code="204",method="OPTIONS"} 26
http_request_duration_seconds_bucket{le="1.5",status_code="204",method="OPTIONS"} 26
http_request_duration_seconds_bucket{le="10",status_code="204",method="OPTIONS"} 26
http_request_duration_seconds_bucket{le="+Inf",status_code="204",method="OPTIONS"} 26
http_request_duration_seconds_sum{status_code="204",met.... Truncated ....
```

References: 
- https://hackerone.com/reports/1026196

**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.67 Safari/537.36' 'https://dsimports.dropbox.com/metrics'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)