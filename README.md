# Economist Pride & Prejudice

||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
## Environments

### Production
[prideandprejudice.economist.com](http://prideandprejudice.economist.com/)

### API (UAT)
[api.economist.mrmclient.com](http://api.economist.mrmclient.com)

### Stage
[stage.economist.mrmclient.com](http://stage.economist.mrmclient.com)

### Dev
[dev.economist.mrmclient.com](http://dev.economist.mrmclient.com)

||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
## Admin Creds

-u: econimist

-p: mrmECON123

||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
## Developer / Deployment Notes

ALl development work is done in the **dev** environment, although, the data itself is rarely kept up to date (occasional data backdowns from staging may be required).

The client makes updates to content on **stage**.

When a push is required, **stage** has a complete file and DB push to **api**. If there are features that need to be integrated, the files are generally included in the **stage** to **api** push, but rarely will the data be able to ported over. This generally requires a manual port, meaning you'll have to create the ACF fields on **stage** and then have all that pushed to **api**.

**api** is used as a UAT environment. This should be a 1-to-1 match to **production**, as this will be pushed and override the live environment.

||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
## THE EVENT

There are a few things to keep in mind about the event:

* Generally there is an Event Slide that's put up on the home page marquee, that showcases the upcoming event.
  * Posts - Events Slide / Event Marquee Slide
    * Needs a bit of CSS love, as it looks like adjustments were made to other parts of the site since last year, so the registration links need to be massaged (there is an event class on that slide).
* The Event spans three cities: Hong Kong, London, and NYC
* On the day of the Event, the Live Stream of the Event will need to be activated on the home page marquee
  * Pages - Overview / Front Page
    * This is where you activate the Live Stream and add the URLs
    * When the Live Stream is activated, it takes over the entire Home Page marquee and overrides the existing carousel

||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
## All about that base

Theme built using Underscores starter theme (http://underscores.me/)

Utilizes Advanced Custom Fields Pro plugin and Contact Form DB plugin for data collection.

||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||||
## Templates / Files

### Main Template Files

#### Theme Files
_header.php_ — Header code, meta tags, and more tracking.

_footer.php_ — Footer code, and tracking codes. JS libs are also attached here. There is also a detect to only serve a minified JS on non-development URLs (mrmclient).

_functions.php_ — functions file for WP theme.

_single.php_ — Template for displaying all single posts; main area that serves content. This pulls in template parts depending on the content type.

#### Styles
_custom.less_ — (and _custom.css, which just includes the custom.css...don't ask) Outputs to custom.css; all site styles other than plugin dependent styles, library dependent styles, or init WP theme styles are here.

#### JS
_js/custom.js_ - (custom-min.js) all JS for the site, includes scrolling sidebar functionality, category tab filtering, carousels, tracking, and odds & ends.

#### Custom Templates for Theme
_home.php_ — Home Page Template; this consists of MANY items, specifically:

* Home page marquee
  * Featured articles
  * Event slide (to show registration and info on livestream)
  * Live Stream (data found on Overview Page in WP)
* Overview section (found in Pages in WP)
* Sponsors
* List of recent posts (Topics)
* Twitter feed
* Sidebar (includes nav, social, etc)

_category.php_ — Category Page Template; has filter tabs under hero image, applies to most pages (Perspectives, Speakers, etc). The tabs work by category: you name the parent category the name of the page, and then sub categories will appear as tabs, and filter those posts under those sub categories. If you also pick more than one item as a "Featured Marquee" category, the hero image will automatically appear as a carousel.

_about.php_ — About Page Template

_contributors.php_ — Contributors Page Template

_sponsor.php_ — Sponsors Page Template

_speakers.php_ — Speakers Page Template

_why-attend.php_ — Event Why Attend Page Template

_event.php_ - Event Page Template (London, Hong Kong, NYC)

_newsletter_form.php_ - Sidebar modal form that fires to sign up for newsletter; no data collection on our end, this is sent over to Econ for submission.

### To be deleted:
* _archive-speaker.php_
* _page-london.php_
* _page-speakers.php_
* _template-parts/content-page-speakers.php_
