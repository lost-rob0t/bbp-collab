### OSINT Extração de URLS (osint-extractor-url) found on https://blog.dropbox.com

----
**Details**: **osint-extractor-url** matched at https://blog.dropbox.com

**Protocol**: HTTP

**Full URL**: https://blog.dropbox.com

**Timestamp**: Sat Dec 9 00:00:39 +0000 UTC 2023

**Template Information**

| Key | Value |
| --- | --- |
| Name | OSINT Extração de URLS |
| Authors | mrcl0wn / osint brazuca |
| Tags | url, consulta, osint |
| Severity | info |
| Description | Extração de URLS via expressão regular |

**Request**
```http
GET / HTTP/1.1
Host: blog.dropbox.com
User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux i686 on x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/53.0.2820.59 Safari/537.36
Connection: close
Accept: */*
Accept-Language: en
Accept-Encoding: gzip


```

**Response**
```http
HTTP/1.1 200 OK
Connection: close
Accept-Ranges: bytes
Age: 8
Cache-Control: max-age=0
Content-Type: text/html;charset=utf-8
Date: Sat, 09 Dec 2023 00:00:38 GMT
Expires: Sat, 09 Dec 2023 00:00:38 GMT
Server: Apache
Vary: Accept-Encoding
Via: 1.1 cb33d1722582b68ec8b5fec11b890e08.cloudfront.net (CloudFront)
X-Amz-Cf-Id: F28RqWJ6KXwhpMZWkHJGft7CBmJwY9FwgpGrSGYIvXnqopr-EBMOWQ==
X-Amz-Cf-Pop: MSP50-P1
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Dispatcher: dispatcher1uswest1
X-Frame-Options: SAMEORIGIN
X-Vhost: dropbox-prod.adobemsbasic.com

<!doctype html>
    
    
    
    
    <html lang="en" xml:lang="en" data-cms-lang="en-us">
    <head>
        <meta charset="utf-8"/>

<title>Work in Progress | Dropbox Blog</title>



<link rel="canonical" href="https://blog.dropbox.com/"/>



<meta name="quotasDisabled" content="true"/>
<meta name="pricingDisabled" content="true"/>



<meta name="primary_color" content="coconut"/>
<meta name="secondary_color" content="orchid plum"/>



<link rel="icon" href="https://aem.dropbox.com/cms/content/dam/dropbox/aem/favicon32.ico" type="image/x-icon"/>
<link rel="alternate" type="application/rss+xml" title="RSS Feed for Dropbox blog" href="https://blog.dropbox.com/feed/"/>




 
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



<meta property="og:url" content="https://blog.dropbox.com/"/>
<meta property="og:type" content="article"/>
<meta property="og:title" content="Work in Progress: by Dropbox"/>

<meta property="og:image" content="https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2019/02/social_card_wip.png"/>


<meta name="twitter:card" content="summary_large_image"/>



<meta content="width=device-width,initial-scale=1.0,user-scalable=no" name="viewport"/>



    <link rel="alternate" hreflang="en-us" href="https://blog.dropbox.com/"/>









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
                a = "\/\/tags.tiqcdn.com\/utag\/dropbox\/blog\/prod\/utag.js";
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
    




<!-- blog-collection-page-horizontal-scroll -->
<style>
body.new-blog-collection__page .u01-header__color-panel {
    transition: none;
}
@media screen and (min-width: 1300px) {
	body.new-blog-collection__page {

		margin: 0;
		padding: 0;
	}

	body.new-blog-collection__page .u01-header {
		transform: translateY(-100%);
	}

    body.new-blog-collection__page .u01-header.visible {
        transform: translateY(0);
        transition: .6s cubic-bezier(0.25, 0, 0, 1);
    }

	body.new-blog-collection__page .u01-header,
	body.new-blog-collection__page .u01-header__header,
	body.new-blog-collection__page .u01-header__color-panel {
		background-color: white;
	}
	body.new-blog-collection__page .u01-header__logo-img--glyph path {
		fill: #000000;
	}
	body.new-blog-collection__page .u01-header__logo-img--word path {
		fill: #000000;
	}
	body.new-blog-collection__page .u03-navigation__list-link:link,
	body.new-blog-collection__page .u03-navigation__list-link:visited,
	body.new-blog-collection__page .u03-navigation__list-link:hover,
	body.new-blog-collection__page .u03-navigation__list-link:active,
	body.new-blog-collection__page .u03-navigation__list-link:focus,
	body.new-blog-collection__page .u03-navigation__list-nolink:link,
	body.new-blog-collection__page .u03-navigation__list-nolink:visited,
	body.new-blog-collection__page .u03-navigation__list-nolink:hover,
	body.new-blog-collection__page .u03-navigation__list-nolink:active,
	body.new-blog-collection__page .u03-navigation__list-nolink:focus {
		color: #000000;
	}
	body.new-blog-collection__page.u03-navigation__dropdown--op.... Truncated ....
```

**Extra Information**

**Extracted results:**

- https://www.dropbox.com/install
- https://dropboxbusinessblog.co.uk/
- https://www.dropbox.com
- https://blog.dropbox.com/topics/work-culture/how-an-ai-powered-telescope-is-helping-astronomers
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/company/2023/eric-cox/Eric%20Cox_Headshot.png/_jcr_content/renditions/Eric%20Cox_Headshot.webp
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/october/october-launch-post/OctoberLaunch_Header.png/_jcr_content/renditions/OctoberLaunch_Header.webp
- https://blog.dropbox.com/authors/graham-isador
- https://blog.dropbox.com/topics/company
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/november/assistive-tech-be-my-eyes/assistive%20tech%20be%20my%20AI%20blog.png/_jcr_content/renditions/assistive%20tech%20be%20my%20AI%20blog.webp
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/july/atelier-bruckner/ATB-MOTF-interior.png/_jcr_content/renditions/ATB-MOTF-interior.webp
- https://blog.dropbox.com/topics/work-culture/stephen-marche-creating-with-ai-without-outsourcing-the-fun
- https://www.dropbox.com/mobile
- https://www.dropbox.com/pithos/privacy_consent,top_frame_marketing_tracker,ux_analytics
- https://blog.dropbox.com/topics/customer-stories/taylor-osullivan
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/july/atelier-bruckner/ATB-MOTF-interior.png
- https://www.dropbox.com/business
- http://www.w3.org/2000/svg
- https://blog.dropbox.com/topics/work-culture/how-ai-will-affect-early-career-training
- https://www.dropbox.com/security
- https://www.dropbox.com/jobs
- http://www.html5rocks.com/en/tutorials/speed/animations/
- https://blog.dropbox.com/topics/made-in-dropbox
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2021/may/building-rapport/Rapport-header.png/_jcr_content/renditions/Rapport-header.webp
- https://www.dropbox.com/plus
- https://www.dropbox.com/business/app-integrations
- https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-blog/clientlib-all.dbef42ca81137e4b726d0f79d4ba6920.js
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/november/nvidia/dropbox-nvdia-social.jpeg
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/december/myth-studio/1080x1080.jpg/_jcr_content/renditions/1080x1080.webp
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/october/virtual-meetings/new-VM-hero.png
- https://www.dropbox.com/pro
- https://blog.dropbox.com/authors/tomi-akitunde
- https://blog.dropbox.com/topics/customer-stories/how-two-entrepreneurs-brought-an-ecuadorian-longevity-elixir-to-the-market
- https://blog.dropbox.com/topics/customer-stories/atelier-bruckner
- https://www.knotch-cdn.com/ktag/latest/ktag.min.js?accountId=4a897efb-0052-440f-82be-86256c8450d2
- https://blog.dropbox.com/topics/company/virtual-first-2023-our-learnings-as-a-lab-for-distributed-work
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/july/jordan-harrod/jordan-harrod-working-smarter-blog-resized.jpg/_jcr_content/renditions/jordan-harrod-working-smarter-blog-resized.webp
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/sundance-2023/aliens/aliens-abducted-my-parents-header.png
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/company/2022/dropbox-glyph-saph-van-1200-628.png
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/august/remotely-curious-creativity/1280x1280.png/_jcr_content/renditions/1280x1280.webp
- https://static.cloud.coveo.com/searchui/v2.10092/7/js/cultures/en.js
- https://blog.dropbox.com/collections/sundance-film-festival-2023
- https://www.dropboxbusinessblog.de/
- https://static.cloud.coveo.com/searchui/v2.10092/7/css/CoveoFullSearch.min.css
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/december/ai-astronomy/astronomers-BTSbot-hero.png/_jcr_content/renditions/astronomers-BTSbot-hero.webp
- https://www.dropbox.com/enterprise
- https://blog.dropbox.com/topics/customer-stories/myth-studio-animation
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/september/nmbello-studio/nifemi-marcus-bello-thumbnail.jpg/_jcr_content/renditions/nifemi-marcus-bello-thumbnail.webp
- https://blog.dropbox.com/topics/customer-stories/Spout
- https://blog.dropbox.com/topics/product/updates-to-our-storage-policy-on-dropbox-advanced
- https://blog.dropbox.com/topics/news/dropbox-and-nvidia
- https://blog.dropbox.com/authors/yiren-lu
- https://dropeverything.com.au/
- https://www.dropboxbusinessblog.fr/
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/december/ai-astronomy/astronomers-BTSbot-hero.png
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/company/2023/vf-recap-2023/vf-recap-hero.png/_jcr_content/renditions/vf-recap-hero.webp
- https://www.hellosign.com/
- https://www.dropbox.com/contact
- https://www.dropbox.com/terms
- https://blog.dropbox.com/collections/working-smarter
- https://blog.dropbox.com/search-results.html
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/november/assistive-tech-be-my-eyes/assistive%20tech%20be%20my%20AI%20blog.png
- https://blog.dropbox.com/authors/matthew-braga
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/october/ai-career-training/Ai-career-training-hero.png/_jcr_content/renditions/Ai-career-training-hero.webp
- https://blog.dropbox.com/feed/
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/july/jordan-harrod/jordan-harrod-working-smarter-blog-resized.jpg
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/company/2023/eric-cox/Eric%20Cox_Headshot.png
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/company/2022/dropbox-glyph-saph-van-1200-628.png/_jcr_content/renditions/dropbox-glyph-saph-van-1200-628.webp
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/august/claire-fry/voiceover-hero.jpg
- https://blog.dropbox.com/topics/company/dropbox-announces-q3-2023-results
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/december/myth-studio/1080x1080.jpg
- https://blog.dropbox.com/authors/ariana-espiritu
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/september/nmbello-studio/nifemi-marcus-bello-thumbnail.jpg
- https://blog.dropbox.com/topics/work-culture
- https://dropbox.tech/
- https://blog.dropbox.com/topics/company/welcome-eric-cox-the-new-chief-customer-officer-at-dropbox
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/october/ai-career-training/Ai-career-training-hero.png
- https://www.knotch-cdn.com/unit/latest/knotch.min.js
- https://blog.dropbox.com/collections
- https://search.cloud.coveo.com/rest/search
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/september/stephen-marche/marche-header.gif
- https://static.cloud.coveo.com/searchui/v2.10092/7/js/templates/templates.js
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/august/chatbot-humor/chatbot-humor-header.mp4
- https://app-sj01.marketo.com/js/forms2/js/forms2.min.js
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2019/02/social_card_wip.png
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/october/october-launch-post/OctoberLaunch_Header.png
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/september/esg-report/ImpactReport_Feature.png/_jcr_content/renditions/ImpactReport_Feature.webp
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/september/chikichikiboomboom/ChikiChikiBoomBoom_feature.png
- https://blog.dropbox.com/topics/customer-stories/late-checkout
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/august/remotely-curious-creativity/1280x1280.png
- https://aem.dropbox.com/cms/etc.clientlibs/settings/wcm/designs/dropbox-blog/clientlib-all.f76cf10fd604257f854377f6bea7b361.css
- https://blog.dropbox.com/topics/product-tips
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/september/chikichikiboomboom/ChikiChikiBoomBoom_feature.png/_jcr_content/renditions/ChikiChikiBoomBoom_feature.webp
- https://www.dropbox.com/privacy
- https://blog.dropbox.com/authors/dropbox-team
- https://blog.dropbox.com/topics/company/our-2022-diversity-report
- https://blog.dropbox.com/topics/work-culture/julia-taylor-rayz-on-AI-humor
- https://blog.dropbox.com/collections/virtual-first
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/company/2023/vf-recap-2023/vf-recap-hero.png
- https://blog.dropbox.com/topics/company/our-2022-impact-fact-sheet
- https://blog.dropbox.com/topics/work-culture/robby-ratan-on-virtual-meetings-in-the-age-of-ai
- https://blogs.dropbox.com/developers
- https://static.cloud.coveo.com/searchui/v2.10092/7/js/CoveoJsSearch.Lazy.min.js
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/september/esg-report/ImpactReport_Feature.png
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/company/2023/glyphs/Dropbox_Glyph_grey_1200x628.jpg/_jcr_content/renditions/Dropbox_Glyph_grey_1200x628.webp
- https://blog.dropbox.com/authors/drew-pearce1
- https://blog.dropbox.com/topics/customer-stories/nifemi-marcus-bello
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/august/late-checkout/late-checkout-header.mp4
- https://blog.dropbox.com/search-results
- https://blog.dropbox.com/topics/work-culture/economist-impact-cost-of-lost-focus-research-study-2023
- https://www.dropbox.com/about
- https://blog.dropbox.com/
- https://blog.dropbox.com/topics/customer-stories/claire-fry
- https://www.dropbox.com/plans?trigger=nr
- https://navi.dropbox.jp/
- https://blog.dropbox.com/topics/customer-stories
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2021/may/building-rapport/Rapport-header.png
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/august/claire-fry/voiceover-hero.jpg/_jcr_content/renditions/voiceover-hero.webp
- https://www.dropbox.com/features?trigger=global_footer
- https://www.dropbox.com/productivity
- https://www.docsend.com/
- https://help.dropbox.com
- https://investors.dropbox.com/
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/november/taylor/Taylor-Osullivan-hero.mp4
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/company/2023/earnings/Earnings-Q3-2023.png/_jcr_content/renditions/Earnings-Q3-2023.webp
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/company/2023/glyphs/Dropbox_Glyph_grey_1200x628.jpg
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/october/virtual-meetings/new-VM-hero.png/_jcr_content/renditions/new-VM-hero.webp
- https://blog.dropbox.com/topics/work-culture/hrishikesh-hirway-on-finding-discipline-and-creativity-in-remote-work
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/october/lost-focus/ei-lost-focus-2023.mp4
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/november/spout/spout-hero_animated.gif
- https://aem.dropbox.com/cms/content/dam/dropbox/www/en-us/news/about-dropbox-feb-2018.pdf
- https://blog.dropbox.com/topics/news
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/november/nvidia/dropbox-nvdia-social.jpeg/_jcr_content/renditions/dropbox-nvdia-social.webp
- https://aem.dropbox.com/cms/content/dam/dropbox/aem/favicon32.ico
- https://blog.dropbox.com/topics/work-culture/will-ai-redefine-workplace-accessibility
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/files/2023/sundance-2023/aliens/aliens-abducted-my-parents-header.png/_jcr_content/renditions/aliens-abducted-my-parents-header.webp
- https://aem.dropbox.com/cms/content/dam/dropbox/blog/company/2023/earnings/Earnings-Q3-2023.png
- https://blog.dropbox.com/topics/company/updated-tools-new-plans-and-web-redesign



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux i686 on x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/53.0.2820.59 Safari/537.36' 'https://blog.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)