# Myself
My name is Dan. I've been at Sauce Labs for close to 4 years. For the first 2 years I was at Sauce Labs I was a contributor to the Appium open source project. For those of you who don't know, Appium is a mobile app testing framework that is similar to Selenium.

# User Interface Testing
* For today's workshop, we're going to be talking about automated web user interface testing and with a specific focus on Cypress, with a hands-on demonstration that you can all follow along with. 
* But first, let's focus on discussing the current state of web user interface testing
* There are many different frameworks that can be used to test user interfaces, but for today, I will be focussing on five specific frameworks
  * Cypress
  * TestCafe
  * Puppeteer
  * Playwright
  * and Selenium
* Let's start with Selenium
  * Selenium is one of the original UI testing frameworks for the web.
  * The way Selenium works is that there's an HTTP server (called the "driver") that runs alongside of the web browser. A Selenium client can then be used to talk to this server and send it "commands". These "commands" look something like this:
     * navigate to "saucelabs.com" (POST /go {url: "http://saucelabs.com})
     * find an element with class name "login" (POST /element {using: "className", "value": "login})
     * click on button (POST /click {})
  * Because it's HTTP 
  * Selenium implements the W3C WebDriver Specification. This is significant, Selenium has a web standard backing it up so you know it's going to be well supported and there is less risk of breaking changes being introduced
  * 