# Pure CSS Icons
by: http://joshnh.com/


Original Example: http://jsfiddle.net/joshnh/mfLCp/show/

Currently, the HTML is set up to be used with classes. Sass can do away with the need for classes, by using something like:

    <ul>
        <li><a href="#"></a></li>
        <li><a href="#"></a></li>
        <li><a href="#"></a></li>
        <li><a href="#"></a></li>
    </ul>


    li { 
        &:first-of-type a { 
            @include newDoc; 
        }
        &:nth-of-type(2) a { 
            @include calenda; 
        }
        &:nth-of-type(3) a { 
            @include user; 
        }
        &:last-of-type a { 
            @include heart; 
       }
    }
