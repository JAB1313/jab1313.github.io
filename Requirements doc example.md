FM - THS Redesign
=================================

## Project Brief
Redesigning The Home Story website and adding a special post type to the homepage.  The redesign will be desktop, mobile & tablet, broken out into
two phases.

### Stakeholders
AM: Damien Cortese   
PM: Jason Betancourt
Lead Dev: Ryan Carlson

### Discovery Notes
The homepage RSS feed "News Wire" will work similarly to how we did it for GE Ventures, where the RSS feeds will pull in stories realtime and be automated. This will be limited to the latest 3 stories. The RSS feeds will use the predefined logos from each feed as the image (ex. CNN & CNBC).

### Ideas and Concepts


### Related Resources & Information
* Homepage "News Weed" RSS feeds to pull from these sources:
 * CNBC:  http://www.cnbc.com/id/10000115/device/rss/rss.html
 * CNN:  http://rss.cnn.com/rss/money_realestate.rss
 * Realtor.org:  http://www.realtor.org/stay-connected/rss-feeds
 * EconomistOutlook:  http://feeds.feedburner.com/EconomistsOutlook
 * Realestatestoryideas:  http://feeds.feedburner.com/realestatestoryideas
 * Speakingofrealestate:  http://feeds.feedburner.com/speakingofrealestate


## Feature Requirements
* The mobile homepage subscribe tile will appear after a certain amount of article tiles.
* The mobile nav is sticky.
* The top nav will be sticky throughout all pages.
* Homepage will be infinite scroll.
* Both the homepage and category landing pages should pull in the latest story based on date.
* The News Wire will pull in stories from select RSS feeds and be limited to the latest three.
 * The homepage infinite scroll will start below the newsfeed.
* The homepage will consist of vertical and horizontal article tiles, with a image and overlay covering the bottom half, with the articles category tag
  article title and the first few lines of the article body.
* The "Subscribe" button on the homepage (top right & bottom right) will open a subscribe lightbox.
 * The message will be the same as the current subscribe lightbox on the site, which is done through SumoMe. 
* Homepage search icon (magnify glass) - when a user opens the search field they will be offered three option:
 * Search - user can type in a search query to return a search result
 * Trending Topics - offer two trending topics that will pull in from most popular article tags
 * Most Popular Searches - offier 1 - 6 most popular searches pulling from GA >> Behavior >> Site Search >> Search Terms
* The HOME mobile app link located at the top & bottom header of all screens will open a lightbox, with the Apple & Google app store buttons, for downloading the mobile app.
 * Apple:  https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewSoftware?id=983025390
 * Google:  https://play.google.com/store/apps/details?id=com.fanniemae.calculator

* Category homepage article tiles and category landing pages will have their own specific color.
 * Color will appear on the top nav when hover over. 
* Category landing pages will mimic the homepage in design minus the newsfeed.
* Category landing pages will be infinite scroll.
* Each category landing page header image will be that category's latest article.
 
* Search Results page will have a sort by (filter by):  Author, Video, Category
* Search Results page will have a date range.

* Article page will have two versions, 1 with a video module and 1 without.
* Article pages will have rightside verticle sticky social buttons
 * Article page with video will have a rightside vertical sticky social sharing buttons stop right above the video.
 * Article page without video will have rightside verticle sticky social sharing buttons stop right above "You Might Also Like"
* Article pages will have related horizontal story tiles below the article content body called "You Might Also Like".
* Article pages will have Disqus feature.
* Article pages will have lightbox fuctionality.
* Article pages will have a image gallery fuction.
 * Image gallery info:  WordPress + jQuery Plugin - single site license
 * Image gallery license key: ec969f95638fa339febd 
 * Image Gallery software:  https://www.dropbox.com/sh/hrx9hdi0riz9l61/AACqUssr3riO03VMr7YiKaEFa?dl=0
* Article pages:  Below the each article there will be "More In", which offers related stories by category links and below that is "You Might Also Like", which offers recommended articles, with article tiles. 
* USE TABOOLA CODE FOR "You Might Also Like".
* Article page:  "More In"- should just show all tags from that particular post.  Use the category landing page design.
* Article page:  Twitter article links should be Bit.ly links

* About Us page content:  https://www.dropbox.com/s/doezjz7mfecy4bg/THS%20About%20Us%202.4.16.docx?dl=0
* About Us page will have three horizontal tiles with some descriptive content, each linking to a different FM site.
 * Tile 1 - Know Your Options:  http://www.knowyouroptions.com/
  * Tile blurb: Housing education and information for renters, homebuyers, and homeowners.  
 * Tile 2 - Fannie Mae:  http://www.fanniemae.com
  * Tile blurb:  Fannie Mae Corporate website. 
 * Tile 3 - Home Path:  https://www.homepath.com/
  * Tile blurb:  Fannie Mae owned properties for sale.
 * Tile 4 - Single-Family Business Portal:  https://www.fanniemae.com/singlefamily/index
  * Tile blurb:  Selling and Servicing Guide resources, technology, training, and more.
 * Tile 5 - Multifamily:  https://www.fanniemae.com/multifamily/index
  * Tile blurb:  Multifamily Guide resources, technology, training, and more. 
 * Tile 6 - HOME by Fannie Mae:  
  * Apple:  https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewSoftware?id=983025390
  * Google:  https://play.google.com/store/apps/details?id=com.fanniemae.calculator
  * Tile blurb:  Mobile app to help guide homebuyers.

* Terms of Use:  http://www.fanniemae.com/portal/legal-disclosure.html
* Privacy Policy:  http://www.fanniemae.com/portal/privacy-statement.html
* "Presented by [FM icon] Fannie Mae" located at the top & bottom header of all screens, will link to the FM corp site.
 * FM corp site:  http://www.fanniemae.com/portal/index.html

* Need to use Taboola search for "Related Stores" feature.



### BROWSERS:
* Explorer 11 is the Windows default within Fannie Mae, but we should built back to IE 9. NO IE 8!
* Firefox 38.1.1
* Chrome 48.0.2564.116 m on the reservation
* For people who don’t have blackberries, the mobile android version of Chrome is 48.0.2564.95.


### Backlog: 
 

List any and all features to be scheduled in future sprints.

