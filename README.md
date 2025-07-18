# Web-Development-day-50
CSS Filter 
The filter CSS property applies graphical effects like blur or color shift to an element. Filters are commonly used to adjust the rendering of images, backgrounds, and borders.

blur()
Applies a Gaussian blur to the input image.-
filter: blur(5px);


brightness()
Applies a linear multiplier to the input image, making it appear more or less bright. Values are linear multipliers on the effect, with 0% creating a completely black image, 100% having no effect, and values over 100% brightening the image.
filter: brightness(2);


contrast()
Adjusts the contrast of the input image. A value of 0% makes the image grey, 100% has no effect, and values over 100% create a contrast.
filter: contrast(200%);


drop-shadow()
Applies the parameter <shadow> as a drop shadow, following the contours of the image. The shadow syntax is similar to <box-shadow> (defined in the CSS backgrounds and borders module), with the exception that the inset keyword and spread parameter are not allowed. As with all filter property values, any filters after the drop-shadow() are applied to the shadow.
filter: drop-shadow(16px 16px 10px black);


grayscale()
Converts the image to grayscale. A value of 100% is completely grayscale. The initial value of 0% leaves the input unchanged. Values between 0% and 100% produce linear multipliers on the effect.
filter: grayscale(100%);


hue-rotate()
Applies a hue rotation. The <angle> value defines the number of degrees around the hue color circle at which the input samples will be adjusted. A value of 0deg leaves the input unchanged.
filter: hue-rotate(90deg);


invert()
Inverts the samples in the input image. A value of 100% completely inverts the image. A value of 0% leaves the input unchanged. Values between 0% and 100% have linear multipliers on the effect.
filter: invert(100%);


opacity()
Applies transparency. 0% makes the image completely transparent and 100% leaves the image unchanged.
filter: opacity(50%);


saturate()
Saturates the image, with 0% being completely unsaturated, 100% leaving the image unchanged, and values of over 100% increasing saturation.
filter: saturate(200%);


sepia()
Converts the image to sepia, with a value of 100% making the image completely sepia and 0% making no change.
filter: sepia(100%);


Combining functions
You may combine any number of functions to manipulate the rendering. The filters are applied in the order declared. The following example enhances the contrast and brightness of the image:
filter: contrast(175%) brightness(103%);
