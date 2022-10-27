# Testing Tools

I keep hearing about new or interesting tools and often forget about them, lose bookmarks, or don't even appreciate how much tooling I use on a daily basis. So I decided to start keeping a list.

The focus is on technical tools, but not exclusively. I'm not trying to capture every tool available, but ones that have been useful. Where other more complete lists exist, I will link to those.


## Browser/UI

* [Requestly](http://www.requestly.in) - manipulate network calls
* [HTML code sniffer](http://squizlabs.github.io/HTML_CodeSniffer/)
* [Colour contrast checker](https://webaim.org/resources/contrastchecker/) - for specific colour combos
* [Viz Palette](https://projects.susielu.com/viz-palette) - evaluate colour schemes against different vision types
* [a11y.css](https://ffoodd.github.io/a11y.css/) and [revenge.css](http://heydonworks.com/revenge_css_bookmarklet/) - bookmarklets for highlighting accessibility errors
* [ANDI](https://www.ssa.gov/accessibility/andi/help/install.html) - bookmarklet for analyzing accessibility
* [Backstop.js](https://github.com/garris/BackstopJS) - visual regression tests
  * cf. [jest-image-snapshot](https://github.com/americanexpress/jest-image-snapshot)
* [pa11y](https://github.com/pa11y/pa11y-ci) - accessibility test runner

### Chrome extensions

* [Emmet Re:view](https://chrome.google.com/webstore/detail/emmet-review/epejoicbhllgiimigokgjdoijnpaphdp?hl=en) - view responsive layouts at multiple sizes at once
* [JSON formatter](https://github.com/callumlocke/json-formatter) - automatically format JSON
* [Edit This Cookie](https://github.com/ETCExtensions/Edit-This-Cookie) - view and manipulate cookies
* [SwitchyOmega](https://github.com/FelisCatus/SwitchyOmega) - Chrome extension for changing proxy settings quickly
* [Lighthouse](https://github.com/GoogleChrome/lighthouse) - built into Chrome Dev Tools
* Accessibility tools
  * [Accessibility Insights](https://accessibilityinsights.io/en/) - several user-friendly a11y checks, visualizations, and a thorough walkthrough for assessing apps
  * [WAVE](https://chrome.google.com/webstore/detail/wave-evaluation-tool/jbbplnpkjmmeebjpijfedlgcdilocofh) - Chrome extension for checking accessibility
  * [aXe](https://chrome.google.com/webstore/detail/axe/lhdoppojpmngadmnindnejefpokejbdd) - Chrome extension for checking accessibility (good to have more than one, they flag different things!)
  * [Colour Contrast Analyzer](https://chrome.google.com/webstore/detail/color-contrast-analyzer/dagdlcijhfbmgkjokkjicnnfimlebcll) - filters rendered page
  * [Colorblindly](https://chrome.google.com/webstore/detail/colorblindly/floniaahmccleoclneebhhmnjgdfijgg) - filter to simulate colour blindness of different types

## APIs / other networking

* [Charles Proxy](https://www.charlesproxy.com/) - analyze network traffic outside a browser
* [Postman](https://www.getpostman.com/)
* [Request mapper](http://requestmap.webperf.tools/) - visualize requests originating from a site
* [htaccess tester](https://htaccess.madewithlove.be/)
* [Page Speed Insights](https://developers.google.com/speed/pagespeed/insights/) - webpage performance metrics from Google
* [WebPageTest.org](https://www.webpagetest.org/) - performance tests from worldwide locations and real devices
* [Pact](https://docs.pact.io/) - contract testing

## Performance / Load

* [Locust](https://locust.io/) - python based performance testing / load testing
* [k6](https://k6.io/) - performance tests written in javascript ([good overview here](https://www.mariedrake.com/post/shifting-performance-testing-to-the-left-with-k6))
* [Lighthouse-CI](https://github.com/GoogleChrome/lighthouse-ci) - Google's performance scans for CI
* [ab](https://httpd.apache.org/docs/2.4/programs/ab.html) - Apache tool for benchmarking HTTP server performance

## Analysis tools / visualizations

* [Regexper](https://regexper.com/) - visualize regular expressions
* [Regex Tester](https://www.regextester.com/) - quick way to test regular expressions
* [Repl.it](https://repl.it/languages) - run, test, and share code snippets in most popular languages
* [Grok Debugger](https://grokdebug.herokuapp.com/) - for testing Logstash grok patterns for log ingestion

## Command line

Bread and butter of working on the command line, so much so that I forget I ever didn't know about them. Worth looking up a tutorial for.

* grep - search for text in a file, line by line
* awk - operate on columns in text files
* sed - text editor, useful for search and replace based on regex
* tr - single character search and replace
* cut - choose which columns of a file to print
* paste - write two text files to screen side by side
* head - print the first few lines of a file
* tail - print the last lines of a file, with `-f` it watches for new lines
* curl - get URLs
* [jq](https://stedolan.github.io/jq/) - parse and manipulate JSON files
* [explainshell](https://explainshell.com/) - get help for what a given command does


## Language-specific

Just look for the `awesome-<language>` repo with the most stars on github.

* [awesome-python](https://github.com/vinta/awesome-python)
* [awesome-javascript](https://github.com/sorrycc/awesome-javascript)


## Documentation tools

* Schema
  * [Swagger](https://swagger.io/) - tools for API documentation
  * [Swagger2 to Postman](https://github.com/postmanlabs/swagger2-to-postman) - convert Swagger docs to Postman collections
  * [JSONSchema.net](https://jsonschema.net/#/editor) - JSON schema creator/editor
* Drawing / Mapping / Diagramming
  * [Text2MindMap](https://tobloef.com/text2mindmap/) - create mind maps from plain text
  * [Mindomo](https://www.mindomo.com) - shareable mindmaps with simple interface, can import/export plain text from the above tool
  * [code2flow](https://code2flow.com/app) - draw flow charts from pseudocode
  * [PlantText](https://www.planttext.com/) - draw network/class relationship diagrams from plain text, with lots of examples
* Writing
  * [Hemingway](http://www.hemingwayapp.com/) - check if writing can be improved
  * [Font Awesome](https://fontawesome.com/icons?d=gallery&m=free) - free font for icons
* Note taking and reporting
  * [Allure](http://allure.qatools.ru/) - pretty reports for test output
  * [TestNote.io](http://testnote.io/) - note taking tool
  * [TestBuddy](https://testbuddy.co/features) - note taking tool
  * [Trello](https://trello.com) - task manager


## Collaboration tools

* [WebWhiteboard](https://www.webwhiteboard.com/) - virtual whiteboard, good for remote sessions
* [Slido](https://www.sli.do/) - Q&A platform with upvoting, could be used for remote lean coffee


## Test ideas

* [awesome-falsehoods](https://github.com/kdeldycke/awesome-falsehood)
* [Big List of Naughty Strings](https://github.com/minimaxir/big-list-of-naughty-strings/blob/master/blns.txt)
* [TestSphere](https://www.ministryoftesting.com/dojo/series/testsphere)


## Practice

* [Restful Booker](https://restful-booker.herokuapp.com/) - playground for experimenting
* [Gilded Rose Kata](https://github.com/emilybache/GildedRose-Refactoring-Kata) - refactoring exercise
* [Black Box Puzzles](http://blackboxpuzzles.workroomprds.com/) - little abstract apps to explore
* [Testers Playground](http://testersplayground.herokuapp.com/) - challenges for testers
* [The Internet](https://the-internet.herokuapp.com/) - examples of all kinds of typical UI components on the web, good for experimenting with automation
* [Flukeout](http://flukeout.github.io/) - css selector practice/tutorial/game


## How-to articles

* [Wizard Zines](https://wizardzines.com/comics/) - Bit-sized explanations of tons of programming concepts by [Julia Evans](https://twitter.com/b0rk)
* [HTTPS on Localhost](https://medium.freecodecamp.org/how-to-get-https-working-on-your-local-development-environment-in-5-minutes-7af615770eec) - set up ssl on localhost


## Community

* [Ministry of Testing Club](https://club.ministryoftesting.com/) - forum for testers
* [Testers.io](http://testers.io) - slack community
* [Software Testing Conferences](https://testingconferences.org/)


## Meta-Testing

* [Questions to ask testers](https://gist.github.com/smariapena/b551d1c0e74483c09df5259c35c779c1)
* [Mindmap for interviewing testers](https://danashby.co.uk/2015/12/07/how-i-interview-testers/)


## Other references

* [Ministry of Testing tools directory](https://www.ministryoftesting.com/directories/tools)
* [Free Learning Resources for Software Testers](https://github.com/PaulWaltersDev/FreeLearningResourcesForSoftwareTesters)
* [Test Automation Patterns Wiki](https://testautomationpatterns.org)
* [Testing Guides](https://github.com/ckenst/testing-guides)
* [30 Things Every New Software Tester Should Learn](https://dojo.ministryoftesting.com/dojo/lessons/30-things-every-new-software-tester-should-learn)
* [The Missing Semester of your CS Education (MIT)](https://missing.csail.mit.edu/)
* [XPath cheatsheet](https://devhints.io/xpath#class-check)

