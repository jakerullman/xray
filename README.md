# xray
A bookmarklet to bypass article paywalls.

xray allows you to see any paywalled content by reloading the page with the Google referer. It works on sites like WSJ, NYT, etc.

To use it, create a bookmark with the address: 
```
javascript:location.href='https://www.google.com/webhp?#q='%20+%20encodeURIComponent(location.href)%20+%20'&btnI=I'
```
