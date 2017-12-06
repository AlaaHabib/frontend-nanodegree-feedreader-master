# Project Overview

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.


## To Run

1. Download the zip 
2. Select index.html to start the app.

## To Use the Application:

Once you have selected index.html to start the app you will notice the application opens to the Udacity Blog.  There is a listing directly below with links to various articles having to do with Udacity.  In the upper left-hand corner, there is a Hamburger Menu icon that when click provides additional options for other feeds.  When you scroll to the bottom of the page you'll notice it's shaded grey and indicates at the beginning Jasmine 2.1.2.  Jasmine is a behavior-driven development framework for testing JavaScript code. It does not depend on any other JavaScript frameworks. It does not require a DOM. And it has a clean, obvious syntax so that you can easily write tests.  It is in this section that Jasmine indicates whether your code will meet expectations.

Looking at this section you will notice a green heading that states "7 specs, 0 failures".  This indicates seven specifications were tested and none failed. These tests are broken down into suites and so you'll notice the first suite is titled "RSS Feeds" and it has three specifications "are defined", "url is defined", and "name is defined".  Looking at the jasmine/spec/feedreader.js file you'll notice these suites described along with the specifications or tests listed.  Because these specifications are met or tests have passed, Jasmine shows green and "7 specs, 0 failures".

You can modify these specifications or tests to see how they indicate your specifications or tests are not being met.  For example, if you modify line 22 from: expect(allFeeds).toBeDefined(); to: expect(feeds).toBeDefined(); and refresh the application it will now be red and will show "7 specs, 1 failure".  You can continue making such changes to see how it will affect the various tests.