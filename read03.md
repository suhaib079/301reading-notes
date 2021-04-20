# template engine (Mustache.js)

* A template engine enables you to use static template files in your application. At runtime, the template engine replaces variables in a template file with actual values and transforms the template into an HTML file sent to the client. 
(a different way to write HTML code and give us some distinctive feature) Some popular template engines is, Mustache

* if using one of the template engines it is able to use for example conditions or loops inside HTML code. <br>


## Mustache.js

    Mustache.js popular JavaScript templating library, Mustache.js makes it easier to separate data from presentation, allowing to write code that is easier to understand, maintain and extend .

`'<p>{{data}}</p>'`
delimiter in mustache.js {{name}} or hooks , the hooks simply tells Mustache hey, we are going to put some data in here, and these hooks are easy to notice by opening and closing a set of double curly braces 
the opening and closing double curly braces indicate to Mustache.js, hey this keyword or property name represents some data I am going to pass to you, and when you get that data, put it in here .


* how to render an html template in web page <br>
    rendering an html template with Mustache means using what is called the render method
    when you include Mustache in your web page , you wind up with global object called Mustache, that object has render method .
    render method of  Mustache object takes 2 argument , the first is the template, the second argument is the data 
    it take template and data and return html

        example 
        var nameObject = {"name": "Sherlynn"}
        res.render('hello', nameObject)

<br>

# Flexbox

The Flexbox Layout aims at providing a more efficient way to layout, align and distribute space among items in a container, even when their size is unknown and/or dynamic.

The main idea behind the flex layout is to give the container the ability to alter its items’ width/height to best fill the available space (to accommodate all kinds of display devices and screen sizes). A flex container expands items to fill available free space or shrinks them to prevent overflow.
    <br>

   *  **Note:** Flexbox layout is most appropriate to the components of an application, and small-scale layouts, while the Grid layout is intended for larger scale layouts


   ### If “regular” layout is based on both block and inline flow directions,the flex layout is based on “flex-flow directions”. 


**Items will be laid out following either the main axis (from main-start to main-end) or the cross axis (from cross-start to cross-end).**

* main axis – The main axis of a flex container is the primary axis along which flex items are laid out. Beware, it is not necessarily horizontal; it depends on the flex-direction property 

* main-start | main-end – The flex items are placed within the container starting from main-start and going to main-end.


* main size – A flex item’s width or height, whichever is in the main dimension, is the item’s main size. The flex item’s main size property is either the ‘width’ or ‘height’ property, whichever is in the main dimension.


* cross-axis – The axis perpendicular to the main axis is called the cross axis. Its direction depends on the main axis direction.

* cross-start | cross-end – Flex lines are filled with items and placed into the container starting on the cross-start side of the flex container and going toward the cross-end side.


* cross size – The width or height of a flex item, whichever is in the cross dimension, is the item’s cross size. The cross size property is whichever of ‘width’ or ‘height’ that is in the cross dimension.
