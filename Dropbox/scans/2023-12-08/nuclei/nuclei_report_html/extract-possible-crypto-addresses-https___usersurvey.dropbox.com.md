### Possible crypto addresses (long strings) extractor (extract-possible-crypto-addresses) found on https://usersurvey.dropbox.com

----
**Details**: **extract-possible-crypto-addresses** matched at https://usersurvey.dropbox.com

**Protocol**: HTTP

**Full URL**: https://usersurvey.dropbox.com

**Timestamp**: Sat Dec 9 00:01:42 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Possible crypto addresses (long strings) extractor |
| Authors | cipher387 |
| Tags | osint, juicy-info, cryptocyrrency |
| Severity | info |
| Description | Extract possible crypto addresses (long strings) from web page body |

**Request**
```http
GET / HTTP/1.1
Host: usersurvey.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.2117.157 Safari/537.36
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
Age: 64675
Content-Type: text/html
Date: Fri, 08 Dec 2023 06:03:48 GMT
Etag: W/"651d7d19cd0f221300cee5d446e87239"
Last-Modified: Fri, 04 Mar 2022 17:39:06 GMT
Server: AmazonS3
Vary: Accept-Encoding
Via: 1.1 6a3d98aad6a6ea4a9a35b5590bdb3da6.cloudfront.net (CloudFront)
X-Amz-Cf-Id: be0kmhY-VXghhGEIMX4sG5jpMWXKJtnxIUrq8Rs3CWro4RJW2c1wJQ==
X-Amz-Cf-Pop: MRS52-P1
X-Cache: Hit from cloudfront

<html>
  <head>
    <script type="text/javascript">
      // TODO (SURFDESK-768): Switch to using TS and our ts build pipeline
      (function() {
        var IS_PROD = 'PROD' === 'PROD';
        var environmentId =  IS_PROD ? 'eHSY0Wh44Y' : 'ROWpl81YT_';
        var expectedOrigin = 'https://www.dropbox.com';

        // Snippet from Sprig (formerly UserLeap) to load their script
        (function(l,e,a,p) {
          window.Sprig = function(){U._queue.push(arguments)}
          var U = window.Sprig;U.appId = a;U._queue = [];
          a=l.createElement('script');
          a.async=1;a.src=e+'?id='+U.appId;
          // set up event listeners once Sprig has loaded
          a.addEventListener("load", setUpEventListeners);

          p=l.getElementsByTagName('script')[0];
          p.parentNode.insertBefore(a, p);
        })(document, 'https://cdn.sprig.com/shim.js', environmentId);

        function updateExpectedOrigin(origin) {
          // default to meta, but if we get a message from another known origin, roll with it
          var knownOrigins = ['https://www.dropbox.com', 'https://paper.dropbox.com'];
          if (expectedOrigin !== origin && knownOrigins.indexOf(origin) !== -1) {
            expectedOrigin = origin;
          }
        }

        function recieveMessage(message) {
          // ignore messages that don't come from parent
          if (message.source !== window.parent) {
            return;
          }

          // recieve messages from metaserver and Paper
          updateExpectedOrigin(message.origin);
          if (message.origin !== expectedOrigin) {
            return;
          }

          data = message.data;

          switch (data.eventType) {
            case 'setUserId':
              window.Sprig('setUserId', data.eventData.userId);
              break;
            case 'setWindowDimensions':
              window.Sprig('setWindowDimensions', data.eventData.width, data.eventData.height);
              break;
            case 'trackEvent':
              window.Sprig('track', data.eventData.eventName);
              break;
            case 'addAttribute':
              window.Sprig('setAttribute', data.eventData.key, data.eventData.value);
              break;
            case 'removeAttribute':
              window.Sprig('removeAttributes', [data.eventData.key]);
              break;
            case 'logout':
              window.Sprig.logoutUser();
              break;
            case 'displayTestSurvey':
              if (!IS_PROD) {
                // displays a test survey from Userleap.
                // The survey id here corresponds with a test survey in Userleap's dev environment
                window.Sprig.displaySurvey(10323);
              }
              break;
            default:
              console.log("invalid event type: " + data.eventType);
          }
        }

        window.addEventListener('message', recieveMessage, false);

        // Send a message to the parent to resize the parent to survey iframe size
        function resizeIframe(data) {
          var surveyFrame = window.document.getElementById('ul-frame');
          if (surveyFrame) {
            var surveyWidth = data.contentFrameWidth || surveyFrame.offsetWidth;
            var surveyHeight = data.contentFrameHeight;
            var messageData = {
                eventType: 'surveyResized',
                surveyHeight: surveyHeight,
                surveyWidth: surveyWidth,
            }
            window.parent.postMessage(messageData, expectedOrigin);
          }
        }

        function surveyClosed() {
          var messageData = {
            eventType: 'surveyClosed',
          }
          window.parent.postMessage(messageData, expectedOrigin);
        }

        function surveyPresented() {
          var messageData = {
            eventType: 'surveyPresented',
          }
          window.parent.postMessage(messageData, expectedOrigin);
        }

        function setUpEventListeners() {
          if (!window.Sprig.UPDATES) {
            // Wait for the SDK to be ready if it's not immediately available.
            //
            // 'sdk.ready' should be Sprig.UPDATES.SDK_READY, but since it's not
            // ready, we can't reference it when adding a listener /shrug
            window.Sprig('addListener', 'sdk.ready', setUpEventListeners);
            return;
          }

          window.Sprig('addListener', window.Sprig.UPDATES.SURVEY_HEIGHT, resizeIframe);
          window.Sprig('addListener', window.Sprig.UPDATES.SURVEY_DIMENSIONS, resizeIframe);
          window.Sprig('addListener', window.Sprig.UPDATES.SURVEY_CLOSED, su.... Truncated ....
```

**Extra Information**

**Extracted results:**

- data.eventData.width
- data.eventData.eventName
- window.addEventListener
- window.document.getElementById
- window.Sprig.UPDATES.SURVEY_DIMENSIONS
- window.Sprig.UPDATES.SURVEY_CLOSED
- p.parentNode.insertBefore
- updateExpectedOrigin
- data.eventData.userId
- data.eventData.value
- Sprig.UPDATES.SDK_READY
- window.Sprig.UPDATES
- window.Sprig.UPDATES.SURVEY_HEIGHT
- knownOrigins.indexOf
- data.eventData.height
- window.Sprig.displaySurvey
- data.contentFrameWidth
- window.parent.postMessage
- l.getElementsByTagName
- window.Sprig.logoutUser
- surveyFrame.offsetWidth
- data.contentFrameHeight
- window.Sprig.UPDATES.SURVEY_PRESENTED



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.2117.157 Safari/537.36' 'https://usersurvey.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)