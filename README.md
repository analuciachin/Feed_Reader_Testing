# Feed Reader Testing Project

Create tests for a web-based application that reads RSS feeds using Jasmine library.
Open the index.html file, after the page is loaded, Jasmine tests will show up at the bottom of the page.

## Test Suites

1) RSS Feeds: 
* test to make sure that the allFeeds variable has been defined and that it is not empty
* test whether URL is defined and not empty
* test whether name is defined and not empty

2) The menu 
* test to ensure the menu element is hidden by default
* test whether the menu changes visibility when clicked

3) Initial Entries
* test to ensure when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container

4) New Feed Selection
* test to ensure when a new feed is loaded by the loadFeed function that the content actually changes