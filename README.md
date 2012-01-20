eraser.css
=============

Eraser.css is a CSS bulldozer reference file that uses brute force to reset all critical properties for elements within an embedded widget.

What does it do?
-----------

* Uses `!important` to override any styles cascading down the document from other sources.

How to use it
-----------

* It is best to use the file as a customisable starting point.
* Replace references to `.x-widget` with the name of your widget.
* Since browsers parse CSS selectors from right to left, you may want to customise the selectors in the main reset rule to rely on classes that your widget uses. 
* Have your widget insert a `link` referencing the `eraser.css`-based CSS.
* Write all your CSS using `!important` for each property.

(Intended) browser support
-----------

* Google Chrome
* Mozilla Firefox 3+
* Apple Safari 4+
* Opera 10+
* Internet Explorer 6+

License
-----------

Public domain

Acknowledgements
------------

Eraser.css incorporates some of the resets found in [Cleanslate](https://github.com/premasagar/cleanslate) and Twitter's Embedded Tweets.
