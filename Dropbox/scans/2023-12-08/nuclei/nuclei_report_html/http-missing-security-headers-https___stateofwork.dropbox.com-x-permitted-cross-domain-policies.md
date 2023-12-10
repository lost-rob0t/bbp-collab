### HTTP Missing Security Headers (http-missing-security-headers:x-permitted-cross-domain-policies) found on https://stateofwork.dropbox.com

----
**Details**: **http-missing-security-headers:x-permitted-cross-domain-policies** matched at https://stateofwork.dropbox.com

**Protocol**: HTTP

**Full URL**: https://stateofwork.dropbox.com

**Timestamp**: Sat Dec 9 14:55:57 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | HTTP Missing Security Headers |
| Authors | socketz, geeknik, g4l1t0, convisoappsec, kurohost, dawid-czarnecki |
| Tags | misconfig, generic |
| Severity | info |
| Description | It searches for missing security headers, but obviously, could be so less generic and could be useless for Bug Bounty. |

**Request**
```http
GET / HTTP/1.1
Host: stateofwork.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 6.3; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2225.0 Safari/537.36
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
Age: 1385
Content-Type: text/html
Date: Sat, 09 Dec 2023 14:32:53 GMT
Etag: W/"688467fdeddda985547e4cf2d31acf0f"
Last-Modified: Tue, 07 Jan 2020 18:25:38 GMT
Server: AmazonS3
Vary: Accept-Encoding
Via: 1.1 9ba4efea4d7fc27f92a66f28df5d1152.cloudfront.net (CloudFront)
X-Amz-Cf-Id: -dynnOtXBlxO1L3IiDO7RC6CLAvZCaPJ0la1tz3ShBzoeVPB8KkKLg==
X-Amz-Cf-Pop: MRS52-C1
X-Cache: Hit from cloudfront

<!DOCTYPE html><html><head><script async="" src="https://www.googletagmanager.com/gtag/js?id=UA-279179-37"></script><noscript><img height="1" width="1" style="display:none" src="https://www.facebook.com/tr?id=1097950916987081&ev=PageView&noscript=1"></noscript><noscript><img height="1" width="1" style="display:none" src="https://www.facebook.com/tr?id=329181751193634&ev=PageView&noscript=1"></noscript><script>function e(){dataLayer.push(arguments)}window.dataLayer=window.dataLayer||[],e("js",new Date),e("config","UA-279179-37"),function(e,t,n,a,i,c,s){e.fbq||(i=e.fbq=function(){i.callMethod?i.callMethod.apply(i,arguments):i.queue.push(arguments)},e._fbq||(e._fbq=i),i.push=i,i.loaded=!0,i.version="2.0",i.queue=[],(c=t.createElement(n)).async=!0,c.src="https://connect.facebook.net/en_US/fbevents.js",(s=t.getElementsByTagName(n)[0]).parentNode.insertBefore(c,s))}(window,document,"script"),fbq("init","1097950916987081"),fbq("track","PageView"),fbq("track","ViewContent"),function(e,t,n,a,i,c,s){e.fbq||(i=e.fbq=function(){i.callMethod?i.callMethod.apply(i,arguments):i.queue.push(arguments)},e._fbq||(e._fbq=i),i.push=i,i.loaded=!0,i.version="2.0",i.queue=[],(c=t.createElement(n)).async=!0,c.src="https://connect.facebook.net/en_US/fbevents.js",(s=t.getElementsByTagName(n)[0]).parentNode.insertBefore(c,s))}(window,document,"script"),fbq("init","329181751193634"),fbq("track","PageView"),function(e,t,n,a,i,c){e.twq||((a=e.twq=function(){a.exe?a.exe.apply(a,arguments):a.queue.push(arguments)}).version="1.1",a.queue=[],(i=t.createElement(n)).async=!0,i.src="//static.ads-twitter.com/uwt.js",(c=t.getElementsByTagName(n)[0]).parentNode.insertBefore(i,c))}(window,document,"script"),twq("init","nvx41"),twq("track","PageView"),_linkedin_partner_id="4373",window._linkedin_data_partner_ids=window._linkedin_data_partner_ids||[],window._linkedin_data_partner_ids.push(_linkedin_partner_id),function(){var e=document.getElementsByTagName("script")[0],t=document.createElement("script");t.type="text/javascript",t.async=!0,t.src="https://snap.licdn.com/li.lms-analytics/insight.min.js",e.parentNode.insertBefore(t,e)}();</script><noscript> <img height="1" width="1" style="display:none;" alt="" src="https://px.ads.linkedin.com/collect/?pid=4373&fmt=gif"> </noscript><meta charset="utf-8"><meta http-equiv="X-UA-Compatible" content="IE=edge"><title>How Work Became a Mess</title><link rel="icon" sizes="16x16" href="favicon.94368490.ico"><meta name="description" content="How Work Became a Mess"><meta name="viewport" content="width=device-width, initial-scale=1"><link rel="stylesheet" href="js.470a5c6b.css"></head><body> <main>  <section id="scrolly"> <div class="end-title-button-container"> <button class="cta-button">Learn More</button> </div> <figure id="scrolly-figure" class="sticky"> <svg id="svg-chapter0" class="chapter-svg"></svg> <div id="title-container"> <div id="spaceholder-paragraph"></div> <div id="title-card-container"> <p id="title-card">  Loading... </p> </div> <div id="logo-container"> <p id="presented-by"> <span id="presented-by-text">Presented by</span> <img id="dbLogo" src="dropbox.abb63f8b.svg"> </p> </div> <div id="carrot-container"> <span class="scroll-down-text">scroll down</span> <img class="down-carrot" src="dc2.b4e293a7.svg" alt=""> </div> </div> <svg id="svg-chapter1" class="chapter-svg"></svg> <svg id="svg-chapter2" class="chapter-svg chapter-svg-text-left"></svg> <div id="overlay"></div> <svg id="svg-chapter2-barchart" class="chapter-svg chapter-svg-text-left"></svg> <svg id="svg-chapter3" class="chapter-svg"></svg> <div id="slide-frame" class="slide-frame"> <div class="slide-center-text-wrapper"> <h1 id="slide-frame-title">The Productivity Paradox</h1> <span id="slide-frame-text"> <p> Around the world, people are realizing their working lives have become exhausting and unproductive. </p> <br> <p> We wake up, write emails, sit in meetings, and switch between a dozen or more apps all day, but somehow it never feels like the work is getting done. </p> </span> </div> </div> </figure> <article> <div class="step step-no-show" datastep="0.1"> <div class="step-container"> <p class="step-paragraph"> 0.1 </p> </div> </div> <div class="step-spacer"></div> <div class="step step-no-show" datastep="0.3"> <div class="step-container"> <p>SLIDE FRAME 1 START</p> </div> <div class="step-spacer"></div> </div> <div class="step step-no-show" datastep="1.0"> <div class="step-container"> <p>SLIDE FRAME 1 END</p> </div> <div class="step-spacer"></div> </div> <div class="step" datastep="1.1"> <div class="step-container"> <p> Over the last two decades, we've taken huge technological strides that shoul.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 6.3; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2225.0 Safari/537.36' 'https://stateofwork.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)