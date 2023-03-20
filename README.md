# project-checklist
a list of things to check before you mark a project as complete

<br/>

### PERSONAL EXPERIENCE

---

- [ ] make sure that all margins are consistent (either all pushing down or all pushing away, whichever is easier to understand)

- [ ] make sure that there is always an h1 tag

- [ ] make sure that you are using h1, h2, h3, h4, etc in their order, not skipping around

- [ ] don't change the size of h1 tags (set up the size in the body tag)

- [ ] make sure that The optimal line height ratio (line height ÷ font size) is equal to the golden ratio. (1.6)

- [ ] make sure that line widths are no more than 40-80 characters per line

- [ ] base font size between 18 and 26 px

- [ ] use fluid type to deliver small type for small screens, medium for medium and large for large

- [ ] use ``` * { margin: 0px; padding: 0px; box-sizing: border box} ``` and ``` <meta name="viewport" content="width=device-width, initial-scale=1.0"> ``` to normalize sizes and create a basis for responsive design

- [ ] make sure you get rid of Create React App extras

- [ ] make sure you update the favicon

- [ ] make sure you update the meta tags

- [ ] deploying --  make sure you take the project out of the parent folder you put them in (i.e. if you create a 'React-Jokes' master folder so that you could do your git-clone in that folder so you don't accidentally have a .git file initialized in the whole big project folder... you know, that whole big mess...) than you will have to get rid of the outermost folder so Netlify will look for the package.json in the right place.  Or you could do the hacky thing of telling it to look one level deeper

- [ ] make sure that there is hierarchy in sizes

- [ ] make sure there is difference in font weights

- [ ] make sure you have a good font-pairing (at least two fonts)

- [ ] use color

- [ ] make sure there is breathing room in margins

### UX/UI

---

- [ ] white space
- [ ] use of line
- [ ] use of negative space
- [ ] alignment
- [ ] contrast
- [ ] scale
- [ ] typography

1. Too many typefaces hinder good user experience
2. Choose typefaces that compliment and contrast with one another
3. Keep readability, legibility, and accessibility top of mind
4. Great visual hierarchy improves UX
5. Make your typography scalable
6. Enrich UX with typography 
7. Experiment with between 130%-180% for optimal readability and accessibility. The goal is to find a sweet spot — too much spacing, and it’s easy to get lost, too little, and it’s hard to read—test different scales on your typeface.

- [ ] Check line spacing when changing fonts or font sizes. Different fonts have different maximum heights, so double-check line spacing for readability.

- [ ] Limit line length to 70–80 characters. Long lines of text can be intimidating and confusing to follow.
Small fonts should have more spacing because smaller fonts are more difficult to read so additional space makes it easier to parse.

- [ ] Rule of thumb; text size should be 16 at minimum. This is obviously device-specific, but it frequently stands. If it’s a TV interface, though, for example, then the text should be even larger.

- [ ] There must be a color contrast ratio of at least 4.5:1 between all text and background. Download the Stark plugin to ensure you’re meeting this standard in XD, Sketch, and Figma.

- [ ] Do not rely on color alone to convey information. For example, an error state shouldn’t only be displayed with a red outline, use a warning icon and descriptive text as well to alert that an issue has occurred.

- [ ] Text resize (1.4.4): Text must be able to be resized up to 200% without negatively affecting the ability to read content or use functions.

- [ ] Images of text (1.4.5): Do not use images of text unless necessary (e.g., logo).

- [ ] Select a font to work with. My favorite places to get high-quality UI fonts are Google fonts or Adobe fonts.

- [ ] Establish a base font size. I start by establishing the most commonly used type scale for body copy like 16pt, for example, then determine a suitable line-height.

- [ ] Line height. As I mentioned earlier, experiment with between 130%-180% for optimal readability. This ratio isn’t always accurate, but it’s a good place to start and then make adjustments as needed.

- [ ] Define a scale. A scale provides consistency, rhythm, and hierarchy to our typography. To set type-scale for h1, h2, h3, body, captions, buttons, and so on, we need a scale value to multiply by our base font size. Common scales for type are 1.250x,1.414x, 1.5x, 1.618x. Again, find a scale that works for your typeface and UI.

- [ ] Test scales on devices. Test font with different scales on multiple device sizes to decide on the right value.

- [ ] no more than two font families

- [ ] visual hierarchy for typography

- [ ] letter spacing and line height

- [ ] font weights and italics

- [ ] color

- [ ] visual hierarchy

- [ ] do you have a pattern library for any elements that are commonly used?

### HEAD

---

<span style="background-color: #FFFF00">Marked text</span>

- [ ] Doctype: The Doctype is HTML5 and is at the top of all your HTML pages.

- [ ] Charset: The charset declared (UTF-8) is declared correctly.

- [ ] Viewport: The viewport is declared correctly.

- [ ] Title: A title is used on all pages

- [ ] Description: A meta description is provided, it is unique and doesn't possess more than 150 characters.

- [ ] Favicons: Each favicon has been created and displays correctly.

- [ ] Apple Web App Meta: Apple meta-tags are present.

- [ ] Windows Tiles: Windows tiles are present and linked.

- [ ] Canonical: Use rel="canonical" to avoid duplicate content.

- [ ] Language attribute: The <code>lang</code> attribute of your website is specified and related to the language of the current page.

- [ ] Direction attribute: The direction of lecture is specified on the html tag (It can be used on another HTML tag).

- [ ] Alternate language: The language tag of your website is specified and related to the language of the current page.

- [ ] Conditional comments: Conditional comments are present for IE if needed.

- [ ] RSS feed: If your project is a blog or has articles, an RSS link was provided.

- [ ] Inline critical CSS: The inline critical CSS is correctly injected in the HEAD.

- [ ] CSS order: All CSS files are loaded before any JavaScript files in the HEAD

- [ ] Facebook Open Graph:

- [ ] Twitter Card:

<br/>

### HTML 

---

- [ ] HTML5 Semantic Elements: HTML5 Semantic Elements are used appropriately (header, section, footer, main...).

- [ ] Error pages: Error 404 page and 5xx exist

- [ ] Noopener: In case you are using external links with target="_blank", your link should have a rel="noopener" attribute to prevent tab nabbing. If you need to support older versions of Firefox, use rel="noopener noreferrer"

- [ ] Clean up comments: Unnecessary code needs to be removed before sending the page to production.

- [ ] W3C compliant: All pages need to be tested with the W3C validator to identify possible issues in the HTML code.

- [ ] HTML Lint: I use tools to help me analyze any issues I could have on my HTML code.

- [ ] Link checker: There are no broken links in my page, verify that you don't have any 404 error.

- [ ] Adblockers test: Your website shows your content correctly with adblockers enabled

<br/>
<br/>

### WEBFONTS

---


- [ ] Webfont format: WOFF, WOFF2 and TTF are supported by all modern browsers.

- [ ] Webfont size: Webfont sizes don't exceed 100 KB (all variants included).

- [ ] Webfont loader: Control loading behavior with a webfont loader.

<br/>

### CSS

---

- [ ] Responsive Web Design: The website is using responsive web design.

- [ ] CSS Print: A print stylesheet is provided and is correct on each page.

- [ ] Unique ID: If IDs are used, they are unique to a page.

- [ ] Reset CSS: A CSS reset (reset, normalize or reboot) is used and up to date.

- [ ] JS prefix: All classes (or id- used in JavaScript files) begin with js- and are not styled into the CSS files.

- [ ] Embedded or inline CSS: Avoid at all cost embeding CSS in <style> tags or using inline CSS

- [ ] Vendor prefixes: CSS vendor prefixes are used and are generated accordingly with your browser support compatibility.

- [ ] Concatenation: CSS files are concatenated in a single file (Not for HTTP/2).

- [ ] Minification: All CSS files are minified.

- [ ] Non-blocking: CSS files need to be non-blocking to prevent the DOM from taking time to load.

- [ ] Stylelint: All CSS or SCSS files are without any errors.

- [ ] Responsive web design: All pages were tested with the correct breakpoints.

- [ ] CSS Validator: The CSS was tested and pertinent errors were corrected.

- [ ] Desktop Browsers: All pages were tested on all current desktop browsers (Safari, Firefox, Chrome, Internet Explorer, EDGE...)

- [ ] Mobile Browsers: All pages were tested on all current mobile browsers (Native browser, Chrome, Safari...)

- [ ] OS: All pages were tested on all current OS (Windows, Android, iOS, Mac...)

- [ ] Reading direction: All pages need to be tested for LTR and RTL languages if they need to be supported.

<br/>
 
### JAVASCRIPT
 
---

- [ ] JavaScript Inline: You don't have any JavaScript code inline (mixed with your HTML code).

- [ ] Concatenation: JavaScript files are concatenated.

- [ ] Minification: JavaScript files are minified (you can add the .min suffix).

- [ ] JavaScript security:

- [ ] noscript tag: Use `<noscript>` tag in the HTML body if a script type on the page is unsupported or if scripting is currently turned off in the browser. This will be helpful in client-side rendering heavy apps such as React.js.

- [ ] Non-blocking: JavaScript files are loaded asynchronously using async or deferred using defer attribute.

- [ ] Modernizr: If you need to target some specific features you can use a custom Modernizr to add classes in your <html> tag.

- [ ] ESLint: No errors are flagged by ESLint (based on your configuration or standards rules).

<br/>
 
### IMAGES

---
 

- [ ] Optimization: All images are optimized to be rendered in the browser. WebP format could be used for critical pages (like Homepage)

- [ ] Picture/Srcset: You use picture/srcset to provide the most appropriate image for the current viewport of the user.

- [ ] Retina: You provide layout images 2x or 3x, support retina display.

- [ ] Sprite: Small images are in a sprite file (in the case of icons, they can be in an SVG sprite image).

- [ ] Width and Height: Set width and height attributes on <img> if the final rendered image size is known (can be omitted for CSS sizing).

- [ ] Alternative text: All <img> have an alternative text which describe the image visually.

- [ ] Lazy loading: Images are lazyloaded (A noscript fallback is always provided).

<br/>
 
### ACCESSIBILITY

---

- [ ] Progressive enhancement: Major functionality like main navigation and search should work without JavaScript enabled.

- [ ] Color contrast: Color contrast should at least pass WCAG AA (AAA for mobile).

- [ ] H1: All pages have an H1 which is not the title of the website.

- [ ] Headings: Headings should be used properly and in the right order (H1 to H6).

- [ ] Specific HTML5 input types are used: This is especially important for mobile devices that show customized keypads and widgets for different types.

- [ ] Label: A label is associated with each input form element. In case a label can't be displayed, use aria-label instead.

- [ ] Accessibility standards testing: Use the WAVE tool to test if your page respects the accessibility standards.

- [ ] Keyboard navigation: Test your website using only your keyboard in a previsible order. All interactive elements are reachable and usable.

- [ ] Screen reader: All pages were tested in two or more screen readers (such as JAWS, VoiceOver, and NVDA).

- [ ] Focus style: If the focus is disabled, it is replaced by visible state in CSS.
 
<br/>

### PERFORMANCE
 
---

- [ ] Page weight: The weight of each page is between 0 and 500 KB.

- [ ] Minified HTML: Your HTML is minified.

- [ ] Lazy loading: Images, scripts and CSS need to be lazy loaded to improve the response time of the current page (See details in their respective sections)

- [ ] Cookie size: If you are using cookies be sure each cookie doesn't exceed 4096 bytes and your domain name doesn't have more than 20 cookies.

- [ ] Third party components:

- [ ] DNS resolution: DNS of third-party services that may be needed are resolved in advance during idle time using dns-prefetch.

- [ ] Preconnection: DNS lookup, TCP handshake and TLS negotiation with services that will be needed soon is done in advance during idle time using preconnect.

- [ ] Prefetching: Resources that will be needed soon (e.g. lazy loaded images) are requested in advance during idle time using prefetch.

- [ ] Preloading: Resources needed in the current page (e.g. scripts placed at the end of <body>) in advance using preload.

- [ ] Google PageSpeed: All your pages were tested (not only the homepage) and have a score of at least 90/100.
 
<br/>
 
### SEO

---

- [ ] Google Analytics: Google Analytics is installed and correctly configured.

- [ ] Headings logic: Heading text helps to understand the content in the current page.

- [ ] sitemap.xml: A sitemap.xml exists and was submitted to Google Search Console.

- [ ] robots.txt: The robots.txt is not blocking webpages.

- [ ] Structured Data: Pages using structured data are tested and are without errors. Structured data helps crawlers understand the content in the current page.

- [ ] Sitemap HTML: An HTML sitemap is provided and is accessible via a link in the footer of your website.

- [ ] Pagination link tags: Provide rel="prev" and rel="next" to indicate paginated content.

*taken from THE FRONT END CHECKLIST https://frontendchecklist.io/*
