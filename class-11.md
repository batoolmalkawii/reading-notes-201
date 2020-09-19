# Explore the Tech! 

In today's blog, I am going to discuss some interesting topics related to _web development_ in ***HTML*** and ***CSS***. So, _let's get started!_

### 1. Images in _HTML_:
You can control the size of an image `<img>` using the `width` and `height` properties in CSS, just like you can for any other box.
Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images, and telling the browser how much space to leave for an
image allows it to render the rest of the page without waiting for the image to download.
To align images, There are two ways that this is commonly achieved:
1. The `float` property is added to the class that was created to represent the size of the image (such as the small class in our example).
2. New classes are created with names such as `align-left` or `align-right` to align the images to the left or right of the page. These class names are used in addition to classes that indicate the size of the image.

To horizontally when it is in block-level element, two methods are used:
1. On the containing element, you can use the `text-align` property with a value of `center`.
2. On the image itself, you can use the use the `margin` property and set the values of the `left` and `right` margins to auto.

The following are properties used for background images:
* `background-image`.
* `background-repeat`:
`repeat`: The background image is repeated both horizontally and vertically (the default way it is shown if the backgroundrepeat property isn't used).
`repeat-x`: The image is repeated horizontally only (as shown in the first example on the left).
`repeat-y`: The image is repeated vertically only.
`no-repeat`: The image is only shown once.
* `background-attachment`: specifies whether a background image should stay in one position or move as the user scrolls up and down the page:
`fixed`: the background image stays in the same position on the page.
`scroll`: the background image moves up and down as the user scrolls up and down the page.
* `background-position`: `left top`, `left center`, `left bottom`, `center top`, `center center`, `center bottom`, `right top`, `right center`, `right bottom`.
* `background`: The background property acts like a shorthand for all of the other background properties

