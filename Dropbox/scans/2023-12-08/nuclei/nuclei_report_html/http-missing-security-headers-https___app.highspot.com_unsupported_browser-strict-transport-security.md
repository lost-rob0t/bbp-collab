### HTTP Missing Security Headers (http-missing-security-headers:strict-transport-security) found on https://view.dropbox.com

----
**Details**: **http-missing-security-headers:strict-transport-security** matched at https://view.dropbox.com

**Protocol**: HTTP

**Full URL**: https://app.highspot.com/unsupported_browser

**Timestamp**: Sat Dec 9 14:56:08 +0000 UTC 2023

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
Host: view.dropbox.com
User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.67 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Cache-Control: no-store, no-cache, must-revalidate, max-age=0
Content-Type: text/html;charset=utf-8
Date: Sat, 09 Dec 2023 14:56:08 GMT
P3p: CP="Highspot does not have a P3P policy."
Referrer-Policy: no-referrer-when-downgrade
Server: Apache
Set-Cookie: rack.session2=eyJzZXNzaW9uX2lkIjoiOTc1ZGNkNTExYzNmMjY4MjMzYjFmNTFjNmU5YjRkOGUyN2QwYjk1M2M0OGRjNmNiNTM3NjQ4MjQ3N2E4OWUwOCJ9--7d25b2026c97d61d92e72e338494f184b23f9124; domain=.highspot.com; path=/; expires=Mon, 08 Jan 2024 14:56:08 GMT; secure; HttpOnly; SameSite=None
Status: 200 OK
Timing-Allow-Origin: https://bam.nr-data.net, https://js-agent.newrelic.com
Vary: Accept-Encoding
X-Content-Type-Options: nosniff
X-Robots-Tag: noai
X-Xss-Protection: 1; mode=block

<!DOCTYPE html><html class='desktop' lang='en'><head>
<meta charset='utf-8'>
<meta content='IE=edge;chrome=1' http-equiv='X-UA-Compatible'>
<meta content='width=device-width,user-scalable=yes' id='meta-viewport' name='viewport'>
<title>Home | Highspot</title>

<script>
try {

var notInWorkerOrNode = typeof window !== 'undefined';
if (notInWorkerOrNode) {
  window.hsDisableRollbarReporting = false;
}
var _rollbarConfig = {
    accessToken: "4334b0fb2b5c40e38d51572453ac0a46",
    autoInstrument: false,
    captureUncaught: true,
    captureUnhandledRejections: false,
    enabled: false,
    payload: {
      client: {
        javascript: {
          code_version: "d7ccf27b"
        }
      },
      environment: "production0-su0"
    },
    verbose: false
};


// Rollbar Snippet
!function(r){var e={};function o(n){if(e[n])return e[n].exports;var t=e[n]={i:n,l:!1,exports:{}};return r[n].call(t.exports,t,t.exports,o),t.l=!0,t.exports}o.m=r,o.c=e,o.d=function(r,e,n){o.o(r,e)||Object.defineProperty(r,e,{enumerable:!0,get:n})},o.r=function(r){"undefined"!=typeof Symbol&&Symbol.toStringTag&&Object.defineProperty(r,Symbol.toStringTag,{value:"Module"}),Object.defineProperty(r,"__esModule",{value:!0})},o.t=function(r,e){if(1&e&&(r=o(r)),8&e)return r;if(4&e&&"object"==typeof r&&r&&r.__esModule)return r;var n=Object.create(null);if(o.r(n),Object.defineProperty(n,"default",{enumerable:!0,value:r}),2&e&&"string"!=typeof r)for(var t in r)o.d(n,t,function(e){return r[e]}.bind(null,t));return n},o.n=function(r){var e=r&&r.__esModule?function(){return r.default}:function(){return r};return o.d(e,"a",e),e},o.o=function(r,e){return Object.prototype.hasOwnProperty.call(r,e)},o.p="",o(o.s=0)}([function(r,e,o){"use strict";var n=o(1),t=o(4);_rollbarConfig=_rollbarConfig||{},_rollbarConfig.rollbarJsUrl=_rollbarConfig.rollbarJsUrl||"https://ddmea0555purw.cloudfront.net/rollbarjs/refs/tags/v2.15.2/rollbar.min.js",_rollbarConfig.async=void 0===_rollbarConfig.async||_rollbarConfig.async;var a=n.setupShim(window,_rollbarConfig),l=t(_rollbarConfig);window.rollbar=n.Rollbar,a.loadFull(window,document,!_rollbarConfig.async,_rollbarConfig,l)},function(r,e,o){"use strict";var n=o(2);function t(r){return function(){try{return r.apply(this,arguments)}catch(r){try{console.error("[Rollbar]: Internal error",r)}catch(r){}}}}var a=0;function l(r,e){this.options=r,this._rollbarOldOnError=null;var o=a++;this.shimId=function(){return o},"undefined"!=typeof window&&window._rollbarShims&&(window._rollbarShims[o]={handler:e,messages:[]})}var i=o(3),s=function(r,e){return new l(r,e)},d=function(r){return new i(s,r)};function c(r){return t((function(){var e=this,o=Array.prototype.slice.call(arguments,0),n={shim:e,method:r,args:o,ts:new Date};window._rollbarShims[this.shimId()].messages.push(n)}))}l.prototype.loadFull=function(r,e,o,n,a){var l=!1,i=e.createElement("script"),s=e.getElementsByTagName("script")[0],d=s.parentNode;i.crossOrigin="",i.src=n.rollbarJsUrl,o||(i.async=!0),i.onload=i.onreadystatechange=t((function(){if(!(l||this.readyState&&"loaded"!==this.readyState&&"complete"!==this.readyState)){i.onload=i.onreadystatechange=null;try{d.removeChild(i)}catch(r){}l=!0,function(){var e;if(void 0===r._rollbarDidLoad){e=new Error("rollbar.js did not load");for(var o,n,t,l,i=0;o=r._rollbarShims[i++];)for(o=o.messages||[];n=o.shift();)for(t=n.args||[],i=0;i<t.length;++i)if("function"==typeof(l=t[i])){l(e);break}}"function"==typeof a&&a(e)}()}})),d.insertBefore(i,s)},l.prototype.wrap=function(r,e,o){try{var n;if(n="function"==typeof e?e:function(){return e||{}},"function"!=typeof r)return r;if(r._isWrap)return r;if(!r._rollbar_wrapped&&(r._rollbar_wrapped=function(){o&&"function"==typeof o&&o.apply(this,arguments);try{return r.apply(this,arguments)}catch(o){var e=o;throw e&&("string"==typeof e&&(e=new String(e)),e._rollbarContext=n()||{},e._rollbarContext._wrappedSource=r.toString(),window._rollbarWrappedError=e),e}},r._rollbar_wrapped._isWrap=!0,r.hasOwnProperty))for(var t in r)r.hasOwnProperty(t)&&(r._rollbar_wrapped[t]=r[t]);return r._rollbar_wrapped}catch(e){return r}};for(var u="log,debug,info,warn,warning,error,critical,global,configure,handleUncaughtException,handleAnonymousErrors,handleUnhandledRejection,captureEvent,captureDomContentLoaded,captureLoad".split(","),p=0;p<u.length;++p)l.prototype[u[p]]=c(u[p]);r.expor.... Truncated ....
```


**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Windows NT 5.1) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/36.0.1985.67 Safari/537.36' 'https://view.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)