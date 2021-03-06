# Changelog

**dd/mm:**

**24/07:**
- Basic setup of my working environment
- I have removed the old stuff from the placeholder/coming-soon site and cleaned up everything so that I can start nearly from scratch with focus on the future

**25/07:**
- Added Markup for Index Page (definitely not completely finished, I will probably make changes to it while I work on the CSS)
- Styled the Header (not yet fully responsive)
- Restructured the Markup/Styles a bit
- Made some changes in gulpfile.js to fix the Live Reload which was not working correctly

**26/07:**
- Finished Header
- Styled the Welcome Section (almost finished, If any, I will probably only make small changes to it)
- Fixed some things about Gulp and removed minification by it because it destroyed my images for any reason

**27/07:**
- Styled the About Section (probably completely finished)
- Styled the Portfolio Section (probably completely finished)
- Simplified/Improved Markup
- Added more images

**28/07:**
- Styled the Blog Section and Resources Section
- Improved Markup
- Further small improvements/changes

**29/07:**
- Styled the Contact Section
- Styled the Footer (will definitely be revised, I'm not really happy with the result)
- Made Modules out of Navigation and Logo for better code structure

**30/07:**
- Revised Navigation Module (especially Footer Nav)
- Added Hover Effect to Social Cards/Items in Contact Section
- Small improvements for responsiveness etc.

**01/08:**
- Fixed padding of nav items
- Added Parallax Effect for Welcome Section
- Added fixed header on scroll (header animates in and stays fixed on the top after you scrolled down 1/5 of the window)
- Further small improvements/changes

**02/08:**
- Improved browser compatibility of Navigation
- Changed Implementation of Parallax Effect in Welcome Section ([parallax library rellax](https://github.com/dixonandmoe/rellax) instead of own code)
- Remove fixed header (caused problems in combination with parallax effect and I not really liked it generally)
- Fixed Gulp bug: Page was not reloaded when a js file was changed
- Added Smooth Scrolling Effect for CTA in Welcome Section
- Added Portfolio Page (almost finished)
- Restructured JS Code for better use across all pages
- Made Module out of Portfolio Card

**03/08:**
- Added Blog and Resources Page
- Changed Favicon
- Revised .htaccess
- Fixed margins of elements on Portfolio and Blog Page
- Further small fixes/improvements

**04/08:**
- Added Tags Page
- Further small fixes/improvements

**05/08:**
- Added Markup of all Portfolio Single/Item Pages
- Linked them up on Homepage and Portfolio Page
- Basic setup for Styles, on which I will proceed tomorrow

**06/08:**
- Added first Desktop Styles for Portfolio Single/Item Pages
- Improved Markup of them
- and many smaller changes/fixes...

**07/08:**
- Fixed various links
- Improved article-image.js
- Responsive Styles for Portfolio Single/Item Pages (will be revised, but for the time being, I will move on and work on the next pages)

**08/08:**
- Added Blog Articles/Posts
- Small Gulp fix
- Restructured Styles a bit

**09/08:**
- Added Resource Pages
- Made everything much more dynamic and easiert to maintain with Jekyll
- Removed unused Gulp plugins/packages

**10/08:**
- Added Tag Pages
- Switched to bigger images
- Further small changes/fixes

**11/08:**
- Made back-button working in every browser
- Added Impressum and Privacy Policy Page
- Added Markup and basic functionality for Contact Form
- Further small changes/fixes

**12/08:**
- Finished Contact Form
- Finished "Thank you" Page

**13/08:**
- Some padding improvements for device-width <= 360px
- Added Styles for ul, ol and article content image without figcaption for Articles
- Changed Implementation of article content image

**14/08:**
- Added Blockquote, Tweet and Table for Articles (table is not yet fully responsive)

**15/08:**
- Added Code Block for Articles
- Added Pen and Gist for Articles
- Small fix for Table

**16/08:**
- Revised Table and made it fully responsive

**17/08:**
- Added Heading Styles for Articles
- Fixed margin when number of items on Portfolio/Blog/Resources Page is odd
- Gulp fix for Resource Pages
- Added Article Components Resource
- Fixed bug: Read more button was not always on the bottom of the article preview or resource card
- Set Canonicals for all pages
- Released version 0.1

**22/08:**
- Changed Error Handling
- Optimized PHP Code for Contact Form
- Added Back to top Button
- further small fixes/changes
- Released version 0.2 and 0.3

**23/08:**
- Put 3rd Party Code in vendor folder or include it with npm
- Optimized Back to top Button: Prevent Footer from being covered by him
- Added Notification for Users who have deactivated JS and then also directly display the Nav

**24/08:**
- Cleaned up some things in Gulp file
- Fixed Background Position in Article Components Resource
- Corrected path for smooth-scroll script
- Optimized Browser Compatibility
- Made Back to top Button rounded
- Added side padding for Article Heading

**25/08:**
- Optimized .htaccess
- Optimized performance

**28/08:**
- Changed that JS is now loaded asynchronously
- Added rel="noopener" to external links
- Fixed that Footer Styles were not loaded and made some links more descriptive
- Optimized Performance and loading of images by lazy loading
- Further small bug fixes and changes

**29/08:**
- Changed Favicon
- Moved Changelog to seperate file
