
# 🚀 Launch List

## Project Setup
Separate concerns by platform, content, media, code; and pick one fight at a time. Track your todos in a place that everyone can see.


## PLATFORM
- [ ] You could get SFTP access in a pinch
- [ ] Cache and CDN options reviewed
- [ ] Have some system for automated backups
- [ ] Consider having the hosting level password hide the site during development


### WordPress
- [ ] Perhaps start from one of our LocalWP Blueprints
- [ ] Create theme / child-theme
- [ ] Update the style.css name
- [ ] Update the screenshot / thumbnail
- [ ] Go through all the WP Core settings
- [ ] Go through all plugin settings
- [ ] Go through theme customizer and widget areas
- [ ] Femove unused plugins and themes
- [ ] Enable Auto updates for themes and plugins
- [ ] For teams: Is there an Admin account in your shared password manager?
- [ ] Test Template Hierarchies and other WP templates
- [ ] Test Search
- [ ] Test Archives (Tag, Cat, date, author)
- [ ] 404
- [ ] Set the client's non-human email as the website's email address in General Settings


### Setup the theme from a Boilerplate
- [ ] Update client specific content variables (name, map location etc.)
- [ ] Update style settings in Sass (colors, fonts, set variables etc.)
- [ ] If recycling code from another project be diligent in scouring everything for signs of the other client's project.
- [ ] Set Google Maps API Key


### Security concerns
- [ ] Use unguessable usernames - Maybe random words like "PurpleTree" or some formula like Sitename + Job title + Number
- [ ] Wordfence + 2FA + setting minimum password strength


***


## CONTENT
- [ ] Did the client provide a copydeck or share a cloud folder of contents, media, social media links?
- [ ] Do any of the sourced images need attribution? Create a photo credits page, link in footer.
- [ ] Page titles and meta descriptions are entered
- [ ] Open Graph Image / Featured Image for all key pages and posts
- [ ] If you have forms and/or analytics tracking you need Privacy, Terms, Cookie policies that are GDPR compliant / relevant to the user's host-site's country
- [ ] Copyright © is in the footer and is dynamic to current year
- [ ] Spell check as you go


## MEDIA
- [ ] Favicon / Site icons and theme colors are in place
- [ ] Optimize images - next gen where possible, well sized; consider using srcset
- [ ] Where possible use SVG for images like logos
- [ ] Lazyload images where practical
- [ ] Favicon works in light or dark mode
- [ ] Check stock photos are sourced (not just output from design file)
- [ ] a11y: Alt descriptions on media, title/description on SVG


## Design
Some of these design steps are for more robust brand type of work
- [ ] [Test color contrast](https://contrast-ratio.com/) - particularly for text colors on the brand colors. It is 10x easier to do this before development
- [ ] Bootstrap assumes that the Primary theme color is dark, has highest contrast - in such cases set the Bootstrap primary to a dark grey and lean on the secondary as accent
- [ ] Competitive analysis
- [ ] Moodboards
- [ ] Building a [Design System](https://support.invisionapp.com/docs/design-system-manager-dsm) or approaching development with [Atomic Design](https://bradfrost.com/blog/post/atomic-web-design/)
- [ ] Full design comps (I recommend designing for desktops, we can make it responsive in browser)


### Development & User Experience
- [ ] Make sure all the "current page" states are set
- [ ] Check the text highlight colors (::selection)
- [ ] Comment code for other developers - inline and/or repo readme
- [ ] Add notes to internal documentation if applicable
- [ ] Any special security to consider?
- [ ] Google Analytics code is present
- [ ] All custom code is in git
- [ ] Fiddley meta data like twitter / Open Graph tags in place and tested for key pages (eg. in Slack)
- [ ] Semantic code used (eg. nav, header, footer, aside)
- [ ] [schema.org](https://schema.org/docs/schemas.html) metadata is present - eg for Person, Organization
- [ ] [Schema markup tests](https://search.google.com/structured-data/testing-tool)
- [ ] a11y: Aria is in place for complex interactive layout stuff (especially "hidden content" patterns like tabs, accordions, carousels)
- [ ] a11y: Animations should be stopped with a "prefers reduced motion" setting
- [ ] a11y: labels on buttons and form labels
- [ ] a11y: links have text descriptions
- [ ] a11y: html lang element present and correct
- [ ] Install [A11y audits extension](https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb)
- [ ] a11y: use Lighthouse to check for low contrast text - [Webaim Contrast tester](https://webaim.org/resources/contrastchecker/)
- [ ] Run [Page speed insights](https://developers.google.com/speed/pagespeed/insights)
- [ ] Run [Mobile Friendly test](https://search.google.com/test/mobile-friendly)
- [ ] Run in-dept [Accessibility Insight](https://accessibilityinsights.io) - this takes hours, should be run annually on the Boilerplate/Blueprint. Or, quicker [a11yproject checklist](https://www.a11yproject.com/checklist) (which is the shorter version of the [wcag "quick" reference](https://www.w3.org/WAI/WCAG21/quickref/))
- [ ] Any new patterns to add to Boilerplate or snippet library?


### Meta
- [ ] Update page list in sitemap.xml
- [ ] Remove unneeded pages, posts, comments
- [ ] Review the files from repo
- [ ] 301 Redirects in .htaccess for full refreshes
- [ ] Updates humans.txt
- [ ] Check robots.txt


***


## Testing

### QA / UAT Testing
- [ ] Review Design Brief / specs / reqs / open issues
- [ ] Meet client brand compliance guidelines (if applicable)
- [ ] Test all state changes, e.g. for products: sale prices, sold state, dates
- [ ] Review print styles
- [ ] Responsive Web Design test browser sizes (height and width)
- [ ] Test on multiple devices
- [ ] Test in browsers (Webkit, Blink, Gecko)
- [ ] Test search widget
- [ ] A11y considerations in place? Alt, ARIA, contrast - see https://a11yproject.com for checklist
- [ ] Most projects have TODO items left incomplete - where should these be tracked as nice-to-have upgrades? e.g. website-birthdays
- [ ] Consider User Testing - observing site-use with an audience member


### Peer Review QA
- [ ] Test the staging site
- [ ] Make issues for bugs with the site
- [ ] Log improvement ideas at the boilerplate level
- [ ] Try briefly on tablet and desktop, test more thorough on mobile
- [ ] Look for broken links
- [ ] Check console for errors, console.log type dev messages
- [ ] Double check CSS and JS are minified
- [ ] Visit every page you find, including multiple posts
- [ ] Test form(s) - for errors, incomplete, that it sends/stores
- [ ] Compare to the design brief
- [ ] Is the map accurate to the address?
- [ ] Check /sitemap.xml
- [ ] Test 404 page


***


## Launch
- [ ] Tell the client / PM / stakeholders / team
- [ ] If applicable plan marketing announcement (social media, press releaes)
- [ ] Add to uptime monitor
- [ ] If WordPress, add to ManageWP
- [ ] Ensure SSL is enabled
- [ ] Share Analytics with appropriate people
- [ ] Cache is on
- [ ] Ensure the WP Core setting isn't blocking search engines

### Post-Launch
- [ ] Confirm Analytics are tracking
- [ ] Check for general JS errors / network 404s
- [ ] Consider adding to the portfolio
- [ ] Submit sitemap to Google Search Console
- [ ] Delete staging environment
- The website is just getting started ;)
