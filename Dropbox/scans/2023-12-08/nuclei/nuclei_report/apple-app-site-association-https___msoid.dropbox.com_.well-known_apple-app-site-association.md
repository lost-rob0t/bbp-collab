### Apple app site association for harvesting end points (apple-app-site-association) found on https://msoid.dropbox.com

----
**Details**: **apple-app-site-association** matched at https://msoid.dropbox.com

**Protocol**: HTTP

**Full URL**: https://msoid.dropbox.com/.well-known/apple-app-site-association

**Timestamp**: Sat Dec 9 08:57:08 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Apple app site association for harvesting end points |
| Authors | panch0r3d |
| Tags | misc, apple |
| Severity | info |

**Request**
```http
GET /.well-known/apple-app-site-association HTTP/1.1
Host: msoid.dropbox.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2227.1 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Content-Length: 3692
Content-Type: application/json; charset=utf-8
Date: Sat, 09 Dec 2023 08:57:07 GMT
Set-Cookie: x-ms-gateway-slice=estsfd; path=/; secure; httponly
Set-Cookie: stsservicecookie=estsfd; path=/; secure; httponly
Strict-Transport-Security: max-age=31536000; includeSubDomains
X-Content-Type-Options: nosniff

{
    "authsrv": {
        "apps": [
            "SGGM6D27TK.com.microsoft.azureauthenticator",
            "UBF8T346G9.com.microsoft.CompanyPortalMac"
        ]
    },
    "applinks": {
        "apps": [],
        "details": [
            {
                "appID": "SGGM6D27TK.com.microsoft.azureauthenticator",
                "paths": [
                    "/applebroker/msauth",
                    "/applebroker/msauthv2"
                ]
            }
        ]
    },
    "webcredentials": {
        "apps": [
            "UBF8T346G9.com.microsoft.azureauthenticator",
            "SGGM6D27TK.com.microsoft.azureauthenticator",
            "UBF8T346G9.com.microsoft.azureauthenticator.ssoextension",
            "SGGM6D27TK.com.microsoft.azureauthenticator.ssoextension",
            "UBF8T346G9.com.microsoft.CompanyPortalMac",
            "UBF8T346G9.com.microsoft.CompanyPortalMac.ssoextension",
            "9KBH5RKYEW.com.microsoft.companyportal-int",
            "SGGM6D27TK.com.microsoft.CompanyPortal",
            "SGGM6D27TK.com.microsoft.companyportal-dev",
            "SGGM6D27TK.com.microsoft.AadRegistrationTool",
            "SGGM6D27TK.com.microsoft.msedge",
            "UBF8T346G9.com.microsoft.edgemac",
            "UBF8T346G9.com.microsoft.edgemac.Canary",
            "UBF8T346G9.com.microsoft.edgemac.Dev",
            "UBF8T346G9.com.microsoft.edgemac.Beta",
            "SGGM6D27TK.com.microsoft.skype.teams",
            "SGGM6D27TK.com.microsoft.onedrive",
            "UBF8T346G9.com.microsoft.OneDrive-mac",
            "UBF8T346G9.com.microsoft.OneDrive",
            "UBF8T346G9.com.microsoft.scmx",
            "UBF8T346G9.com.microsoft.Office.Word",
            "UBF8T346G9.com.microsoft.Office.Word-dogfood",
            "UBF8T346G9.com.microsoft.Office.Excel",
            "UBF8T346G9.com.microsoft.Office.Excel-dogfood",
            "UBF8T346G9.com.microsoft.Office.Powerpoint",
            "UBF8T346G9.com.microsoft.Office.Powerpoint-dogfood",
            "UBF8T346G9.com.microsoft.officemobile",
            "UBF8T346G9.com.microsoft.officemobile-dogfood",
            "SGGM6D27TK.com.microsoft.to-do",
            "9KBH5RKYEW.com.microsoft.to-do-dogfood",
            "9KBH5RKYEW.com.microsoft.to-do-nightly",
            "UBF8T346G9.com.microsoft.to-do-mac",
            "UBF8T346G9.com.microsoft.to-do-mac-dev",
            "UBF8T346G9.com.microsoft.to-do-mac-dogfood",
            "UBF8T346G9.com.microsoft.to-do-mac-nightly",
            "SGGM6D27TK.com.microsoft.Office.Outlook",
            "9KBH5RKYEW.com.microsoft.Office.Outlook-dev",
            "9KBH5RKYEW.com.microsoft.Office.Outlook-dogfood",
            "9KBH5RKYEW.com.microsoft.Office.Outlook-wip",
            "UBF8T346G9.com.microsoft.rdc.macos",
            "SGGM6D27TK.com.microsoft.rdc.osx.beta",
            "SGGM6D27TK.com.microsoft.rdc.ios",
            "SGGM6D27TK.com.microsoft.rdc.ios.beta",
            "SGGM6D27TK.com.microsoft.powerbimobile",
            "SGGM6D27TK.wefwef",
            "SGGM6D27TK.com.microsoft.msapps",
            "SGGM6D27TK.com.microsoft.dynamics.iphone.moca.fieldServices",
            "SGGM6D27TK.com.microsoft.dynamics.iphone.moca.sales",
            "9KBH5RKYEW.com.microsoft.msapps-df",
            "9KBH5RKYEW.com.microsoft.dynamics.iphone.moca.fieldServices-df",
            "9KBH5RKYEW.com.microsoft.dynamics.iphone.moca.sales-df",
            "UBF8T346G9.com.microsoft.teams",
            "UBF8T346G9.com.microsoft.teams2",
            "UBF8T346G9.com.microsoft.MSALMacTestApp",
            "SGGM6D27TK.com.microsoft.MSALiOSTestApp"
        ]
    }
}

```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2227.1 Safari/537.36' 'https://msoid.dropbox.com/.well-known/apple-app-site-association'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)