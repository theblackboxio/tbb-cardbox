# tbb-cardbox

This Polymer component is a little box with top and bottom placeholders, easy to extend and integrate.

## Usage 

Include the dependency in your html:

    <link rel="import" href="<your components path>/tbb-cardbox/tbb-cardbox.html">

And use adding within section elements marked with `top` and `bottom` classes.

    <tbb-cardbox>
        <section class="top">
            <img src="http://assets-cdn.github.com/images/modules/logos_page/GitHub-Mark.png"/>
        </section>
        <section class="bottom">
            <h1>Github</h1>
            <h2><a href="https://github.com/theblackboxio" target="_blank">@theblackboxio</a></h2>
        </section>
    </tbb-cardbox>
    
Links and mails in `h2` are decorated with some fancy svg and animation.

## Licenses

Copyright (c) 2015 theblackbox.io Authors. All rights reserved.
This code may only be used under the BSD style license found at LICENSE
The complete set of authors and contributors may be found at http://theblackboxio.github.io/humans.txt

The media content is licensed:

* `media/hyperlink.svg` made by [SimpleIcon](http://www.flaticon.com/authors/simpleicon) and licensed by [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/).
 
* `media/hyperlink.svg` made by [Designmodo](http://www.flaticon.com/authors/designmodo) and licensed by [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/).
