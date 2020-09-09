# Explore the Tech!

In today's blog, I am going to discuss some topics related to web development using **HTML AND CSS**. So, _let's get started!_

### 1. Images in _HTML_:
To add an image into the page you need to use an `<img>` element. It must carry the following two attributes: `src`, which tells the browser where it can find the image file. `alt`, whcih provides a text description of the image which describes the image if you cannot see it, and `title` to provide additional information about the image. There are addintional attributes that can be added to the `<img>` tag, described as follows:
* `height` and `width`.
* `align`, which can be `left` and `right` for horizantal alginment, and `top`, `middle` and `bottom` for vertical alignment.

Images can be displayed in different places on the webpage, such as:
1. before a paragraph.
2. inside the start of a paragraph.
3. in the middle of a paragraph

The images you use on your website should be saved at the same width and height that you want them to appear on the page. Generally, there are three rules for creating images:
1. Save images in the right format.
2. Save images at the right size.
3. Use the correct resolution.

There are several image formats, such as **JPG**, **PNG**, and **GIF**, which are pixel images. Also, you can use vectorized images that are based on mathemetical representation, and if you want to crop an image, it is important not to lose valuable information. It is best to source
images that are the correct shape if possible.

### 2. Color in _CSS_:
The `color` property allows you to specify the color of text inside an element (foreground color). You can specify any color in CSS in one of three ways: **rgb values**, **hex codes**, and **colors names**. In the same way, `background-color` property is used to define the color of the webpage background. 
Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker. the `opacity`
property which allows you to specify the opacity of an element and any of its child elements. Also, `rgba` property allows you to specify a color, just like you would with an RGB value, but adds a fourth value to indicate opacity.
Also, _CSS_ uses another coloring scheme, which is _hue, saturation and brightness_. It is defined by the `hsl` and `hsla` porperty that indicates the values of the 3 features. 

### 3. Text in _CSS_:
Typeface terminologies (fonts) used in css include the following:
* Serif: have extra details on the ends of the main strokes of the letters.
* Sans-Serif: have straight ends to letters.
* Monospace: every letter in a monospace (or fixed-width) font is the same width.
* Cursive: either have joining strokes or other cursive characteristics.
* Fantasy: usually decorative fonts and are often used for titles.
* Weight: Light, Medium, **Bold**, ***Black***
* Style: Normal, _Italic_, Oblique.
* Stretch: Condensed, Regular, Extended.

The following properties are used with fonts in _CSS_:
* `font-family` property is used to specify a font of the text.
* `font-size` that can be in `px`, `em` and `%`. 
* `font-weight` that contains `normal` and `bold`.
* `font-style` contains `normal`, `italic` and `oblique`.
* `text-transform` used to change the case of text giving it one of the following values: `capitalize`, `lowercase`, and `uppercase`.
* `text-decoration`: `none`, `underline`, `overline`, `line-through`, and `blink`.
* `line-height` sets the height of an entire line of text.
* `letter-spacing` and `word-spacing`.
* `text-align`: `left`, `right`, `center`, and `justify`.
* `vertical-align`: `baseline`, `sub`, `super`, `top`, `text-top`, `middle`, `bottom`, and `text-bottom`.
* `text-indent`.
