# Frontend-Nanodegree-Feedreader Project

## Table of Contents

* [Overview](#overview)
* [Running](#running)
* [Features](#features)

## Overview

Use Jasmine to write a number of tests against a pre-existing application.

## Running

Open the index.html file in your browser to see Jasmine running the tests.

## Features

There are 7 specs total.
RSS Feeds
	are defined
	URLS defined
	name defined

The Menu
	hidden by default
	changes visibility

Initial Entries
	at least a single entry populated

New Feed Selection
	content actually changes


Perform the following test:
1. Test that loops through each feed in the allFeeds object and ensures it has a URL defined and that the URL is not empty.
2. Test that loops through each feed in the allFeeds object and ensures it has a name defined and that the name is not empty.
3. Test that ensures the menu element is hidden by default
4. Test that ensures the menu changes visibility when the menu icon is clicked. 
	a. The menu displays itself when clicked
	b. Does it hide when clicked again?
5. Test that ensures when the loadFeed function is called and completes its work, there is at least a single .entry element within the .feed container.
6. Test that ensures when a new feed is loaded by the loadFeed function that the content actually changes
