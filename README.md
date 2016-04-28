# analytics-file-downloads

Triggers Google Analytics track event when a user clicks a file download link

## Requirements

* jQuery
* Google Analytics script

## Installation

Install using Bower: `bower install analytics-file-downloads`

Include `bower_components/analytics-file-downloads.js` in your HTML file after your Google Analytics code.

Example:

```html
<!-- Google Analytics -->
<script type="text/javascript">
    <!--//--><![CDATA[//><!--
    (function(i,s,o,g,r,a,m){i["GoogleAnalyticsObject"]=r;i[r]=i[r]||function(){(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)})(window,document,"script","//www.google-analytics.com/analytics.js","ga");ga("create", "[YOUR_GA_CODE]", {"cookieDomain":"auto"});ga("send", "pageview");
    //--><!]]>
</script>

<script src="bower_components/analytics-file-downloads/analytics-file-downloads.js"></script>
```

## Maintainers

* Matt West <west.matt@sochadev.com>

## Acknowledgments 

This script is based on code from Ryan Chase found here:

http://www.blastam.com/blog/index.php/2013/03/how-to-track-downloads-in-google-analytics-v2
