# xray
A bookmarklet and Chrome Extension to bypass article paywalls.

xray allows you to see any paywalled content by reloading the page with the Google referer. It works on sites like WSJ, NYT, etc.

You can install the Chrome Extension from the [Chrome Web Store](https://chrome.google.com/webstore/detail/xray/dgkdfehohjdbmnldpcegekjakcdjlnkg), or to use the bookmarklet, create a bookmark with the following address: 
```
javascript:location.href='https://www.google.com/webhp?#q='%20+%20encodeURIComponent(location.href)%20+%20'&btnI=I'
```
