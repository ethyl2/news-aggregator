#News Aggregator
This app is based on a project from Udacity -- (https://github.com/udacity/news-aggregator)
Our assignment is to modify it to become more performant.

##Some of the ways it was modified:
1. Functions that make a visible change to the page now happen inside a
requestAnimationFrame().
2. An unnecessary style function, which didn't really make much of difference,
called colorizeAndScaleStories(), was eliminated.
3. The code for displaying stories, for when the user clicks on them, is handled
with CSS transitions instead of JavaScript.

To more easily tell my project apart from the original one, I tweaked the colors
a bit and added the current date/time to the subheader.

-----------------------------------------------------------------------------
# Udacity 60fps Course Samples

**Please note: this code is intended for you to hone your debugging skills. It contains a lot of code that you should not use in production!**

This is a simple web app that shows the top stories from [Hacker News](https://news.ycombinator.com/news) via [its API](http://blog.ycombinator.com/hacker-news-api).

Unfortunately it has a bunch of performance issues, such as:

* Layout Thrashing
* Expensive painting
* Unnecessary layouts
* Long-running and badly-timed JavaScript
* Bad touch handling

Your mission is to find and fix the issues, and make the app gloriously performant!

## License

See /LICENSE for more.

This is not a Google product.
