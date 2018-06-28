# Udacity Feed Reader

## Project Overview

This is my 5th project during the Udacity Front-End Web Developer Nanodegree Program.
Udacity Feedreader is a web-based application that reads RSS feeds (with jQuery and handlebars for JS templating).
My task was to complete unit tests in **./jasmine/spec/feedreader.js** file, sing [Jasmine](http://jasmine.github.io/) framework.

## Tests Included
The following tests are created and completed (green) in this project:
- RSS Feeds
	- are defined
	- have valid url property
	- have valid name
- Menu
	- is hidden by default
	- changes visibility when the menu icon is clicked
- Initial Entries
	- has at least a single entry
- New Feed Selection
	- loads new content on the feed list

As loadFeed() is an asynchronous task, callbacks are used to ensure that feeds are loaded before they are tested.

## How to use
Download and open index.html in your browser to see the application working.
- You can read any feed by clicking on its title.
- Switch between feed resources by using the hamburger menu.
- Jasmine spec are displayed at the bottom of the page.

Clone this repository to add new functions and add unit tests.
