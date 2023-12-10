### Urls extractor (extract-urls) found on https://help.dropbox.com

----
**Details**: **extract-urls** matched at https://help.dropbox.com

**Protocol**: HTTP

**Full URL**: https://help.dropbox.com

**Timestamp**: Sat Dec 9 00:01:08 +0000 UTC 2023

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
Host: help.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Cache-Control: max-age=0
Content-Type: text/html;charset=utf-8
Date: Sat, 09 Dec 2023 00:01:04 GMT
Expires: Sat, 09 Dec 2023 00:01:03 GMT
Server: Apache
Vary: Accept-Encoding
Via: 1.1 887aba73f027fe4e82f965d15238ed3e.cloudfront.net (CloudFront)
X-Amz-Cf-Id: VzCLHHa0CcvDa6JhV-bpta03bOX86ML3lc0L-BqvOv6iUiwXiiaffg==
X-Amz-Cf-Pop: CDG52-P4
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Dispatcher: dispatcher1uswest1
X-Frame-Options: SAMEORIGIN
X-Vhost: dropbox-prod.adobemsbasic.com

<!doctype html>


    
    
    

    


    
    
    
    

    
    
    
    

    <html data-cms-lang="en-us">
    <head>
        

<meta charset="utf-8"/>




    <title>Dropbox Help Center - How to use Dropbox - Dropbox Help</title>



<meta name="coveopagetitle" content="Dropbox Help Center - How to use Dropbox"/>




<meta name="description" content="Explore the Dropbox Help Center to learn how to use Dropbox on your computer, phone, and tablet, and find answers to common questions."/>


<meta name="page-id" content="en-us-help"/>

    <link rel="canonical" href="https://help.dropbox.com/"/>




<meta name="uxAnalyticsEnabled" content="true"/>





<link rel="icon" href="https://aem.dropbox.com/cms/content/dam/dropbox/aem/favicon32.ico" type="image/x-icon"/>


 
<script>
    window.utag_cfg_ovrd = window.utag_cfg_ovrd || {};
    window.utag_cfg_ovrd.noview = true;
    window.utag_data = window.utag_data || {};
    window.utag_data.evidon_enabled = true;
    if(window.utag_data.consent_categories == undefined){
        window.utag_data.consent_categories = "";
    }
</script>
<script src="https://www.dropbox.com/pithos/privacy_consent,top_frame_marketing_tracker,ux_analytics" async="true"></script>






<meta property="og:url" content="https://help.dropbox.com/"/>
<meta property="og:type" content="article"/>
<meta property="og:title" content="Dropbox Help Center - How to use Dropbox"/>
<meta property="og:description" content="Explore the Dropbox Help Center to learn how to use Dropbox on your computer, phone, and tablet, and find answers to common questions."/>



<meta name="twitter:card" content="summary_large_image"/>



<meta content="width=device-width,initial-scale=1.0,user-scalable=no" name="viewport"/>



    <link rel="alternate" hreflang="id" href="https://help.dropbox.com/id-id"/>
    <link rel="alternate" hreflang="ms" href="https://help.dropbox.com/ms-my"/>
    <link rel="alternate" hreflang="da" href="https://help.dropbox.com/da-dk"/>
    <link rel="alternate" hreflang="de" href="https://help.dropbox.com/de-de"/>
    
    
    <link rel="alternate" hreflang="en" href="https://help.dropbox.com/"/>
    <link rel="alternate" hreflang="es-ES" href="https://help.dropbox.com/es-es"/>
    <link rel="alternate" hreflang="es" href="https://help.dropbox.com/es-la"/>
    <link rel="alternate" hreflang="fr" href="https://help.dropbox.com/fr-fr"/>
    <link rel="alternate" hreflang="it" href="https://help.dropbox.com/it-it"/>
    <link rel="alternate" hreflang="nl" href="https://help.dropbox.com/nl-nl"/>
    <link rel="alternate" hreflang="no" href="https://help.dropbox.com/nb-no"/>
    <link rel="alternate" hreflang="pl" href="https://help.dropbox.com/pl-pl"/>
    <link rel="alternate" hreflang="pt-BR" href="https://help.dropbox.com/pt-br"/>
    <link rel="alternate" hreflang="ru" href="https://help.dropbox.com/ru-ru"/>
    <link rel="alternate" hreflang="sv" href="https://help.dropbox.com/sv-se"/>
    
    <link rel="alternate" hreflang="zh-CN" href="https://help.dropbox.com/zh-cn"/>
    <link rel="alternate" hreflang="zh-TW" href="https://help.dropbox.com/zh-tw"/>
    <link rel="alternate" hreflang="ja" href="https://help.dropbox.com/ja-jp"/>
    <link rel="alternate" hreflang="ko" href="https://help.dropbox.com/ko-kr"/>




<!--/* Calling the tealium utag sync to avoid adobe target flickering */ -->



    
         
          <!-- CMS-5456 : Optimizing target calls -->
                
         
    

<!-- /* Calling the tealium utag sync to avoid adobe target flickering */  -->

    
        <script type="text/javascript">
            var attr = "tealium_event$cms".split(",");
            var utag_data = window.utag_data || {}
            attr.forEach(function (item) {
                if (item && item.indexOf("$") > -1)
                    utag_data[item.split("$")[0]] = item.split("$")[1];
            })
        </script>
        <script type="text/javascript">
            (function (a, b, c, d) {
                a = "\/\/tags.tiqcdn.com\/utag\/dropbox\/main\/prod\/utag.js";
                b = document;
                c = 'script';
                d = b.createElement(c);
                d.src = a;
                d.type = 'text/java' + c;
                d.async = true;
                a = b.getElementsByTagName(c)[0];
                a.parentNode.insertBefore(d, a);
            })();
        </script>
    




 .... Truncated ....
```

**Extra Information**

**Extracted results:**

- https://aem.dropbox.com/cms/etc.clientlibs/dropbox-dmep/clientlibs/clientlib-base.9d86e5741780393fe182a97b50a39567.css
- https://www.dropbox.com/business/buy
- https://help.dropbox.com/nl-nl
- https://help.dropbox.com/pl-pl
- https://www.dropboxforum.com/t5/Dropbox-API-Support-Feedback/my-android-app-not-uploading-photo-directly-to-Dropbox-app/td-p/732039
- https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-common/clientlib-search-helper.044960b7d350aeaaea97a8a410ecc62b.js
- https://help.dropbox.com/sv-se
- https://help.dropbox.com/share
- https://help.dropbox.com/?fallback=true
- https://www.dropbox.com/2/gromit/notify_interaction_event
- https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-birch-help/clientlib-all/resources/icon-top-up.svg
- https://help.dropbox.com/storage-space
- https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-birch-help/clientlib-all/resources/icon-view.svg
- https://www.dropboxforum.com/t5/View-download-and-export/All-files-downloaded-from-Dropbox-are-corrupt/td-p/734242
- https://www.dropboxatwork.com/
- https://help.dropbox.com/backup.html
- https://aem.dropbox.com/cms/content/dam/dropbox/dmep/assets/dwg-assets/icons/PersonMultiple.svg
- https://help.dropbox.com/ja-jp
- https://www.knotch-cdn.com/unit/latest/knotch.min.js
- https://help.dropbox.com/plans
- https://help.dropbox.com/installs
- http://schema.org/ImageObject
- https://help.dropbox.com/account-settings
- https://help.dropbox.com/dash
- https://learn.dropbox.com
- https://www.dropbox.com/business/trust
- https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-birch/clientlib-all/resources/arrow-black.svg
- https://help.dropbox.com/backup
- https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-birch-help/clientlib-all/resources/40_Wordmark.svg
- https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-birch-help/clientlib-all/resources/icon-thumb.svg
- https://investors.dropbox.com
- https://www.dropbox.com/privacy
- https://www.dropbox.com/2/gromit/get_support_resources
- https://help.dropbox.com/ru-ru
- https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-birch-help/clientlib-all/resources/search.svg
- https://help.dropbox.com/sign
- https://www.dropbox.com/business/app-integrations
- https://twitter.com/dropboxbusiness
- https://www.dropboxforum.com?trigger=_footer
- https://help.dropbox.com/
- https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-birch-help/clientlib-all/resources/icon-inner-up.svg
- http://www.w3.org/2000/svg
- https://search.cloud.coveo.com/rest/search
- https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-birch-help/clientlib-all/resources/icon-chat.svg
- https://help.dropbox.com/da-dk
- https://help.dropbox.com/es-es
- https://www.dropboxforum.com/t5/English/ct-p/English
- https://www.dropbox.com/enterprise
- https://www.dropbox.com/business/resources/faqs
- https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-birch-help/clientlib-all/resources/icon-top-down.svg
- https://www.dropbox.com/
- https://help.dropbox.com/replay.html
- https://www.dropbox.com/news
- https://www.dropbox.com/pithos/privacy_consent,top_frame_marketing_tracker,ux_analytics
- https://help.dropbox.com/capture.html
- https://help.dropbox.com/share/share-file-or-folder
- https://www.dropboxforum.com/t5/Apps-and-Installations/I-can-no-longer-open-Dropbox-from-the-icon-pinned-to-the-taskbar/td-p/735148
- https://www.dropbox.com/business/trust/security
- https://www.dropbox.com/contact
- https://static.cloud.coveo.com/searchui/v2.10092/7/js/CoveoJsSearch.Lazy.min.js
- https://static.cloud.coveo.com/searchui/v2.10092/7/js/templates/templates.js
- https://www.dropboxforum.com/t5/Delete-edit-and-organize/Mass-assign-an-existing-member-to-our-Team-Groups-Possible/td-p/731976
- https://www.dropbox.com/business
- https://help.dropbox.com/ko-kr
- https://aem.dropbox.com/cms/content/dam/dropbox/dmep/assets/dwg-assets/icons/Sprout.svg
- https://www.dropbox.com/features?trigger=global_footer
- https://static.cloud.coveo.com/searchui/v2.10107/css/CoveoFullSearch.css
- https://help.dropbox.com/es-la
- https://help.dropbox.com/zh-cn
- https://help.dropbox.com/billing/change-information
- https://www.dropbox.com/terms/cookies
- https://static.cloud.coveo.com/searchui/v2.10107/js/CoveoJsSearch.Lazy.min.js
- https://www.dropbox.com/support
- https://help.dropbox.com/create-upload
- https://help.dropbox.com/transfer
- https://www.dropbox.com/mobile
- https://help.dropbox.com/capture
- https://aem.dropbox.com/cms/content/dam/dropbox/aem/favicon32.ico
- https://static.cloud.coveo.com/coveo.analytics.js/2/coveoua.js
- https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-birch-help/clientlib-all/resources/40.svg
- https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-birch-help/clientlib-all/resources/32.svg
- https://help.dropbox.com/security
- https://www.dropbox.com/install
- https://help.dropbox.com
- https://www.dropbox.com/developers
- https://help.dropbox.com/de-de
- https://help.dropbox.com/nb-no
- https://help.dropbox.com/account-access
- https://help.dropbox.com/organize/how-to-use-dropbox-backup
- https://www.dropbox.com/business/partners
- https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-birch-help/clientlib-all/resources/icon-inner-down.svg
- https://help.dropbox.com/replay
- https://static.cloud.coveo.com/searchui/v2.10092/7/js/cultures/en.js
- https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-birch-help/clientlib-all/resources/search-black.svg
- https://help.dropbox.com/search-results
- https://help.dropbox.com/delete-restore
- https://help.dropbox.com/organize
- https://aem.dropbox.com/cms/content/dam/dropbox/dmep/assets/dwg-assets/icons/Lightbulb.svg
- https://help.dropbox.com/it-it
- https://static.cloud.coveo.com/searchui/v2.9856/8/css/CoveoFullSearch.min.css
- https://help.dropbox.com/id-id
- https://aem.dropbox.com/cms/etc.clientlibs/dropbox-dmep/clientlibs/clientlib-coveo.40a03dd75529d1abf2da25a1bed7a633.css
- https://help.dropbox.com/view-edit
- https://help.dropbox.com/integrations
- https://help.dropbox.com/fr-fr
- https://help.dropbox.com/sync
- https://www.dropbox.com/business/pricing
- https://www.dropbox.com/referrals
- https://aem.dropbox.com/cms/etc.clientlibs/dropbox-dmep/clientlibs/clientlib-dependencies.4309b328bfd674671ae561f47a29ba61.js
- https://www.dropboxforum.com/t5/Create-upload-and-share/Syncing-problem-on-Sonoma-14-1/td-p/733803
- https://www.dropboxforum.com/
- https://www.youtube.com/user/dropbox
- https://help.dropbox.com/ms-my
- https://aem.dropbox.com/cms/etc.clientlibs/dropbox-dmep/clientlibs/clientlib-base.bd1c8b8674d71c25d278618716d1a119.js
- https://help.dropbox.com/billing
- https://help.dropbox.com/passwords
- https://help.dropbox.com/security/password-reset
- https://www.facebook.com/Dropbox
- https://help.dropbox.com/pt-br
- https://help.dropbox.com/zh-tw
- https://www.knotch-cdn.com/ktag/latest/ktag.min.js?accountId=4a897efb-0052-440f-82be-86256c8450d2
- https://learn.dropbox.com/
- https://www.dropbox.com/sitemap
- https://help.dropbox.com/transfer.html
- https://help.dropbox.com/passwords.html



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.114 Safari/537.36' 'https://help.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)