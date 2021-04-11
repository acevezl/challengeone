# 01 HTML CSS Git: Code Refactor

* [User Story](#User-Story)
* [Acceptance Criteria](#Acceptance-Criteria)
* [Review](#Review)
* [Solution Implemented](#Solution-Implemented)

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

## Solution Implemented

The following changes were implemented as a solution to this challenge:

* Added alt and title attributes with descriptive text to all images.

> alt is for accessibility, while title is for the popup.

* Added alt and title to all h1, h2, and h3 elements, as well as to all anchors to allow screen readers to detect and read these elements outloud.

* Swapped non-semantic containers (i.e. _div_) into semantic containers like: _section_, and _article_.

* Optimized images: Image sizes were reduced and files optimized for web. Files were saved in next-gen format to improve download speed and data consumption.

> The images provided on the base code were massively large.

* Switched classes to IDs to take advantage of using an anchor for topNav while also applying styles.  For example:
> Instead of: id="online-reputation-management" class="online-reputation-management"

> Simply use: id="online-reputation-management" by updating the class .online-reputation-management to #online-reputation management.

* Resized h1, h2, h3, and p for easier readibility and contrast against background. 

* Re-styled containers to flex, for a fully responsive design on different viewports.

* Ran a [Lighthouse](https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Facevezl.github.io%2Fchallengeone%2Findex.html&strategy=mobile&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa&utm_source=lh-chrome-ext#accessibility) report to validate performance, accessibility, best practices and SEO.


- - -
Luis Arnaut