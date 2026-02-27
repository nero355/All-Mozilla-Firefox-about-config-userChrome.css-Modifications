## All Mozilla Firefox about:config & userChrome.css Modifications
Everything needed to make Firefox useable again!

### All <a href="about:config">'about:config'</a> options used so far :

/* Enable userChrome.css in Profile Directory chrome */<br>
toolkit.legacyUserProfileCustomizations.stylesheets true<br>

/* Enable old Compact Mode again */<br>
browser.compactmode.show true<br>

/* Disable Trim URL Bar both Protocol and trailing / */<br>
browser.urlbar.trimHttps false<br>
browser.urlbar.trimURLs false<br>

/* Disable all Hover Tab Preview functions */<br>
browser.tabs.hoverPreview.enabled false<br>
browser.tas.hoverPreview.showThumbnails false<br>

/* Disable/Hide ALL 'HTML5 Video Fullscreen Message' related things */<br>
full-screen-api.transition-duration.enter 0 0<br>
full-screen-api.transition-duration.leave 0 0<br>
full-screen-api.transition-duration.timeout 0<br>
full-screen-api.warning.delay 0<br>
full-screen-api.warning.timeout 0<br>

The first two are DEFAULTS in LibreWolf it seems!<br>

/* Disable ALL Smoth Scrolling */<br>
general.smoothScroll false<br>
general.smoothScroll.lines false<br>
general.smoothScroll.mouseWheel false<br>
general.smoothScroll.msdPhysics.enabled false<br>
general.smoothScroll.pixels false<br>
general.smoothScroll.scrollbars false<br>
toolkit.scrollbox.smoothScroll false<br>

Some of these might be Disabled by Default but just check them all anyway!<br>

### For everything else modded see the 'chrome' directory uploaded to this repository !!
<br>
<br>
<b><i>*** Disclaimer : ***</i></b><br>
<i>Everything you can find in the userChrome.css can be found elsewhere on the web!<br>
So if you recognize your own code by any chance : Thank you for helping others with their Mozilla Firefox related modifications!</i> ;)
