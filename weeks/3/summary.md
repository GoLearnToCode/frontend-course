## The Problem

So far, we've scratched the surface of HTML and CSS. We've seen how a website is composed of one or more web pages, how the content and structure of these pages are written using HTML, and how CSS is used to control how these pages look.

Unfortunately, building modern web sites isn't quite this simple. As technology has matured in the last several years, there are several issues web developers have been forced to consider.

### Web Browsers

It would be ideal if everyone who used the Internet used exactly the same version of the same web browser software, but of course, the percentage of people who use the various versions of Google Chrome, Internet Explorer, Firefox, Safari, among many others, is almost constantly in flux.

### Devices

People visiting your website are using a wide variety of platforms and devices - desktop computers, laptops, tablets, and mobile phones - and these devices all have different screen sizes and resolutions.

### Accessibility

Users of your site could be optimizing for a variety of special use cases, e.g. making the font size larger or utilizing screen reader software.

As web technology has matured, browser developers and web developers have worked together to invent several solutions to these problems.

### CSS Resets

It might surprise you that web browsers don't treat things like margins, padding, line heights, and font sizes all the same way. It happens that every web browser has its own ***user agent stylesheet*** – which is used to style elements that are not otherwise styled using your own CSS. The goal of a CSS reset is to maintain consistency among browsers by "resetting" the styling of HTML elements to a common baseline.

### Media Queries

We are able to deal with screen resolution issues using ***media queries***.

### Conditional CSS

Older versions of Internet Explorer often need help to display your page the way you've expected, so web browsers support the use of conditional CSS to deal with these quirks.

## CSS Frameworks

A common theme among software developers, regardless of technology, is the idea that we don't want to do things that are repetitive or that reinvent the wheel. Or, said another way, we don't want to spend our time solving problems that have already been solved.

It turns out that dealing with screen resolutions, platforms, accessibility, and idiocyncrasies among web browsers have indeed already been thought through by the legions of web developers that have come before you. And the solutions have been bundled in these things called ***CSS Frameworks***.

CSS frameworks are reusuable bundles of code, patterns, and best practices that many professional web developers use to get work done faster.

* Patterns (header-sidebar-content) -> Grid system
* Bootstrap includes:
  * Media queries
  * CSS reset
  * Conditional CSS
  * Grid system
  * Commonly-used components and patterns
