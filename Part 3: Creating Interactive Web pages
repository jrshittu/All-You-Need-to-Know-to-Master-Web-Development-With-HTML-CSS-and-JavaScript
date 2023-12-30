# Creating Interactive Web pages 
## Contents
[CSS Positioning](#pos)
[CSS Transition](#trans)
[CSS Animation](#anime)
[CSS Transforms](#transform)
[Project 1](#pro1)
[Project 2](#pro2)
[Project 3](#pro3)
[Project 4](#pro4)
[Project 5](#pro5)
[References](#ref)

## CSS Positioning <a name="pos"></a>
**CSS Positioning:** deals with how elements are positioned and arranged on a web page. It's like arranging furniture in a room – you can position elements wherever you want to create the desired layout. It includes properties like:
    - `position`: Specifies the type of positioning for an element (static, relative, absolute, fixed, or sticky).
    - `top`, `right`, `bottom`, `left`: Set the position of an element relative to its parent or the viewport.
    - `z-index`: Controls the stacking order of positioned elements.

![Position All](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/lb02ldtgymslmeazl3qj.png) Photo Credits: [CSS Solid](https://www.csssolid.com/css-position.html)

There are five main positioning values in CSS:

* **Static:** This is the default positioning for all elements. Elements positioned as static behave as they would in the normal flow of the document.

![Static](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/0ffmmfyukt8931zupj6b.png)

* **Relative:** Relative positioning allows you to move an element relative to its normal position in the document flow. You can use the `top`, `bottom`, `left`, and `right` properties to specify the offset.

![Relative](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/luyu6eyy26nw5kv0v17j.png)

* **Absolute:** Absolute positioning removes an element from the normal flow of the document and positions it relative to its nearest positioned ancestor or the browser viewport.

![Absolute](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ik7th778mx6ru0eo6c7k.png)

* **Fixed:** Fixed positioning is similar to absolute positioning, but the element is positioned relative to the browser viewport, not its nearest positioned ancestor. This means the element will stay in place even when the page is scrolled.

![Fixed](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/g9nqtozrk8o2md84k21s.png)

![Fixed](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/1bu8dmgqsska7yelfvno.png)Photo Credits: [StackOverFlow](https://stackoverflow.com/questions/29469911/element-position-fixed-is-related-to-parent-instead-to-the-viewport)

* **Sticky:** Sticky positioning is a combination of relative and fixed positioning. The element is positioned relative to its normal position until it reaches the top of the viewport, at which point it becomes fixed.

![Sticky](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/62j1tsmj8q3uzrwuwlgl.png)
![Sticky](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ko44wrztdswf5x582eof.PNG) Photo Credits: [Terluinwebdesig](https://www.terluinwebdesign.nl/en/css/position-sticky-not-working-try-overflow-clip-not-overflow-hidden/)

## CSS Transition <a name="trans"></a>
CSS Transitions add a smooth and gradual animation to the changes of CSS properties. When an element's property is changed, it transitions to the new value over a specified duration. This creates a more visually appealing and user-friendly experience.

**CSS Transitions Syntax**

Transitions in CSS are made up of four properties, giving us control over how the transition will animate.

![Syntax](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/zhubs9hh3xwb1pan9d57.png)

**Breakdown of the syntax:**
* `<property>`: This is the CSS property that you want to transition. For example, you could transition the `opacity`, `background-color`, or `margin` property.
* `<duration>`: This is the duration of the transition in seconds. For example, `1s` would make the transition last for one second.
* `<timing-function>`: This is the timing function that determines how the transition should accelerate or decelerate. There are a number of different timing functions available, such as `ease`, `ease-in`, `ease-out`, and `linear`.
* `<delay>`: This is the delay in seconds before the transition starts. For example, `2s` would make the transition start two seconds after the property change occurs.

**Use Cases**

CSS Transitions can be used for a variety of purposes, including:

- Smoothing out property changes

- Creating hover effects

- Animating elements

**Example**

Create a hover effect that fades an element in and out using CSS Transition:

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/08qrhbby67cmtmjy4x8n.png)

## CSS Animation <a name="anime"></a>
CSS Animation allows you to add visual effects and motion to your web pages. It enables you to transform the appearance of HTML elements over time, creating engaging animations that enhance the user experience.

**CSS Keyframes**
Keyframe animations are defined using the `@keyframes` rule, followed by a unique identifier for the animation. Inside the `@keyframes` rule, you specify the keyframes using percentages or keyword values.

![Keyframes](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/i2yw1y2ko8w0jdiwbqsv.png)

**Percentage Animations**
The start of the animation is marked by 0%, while it ended at 100%. This approach allows developers to pinpoint the exact moment when each keyframe's styles should be applied.

![Percentage Animation](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4h5h8wvjqo32gxusykdt.png)

**Keyword Animations**
Offers a straightforward approach to animation control, utilizing predefined animation steps for common use cases. Keywords like 'from', 'to', 'step-start', 'step-middle', and 'step-end' simplify the animation definition process.

![Keyword Animation](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/9by0gyzexd383dqzb0jm.png)

**Applying Animation**
To attach elements with the desired animations, developers use the animation-name property. This property specifies the identifier of the keyframe animation that should be applied to the element.

![Applying Animation](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/j0ywkwf208ljnb00r0uw.png)

**Animation properties and their values:**

| Property | Value | Description |
|---|---|---|
| `animationName` | The name of the keyframe animation to apply |
| `duration` | A number in seconds | The duration of the animation |
| `timingFunction` | `ease`, `ease-in`, `ease-out`, or `linear` | The timing function of the animation |
| `fillMode` | `none`, `forwards`, or `backwards` | The fill mode of the animation |
| `playState` | `running` or `paused` | The play state of the animation |
| `delay` | A number in seconds | The delay before the animation starts |
| `iterationCount` | A positive integer or `infinite` | The number of times the animation should play |
| `direction` | `normal`, `reverse`, or `alternate` | The direction of the animation |


**Animation-timing-function**
The `animation-timing-function` property plays a crucial role in regulating the animation's pacing, determining how it speeds up or slows down over time. Options like `ease`, `ease-in`, `ease-out`, and `linear` provide developers with the flexibility to create animations that match the desired visual effect.

![Animation Timing Function](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/v8gg3skkqf1scpcnlqsz.png)

**Animation-direction**
The animation-direction property control the animation's playback direction, controlling whether it plays `forward`, `backward`, or alternates between forward and backward directions. Keywords like `normal`, `reverse`, and alternate enable developers to tailor the animation's behavior to their specific needs.

![Animation Direction](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/mcp2dycnbkk1982dkffr.png)

**Animation-fill-mode**

The animation-fill-mode property dictates how an element's style is maintained before and after the animation plays. For example, setting the value to ‘forwards’ will keep the property values from the end of the animation, whereas the default value ‘none’ will return the elements to their original state after the animation has finished.

![Animation Fill mode](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/74f6xomuej001d59u331.png)

**Animation Shorthand**

CSS Animation offers a convenient shorthand notation that allows developers to combine multiple animation properties into a single declaration.

![Shorthand](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ohubxg9q0xqs4huyj970.png)



**Example: FadeIn Animation**
Let's create an animation to fade an element into view over two seconds with a smooth easing function.

![FadeIn Animation](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/gnez9zigvo42l79bp2hz.png)

## CSS Transforms
CSS Transforms are a powerful tool for manipulating the appearance of HTML elements without affecting their position in the document flow. They allow you to `rotate`, `scale`, `translate`, and `skew` elements, creating visually engaging and interactive web pages.

**Examples of CSS Transforms:**

* **Rotate an element:**

![Rotate](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/nwbdrm7jtsijq7ccf9ku.png)

* **Scale an element:**

![Scale](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/7f9nqmedrdaclw55p8i1.png)

* **Translate an element:**

![Translate](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4s63lbvoltk5pgo4w0bs.png)

* **Skew an element:**

![Skew Element](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/gixdxex62j1v7nsd99d4.png)

# Projects

## Project 1: Build A Robot <a name="pro1"></a>

![Robot](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/0sbb49mhkr6j3wei0rsb.png)
Click [here](https://projects.raspberrypi.org/en/projects/build-a-robot/0) for the instructions
Click [here](https://trinket.io/embed/html/b29b50e571) to open the starter project

## Project 2: Image Gallery with Transition Effects <a name="pro2"></a>

![Image Gallery](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/cdu7mupdpwejkt2esc4k.PNG)
Click [here](https://trinket.io/html/10e9324640) to open the finished project
Click [here](https://trinket.io/html/8f0e24abe0) to start your own.

## Project 3: Top 5 Emoji <a name="pro3"></a>

![Image pro3](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/b296emvsqxffc2cmezn6.PNG)
Click [here](https://projects.raspberrypi.org/en/projects/top-5-emoji-list/0) for the instructions
Click [here](https://editor.raspberrypi.org/en/projects/top-5-emoji-list-starter) to start your own
## Project 4: Sunrise<a name="pro4"></a>

![Sunrise](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/cr9339ey1tktag2k7goa.PNG)
Click [here](https://projects.raspberrypi.org/en/projects/sunrise/0) for the instructions
Click [here](https://trinket.io/embed/html/5085f92143) to start your own

## Project 5: Interactive Landing Page with Positioning, Transitions, and Animations <a name="pro5"></a>

Click [here](https://www.filesilo.co.uk/tutorial-files/create-animated-page-transitions/) to download project files.
![Interactive](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/9a7pt5npql2xz7a05fg4.PNG)
Click [here](https://drive.google.com/file/d/11FHtWs_43Ixms1ZVXbuTnI_g49Xmn4cj/view?usp=sharing) to download project instructions.

## References and Resources

- **"Creating a Simple Navigation Menu with CSS Transitions"** by CSS-Tricks ([https://css-tricks.com/solved-with-css-dropdown-menus/](https://css-tricks.com/solved-with-css-dropdown-menus/))

- **"Building an Image Gallery with Smooth Transitions"** by Tuts+ ([https://m.youtube.com/watch?v=TC5kV8By4Ew](https://m.youtube.com/watch?v=TC5kV8By4Ew))

- **"Enhancing an Image Gallery with Additional Features"** by Author ([https://stackoverflow.com/questions/tagged/image-gallery](https://stackoverflow.com/questions/tagged/image-gallery))

- **"Interactive Product Showcase with CSS Transforms"** by SitePoint ([https://tutorialzine.com/2012/02/css3-product-showcase](https://tutorialzine.com/2012/02/css3-product-showcase))

- **"Creating an Interactive Product Showcase without JavaScript"** by Creative Bloq ([https://www.codewithfaraz.com/content/35/create-a-responsive-product-showcase-carousel](https://www.codewithfaraz.com/content/35/create-a-responsive-product-showcase-carousel))

**☕ Enjoyed this article? Support my work with a coffee: [https://www.buymeacoffee.com/cqvuesleq](https://www.buymeacoffee.com/cqvuesleq)**

**Also open for technical writing and frontend dev roles!**









