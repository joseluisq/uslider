uSlider
=======

Simple Mootools CSS3 Adaptable Slider.


How to use
----------

The js code :
        
#js
var uslider = new uSlider($('myslider'), {
    directionnav: true,
    centercrop: true,
    effect: 'slide'
});


The html code :

#html
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

Live Demos
-----------

* [Basic usage](http://goo.gl/QSbn4)
* [Advanced usage](http://goo.gl/wIinb)


Screenshot
-----------
![Screenshot](http://goo.gl/7zZdC)


Base Doc
-----------

Options :

  * controlnav          Boolean
  * directionnav        Boolean
  * keymove             Boolean
  * resize              Boolean
  * autoslide           Boolean 
  * delay               Number  | Delay of the autoslide
  * duration            Number  | Duration of the animation
  * effect              String  | 'slide' or 'fade'
  * transition          String  | 'quint:out' for more transitions check the transitioncss property in the class
  * imageclass          String  | Class name for identify the images to load.
  * centercrop          Boolean | For center-crop images in container, it's necessary include [the uSizer Class](https://github.com/joseluisq/usize)

Public Methods :
    
  * uSlider.back()
  * uSlider.next()
  * uSlider.move()
    
Events :

  * show({i, slide})
