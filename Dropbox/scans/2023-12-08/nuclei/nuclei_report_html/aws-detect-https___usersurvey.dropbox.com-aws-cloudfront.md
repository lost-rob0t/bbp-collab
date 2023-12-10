### AWS Service - Detect (aws-detect:aws-cloudfront) found on https://usersurvey.dropbox.com

----
**Details**: **aws-detect:aws-cloudfront** matched at https://usersurvey.dropbox.com

**Protocol**: HTTP

**Full URL**: https://usersurvey.dropbox.com

**Timestamp**: Sat Dec 9 09:09:22 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | AWS Service - Detect |
| Authors | 6mile |
| Tags | tech, aws, amazon, alb, cloudfront, codebuild, gateway, xray, captcha, dynamodb, kms |
| Severity | info |
| Description | Detect if AWS is being used in the application. |
| CWE-ID | [CWE-200](https://cwe.mitre.org/data/definitions/200.html) |
| CVSS-Score | 0.00 |

**Request**
```http
GET / HTTP/1.1
Host: usersurvey.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 4.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/37.0.2049.0 Safari/537.36
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
Age: 11132
Content-Type: text/html
Date: Sat, 09 Dec 2023 06:04:31 GMT
Etag: W/"651d7d19cd0f221300cee5d446e87239"
Last-Modified: Fri, 04 Mar 2022 17:39:06 GMT
Server: AmazonS3
Vary: Accept-Encoding
Via: 1.1 54ba4737103cb6263e414e602fbbe752.cloudfront.net (CloudFront)
X-Amz-Cf-Id: PfJ6_MzBu1jRfn-0iisNfRpkjjMF8wtuI4jmDAmulVBZfbtFuET2GQ==
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

References: 
- https://github.com/6mile/cloud-headers

**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 4.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/37.0.2049.0 Safari/537.36' 'https://usersurvey.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)