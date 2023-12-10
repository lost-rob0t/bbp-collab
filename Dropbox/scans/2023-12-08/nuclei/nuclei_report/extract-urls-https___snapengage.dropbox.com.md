### Urls extractor (extract-urls) found on https://snapengage.dropbox.com

----
**Details**: **extract-urls** matched at https://snapengage.dropbox.com

**Protocol**: HTTP

**Full URL**: https://snapengage.dropbox.com

**Timestamp**: Sat Dec 9 00:01:34 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | Urls extractor |
| Authors | cipher387 |
| Tags | osint, juicy-info |
| Severity | info |
| Description | Extract urls from web page body |

**Request**
```http
GET / HTTP/1.1
Host: snapengage.dropbox.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_8_4) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/49.0.2656.18 Safari/537.36
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
Date: Sat, 09 Dec 2023 00:01:34 GMT
Etag: "a2b8c8eea0df655e9f71f940eb8bccc3"
Last-Modified: Thu, 12 Oct 2023 23:25:23 GMT
Server: AmazonS3
Via: 1.1 4e5f1284c7adec8eb684759fa9456cb0.cloudfront.net (CloudFront)
X-Amz-Cf-Id: wr6xy43MnWx-_P69fe8toirafQuRArX0vY2-b_DePaXsQuGcovSEWQ==
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

- https://formswift.com
- https://experience.dropbox.com
- https://loc.formswift.com
- https://staging.formswift.com
- https://www.formswift.com
- https://cc.pp.dropbox.com/app/hmac_verification?user_id=
- https://www.dropbox.com
- https://help.dropbox.com
- https://help-stg.dropbox.com
- https://experience-stg.dropbox.com



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_8_4) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/49.0.2656.18 Safari/537.36' 'https://snapengage.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)