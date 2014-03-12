---
layout: single
title: Install Squirt Mobile
---

---

## This should only take a minute...

*Instructions are for iOS Chrome and Safari, but should be sufficient for the enterprising Android user.*

- Open this page on your phone
- Select and copy the JavaScript below to your clipboard:

<pre class="bookmarklet">javascript:(function(){if(window.sq){window.sq.closed&&window.document.dispatchEvent(new Event('squirt.again'));}else{window.sq={};window.sq.userId='586ed654-2804-4302-95e3-1185899b73a7';s=document.createElement('script');s.src='http://www.squirt.io/bm/squirt.js';s.s=window.location.search;s.idx=s.s.indexOf('sq-dev');if(s.idx!=-1){s.ampIdx=s.s.indexOf('&');s.host=s.s.substring(s.idx+7,s.ampIdx==-1?s.s.length:s.ampIdx);s.src='http://'+(s.host?s.host:'localhost')+':4000/bm/squirt.js';}document.body.appendChild(s);}})();</pre>

- Bookmark the current page
- Open your bookmarks manager
  - **Chrome**: menu icon, right of the URL bar
  - **Safari**: book icon, bottom toolbar
- Edit the newly added bookmark
  - **Chrome**: top right (pencil icon)
  - **Safari**: bottom left ("Edit")
- Change the name to "Squirt"
- Clear the URL, paste the copied JavaScript, and save

### Bookmarklet installed! Time to read

- Visit [an article](http://zenhabits.net/) you want to read
- Run the bookmarklet
  - **Chrome**
    * Tap the URL bar
    * Type "Squirt", overwriting the current URL
    * Tap "Squirt" in the autocomplete list
  - **Safari**
    - Tap the URL bar
    - Tap the Squirt bookmarklet in the grid of icons

So read. Very speed. Wow.
