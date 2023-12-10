### Cisco ASA VPN panel detect (cisco-asa-panel-detect) found on https://iad.vpn.dropboxer.net

----
**Details**: **cisco-asa-panel-detect** matched at https://iad.vpn.dropboxer.net

**Protocol**: HTTP

**Full URL**: https://iad.vpn.dropboxer.net/+CSCOE+/logon.html?fcadbadd=1

**Timestamp**: Sat Dec 9 09:42:32 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Cisco ASA VPN panel detect |
| Authors | organiccrap |
| Tags | cisco, panel |
| Severity | info |

**Request**
```http
GET /+CSCOE+/logon.html HTTP/1.1
Host: iad.vpn.dropboxer.net
User-Agent: Mozilla/5.0 (Windows NT 6.3; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2226.0 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Transfer-Encoding: chunked
Cache-Control: no-store
Connection: Keep-Alive
Content-Security-Policy: default-src 'self' 'unsafe-inline' 'unsafe-eval' data: blob:; frame-ancestors 'self'
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 09:42:32 GMT
Pragma: no-cache
Set-Cookie: webvpn=; expires=Thu, 01 Jan 1970 22:00:00 GMT; path=/; secure
Set-Cookie: webvpnc=; expires=Thu, 01 Jan 1970 22:00:00 GMT; path=/; secure
Set-Cookie: webvpn_as=; expires=Thu, 01 Jan 1970 22:00:00 GMT; path=/; secure
Set-Cookie: webvpn_portal=; expires=Thu, 01 Jan 1970 22:00:00 GMT; path=/; secure
Set-Cookie: webvpnSharePoint=; expires=Thu, 01 Jan 1970 22:00:00 GMT; path=/; secure
Set-Cookie: samlPreauthSessionHash=; expires=Thu, 01 Jan 1970 22:00:00 GMT; path=/; secure
Set-Cookie: acSamlv2Token=; expires=Thu, 01 Jan 1970 22:00:00 GMT; path=/; secure
Set-Cookie: acSamlv2Error=; expires=Thu, 01 Jan 1970 22:00:00 GMT; path=/; secure
Set-Cookie: webvpnlogin=1; path=/; secure
Set-Cookie: webvpnLang=en; path=/; secure
Strict-Transport-Security: max-age=31536000; includeSubDomains
X-Content-Type-Options: nosniff
X-Frame-Options: SAMEORIGIN
X-Xss-Protection: 1


<!DOCTYPE html>
<html style="height:100%;width:100%;">
<head>

<title>SSL VPN Service</title>
<meta name="HandheldFriendly" content="true" />
<meta name="viewport" content="width=500,user-scalable=no" />
<script>
if(self != top) top.location.href="/+CSCOE+/logon.html";



var blinkCounter=0;
var dap;

if (typeof navigator === 'object' && 'serviceWorker' in navigator && typeof navigator.serviceWorker === 'object' && 'register' in navigator.serviceWorker) {
    navigator.serviceWorker.getRegistration('/').then(function(registration) {
        if (registration) {
            registration.unregister().then(function() {
                location.reload();
            });
        }
    });
}
 
function scrollToLogonForm() {
    document.location.hash = "form_title_text";
}

function dap_message(){

      if(!dap) return;
      
      if(dap.style.visibility == "visible"){
         dap.style.visibility = "hidden"
      }else{
         dap.style.visibility = "visible"
      }
      blinkCounter++;
      if(dap.style.visibility == "visible" && blinkCounter > 5)
	      clearInterval(dap_interval)
} 

function blinkDapMessage(){
        dap=document.getElementById("dap");
        if(dap){
           dap_interval = setInterval('dap_message()',1000)
        }
}

function showDapMessage(){
        obj=document.getElementById("dap_message");
        if(obj){
           obj.style.visibility = "visible"
           obj.style.top = (document.body.clientHeight - obj.clientHeight)/2+"px"
           obj.style.left = (document.body.clientWidth - obj.clientWidth)/2+"px"
        }

        obj1=document.getElementById("dap_message_shield");
        if(obj1){
           obj1.style.visibility = "visible"
           obj1.style.top = (document.body.clientHeight - obj.clientHeight)/2+"px"
           obj1.style.left = (document.body.clientWidth - obj.clientWidth)/2+"px"
           obj1.style.height = obj.clientHeight+"px"
           obj1.style.width = obj.clientWidth+"px"
        }
} 

function hideDapMessage(){
        obj=document.getElementById("dap_message");
        if(obj){
           obj.style.visibility = "hidden"
        }

        obj1=document.getElementById("dap_message_shield");
        if(obj1){
           obj1.style.visibility = "hidden"
        }
} 









function base64_encode(data) {
  var b64 = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/=';
  var o1, o2, o3, h1, h2, h3, h4, bits, i = 0,
    ac = 0,
    enc = '', 
    tmp_arr = []; 
  if (!data) {
    return data;
  }
  do {
    // pack three octets into four hexets
    o1 = data.charCodeAt(i++);
    o2 = data.charCodeAt(i++);
    o3 = data.charCodeAt(i++);
    bits = o1 << 16 | o2 << 8 | o3; 
    h1 = bits >> 18 & 0x3f;
    h2 = bits >> 12 & 0x3f;
    h3 = bits >> 6 & 0x3f;
    h4 = bits & 0x3f;
    // use hexets to index into b64, and append result to encoded string
    tmp_arr[ac++] = b64.charAt(h1) + b64.charAt(h2) + b64.charAt(h3) + b64.charAt(h4);
  } while (i < data.length);
  enc = tmp_arr.join('');
  var r = data.length % 3;
  return (r ? enc.slice(0, r - 3) : enc) + '==='.slice(r || 3); 
}
function updateLogonForm(group,reload){

    if(reload[group]){
    	var obj=document.getElementById("login");
    	if(obj) {
           obj.disabled=true
        }
         
        document.cookie = "tg=1" + base64_encode(group) + "; path=/; secure";
    	document.location = "/+CSCOE+/logon.html";
        return
    }
}
function PrefillError() {
      var obj = document.getElementById("logon_message_text");
      if (obj) {
         obj.innerHTML="Your certificate is invalid for the selected group";
         obj.style.fontWeight="bold";
         obj.style.color="red";
      }
      obj = document.getElementById("Login");
      if (obj) {
         obj.disabled=true;
      }
}
</script>


<link href="/+CSCOU+/portal.css" rel="stylesheet" type="text/css">
<link href="/+CSCOE+/logon_custom.css" rel=.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.3; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2226.0 Safari/537.36' 'https://iad.vpn.dropboxer.net/+CSCOE+/logon.html'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)