### Cisco Secure Desktop (cisco-secure-desktop) found on https://vpn.dropbox.com

----
**Details**: **cisco-secure-desktop** matched at https://vpn.dropbox.com

**Protocol**: HTTP

**Full URL**: https://vpn.dropbox.com/CACHE/sdesktop/install/start.htm

**Timestamp**: Sat Dec 9 09:44:08 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Cisco Secure Desktop |
| Authors | pdteam |
| Tags | cisco, panel |
| Severity | info |

**Request**
```http
GET /CACHE/sdesktop/install/start.htm HTTP/1.1
Host: vpn.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 6.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2228.0 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Content-Length: 9022
Cache-Control: max-age=6000
Connection: Keep-Alive
Content-Security-Policy: default-src 'self' 'unsafe-inline' 'unsafe-eval' data: blob:; frame-ancestors 'self'
Content-Type: text/html
Date: Sat, 09 Dec 2023 09:44:08 GMT
Strict-Transport-Security: max-age=31536000; includeSubDomains
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Xss-Protection: 1

<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN">
<html>
<head>
<style type="text/css">
/* CUES: Header and Wizard CSS */

body {font-family: Verdana; font-size: 0.7em; color: #000000; margin:20; padding:0; border:0;} 

td {font-family: Verdana; font-size: 0.7em; color: #000000;} 
 
/* Header Area*/ 
.cuesHeaderBg {width: 500; background-image:url('images/headerBgGradient.gif'); }
.cuesHeaderAccent {background: #003333; height:8px} 
.cuesHeaderTitleLogo {font-weight:bold; font-size: 1.05em; color: #003333; height:59px;}
.cuesHeaderText {font-size: 0.7em; color: #FFFFFF;}
a.cuesHeaderLink:link {color: #FFFFFF; text-decoration: none; padding:0 12px} 
a.cuesHeaderLink:visited {color: #FFFFFF; text-decoration: none; padding:0 12px}
a.cuesHeaderLink:hover {color: #FFFFFF; text-decoration: underline; padding:0 12px;}
a.cuesHeaderLink:active {color: #FFFFFF; text-decoration: none; padding:0 12px} 

/* Wizard */
.cuesWizardIcon {padding:20px 0 20px 10px} 
.cuesWizardTitle {font-size: 0.9em; font-weight:bold; color: #003366; padding:20px 10px} 
.cuesWizardStepPanel {width:33%; height:100%; vertical-align:top;  background: #F8F8F8; border-right: 1px solid #000000; margin-right:20px}
.cuesWizardStepCompleted {font-weight:bold; color: #003366; padding:4px 14px 4px 0;} 
.cuesWizardStepCompletedNo {width:6px; font-weight:bold; color: #003366; padding:4px 0 4px 14px; text-align:right} 
.cuesWizardStepCompletedDash {width:4px; font-weight:bold; color: #003366; padding:4px 4px;} 
.cuesWizardStepSelected {font-family: Verdana; font-size: 0.7em; color: #000000;font-weight:bold; color: #003366; background-color:#EFEFEF; border-top: 1px solid #C0D5D5; border-bottom: 1px solid #C0D5D5; padding:4px 14px 4px 0;} 
.cuesWizardStepSelectedNo {width:6px; font-weight:bold; color: #003366; background-color:#EFEFEF; border-top: 1px solid #C0D5D5;  border-bottom: 1px solid #C0D5D5; padding:4px 0 4px 14px; text-align:right } 
.cuesWizardStepSelectedDash {width:4px; font-weight:bold; color: #003366; background-color:#EFEFEF; border-top: 1px solid #C0D5D5; border-bottom: 1px solid #C0D5D5; padding:4px 4px} 
.cuesWizardStepFuture {font-weight:bold; color: #A6B8CA; padding:4px 14px 4px 0;} 
.cuesWizardStepFutureNo {width:6px; font-weight:bold; color: #A6B8CA; padding:4px 0 4px 14px; text-align:right} 
.cuesWizardStepFutureDash {width:4px; font-weight:bold; color: #A6B8CA; padding:4px 4px;} 
.cuesWizardContent {width:67%; height:100%; vertical-align:top; background: #EFEFEF;}
#cuesWizardWelcomeTitle {vertical-align:top; margin:0 10px;} 
#cuesWizardStepTitle {vertical-align:top; font-weight:bold; border-bottom: 1px solid #000000; padding:0 0 2px 0; margin:20px 20px 12px 20px;} 
#cuesWizardContentBody {vertical-align:top; margin:0 12px 12px 20px; overflow:auto;}
#cuesWizardContentNavButtons {text-align: right; vertical-align:bottom; border-top: 1px solid #000000; padding:12px 0; margin:12px 20px 0 20px}
.cuesWizardCancelButton { margin: 0 0 0 14px}

</style>

<meta name="expires" content="Sat, 01 Jan 2000 24:00:00 GMT"/>
<title>Installation</title>
<script type="text/javascript" language="JavaScript1.1" src="binaries/pkginit.js"></script>
<script type="text/javascript" language="JavaScript1.1" src="binaries/mainv.js"></script>
<script type="text/javascript" language="JavaScript1.1" src="strings.js"></script>
<script type="text/javascript" language="JavaScript1.1"> translatemessages(); </script>
<script type="text/javascript" language="JavaScript1.1">
function openTipsWindow() {
      var x = 310;
      window.open('tips.htm', 'tips',
        'width=' + x + ',scrollbars=yes,toolbar=no,directories=no,' +
           'status=no,menubar=no,top=0,screenY=0,resizable,' +
           'left=' + (screen.width - x) + ',screenX=' + (screen.width - x));
}

function skipToManualInstall() {
    iStatus=-70;
    Start(iStatus);
}

// preload images
var preloadedImgs = new Array();

preloadedImgs[0] = new Image(110, 73);
preloadedImgs[0].src = "images/logo.gif";

preloadedImgs[1] = new Image(16, 16);
preloadedImgs[1].src = "images/csd-icon.gif"

preloadedImgs[2] = new Image(160, 67);
preloadedImgs[2].src = "images/buttons.gif";

preloadedImgs[3] = new Image(282, 88);
preloadedImgs[3].src = "images/infobar.gif";

preloadedImgs[3] = new Image(172, 14);
preloadedImgs[3].src = "images/loading.gif";

</script>
</head>
<body onload='loadPackage();'>
<div align="center">
<table style="border-style:outset;border-color:black;border-width:1" width="500" border="0" cellpadding="0" cellspacing="0" class="cuesHeaderBg" height="67">
<tr><td colspan="2" class="cuesHeaderAccent"></td></tr>
<tr.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2228.0 Safari/537.36' 'https://vpn.dropbox.com/CACHE/sdesktop/install/start.htm'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)