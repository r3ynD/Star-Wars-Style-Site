# Star-Wars-Style-Site
Just site with text annimation that looks like from "Star Wars"

<h2>Annimation demonstration (8 sec animation long):</h2>

![Видео без названия — сделано в Clipchamp (2)](https://github.com/r3ynD/Star-Wars-Style-Site/assets/127958857/5cedf885-5c2b-48de-83fa-68add95fb415)

<h2>Background Style:</h2>

![image](https://github.com/r3ynD/Star-Wars-Style-Site/assets/127958857/c32a64f6-5256-4bf5-bd9b-b294661d0bfa)

<h2>Text Style:</h2>

![image](https://github.com/r3ynD/Star-Wars-Style-Site/assets/127958857/cb089296-4791-484e-ba41-f94f875a29dc)

- `font-size` sets the font size to 400% of the standard size;
- `font-weight` defines the font thickness as 600 (bold);
- `letter-spacing` sets the distance between characters to 6 pixels;
- `line-height` sets the height of the text line to 150%;
- `perspective` sets the perspective for 3D transformations to 400 pixels;
- `text-align` aligns the text width within the element width (distributes characters across the block);
- `display:flex` sets a block-level container with child elements positioned along the main axis, the initial starting point at the beginning of the container, and moves the key element to the next line when the space in the line is filled.
- `justify-content` aligns the content of the created block-level container to the center;
- `position` determines the method of positioning the element on the page, in this case, positioned relatively, that is, positions the element relative to its original location;
- `height` sets the element's height to 800 pixels;
- `color` sets the text color to yellow;
- `font-family` specifies that the text should use the 'Pathway Gothic One' font, which is a sans-serif font.

<h2>Annimation:</h2>
CSS animation works by defining keyframes that specify how an element should appear at specific times during the animation. In the example provided, the `@keyframes crawl` rule is defined with two keyframes - one at 0% and one at 100%. Inside each keyframe block, you can define the CSS properties that should be applied to the element at that point in the animation.

The `crawl` animation specifies the following properties:

![image](https://github.com/r3ynD/Star-Wars-Style-Site/assets/127958857/8bf65dd0-5b49-4a80-8431-206f788a94da)

- `top`: This property controls the vertical position of the element. At the start of the animation (0%), the element is positioned at the top of the page (top: 0), and by the end of the animation (100%), it has moved up 6000 pixels (top: -6000px).

- `transform`: This property allows you to apply various types of transformations to an element, such as rotating, scaling, or translating it. In this case, the transform property is used to rotate the element around the X-axis by a certain degree, as well as translate it along the Z-axis by a certain distance. By the end of the animation, the element is rotated slightly more and translated much further than at the beginning, creating a crawling effect.

- `-webkit-transform`, `-moz-transform`, `-ms-transform`, and `-o-transform`: These vendor-prefixed versions of the transform property are included for cross-browser compatibility, as some older browsers require them to apply CSS animations correctly.

By changing the values of these properties across the keyframes, you can create many different types of animations. Other properties that can be animated using CSS include opacity, color, width, height, and background, among others.

<h4>To change annimation time you need change these values in "style.css" file:</h4>

![image](https://github.com/r3ynD/Star-Wars-Style-Site/assets/127958857/a3fdc14c-48f4-439e-a3ca-cbf73b5a0734)

