# CookieNotice (Simplified)

This is a simplified version of [CookieNotice](https://github.com/AOEpeople/cookie-notice) by AOEpeople.

# Configuration

```html
<script src="js/cookie.notice.min.js"></script>
<script>
    new cookieNoticeJS({

       // Localizations of the notice message
       'i18n': {
         'en': 'Custom localized message'
       },

       // The href of the learn more link must be applied if (learnMoreLinkEnabled=true)
       'linkHref': '/privacy',

       // Text for optional learn more button
       'linkText':{
           'en':'learn more'
       },

       // The message will be shown again in X days
       'expiresIn': 30

    });
</script>
```

## Configuration via `data-` attribute

Configuration options can be put in a `data-cookie-notice` HTML attribute in JSON format.

For example:

```html
<div
  data-cookie-notice='{ "linkHref": "/privacy.html" }'></div>

<script>
  src="cookie.notice.min.js"
></script>
```
