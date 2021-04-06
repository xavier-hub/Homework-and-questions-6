# Homework-and-questions-6
1.Responsive web design makes web pages look good on all devices.
2.Responsive design only uses Html and css.
3.Web design considered responsive web design CSS and HTML to resize, hide, shrink, enlarge, or move the content to make it look good on any screen.
4.Web pages can be viewed on many different devices, the content looks good on any screen, And it becomes easy to use.
5.The CSS media query  is a CSS technique and it uses the @media rule to include a block of CSS properties.
6.Their two places where we will use media queries the site navigation and our CSS Grid columns containing our images on our portfolio page and
the reason why is because those are the two available opportunities right now.
7.```@media (max-width: 899px) {
  .header {
    background: rgba(104, 151, 187, 1);
    margin-top: 0;
    position: sticky;
    top: 0;
  }```
  8.```@media (max-width: 799px) {
  section {
    display: block;
    margin: 0 auto;
    width: 97.5%;
  }```
  9. CSS media queries are useful when you want to modify your site or app depending on a device's general media type and specific characteristics and parameters.
  10. The CSS code considered mobile design when you use the min-width CSS property in our media query and the specified width is that of larger screens. 
  11. The CSS code considered desktop first design when we use the max-width CSS property in our media query and the specified width is that of smaller screens.
  12. mobile first design ```figure { border: 1px solid; display: block; margin: 4rem auto; max-width: 800px; width: 90%; }```
  13. desktop first design ```@media (max-width: 899px) { header { background: rgba(104, 151, 187, 1); margin-top: 0; position: sticky; top: 0;}```
  14. media query consists of an optional media type and any number of media feature expressions and a media feature expression is the part of a media query where the media feature and its value also each media feature expression around surround by parentheses.
  15. A media query condition is when a media type is true if it matches the device on which the document is being displayed and all media feature expressions compute to true.
  16. unknown media types always evaluate to false.
  17. Media types describe the general category of a device.
  18. we do for smaller screen devices to stack images on top of each other.
  19. all: suitable for all devices, print: Intended for paged material and documents viewed on a screen in print preview mode, speech: Intended for speech synthesizers
  20. A media feature is a specific characteristics of the user agent, output device, or environment. Media feature expressions test for their presence or value, and are entirely optional. 
  21.A media feature expression is the part of a media query where the media feature and its value and the media feature expression tests for the presence or value of a media feature, and it is entirely optional. Each media feature expression must be surrounded by parentheses () and yes we need both for small screens and bigger screens to render site navigation and CSS Grid columns differently on both. ```(max-width: 799px)```
  22.any-hover: Does any available input mechanism allow the user to hover over elements? 

any-pointer: Is any available input mechanism a pointing device, and if so, how accurate is it?

aspect-ratio: The ratio between the width and the height of the viewport.

color: The number of bits per color component for the output device.

color-gamut: The approximate range of colors that are supported by the user agent and output device.

color-index: The number of colors the device can display.

grid: Whether the device is a grid or bitmap.

height: The viewport height.

hover: Does the primary input mechanism allow the user to hover over elements? 

inverted-colors: Is the browser or underlying OS inverting colors?

light-level: Current ambient light level 

max-aspect-ratio: The maximum ratio between the width and the height of the display area

max-color: The maximum number of bits per color component for the output device.

max-color-index: The maximum number of colors the device can display.

max-height: The maximum height of the display area, such as a browser window.

max-monochrome: The maximum number of bits per "color" on a monochrome (greyscale) device.

max-resolution: The maximum resolution of the device, using dpi or dpcm.

max-width: The maximum width of the display area, such as a browser window.

min-aspect-ratio: The minimum ratio between the width and the height of the display area.

min-color: The minimum number of bits per color component for the output device.

min-color-index: The minimum number of colors the device can display.

min-height: The minimum height of the display area, such as a browser window.

min-monochrome: The minimum number of bits per "color" on a monochrome (greyscale) device.

min-resolution: The minimum resolution of the device, using dpi or dpcm.

min-width: The minimum width of the display area, such as a browser window.

monochrome: The number of bits per "color" on a monochrome (greyscale) device.

orientation: The orientation of the viewport (landscape or portrait mode).

overflow-block: How does the output device handle content that overflows the viewport along the block axis.

overflow-inline: Can content that overflows the viewport along the inline axis be scrolled.

pointer: Is the primary input mechanism a pointing device, and if so, how accurate is it?

resolution: The resolution of the output device, using dpi or dpcm.

scan: The scanning process of the output device.

scripting: Is scripting (e.g. JavaScript) available?

update: How quickly can the output device modify the appearance of the content. 

width: The viewport width.

23. ```@media (max-width: 799px) {.landing-section {margin: 12vh auto;width: 90%;}``` the media feature is max-width which is the max display such as broswer windows and the part of the that is the media feature is ```(max-width: 799px)```.
