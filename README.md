# Vue.js Demos
Small collection of projects I'm doing while learning Vue.js

## Projects
Some are original projects, if the demo is related to a particular course or
tutorial it will be noted and linked to below.

* Shopping Cart
  * [Demo](https://vuejs.mikesprague.me/shopping-cart/) | [Source](https://github.com/mikesprague/vuejs-shopping-cart)
  * Notes:
    * From Udemy Course: [Getting Started with Vue.js](https://www.udemy.com/getting-started-with-vuejs/)
    * Cart uses static data provded with course
* Person Lookup
  * [Demo](https://vuejs.mikesprague.me/person-lookup/) | [Source](https://github.com/mikesprague/vuejs-person-lookup)
  * Notes:
    * Loosely based on demo from Udemy Course: [Getting Started with Vue.js](https://www.udemy.com/getting-started-with-vuejs/)
    * Grabs names for group of people with ability to display extended data for individual person
    * Made using:
      * Data from API at [https://randomuser.me/](https://randomuser.me/)
      * [Vue-resource](https://github.com/vuejs/vue-resource) plugin
* To-Do List
  * [Demo](https://todo-list.mikesprague.me) | [Source](https://github.com/mikesprague/vuejs-todo-list)
  * [![Build Status](https://travis-ci.org/mikesprague/vuejs-todo-list.svg?branch=master)](https://travis-ci.org/mikesprague/vuejs-todo-list)
  * Notes:
    * Very simple to-do list app
    * Starts with 2 example items
    * Enter text and hit enter key to add new items
    * Click on items to toggle completed status
    * Each item can be removed with delete button on right-hand side
    * Click on priority label to change task priority
    * Tasks auto-sort by priority and when they were created (highest priority and newest tasks first)
    * To-do list uses local storage, items persist unless browser cache is cleared
    * Moved hosting of this app to [Firebase](https://firebase.google.com) to prepare for new features that will be added
* Subreddit Feeds
  * [Demo](https://vuejs.mikesprague.me/subreddit-feeds/) | [Source](https://github.com/mikesprague/vuejs-subreddit-feeds)
  * Notes:
    * Based on Tutorialzine article: [Building Your First App With Vue.js](http://tutorialzine.com/2016/08/building-your-first-app-with-vue-js/)
    * Grabs content from predetermined list of subreddits on Reddit
    * No searching or filtering at this time
    * Makes use of [Vue-resource](https://github.com/vuejs/vue-resource) plugin
* Random Design Quotes
  * [Demo](https://vuejs.mikesprague.me/design-quotes/) | [Source](https://github.com/mikesprague/vuejs-design-quotes)
  * Notes:
    * Very barebones random desing quote generator
    * Truncates quote in Tweet content if necessary
    * Uses API at [https://quotesondesign.com/api-v4-0/](https://quotesondesign.com/api-v4-0/)
    * Makes use of [Vue-resource](https://github.com/vuejs/vue-resource) plugin
