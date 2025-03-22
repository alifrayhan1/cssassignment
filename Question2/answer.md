# Multiple Background Image

## Yes, multiple background images can be used inside a `div`.

The `background-image` property allows multiple background images, which are separated by commas.

```css
background-image: url(image1.png), url(image2.png), url(image3.png), url(image4.png);
```

Similarly, all background-related property values are also separated by commas. However, if other background properties have a single value, it applies to all images. If there are two values, the first value affects the first image, and the second value applies to the rest of the images.

```css
background-size: cover, contain, 100% 80%, 200px 200px;
background-position: top right, bottom left, 500px 200px, center center;
```



