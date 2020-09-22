# Explore the Tech!

In today's blog, I am going to discuss some interesting topics related to _web development_ in ***CSS***. So, _let's get started!_


### 1. Transforms:
The `transform` property comes in two different settings, 2D and 3D. Each of these come with their own individual _properties_ and _values_.
Syntax for the `transform` property includes the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses. `transform: scale(1.5);`.

***2D Transforms***
Two-dimensional transforms work on the `x` and `y` axes, known as `horizontal` and `vertical` axes.
* 2D rotate: the `rotate` value provides the ability to rotate an element from `0` to `360` degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise.
* 2D scale: the `scale` value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.
* 2D translate: using the `translateX` value will change the position of an element on the horizontal axis while using the `translateY` value will change the position of an element on the vertical axis.
* 2D skew: Using the `skewX` value distorts an element on the horizontal axis while the `skewY` value distorts an element on the vertical axis.

Also, it is common for multiple transforms to be used at once, rotating and scaling the size of an element at the same time.

The default transform `origin` is the dead `center` of an element, both 50% horizontally and 50% vertically. To change this default origin position the `transform-origin` property may be used, which can accept one or two values. When only one value is specified, that value is used for both the horizontal and vertical axes. 


***3D Transforms***
* `perspective`: The `perspective` for each element can be thought of as a vanishing point, similar to that which can be seen in 3D drawings. the perspective value within the transform property works great for transforming one element from a single, unique perspective. 
* `perspective-origin`: similar to `transform-origin`, but large difference between the two falls where the origin of a transform determines the coordinates used to calculate the change of a transform, while the origin of a perspective identifies the coordinates of the vanishing point of a transform.
* 3D rotate: including `rotateX`, `rotateY`, and rotateZ.
* 3D scale: `scaleX`, `scaleY`, and `scaleZ`.
* 3D translate: `translateX`, `translateY`, `translateZ`.
* 3D skew: `skewX`, `skewY`, `skewZ`.



### 2. Transitions and Animation:
With CSS3 transitions you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.
Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes. Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes.
The easiest way for determining styles for different states is by using the `:hover`, `:focus`, `:active`, and `:target` pseudo-classes. There are four transition related properties in total, including `transition-property`, `transition-duration`, `transition-timing-function`, and `transition-delay`.

***Transitions***

* `transition-property`: determines exactly what properties will be altered in conjunction with the other transitional properties. By default, all of the properties within an element’s different states will be altered upon change. .
* `transition-duration`: sets the duration in which a transition takes place.
* `transition-timing-function`: used to set the speed in which a transition will move.
* `transition-delay`: the delay sets a time value, seconds or milliseconds, that determines how long a transition should be stalled before executing.

***Animation***

`@keyframe` rule: To set multiple points at which an element should undergo a transition, which includes the`animation-name`, any `animation-breakpoints`, and the `properties` intended to be animated.
The following are cool CSS transitions that can be applied to your web application:
* Fade in.
* Change color.
* Grow and shrink.
* Rotate elements.
* Square to circle.
* 3D shadow.
* Swing.
* Inset border.



