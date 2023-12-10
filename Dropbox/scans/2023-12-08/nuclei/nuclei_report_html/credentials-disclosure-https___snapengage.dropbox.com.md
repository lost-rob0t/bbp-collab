### Credentials Disclosure Check (credentials-disclosure) found on https://snapengage.dropbox.com

----
**Details**: **credentials-disclosure** matched at https://snapengage.dropbox.com

**Protocol**: HTTP

**Full URL**: https://snapengage.dropbox.com

**Timestamp**: Sat Dec 9 08:32:14 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Credentials Disclosure Check |
| Authors | sy3omda, forgedhallpass, geeknik |
| Tags | exposure, token, key, api, secret, password |
| Severity | info |
| Description | Look for keys/tokens/passwords in HTTP responses, exposed keys/tokens/secrets requires manual verification for impact evaluation. |

**Request**
```http
GET / HTTP/1.1
Host: snapengage.dropbox.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_2) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1944.0 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Content-Length: 30772
Content-Type: text/html
Date: Sat, 09 Dec 2023 08:32:06 GMT
Etag: "a2b8c8eea0df655e9f71f940eb8bccc3"
Last-Modified: Thu, 12 Oct 2023 23:25:23 GMT
Server: AmazonS3
Via: 1.1 472d8295289753113caedd2aa0660466.cloudfront.net (CloudFront)
X-Amz-Cf-Id: nbeCfw7Np3x-zlr9-_mWKxDV4dsPeHdbjkLp44vibRYLRGCntQQ6Rg==
X-Amz-Cf-Pop: MRS52-C2
X-Amz-Version-Id: 9qILw538dQnN.P02XORAW4pV6RkNGzA6
X-Cache: RefreshHit from cloudfront

<html>
  <head>
    <title>Dropbox SnapEngage Chats</title>
  </head>
  <body style="background-color: transparent">
    <script type="text/javascript">
      (function() {
        var TARGET_URL = 'https://www.dropbox.com';
        var TARGET_URLS = [
                'https://help.dropbox.com',
                'https://help-stg.dropbox.com',
                'https://experience.dropbox.com',
                'https://experience-stg.dropbox.com',
                'https://loc.formswift.com',
                'https://staging.formswift.com',
                'https://www.formswift.com',
                'https://formswift.com',
                TARGET_URL
        ];
        // window.postmessage requires a targetOrigin. Since there are multiple valid origins
        // we rely on this iframe first receiving a message before it sends a message, and store
        // where the valid received message origin is from.
        var STORED_VALID_ORIGIN;
        var PROACTIVE_IDS = {
          DEFAULT: 'd5c1efed-d0ef-4fca-8c7d-faff398ad272',
          TEST: 'd4fc2e96-d0eb-45c4-a48f-4526366894ca',
          DISCOVER_EXPERIMENT: 'ec36c6a5-a14c-43c0-920d-918cc8629527',
        };
        var REACTIVE_ID = 'aac361ec-f445-43be-a7c8-a6d25df31ced';
        var SUPPORT_ID;
        var legacyWidgetId = 'SnapABug_WP';
        // the chat widget itself
        var dsWidgetId = 'designstudio';
        // used if an agent is connected and has a profile pic
        var customButtonId = 'designstudio-minimize';
        // fallback if no agent is available or has no profile pic
        var stdButtonId = 'designstudio-button';

        var buttonIds = [customButtonId, stdButtonId];
        var childIds = [dsWidgetId].concat(buttonIds);

        function getProactiveChatId(key) {
          var id = PROACTIVE_IDS[key];
          return id ? id : PROACTIVE_IDS.DEFAULT;
        }

        (function polyfill() {
          Array.prototype.map =
            Array.prototype.map ||
            function(fn) {
              var rv = [];

              for (var i = 0, l = this.length; i < l; i++) {
                rv.push(fn(this[i]));
              }
              return rv;
            };
          Array.prototype.find =
            Array.prototype.find ||
            function(fn) {
              for (var i = 0, l = this.length; i < l; i++) {
                if (fn(this[i])) {
                  return this[i];
                }
              }
              return undefined;
            };
        })();

        function initializeVisitorInfo(data) {
          // Please see README
          window.chatData = {
            FirstName: data.FirstName,
            LastName: data.LastName,
            Email: data.Email,
            locale: data.locale,
            SessionID: data.SessionID,
            Country: data.Country,
            MktoInfo: data.MktoInfo,
            Pricing: data.pricing,
            user_id: data.user_id,
            authToken: data.authToken,
            proactiveMessage: '',
            proactiveAgentName: '',
            visitorFirstTimeVisitor: '',
            visitorAmountOfPreviousChats: '',
            visitorAmountOfPagesVisited: '',
            visitorTimeOnSite: '',
            visitorTimeOnPage: '',
            pageLoadTs: data.pageLoadTs,
            chatHmac: data.chatHmac,
            cxChatbotName: data.cxChatbotName,
            ncct: data.ncct,
            serviceTier: data.serviceTier,
            tags: data.tags,
            phoneSupportForPlusUsers: data.phoneSupportForPlusUsers,
            supportExperimentShowOnboardingNumber: data.supportExperimentShowOnboardingNumber,
            supportExperimentHideEmailOption: data.supportExperimentHideEmailOption,
            supportExperimentBasic36HourSla: data.supportExperimentBasic36HourSla,
            phoneSupportForProfessionalUsers: data.phoneSupportForProfessionalUsers,
            supportExperimentProfessionalPhoneSupportedLanguages:
              data.supportExperimentProfessionalPhoneSupportedLanguages,
          };
        }

        /**
         * The V2 check status only checks the status, it does not try to figure out
         * which chat id is current and switch the widget.
         * */
        function checkChatStatusV2() {
            SnapEngage.getAgentStatusAsync(function(online) {
                sendMessage('UpdateChatStatus', {online: online});
            });
        }

        /**
         * As opposed to startSupportChat/startReactiveChat, startChats only responsibility
         * is to try to start a chat with style overrides. It does not switch the widget.
         * */
        func.... Truncated ....
```

**Extra Information**

**Extracted results:**

- authToken: data



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_2) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1944.0 Safari/537.36' 'https://snapengage.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)