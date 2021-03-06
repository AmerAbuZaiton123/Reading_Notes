# Transforms
The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.
Within this lesson we’ll take a look at both two-dimensional and three-dimensional transforms. 
## Syntex
`selector {
    transform: value;
}`
## 2D Transforms


## 2D Rotate
The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise.
 html 
`<figure class="box-1">Box 1</figure>
 figure class="box-2">Box 2</figure>`
css
`
.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}
`
##  Scale
Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.

## 2D Skew
The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both. The syntax is very similar to that of the scale and translate values. Using the skewX value distorts an element on the horizontal axis while the skewY value distorts an element on the vertical axis. To distort an element on both axes the skew value is used, declaring the x axis value first, followed by a comma, and then the y axis value.%p
