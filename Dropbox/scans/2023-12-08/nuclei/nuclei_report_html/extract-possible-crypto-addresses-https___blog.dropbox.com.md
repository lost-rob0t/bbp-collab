### Possible crypto addresses (long strings) extractor (extract-possible-crypto-addresses) found on https://blog.dropbox.com

----
**Details**: **extract-possible-crypto-addresses** matched at https://blog.dropbox.com

**Protocol**: HTTP

**Full URL**: https://blog.dropbox.com

**Timestamp**: Sat Dec 9 00:00:41 +0000 UTC 2023

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

- -header__logo-img--glyph
- 9-homepage-plank__content-plane
- 9-homepage-plank__collections-pagination
- -navigation__dropdown--open
- -navigation__dropdown-toggle
- -featured-articles-plank__hero-title
- astronomers-BTSbot-hero.png
- -topic-carousel-plank__article-author
- julia-taylor-rayz-on-AI-humor
- window.utag_data.consent_categories
- document.body.classList.contains
- dropbox-nvdia-social.jpeg
- dropbox-nvdia-social.webp
- u09-language-selector__modal-list-link
- window.utag_data.evidon_enabled
- 9-homepage-plank__collection-eyebrow
- -navigation__list-link
- -article-collection-plank__article-content-div
- data-sly-attribute.data-id
- -featured-articles-plank__hero
- economist-impact-cost-of-lost-focus-research-study-
- data-transition-direction
- u09-language-selector__container
- -oZKeFsPSLcb0QcewzCMLr
- 9-homepage-plank__wrapper
- -topic-carousel-plank__article-img-colorPane
- ImpactReport_Feature.webp
- jordan-harrod-working-smarter-blog-resized.webp
- a.parentNode.insertBefore
- document.getElementsByClassName
- -article-progress-bar
- body.sidebar-nav--is-open
- dropeverything.com.au
- CoveoFullSearch.min.css
- 9-homepage-plank__collection-cta-content
- controllerItem.classList.add
- -navigation__dropdown-item
- -featured-articles-plank__article-topic
- 9-homepage-plank__collection-description
- -navigation__list-link-icon
- 9-homepage-plank__collection-cta
- mql.addEventListener
- -article-progress-bar__progress
- data-pagination-color
- nifemi-marcus-bello-thumbnail.jpg
- www.dropboxbusinessblog.fr
- -featured-articles-plank
- jordan-harrod-working-smarter-blog-resized.jpg
- dropbox-glyph-saph-van-
- data-marketo-form-id
- blog-collection-page-horizontal-scroll
- -featured-articles-plank__grid
- -navigation__toggle-bar
- -navigation__dropdown-link
- spout-hero_animated.gif
- -topic-carousel-plank__article-link
- -topic-carousel-plank__title
- -topic-carousel-plank__eyebrow
- -topic-carousel-plank__article-img-wrap
- data-snapengage-widget-id
- NVAcKvVezXUCAxIklKyGEptRepHDvt
- will-ai-redefine-workplace-accessibility
- aliens-abducted-my-parents-header.png
- -topic-carousel-plank
- data-sly-attribute.height
- -topic-carousel-plank__article-img
- -featured-articles-plank__colorPane
- window.utag_cfg_ovrd
- document.body.classList.add
- u09-language-selector__modal-list
- -footer__lang-disclaimer
- u09-language-selector__modal-wrapper
- document.createElement
- -article-progress-bar__header
- -topic-carousel-plank__header
- -featured-articles-plank__article-title
- placeholder-slider-p
- -subscribe__marquee-content
- CoveoJsSearch.Lazy.min.js
- .page__slider--controller
- data-background-desktop
- -navigation__dropdown
- robby-ratan-on-virtual-meetings-in-the-age-of-ai
- controller.appendChild
- -featured-articles-plank__article-img
- data-slider-background
- document.querySelectorAll
- data-sly-test.highRes
- -featured-articles-plank__hero-topic
- requestAnimationFrame
- Ai-career-training-hero.png
- -header__logo-img--word
- -featured-articles-plank__hero-image-link
- welcome-eric-cox-the-new-chief-customer-officer-at-dropbox
- -featured-articles-plank__hero-text
- -featured-articles-plank__color-panel
- remotely-curious-creativity
- blog-page__container
- window.addEventListener
- -topic-carousel-plank__article
- window.failedAttempts
- window.requestAnimationFrame
- 9-homepage-plank__collections-content
- how-two-entrepreneurs-brought-an-ecuadorian-longevity-elixir-to-the-market
- -footer__group-list-item
- -featured-articles-plank__hero-photographer
- -our-learnings-as-a-lab-for-distributed-work
- updated-tools-new-plans-and-web-redesign
- OctoberLaunch_Header.png
- static.cloud.coveo.com
- 9-homepage-plank__container
- dropboxbusinessblog.co.uk
- stephen-marche-creating-with-ai-without-outsourcing-the-fun
- aem-GridColumn--default--
- -featured-articles-plank__hero-image-transition
- ChikiChikiBoomBoom_feature.png
- scrollContainer.scrollTop
- containerScrollHeight
- window.removeEventListener
- dropboxproductionpmlw0l
- -article-progress-bar__container
- data-transition-background
- u09-language-selector__modal-x
- u09-language-selector__modal-list-item
- slidingOverlay__animated-logo
- -featured-articles-plank__hero-image
- how-an-ai-powered-telescope-is-helping-astronomers
- -navigation__list-nolink
- u09-language-selector
- 9-homepage-plank__content
- OctoberLaunch_Header.webp
- u09-language-selector__modal
- -featured-articles-plank__article
- assistive-tech-be-my-eyes
- 9-homepage-plank__image-plane
- -footer__link-list-item
- body.new-blog-collection__page.u0
- scrollContainer.scrollHeight
- slider.style.transform
- 9-homepage-plank__collection-title
- ATB-MOTF-interior.webp
- slidingOverlay__logo
- topic-slide-trigger-
- u09-language-selector__modal-content
- u09-language-selector__selector-link
- -topic-carousel-plank__wrapper
- www.dropboxbusinessblog.de
- slider.removeAttribute
- search.cloud.coveo.com
- data-secondary-color
- investors.dropbox.com
- document.getElementById
- u09-language-selector__modal-box
- document.querySelector
- -topic-carousel-plank__carousel
- -topic-carousel-plank__article-topic-tag
- how-ai-will-affect-early-career-training
- myth-studio-animation
- topic-slide-trigger-0
- data-sly-attribute.width
- Taylor-Osullivan-hero.mp
- ChikiChikiBoomBoom_feature.webp
- u09-language-selector__modal-title
- top_frame_marketing_tracker
- nifemi-marcus-bello-thumbnail.webp
- Ai-career-training-hero.webp
- b.getElementsByTagName
- scrollContainer.addEventListener
- u09-language-selector__selector-modal
- google-site-verification
- -featured-articles-plank__img_wrapper
- -topic-carousel-plank__article-publish
- window.utag_cfg_ovrd.noview
- -topic-carousel-plank__article-title
- hrishikesh-hirway-on-finding-discipline-and-creativity-in-remote-work
- overlay.classList.add
- -navigation__list-item
- aliens-abducted-my-parents-header.webp
- -header__header-logo
- scrollContainer.removeEventListener
- data-transition-foreground
- ImpactReport_Feature.png
- -featured-articles-plank__hero-image-transition_wrapper
- 9-homepage-plank__collection-item
- body.new-blog-collection__page
- -header__color-panel
- -featured-articles-plank__wrapper
- astronomers-BTSbot-hero.webp
- updates-to-our-storage-policy-on-dropbox-advanced
- new-blog-collection__page
- -featured-articles-plank__hero-media
- late-checkout-header.mp
- coveo-search-section
- -topic-carousel-plank__button
- 9-homepage-plank__collections
- ATB-MOTF-interior.png
- chatbot-humor-header.mp
- sundance-film-festival-
- data-query-suggest-character-threshold
- animation-img-container
- u09-language-selector__modal-overlay



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (X11; Ubuntu; Linux i686 on x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/53.0.2820.59 Safari/537.36' 'https://blog.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)