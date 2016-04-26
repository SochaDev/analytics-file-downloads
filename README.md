# jquery-ga-track-downloads
jQuery plugin that triggers Google Analytics track event when a user downloads file attachements

## Requirements

* jQuery
* Google Analytics script

## Installation

Include `jquery-ga-track-download.js` or `jquery-ga-track-download.min.js` in your HTML file after your Google Analytics code.

Example:

```html
<!-- Google Analytics -->
<script type="text/javascript">
    <!--//--><![CDATA[//><!--
    (function(i,s,o,g,r,a,m){i["GoogleAnalyticsObject"]=r;i[r]=i[r]||function(){(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)})(window,document,"script","//www.google-analytics.com/analytics.js","ga");ga("create", "[YOUR_GA_CODE]", {"cookieDomain":"auto"});ga("send", "pageview");
    //--><!]]>
</script>

<script src="jquery-ga-track-downloads.js"></script>
```

## Acknowledgments 

This script is based on code from Ryan Chase found here:

http://www.blastam.com/blog/index.php/2013/03/how-to-track-downloads-in-google-analytics-v2