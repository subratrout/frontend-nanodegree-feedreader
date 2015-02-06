# Project Overview

This project is a web-based application that reads RSS feeds.


## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.


## What I have learnt from the Project?

i have learnt how to use Jasmine to write a number of tests against a pre-existing application. These tests test the underlying business logic of the application as well as the event handling and DOM manipulation.


## How will this help my career?

* Writing effective tests requires analyzing multiple aspects of an application including the HTML, CSS and JavaScript - an extremely important skill when changing teams or joining a new company.
* Good tests give the ability to quickly analyze whether new code breaks an existing feature within your codebase, without having to manually test all of the functionality.


# What I have done to complete this project?

1. Downloaded the [required project assets](http://github.com/udacity/frontend-nanodegree-feedreader).
2. Reviewed the functionality of the application within your browser.
3. Explored the application's HTML (*./index.html*), CSS (*./css/style.css*) and JavaScript (*./js/app.js*) to gain an understanding of how it works.
4. Explored the Jasmine spec file in *./jasmine/spec/feedreader.js*
5. Edited the allFeeds variable in *./js/app.js* to make the provided test fail and see how Jasmine visualizes this failure in your application.
6. Returned the allFeeds variable to a passing state.
7. Wrote a test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
8. Wrote a test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
9. Wrote a new test suite named "The menu".
10. Wrote a test that ensures the menu element is hidden by default. I analyzed the HTML and the CSS to determine how we're performing the hiding/showing of the menu element.
11. Wrote a test that ensures the menu changes visibility when the menu icon is clicked. This test has two expectations: does the menu display when clicked and does it hide when clicked again.
12. Wrote a test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container. LoadFeed() is asynchronous so this test required the use of Jasmine's beforeEach and asynchronous done() function.
13. Wrote a test that ensures when a new feed is loaded by the loadFeed function that the content actually changes.
14. When completed - all of my tests passed.

# To see the Project in action:
(http://subratrout.github.io/frontend-nanodegree-feedreader/)
