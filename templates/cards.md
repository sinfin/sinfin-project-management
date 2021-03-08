# Project board cards template

## Usability checks

All these check you have to do on production environment!

### Common

- [ ] Run and analyze [W3C Markup Validation Service](https://validator.w3.org/) & [W3C Internationalization Checker](https://validator.w3.org/i18n-checker/) for important URLs at least.
- [ ] Check **favicon**. You can use [favicon-cheat-sheet](https://github.com/audreyfeldroy/favicon-cheat-sheet) on Gihub.
- [ ] Check existence of **404** & **500** pages.
- [ ] Check if all URLs are localized and friendly.
- [ ] Check if CSS if [print firendly](https://www.smashingmagazine.com/2011/11/how-to-set-up-a-print-style-sheet/).

### Usability

- [ ] Do the [Mobile-Friendly Test](https://search.google.com/test/mobile-friendly).

### Structured data

- [ ] Ad [structured data](https://schema.org/docs/gs.html)) & test  [them](https://search.google.com/structured-data/testing-tool).
- [ ] Test [Google Rich Snippets](https://search.google.com/test/rich-results).

### Social networks and page snippets

- [ ] Run [Facebook sharing debugger](https://developers.facebook.com/tools/debug/) & [Twitter Card Validator](https://cards-dev.twitter.com/validator) on main & typical URLs.

## Analytics and Trackers

- [ ] Check if [Google Analytics](https://analytics.google.com/analytics/web/) is up and running.
- [ ] Setup [Google Search Console](https://search.google.com/search-console) and verify a domain.
- [ ] Move trackers to [Goog Tag Manager](https://marketingplatform.google.com/) if there is more tracking and analytics scripts.
- [ ] Setup [GTM dataLayer](https://developers.google.com/tag-manager/devguide) if needed.
- [ ] Check possible ad scripts (Google Ads / Sklik.cz / ... ).

## SEO Sitemap.xml

- [ ] Setup [sitemap.rb](https://github.com/kjvarga/sitemap_generator) for all visible controllers.
- [ ] Optimize `changefreq` and `priority`.
- [ ] Check a [image sitemap](https://developers.google.com/search/docs/advanced/sitemaps/image-sitemaps?visit_id=637508300506565427-1547666485&rd=1) functionality.
- [ ] Check a correct sitemap URL in robots.txt.
- [ ] Check if there is `sitemap:refresh ` task in [schedule.rb](https://github.com/javan/whenever).

## SEO Robots.txt

- [ ] Check if the Disallow sections is needed.
- [ ] Check a correct sitemap URL in robots.txt.

## Performance

All these check you have to do on production environment. You can consult your strategy with the book [The Complete Guide to Rails Performance](https://www.railsspeed.com/).

- [ ] Check if database indexes are added and relevant.
- [ ] Check if fragment caching is on and relevant.
- [ ] Optimize a [response time](https://github.com/MiniProfiler/rack-mini-profiler) for all controllers with  `?rmp=1` parameter.
- [ ] Check if [Google PageSpeed](https://developers.google.com/speed/pagespeed/insights/) score is 90+.
- [ ] Check for common errors in Google PageSpeed Insights (webp, images size, HTTP/2 etc).

## Security

- [ ] Verify **domain name** and [**SSL certificate**](https://www.ssllabs.com/ssltest/).
- [ ] Run & analyze [Observatory by Mozilla](https://observatory.mozilla.org/).
- [ ] Setup & test [HTTP Strict Transport Security](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Strict-Transport-Security).
- [ ] Enable (by [Google](https://developers.google.com/web/fundamentals/security/csp), by [Mozilla](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP) & [test](https://csp-evaluator.withgoogle.com/) Content Security Policy.

## Final check

Do the [Toptal final check](https://www.toptal.com/developers/webdevchecklist).
