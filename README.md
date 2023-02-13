# project-checklist
a list of things to check before you mark a project as complete

HEAD

- [ ] Doctype: The Doctype is HTML5 and is at the top of all your HTML pages.

Charset: The charset declared (UTF-8) is declared correctly.

Viewport: The viewport is declared correctly.

Title: A title is used on all pages

Description: A meta description is provided, it is unique and doesn't possess more than 150 characters.

Favicons: Each favicon has been created and displays correctly.

Apple Web App Meta: Apple meta-tags are present.

Windows Tiles: Windows tiles are present and linked.

Canonical: Use rel="canonical" to avoid duplicate content.

Language attribute: The <code>lang</code> attribute of your website is specified and related to the language of the current page.

Direction attribute: The direction of lecture is specified on the html tag (It can be used on another HTML tag).

Alternate language: The language tag of your website is specified and related to the language of the current page.

Conditional comments: Conditional comments are present for IE if needed.

RSS feed: If your project is a blog or has articles, an RSS link was provided.

Inline critical CSS: The inline critical CSS is correctly injected in the HEAD.
HTML TAG CSS PERFORMANCE

CSS order: All CSS files are loaded before any JavaScript files in the HEAD
HTML TAG

Facebook Open Graph:
SOCIAL META TESTING

Twitter Card:

0 % HTML items are ✓
 
 

HTML5 Semantic Elements: HTML5 Semantic Elements are used appropriately (header, section, footer, main...).
HTML BEST PRACTICES

Error pages: Error 404 page and 5xx exist
HTML BEST PRACTICES

Noopener: In case you are using external links with target="_blank", your link should have a rel="noopener" attribute to prevent tab nabbing. If you need to support older versions of Firefox, use rel="noopener noreferrer"
HTML BEST PRACTICES SECURITY

Clean up comments: Unnecessary code needs to be removed before sending the page to production.
HTML BEST PRACTICES

W3C compliant: All pages need to be tested with the W3C validator to identify possible issues in the HTML code.
HTML TESTING

HTML Lint: I use tools to help me analyze any issues I could have on my HTML code.
HTML TESTING

Link checker: There are no broken links in my page, verify that you don't have any 404 error.
HTML TESTING

Adblockers test: Your website shows your content correctly with adblockers enabled
HTML TESTING
WEBFONTS

0 % Webfonts items are ✓
 
 

Webfont format: WOFF, WOFF2 and TTF are supported by all modern browsers.
WEBFONT

Webfont size: Webfont sizes don't exceed 100 KB (all variants included).
WEBFONT

Webfont loader: Control loading behavior with a webfont loader.
WEBFONT
CSS

0 % CSS items are ✓
 
 

Responsive Web Design: The website is using responsive web design.
CSS

CSS Print: A print stylesheet is provided and is correct on each page.
CSS

Unique ID: If IDs are used, they are unique to a page.
CSS

Reset CSS: A CSS reset (reset, normalize or reboot) is used and up to date.
CSS

JS prefix: All classes (or id- used in JavaScript files) begin with js- and are not styled into the CSS files.
JAVASCRIPT BEST PRACTICES

Embedded or inline CSS: Avoid at all cost embeding CSS in <style> tags or using inline CSS
CSS

Vendor prefixes: CSS vendor prefixes are used and are generated accordingly with your browser support compatibility.
CSS

Concatenation: CSS files are concatenated in a single file (Not for HTTP/2).
CSS PERFORMANCE

Minification: All CSS files are minified.
CSS PERFORMANCE

Non-blocking: CSS files need to be non-blocking to prevent the DOM from taking time to load.
CSS PERFORMANCE

Stylelint: All CSS or SCSS files are without any errors.
CSS TESTING

Responsive web design: All pages were tested with the correct breakpoints.
CSS TESTING

CSS Validator: The CSS was tested and pertinent errors were corrected.
CSS TESTING

Desktop Browsers: All pages were tested on all current desktop browsers (Safari, Firefox, Chrome, Internet Explorer, EDGE...)
CSS TESTING

Mobile Browsers: All pages were tested on all current mobile browsers (Native browser, Chrome, Safari...)
CSS TESTING

OS: All pages were tested on all current OS (Windows, Android, iOS, Mac...)
CSS TESTING

Reading direction: All pages need to be tested for LTR and RTL languages if they need to be supported.
CSS TESTING
JAVASCRIPT

0 % JavaScript items are ✓
 
 

JavaScript Inline: You don't have any JavaScript code inline (mixed with your HTML code).
JAVASCRIPT

Concatenation: JavaScript files are concatenated.
JAVASCRIPT

Minification: JavaScript files are minified (you can add the .min suffix).
JAVASCRIPT

JavaScript security:
JAVASCRIPT SECURITY

noscript tag: Use `<noscript>` tag in the HTML body if a script type on the page is unsupported or if scripting is currently turned off in the browser. This will be helpful in client-side rendering heavy apps such as React.js.
JAVASCRIPT

Non-blocking: JavaScript files are loaded asynchronously using async or deferred using defer attribute.
JAVASCRIPT PERFORMANCE

Modernizr: If you need to target some specific features you can use a custom Modernizr to add classes in your <html> tag.
JAVASCRIPT

ESLint: No errors are flagged by ESLint (based on your configuration or standards rules).
JAVASCRIPT TESTING
IMAGES

0 % Images items are ✓
 
 

Optimization: All images are optimized to be rendered in the browser. WebP format could be used for critical pages (like Homepage)
IMAGES BEST PRACTICES

Picture/Srcset: You use picture/srcset to provide the most appropriate image for the current viewport of the user.
IMAGES

Retina: You provide layout images 2x or 3x, support retina display.
IMAGES

Sprite: Small images are in a sprite file (in the case of icons, they can be in an SVG sprite image).
IMAGES

Width and Height: Set width and height attributes on <img> if the final rendered image size is known (can be omitted for CSS sizing).
IMAGES

Alternative text: All <img> have an alternative text which describe the image visually.
IMAGES

Lazy loading: Images are lazyloaded (A noscript fallback is always provided).
IMAGES PERFORMANCE
ACCESSIBILITY

0 % Accessibility items are ✓
 
 

Progressive enhancement: Major functionality like main navigation and search should work without JavaScript enabled.
BEST PRACTICES

Color contrast: Color contrast should at least pass WCAG AA (AAA for mobile).
BEST PRACTICES

H1: All pages have an H1 which is not the title of the website.
BEST PRACTICES SEO

Headings: Headings should be used properly and in the right order (H1 to H6).
BEST PRACTICES

Specific HTML5 input types are used: This is especially important for mobile devices that show customized keypads and widgets for different types.

Label: A label is associated with each input form element. In case a label can't be displayed, use aria-label instead.

Accessibility standards testing: Use the WAVE tool to test if your page respects the accessibility standards.
TESTING

Keyboard navigation: Test your website using only your keyboard in a previsible order. All interactive elements are reachable and usable.
TESTING

Screen reader: All pages were tested in two or more screen readers (such as JAWS, VoiceOver, and NVDA).
TESTING

Focus style: If the focus is disabled, it is replaced by visible state in CSS.
TESTING
PERFORMANCE

0 % Performance items are ✓
 
 

Page weight: The weight of each page is between 0 and 500 KB.
PERFORMANCE

Minified HTML: Your HTML is minified.
HTML PERFORMANCE

Lazy loading: Images, scripts and CSS need to be lazy loaded to improve the response time of the current page (See details in their respective sections)
BEST PRACTICES

Cookie size: If you are using cookies be sure each cookie doesn't exceed 4096 bytes and your domain name doesn't have more than 20 cookies.
BEST PRACTICES

Third party components:
BEST PRACTICES

DNS resolution: DNS of third-party services that may be needed are resolved in advance during idle time using dns-prefetch.
REQUESTS

Preconnection: DNS lookup, TCP handshake and TLS negotiation with services that will be needed soon is done in advance during idle time using preconnect.
REQUESTS

Prefetching: Resources that will be needed soon (e.g. lazy loaded images) are requested in advance during idle time using prefetch.
REQUESTS

Preloading: Resources needed in the current page (e.g. scripts placed at the end of <body>) in advance using preload.
REQUESTS

Google PageSpeed: All your pages were tested (not only the homepage) and have a score of at least 90/100.
TESTING
SEO

0 % SEO items are ✓
 
 

Google Analytics: Google Analytics is installed and correctly configured.
SEO

Headings logic: Heading text helps to understand the content in the current page.
SEO ACCESSIBILITY HTML

sitemap.xml: A sitemap.xml exists and was submitted to Google Search Console.
SEO

robots.txt: The robots.txt is not blocking webpages.
SEO TESTING

Structured Data: Pages using structured data are tested and are without errors. Structured data helps crawlers understand the content in the current page.
SEO TESTING

Sitemap HTML: An HTML sitemap is provided and is accessible via a link in the footer of your website.
SEO HTML

Pagination link tags: Provide rel="prev" and rel="next" to indicate paginated content.
SEO HTML
Project Name
Page title or URL
Developer's name or team
0/47 ✓ high priority
0/25 ✓ medium priority
0/16 ✓ low priority
F
Front‑End_Checklist followed
