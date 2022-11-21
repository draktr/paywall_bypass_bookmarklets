# 12ft_bookmarklet

Bookmarklet for [12ft Ladder](https://12ft.io/), a paywall bypassing service

## What is 12ft Ladder?

[12ft Ladder](https://12ft.io/) bypasses paywalls for websites online by accessing Google crawler cache that Google uses to index online content. I am NOT the author or developer of 12ft Ladder, nor am I in any way related to the service itself.

## What is 12ft Bookmarklet

12ft Ladder Bookmarklet makes it more convenient to use the service. It allows the user to remove paywall via 12ft Ladder by just one click, without the need to go to the website itself and copy+paste links.

## How to use 12ft Bookmarklet

GitHub Markdown [doesn't allow scripts in README.md files](https://stackoverflow.com/a/21340902/10544368), so the bookmarklet needs to be added manually. To do that, you

1) Copy the following script: `javascript:void(location.href='https://12ft.io/'+location.href);`
2) In your browser, right-click on the bookmarks/favourites toolbar and select "Add Bookmark..." or something similar, depending on your browser.
3) Paste the script into the URL/Link field and save the bookmark
4) Optionally, name/rename the bookmark
