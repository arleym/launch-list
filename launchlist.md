
# 🚀 Launch List

### Setup the theme

* Update client specific variables (map location etc.)
* Update style settings in Sass (colors, fonts, font size etc.)


### Development

* Check stock photos are sourced (not just output from design file)
* Do any of the sourced images need attribution? Create a photo credits page, link in footer.
* Page titles and meta descriptions are entered
* Favicon / Site icons and theme colors are in place (manifest)
* Make sure all the current_page and current_child vars are set right for each page "current" state in the nav
* Check the text highlight colors (::selection)
* If recycling another project do a find for the previous client's name
* Set Google Maps API Key: http://confluence.carpages.ca/display/DSP/Get+a+Google+Maps+API+Key
* Comment code
* Add notes to internal documentation if applicable.
* Any new patterns to add to pattern lab / snippet library?
* Any special security to consider e.g. form sanitization
* Google Analytics code is present
* Everything is in git
* Fiddley meta data like twitter / Open Graph tags
* a11y and schema.org metadata


### Meta

* Update page list in sitemap
* Remove unneeded pages in views/Page
* Review the files from repo
* 301 Redirects in .htaccess for full refreshes
* Updates humans.txt
* Check robots.txt


### Dev QA

* Review Design Brief / specs / reqs / issues
* Meet client brand compliance guidelines (if applicable)
* Test all state changes, e.g. sale prices, sold state, dates
* Review print styles
* QA test on devices
* QA test in browsers (especially Internet Explorer IE11, Edge as applicable)
* Make sure there is inventory on the beta server
* Test front page search widget
* Is provincial tax rate correct? 
* A11y considerations in place? Alt, ARIA, contrast - see https://a11yproject.com for checklist
* Most projects have TODO items left incomplete - where should these be tracked as nice-to-have upgrades? e.g. website-birthdays


### Peer Review QA

* Test the staging site
  * Make issues for bugs with the site
  * Log improvement ideas at the boilerplate level
* Try briefly on tablet and desktop, test more thorough on mobile
* Look for broken links
* Spell check
* Check console for errors, console.log type dev messages
* Double check CSS and JS are minified
* Visit every page you find, including multiple posts
* Test form(s)
* Compare to the design brief
* Is the map accurate to the address?
* Check /sitemap.xml


### Launch

* Tell the client / PM
* If applicable plan marketing announcement (social media, press releaes, team announcement)
* add to uptime monitor
* if WP, add to wp manage


### Post Launch

* Enable SSL
* Confirm Analytics are tracking
* Test 404 page
* Check for general JS errors / network 404s
* Consider adding to the portfolio


### Site Audit / Upgrades

* Page speed insights: https://developers.google.com/speed/pagespeed/insights  
* Schema markup tests: https://search.google.com/structured-data/testing-tool  
* A11y audits extension: https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb    
* Code linters and validators are nice, but often are impractical    
