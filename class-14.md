# Reading Journal 14

## CSS Transforms, Transitions, and Animations

The ability to change the state of an objects being without using JavaScript is something that web page designers have been asking for for a long time.  It has finally come with the transform property in CSS, but it still has a long way to go.  It is still not widely functional across all of the browsers so there are vendor prefixes that need to be used when writing this property into firefox, chrome, and other browsers.  These prefixes are as follows:

- -webkit-transform
- -moz-transform
- -o-transform
- transform

Webkit is used for android, chrome, iOS, and safari; moz is for firefox; o is for Opera, and internet explorer is the only one that does not require a prefix to write this property into the browser.  It is still a work in progress, but is a very effective way to apply interactivity within your page using pseudo-classes such as :hover and :focus.  Through these means, however, we will be able to manipulate different objects in our page much more efficiently.

Transforms, transitions, and animations all come with a fair amount of property\value pairs to affect different aspects of the object and how exactly they will be manipulated.  Firstly, you are able to choose whether you are changing the object on a 2d or 3d scale for a variety of effects.  For sizing, rotating, skewing, and the like, you have to identify which scale \(x, y, or z\) you are changing, and then how and how much it will be changing.  There are also color properties you can adjust, as well as timing customizations to define how long the transformation will take, or speed up and slow down as it happens, and you can even cause an animation to happen infinitely as long as it is being interacted with accordingly.

There are, however, a few animations and transformations that are highly sought after in the industry.  Very simple, but powerful, manipulations you can make in CSS to give your users much more satisfaction from using your application.  These popular changes include fading in, growing and shrinking buttons, shape changing from square to circle \(and vice versa\), applying a shadow to have an element stand out on the page, and a few more that are both easy to accomplish and effective for user satisfaction.  The web is your canvas if you have the mind to paint your heart's desire through code!
