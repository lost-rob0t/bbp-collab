### Possible crypto addresses (long strings) extractor (extract-possible-crypto-addresses) found on https://status.dropbox.com

----
**Details**: **extract-possible-crypto-addresses** matched at https://status.dropbox.com

**Protocol**: HTTP

**Full URL**: https://status.dropbox.com

**Timestamp**: Sat Dec 9 00:01:38 +0000 UTC 2023

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
Host: status.dropbox.com
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.1916.47 Safari/537.36
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
Accept-Ranges: bytes
Access-Control-Allow-Origin: *
Atl-Traceid: 6201d1e9ff73427096af7ca1d6b794fa
Cache-Control: max-age=3, public
Content-Type: text/html; charset=utf-8
Date: Sat, 09 Dec 2023 00:01:36 GMT
Etag: W/"d82d02e160ac8b3247245f26ce5199c3"
Link: <https://dka575ofm4ao0.cloudfront.net/assets/register_subscription_form-589b657fec607087fc5c740c568270907310bc4f6aaa20256e70f01b103025ca.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/status_common-c1b99d73ee7ab0fea796bd170723c1daac1381095a7dd7501a38ce6f333d86b3.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/0.6bb03ffda3ffadfa27a1.css>; rel=preload; as=style; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/status/status_manifest-cc9fd99d26ea5cca6f3352190ad1a451683d356cd9a12bb1c7d57870bed73318.css>; rel=preload; as=style; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/jquery-3.5.1.min-729e416557a365062a8a20f0562f18aa171da57298005d392312670c706c68de.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/assets/status_manifest-fe51120c5309a42b8fe23d0af40c6d1ddf533e0e24ebfb16557e15cd82189121.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/common-c3ca024b93f2e64d6f01.chunk.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/globals-3e964b59fb236dbfabd1.chunk.js>; rel=preload; as=script; nopush,<https://dka575ofm4ao0.cloudfront.net/packs/runtime-845beefc293f0b2f3a9a.js>; rel=preload; as=script; nopush
Nel: {"failure_fraction": 0.001, "include_subdomains": true, "max_age": 600, "report_to": "endpoint-1"}
Referrer-Policy: strict-origin-when-cross-origin
Report-To: {"endpoints": [{"url": "https://dz8aopenkvv6s.cloudfront.net"}], "group": "endpoint-1", "include_subdomains": true, "max_age": 600}
Server: AtlassianEdge
Strict-Transport-Security: max-age=63072000; preload
Vary: Accept,Accept-Encoding
Via: 1.1 bf5c45d38bcbc855bc2d697c4a8787b2.cloudfront.net (CloudFront)
X-Amz-Cf-Id: zjkQ5NzwXUgbqm_nGcVx3UfXdRfULbxgu6paUnWxadbNKEQIUSuAtA==
X-Amz-Cf-Pop: MRS52-C1
X-Cache: Miss from cloudfront
X-Content-Type-Options: nosniff
X-Download-Options: noopen
X-Edge-Cache-Ttl: 3
X-Permitted-Cross-Domain-Policies: none
X-Pollinator-Metadata-Service: status-page-web-pages
X-Runtime: 0.084504
X-Statuspage-Skip-Logging: true
X-Statuspage-Version: a7b5d580f11e475f053998d3a95134154d95445a
X-Xss-Protection: 1; mode=block

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <!-- force IE browsers in compatibility mode to use their most aggressive rendering engine -->

    <meta charset="utf-8">
    <title>Dropbox Status</title>
    <meta name="description" content="Welcome to Dropbox&#39;s home for real-time and historical data on system performance.">

    <!-- Mobile viewport optimization -->
    <meta name="HandheldFriendly" content="True">
    <meta name="MobileOptimized" content="320">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0">

    <!-- Time this page was rendered - http://purl.org/dc/terms/issued -->
    <meta name="issued" content="1702079818">

    <!-- Mobile IE allows us to activate ClearType technology for smoothing fonts for easy reading -->
    <meta http-equiv="cleartype" content="on">

    <!-- Le fonts -->
<style>
  @font-face {
    font-family: 'proxima-nova';
    src: url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaLight-f0b2f7c12b6b87c65c02d3c1738047ea67a7607fd767056d8a2964cc6a2393f7.eot?host=status.dropbox.com');
    src: url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaLight-f0b2f7c12b6b87c65c02d3c1738047ea67a7607fd767056d8a2964cc6a2393f7.eot?host=status.dropbox.com#iefix') format('embedded-opentype'),
         url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaLight-e642ffe82005c6208632538a557e7f5dccb835c0303b06f17f55ccf567907241.woff?host=status.dropbox.com') format('woff'),
         url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaLight-0f094da9b301d03292f97db5544142a16f9f2ddf50af91d44753d9310c194c5f.ttf?host=status.dropbox.com') format('truetype');
    font-weight:300;
    font-style:normal;
  }
   
  @font-face {
    font-family: 'proxima-nova';
    src: url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegular-366d17769d864aa72f27defaddf591e460a1de4984bb24dacea57a9fc1d14878.eot?host=status.dropbox.com');
    src: url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegular-366d17769d864aa72f27defaddf591e460a1de4984bb24dacea57a9fc1d14878.eot?host=status.dropbox.com#iefix') format('embedded-opentype'),
         url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegular-2ee4c449a9ed716f1d88207bd1094e21b69e2818b5cd36b28ad809dc1924ec54.woff?host=status.dropbox.com') format('woff'),
         url('https://dka575ofm4ao0.cloudfront.net/assets/ProximaNovaRegular-a40a469edbd27b65b845b8000d47445a17def8ba677f4eb836ad1808f7495173.ttf?host=status.dropbox.com') form.... Truncated ....
```

**Extra Information**

**Extracted results:**

- .components-statuses
- updates-dropdown-container
- relatedEvents.length
- register_subscription_form-
- custom-header-container
- wrapperDiv.setAttribute
- cloneList.appendChild
- .parentElement.parentElement.style.zIndex
- subscribers_disabled_error
- status_manifest-cc9fd99d
- css_body_background_color.
- .incident-title.impact-critical
- .layout-content.status.manage-subscriptions
- grecaptcha.enterprise.render
- .component-container.status-orange
- .update-title.impact-maintenance
- .layout-content.status.status-api
- show-updates-dropdown
- updates-dropdown-atom-btn
- captcha-terms-of-service-link
- this.mouseEnteredTooltip.bind
- document.querySelector
- event.target.getAttribute
- direct_message_channel_error
- .component-container.status-blue
- .page-status.status-none
- component-group-opener
- .outage-field.partial
- tooltipster-borderless
- ProximaNovaRegular-a
- .layout-content.status.status-full-history
- .incident-title.impact-maintenance
- smsSubscriberCaptchaError
- document.getElementById
- rect.addEventListener
- grecaptcha.enterprise.reset
- incidentForm.querySelector
- .grouped-items-selector
- www.googletagmanager.com
- subscriptions.statuspage.io
- this.activeDay.hovered
- UptimeTooltipHandler.prototype.updateTooltipData
- this.updateGroupOutageFields
- related-event-header
- .components-uptime-link
- externalities-sms-container
- components-container
- UptimeTooltipHandler.prototype.updateOutageFields
- div.modal-open-incident-subscribe
- currentUptime.parentNode.replaceChild
- this.tooltipListener.bind
- UptimeTooltipHandler.prototype.bladeTouched
- UptimeTooltipHandler.prototype.hideTooltip
- submitNewWebhookSubscriber
- ProximaNovaSemibold-
- .shared-partial.uptime-90-days-wrapper
- iframesWithTitle.length
- duplicate_private_channel_error
- this.unhoverTooltip.bind
- UptimeTooltipHandler.prototype.updateHoveredDay
- .components-container
- updates-dropdown-sms
- updates-dropdown-slack
- email-notification-field
- availability-time-line-legend-day-count
- currentUptime.cloneNode
- this.pointerCenter.y
- .updates-dropdown-nav
- groupParentIndicator.attr
- submitCaptchaIncidentSubscribe
- updates-dropdown-atom
- phone-country-wrapper
- d.getElementsByTagName
- dayCountElements.length
- this.tooltip.style.display
- submitIncidentSubscriberError
- updates-dropdown-slack-btn
- updates-dropdown-section
- submit_incident_code
- ProximaNovaSemibold-09
- .page-status.status-maintenance
- dropbox_logo_glyph_m
- replace-with-subscribe
- updates-dropdown-twitter-btn
- submitNewEmailSubscriber
- scheduled-maintenance
- grecaptcha.enterprise.execute
- .incident-title.impact-none
- .component-container.status-red
- .component-container.status-yellow
- components-uptime-link
- UptimeTooltipHandler.prototype.resizeListener
- event.preventDefault
- .layout-content.status.status-index
- .component-inner-container.status-orange
- a.related-event-link
- fjs.parentNode.insertBefore
- document.addEventListener
- .page-status.status-critical
- .update-title.impact-major
- .incident-name.impact-minor
- partial-outage-group-count
- this.positionTooltip
- .update-title.impact-none
- product-specific-terms
- uptime-90-days-wrapper
- UptimeTooltipHandler.prototype.calculateBoxPosition
- g-recaptcha-response
- webhookSubscriberCaptchaError
- window.location.search
- ProximaNovaSemibold-cf
- .grouped-item.active
- .incident-name.impact-critical
- .update-title.impact-minor
- this.updateHoveredDay
- incidentCode.setAttribute
- updates-dropdown-sms-btn
- updates-dropdown-email
- cloud-terms-of-service
- .twitter-follow-button
- tooltipHandler.unhoverTooltip
- this.hoursFromSeconds
- updateCaptchaIframeTitle
- ProximaNovaRegularIt-0bf
- .unresolved-incident.impact-minor
- .confirmation-infobox
- fa-exclamation-triangle
- this.tooltip.getElementsByClassName
- updates-dropdown-twitter
- updates-dropdown-close-btn
- uptimeLinkVar.innerHTML
- cfl.dropboxstatic.com
- componentsContainer.addEventListener
- custom-footer-container
- subscribe-incident-recaptcha
- .unresolved-incident.impact-major
- www.dropboxforum.com
- resendBtn.style.display
- eventList.parentNode.replaceChild
- incidentForm.dispatchEvent
- .update-title.impact-critical
- component-statuses-legend
- componentCodeFromClass
- UptimeTooltipHandler.prototype.handleTouch
- this.activeDay.index
- this.calculateBoxPosition
- SP.currentPage.registerSubscriptionForm
- .layout-content.status-incident
- .incident-name.impact-major
- bnGeRfMZrCLNzkQTMkRoinbxmHGZ9HePnHaD
- Attention-SMS-notifications-will-be-disabled-on-August-
- UptimeTooltipHandler.prototype.orientationListener
- .group-parent-indicator
- ProximaNovaRegularIt-0c
- subscribe-form-email
- terms_and_privacy_information
- slack_authentication
- legend-item-date-range
- this.handleTouch.bind
- document.body.appendChild
- .incident-title.impact-minor
- dropdown.addEventListener
- tooltipHandler.updateHoveredDay
- .incident-name.impact-maintenance
- updates-dropdown-email-btn
- emailSubscriberCaptchaError
- checkSelectedCountry
- columnInfo.uptimeKey
- this.orientationListener.bind
- .flat-button.background-red
- document.querySelectorAll
- UptimeTooltipHandler.prototype.mouseEnteredTooltip
- this.updateOutageFields
- this.activeDay.bounds
- .layout-content.status-full-history
- .grouped-items-selector.inline
- document.createElement
- this.calculatePointerCenter
- .page-status.status-minor
- .component-inner-container.status-green
- availability-time-line-graphic
- UptimeTooltipHandler
- this.pointerCenter.x
- .component-container.status-green
- .updates-dropdown-container
- opt-container-section
- btn-subcriber-change-number
- event.stopPropagation
- UptimeTooltipHandler.prototype.updateGroupOutageFields
- .scheduled-incidents-container
- document.body.style.overflow
- document.body.style.height
- ProximaNovaLight-f0b
- document.getElementsByClassName
- window.Routes.incident_path
- groupParentIndicator.toggleClass
- ProximaNovaLight-0f09
- submitNewSmsSubscriber
- UptimeTooltipHandler.prototype.tooltipListener
- submitIncidentSubscriberSuccess
- event.target.getBoundingClientRect
- this.minutesFromSeconds
- UptimeTooltipHandler.prototype.positionTooltip
- UptimeTooltipHandler.prototype.calculatePointerCenter
- groupParentIndicator
- uptimeSpan.innerText
- .parsedResult.platform.type
- this.hideTooltip.bind
- UptimeTooltipHandler.prototype.minutesFromSeconds
- css_body_background_color
- .component-inner-container.status-red
- window.pageColorData
- .component-inner-container.status-blue
- page_display_customizations-custom_css_externals
- data-show-screen-name
- data.subscriber_code
- this.activeDay.isGroup
- ProximaNovaRegularIt-9e
- .timeframes-container
- this.activeDay.component
- updates-dropdown-close
- updates-dropdown-sections-container
- .getElementsByTagName
- tooltipBox.addEventListener
- submitIncidentSubscriber
- sms-notification-field
- document.createTextNode
- .component.startDate
- showcasedComponentsCount
- dropdown.selectedIndex
- subscribe-form-webhook
- .unresolved-incident.impact-critical
- SP.currentPage.updatesDropdown.hide
- tooltipCloseButton.addEventListener
- UptimeTooltipHandler.prototype.updateTooltip
- cpt-notification-container
- .layout-content.status
- updates-dropdown-nav
- window.addEventListener
- this.resizeListener.bind
- groupComponents.length
- .incident-title.impact-major
- twitter-follow-button
- window.navigator.userAgent
- UptimeTooltipHandler.prototype.hoursFromSeconds
- _globalsign-domain-verification
- tooltipHandler.updateTooltip
- this.updateTooltipData
- .updates-dropdown-section
- .unresolved-incident.impact-maintenance
- LtEkK-vxNAWKKksEQKpcoz
- community.atlassian.com
- selectedOption.getAttribute
- data-component-status
- statuspage-specific-terms
- incidentCaptcha.setAttribute
- phone-number-country-code
- component-inner-container
- UptimeTooltipHandler.prototype.unhoverTooltip
- .component-container
- data-revert-on-success
- el.parentNode.replaceChild
- .legend-item-date-range
- platform.twitter.com
- major-outage-group-count
- scheduled-maintenances-container
- modal-open-incident-subscribe
- .layout-content.status-index
- phoneNumberInput.prop
- event.target.classList.contains
- .show-updates-dropdown
- tooltipCloseButton.className
- listItem.appendChild
- event.target.id.split
- private_channel_success
- .page-status.status-major
- .component-inner-container.status-yellow
- legend-item-uptime-value



**CURL command**
```sh
curl -X 'GET' -H 'Accept: */*' -H 'Accept-Language: en' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.1916.47 Safari/537.36' 'https://status.dropbox.com'
```

----

Generated by [Nuclei v3.1.0-dev](https://github.com/projectdiscovery/nuclei)