There are few pages where readabilty on widescreen monitors is not great.

The aim here is to narrow down the text body so text would be easty to glance.

For example, most newspapers aim for 3-5 words per paragraph, because your brain chunks text into pieces.

Use this bookmarklet to narrow down text on [Hacker News](https://news.ycombinator.com) comments:

<pre> javascript:(function(){document.getElementById("hnmain").width="50%"})(); </pre>
(I haven't found yet why this does not work on Safari (Chrome is fine though))

Use this for Wikipedia:
<pre> javascript:(function(){document.getElementsByTagName('body')[0].style.cssText="width:70%;margin:auto;"})(); </pre>

Use this for Salesforce developer reference pages 
<pre> javascript:(function(){document.getElementsByTagName('body')[0].style.cssText="width:40%;margin:auto;"})(); </pre>
