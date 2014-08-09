uSlider
=======

Simple Mootools CSS3 adaptable slider.


How to use
----------

JS :
```js
var slider = new uSlider($('myslider'), {
    effect: 'slide',
    directionnav: true,
    centercrop: true
});
```

HTML :
```html
<div id="myslider" class="uSlider">
    <ul class="uSlider-slides">
        <li>
            <img src="http://farm9.staticflickr.com/8063/8162601499_3926d3bd5e_c.jpg" class="load" />
        </li>
        <li>
            <img src="http://farm9.staticflickr.com/8070/8162638266_6a28e0526a_c.jpg" class="load" />
        </li>
        <li>
            <img src="http://farm9.staticflickr.com/8489/8162653194_5a2d6d8fc4_c.jpg" class="load" />
        </li>
        <li>
            <img src="http://farm8.staticflickr.com/7254/8162630593_1c77bfc9b7_c.jpg" class="load" />
        </li>
   </ul>
</div>
```

Examples
-----------

* [Basic usage](http://goo.gl/QSbn4)
* [Advanced usage](http://goo.gl/wIinb)


Screenshot
-----------
![Screenshot](http://goo.gl/7zZdC)


Reference
-----------

***Options :***
  * ***controlnav***          Boolean
  * ***directionnav***        Boolean
  * ***keymove***             Boolean
  * ***resize***              Boolean
  * ***autoslide***           Boolean 
  * ***delay***               Number  | Delay of the autoslide
  * ***duration***            Number  | Duration of the animation
  * ***effect***              String  | 'slide' or 'fade'
  * ***transition***          String  | 'quint:out' for more transitions check the transitioncss property in the class
  * ***imageclass***          String  | Class name for identify the images to load.
  * ***centercrop***          Boolean | For center-crop images in container, it's necessary include [the uSizer Class](https://github.com/joseluisq/usize)

***Public Methods :***
  * `uSlider.back()` - Move the slider to previous slide.
  * `uSlider.next()` - Move the slider to next slide.
  * `uSlider.move(i)` - Move the slider to a specific index.

***Events :***
  * `uSlider.addEvent('show', function(i, slide){ });` - Fires when the slides change, the first param `i` is the index for the current slide and the second param `slide` is the current `li` element.

History
-----------
Check out [the releases](https://github.com/joseluisq/uslider/releases) changelog.

License
-----------
Released under [MIT Licence](http://www.opensource.org/licenses/mit-license.php)