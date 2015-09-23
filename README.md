# notes

My personal notes and bookmarks about various web-dev topics. Originally collected in 
outr internal bookmarking system, but now moved and re-selected here.
Mainly collected from older projects, all this needs a massive review.

see also 

-[Essential JavaScript Links](https://github.com/ericelliott/essential-javascript-links/).
-[awesome-wpo](https://github.com/davidsonfellipe/awesome-wpo)

# Architecture

- <http://www.codingthearchitecture.com/>
- <http://www.martinfowler.com/>


# Web Components, Widgets, Mashups

- <http://blogs.windows.com/msedgedev/2015/07/14/bringing-componentization-to-the-web-an-overview-of-web-components/>
- <http://webcomponents.org/articles/>
- [An Addendum to Why Web Components Aren't Ready for Production Yet](<http://tjvantoll.com/2014/07/18/an-addendum-to-why-web-components-arent-ready-for-production-yet)


- [A W3C Custom Elements Alternative]<http://webreflection.blogspot.sk/2014/07/a-w3c-custom-elements-alternative.html>
- [Style tools for UI components]<https://suitcss.github.io>
- <http://www.stevesouders.com/blog/2012/05/22/self-updating-scripts/>
- <https://www.sitepen.com/blog/2008/08/01/secure-mashups-with-dojoxsecure/>

# AST

## JS
- <http://www.graspjs.com> - heavy usage for QA checks
- <https://github.com/tweakjs/ast-tree> - TODO: review
- <https://github.com/estools/estraverse> see also other modules used by 'plato'


## CSS
- <https://github.com/stoyan/gonzales-ast>

# Compatibility Matrixes

- CLI caniuse <http://davidwalsh.name/caniuse-command-line>
- CLI compat-table (kangax) <https://github.com/ainthek/compat-table> 

- <http://caniuse.com/>
- <https://kangax.github.io/compat-table/es6/>
- <https://status.modern.ie/>
- <https://www.chromestatus.com/features>
- [CSS Compatibility and Internet Explorer](https://msdn.microsoft.com/en-us/library/cc351024\(v=vs.85\).aspx)
- <http://fmbip.com/litmus>
- <http://www.quirksmode.org/compatibility.html>
- <http://modernizr.com/>

- [X-Frame-Options compatibility test](http://erlend.oftedal.no/blog/tools/xframeoptions/)

# ES5, ES6

- <https://github.com/medikoo/es5-ext>
- JavaScript and the living ECMAScript Standard <http://webreflection.blogspot.de/2015/01/javascript-and-living-ecmascript.html>
- ES6 In Depth Articles <https://hacks.mozilla.org/category/es6-in-depth/>
- es6-equivalents-in-es5 <https://github.com/addyosmani/es6-equivalents-in-es5#template-literals>

- exploring-es6 (book) <https://leanpub.com/exploring-es6/read>
# Progressive Enhancement

- [The JavaScript-Dependency Backlash: Myth-Busting Progressive Enhancement](http://www.sitepoint.com/javascript-dependency-backlash-myth-busting-progressive-enhancement/)
- [progressive-reduction](http://www.dtelepathy.com/blog/design/progressive-reduction-evolving-the-experience-for-your-most-frequent-users)

# Charting

- <http://www.jsgraphs.com/>

# Performance 

- [Best Practices for Speeding Up Your Web Site, yahoo](https://developer.yahoo.com/performance/rules.html)
- <http://www.stevesouders.com/blog/>
- [High Performance Web Sites, Essential Knowledge for Front-End Engineers](http://shop.oreilly.com/product/9780596529307.do)
- [Web Performance Daybook Volume 2, Techniques and Tips for Optimizing Web Site Performance](http://shop.oreilly.com/product/0636920025955.do)
- <http://www.phpied.com/conditional-comments-block-downloads/>

## Online Perf. Test Websites
- <http://www.webpagetest.org>

## Image Optimization Tools
- [Smush it](http://www.imgopt.com/)

# Security

- <https://www.youtube.com/user/OWASPGLOBAL>
- Mario Heiderich <http://www.slideshare.net/x00mario?utm_campaign=profiletracking&utm_medium=sssite&utm_source=ssslideview>
- <http://matasano.com/articles/javascript-cryptography/>

- <https://nodesecurity.io>
- Tangled Web Book <http://www.nostarch.com/tangledweb.html>

- HTTP access control (CORS) <https://developer.mozilla.org/en-US/docs/Web/HTTP/Access_control_CORS>
- Content Security Policy <https://developer.mozilla.org/en-US/docs/Web/Security/CSP/Introducing_Content_Security_Policy>

- <https://blog.mozilla.org/javascript/2015/02/26/the-path-to-parallel-javascript/>

- <http://docs.spring.io/autorepo/docs/spring-security/3.2.0.CI-SNAPSHOT/reference/html/csrf.html>



## SAML , OAuth, Open Connect

- Choosing an SSO Strategy: SAML vs OAuth2 <https://www.mutuallyhuman.com/blog/2013/05/09/choosing-an-sso-strategy-saml-vs-oauth2/>

- <https://developers.google.com/oauthplayground>
- <http://jwt.io/>

### OpenId Connect

- <https://www.youtube.com/watch?v=Kb56GzQ2pSk>

- <http://openid.net/connect/>
- <http://nat.sakimura.org/2012/01/20/openid-connect-nutshell/>
- <http://nat.sakimura.org/2013/07/28/write-openid-connect-server-in-three-simple-steps/>

- <http://fr.slideshare.net/zeronine1/open-id-connect-lecture-for-mit>
- <https://github.com/GluuFederation>

## iframes

- <https://www.tinfoilsecurity.com/blog/protect-your-website-from-embedded-content-iframe-security>
- <http://seclab.stanford.edu/websec/framebusting/framebust.pdf>


## Security Headers

- Guidelines for Setting Security Headers <https://www.veracode.com/blog/2014/03/guidelines-for-setting-security-headers>
- List of useful HTTP headers <https://www.owasp.org/index.php/List_of_useful_HTTP_headers>

## Attacks and Vulns

- xss.io <https://github.com/evilpacket/xss.io>
	(web will go down on 30.9.2015, this is the code)
- ReDoS <https://www.owasp.org/index.php/Regular_expression_Denial_of_Service_-_ReDoS>
- JSON regexp is Bypassable] <http://blog.mindedsecurity.com/2011/08/ye-olde-crockford-json-regexp-is.html>
- <https://auth0.com/blog/2015/03/31/critical-vulnerabilities-in-json-web-token-libraries/>

# Css

Shaped Corners/Borders

- Slanted Corner <http://stackoverflow.com/questions/7059597/slanted-corner-on-css-box>
- Old fashion solution <http://meyerweb.com/eric/css/edge/slantastic/demo.html>
- CSS Polygons <https://alastairc.ac/2007/02/dissecting-css-polygons/>
- Furture <http://lea.verou.me/2013/03/preview-border-corner-shape-before-implementations/>

(Unused) Selectors

- http://addyosmani.com/blog/removing-unused-css/
- http://andy.edinborough.org/CSS-Stress-Testing-and-Performance-Profiling

# Testing

- UI Testing (my repo with links and notes) <https://github.com/ainthek/ui-testing>
- [Why I use Tape Instead of Mocha and So Should You](https://medium.com/javascript-scene/why-i-use-tape-instead-of-mocha-so-should-you-6aa105d8eaf4)

# Reactive Programming

- <https://gist.github.com/staltz/868e7e9bc2a7b8c1f754>
- <http://blog.ractivejs.org/posts/whats-the-difference-between-react-and-ractive/>

- <http://www.flapjax-lang.org>
- <http://conal.net/papers/simply-reactive/old-tech-report-superceded.pdf>

# Others

- <http://www.grpc.io/>