# Paywall Bypass Bookmarklets

One click to bypass a paywall. Two at most.

## What Is This Repo?

This repository contains JavaScript code to create bookmarklets for bypassing paywalls or accessing older versions of a particular web page. A bookmarklet is a web browser bookmark that provides some functionality. These bookmarklets simply apply a particular paywall bypassing service to the currently opened web page. I am NOT the author or developer of any of these services, nor am I in any way related to the service itself. While I did use the bookmarklets listed here, I cannot guarantee their quality or integrity. Paywall bypassing services are useful for one-time content access or for when it would be compromising to have access to a paywalled website. If you benefit from an author/creator, support them and buy subscriptions or patronize them.

The reality is that sometimes one service will work while another one won't. That's why I have created bookmarklets for multiple services with additional alternatives outlined below.

## Available Services

### Bookmarklets available

* Google Cache retrieves a saved copy of a web page from Google's servers. Does NOT require a Google account.
* [archive.today](https://archive.today/) retrieves a saved copy of a web page from [archive.today](https://archive.today/) servers.
* [1ft](https://1ft.io/) is a paywall-bypass solution by [DevBlond](https://journal.devblond.com/)
* [RemovePaywall](https://www.removepaywall.com/) bypasses soft paywalls for over a hundred websites.
* Facebook Redirect - pretends that you found a link to the webpage on Facebook, allowing you to the bypass paywall. After activating the bookmarklet, click *Follow Link* button. Does NOT require a Facebook account.
* \]**DEPRECATED**\] NOTE: 12ft Ladder service doesn't work anymore (with or without the bookmarklet). [12ft Ladder](https://12ft.io/) bypasses paywalls for websites online by accessing the Google crawler cache that Google uses to index online content.

### Alternative tools

* [GitHub - everywall/ladder](https://github.com/everywall/ladder) is a self-hosted alternative to [1ft](https://1ft.io/) and [12ft Ladder](https://12ft.io/). Uses the same paywall-bypass approach as the aforementioned services. Not intended for beginners.
* [GitHub - wasi-master/13ft](https://github.com/wasi-master/13ft) is another self-hosted alternative to [1ft](https://1ft.io/) and [12ft Ladder](https://12ft.io/) that allegedly works with more sites than the aforementioned. Not intended for beginners.

### Alternative methods

* Using your web browser's Private/Incognito Mode
* Pasting the headline into Google
* Disabling JavaScript in your browser. Not recommended because it can break many websites. Not intended for beginners.
* Inspecting and editing elements of the webpage. Works only for soft paywalls. Not intended for beginners.
* Installing browser extensions/add-ons such as [unpaywall](https://unpaywall.org/products/extension) and BypassPaywalls for [Chrome](https://github.com/iamadamdev/bypass-paywalls-chrome) and [Firefox](https://github.com/iamadamdev/bypass-paywalls-firefox). Before installing make sure you trust the extension/add-on authors.

## How to install a bookmarklet

GitHub Markdown [doesn't allow scripts in README.md files](https://stackoverflow.com/a/21340902/10544368), so the bookmarklet needs to be added manually. To do that, you

1. Open the `.js` file of the service that you want to install a bookmarklet and copy all the code inside the file. For example, if you want to install [archive.today](https://archive.today/) bookmarklet, open `archive.today_bookmerklet.js` and copy all the code inside of it, i.e. `javascript:void(location.href='https://archive.today/'+location.href);`.
2. In your browser, right-click on the bookmarks/favorites toolbar and select "Add Bookmark..." or something similar, depending on your browser.
3. Paste the code into the URL/Link field and save the bookmark.
4. Optionally, name/rename the bookmark.
