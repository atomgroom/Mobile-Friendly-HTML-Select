* * *    	
    
    Atom Groom - Mobile Friendly HTML Select Menu
    	
* * *  

    Designed and Built by Atom Groom - http://www.atomgroom.com
    All content, design, markup, and css (C) Atom Groom Design, Inc.
    All rights reserved.
    
* * *

# Mobile Friendly HTML Select - Scalable and Modular

Change Log:

01.04.13

* Initial Commit.  I created this as part of a larger mobile project and thought that it might be useful to developers in the open source community.  This repository contains an HTML select menu that works great on modern mobile browsers. 

* During a project I was challenged by the design of a prototype with a dropdown menu that looked like a DIV based menu.  However, in development it was coded as an HTML select. Selects are hard to manipulate visually with CSS. The challenge here was to get the code to look just like the prototype.  With this technique, you get the benefits of the mobile browser / OS behavior of select menus, which pops up the OS default menu.  You also get the benefit of an cooler looking drop down menu.

* We accomplish this by first removing the basic browser select drop down arrow and borders. We then apply our dropdown triangle with a pseudo element, and apply background, borders and other general style to the containing DIV.  Now, when the user taps the element, the mobile operating system automatically triggers the standard OS select menu.

* The CSS and Markup are both built scalable and fully modular.  You can drop the markup directly into a containing grid DIV and it will scale accordingly.  Style it to your liking! 

* This file uses a grid system I built from the 960gs, you can drop it into your grid an apply classes accordingly to get it to scale correctly in your framework.

* Tested on iOS and Android and works as described.  Older mobile browsers will treat the select normally, it just won't look as good.


...........................................................................................

Atom Groom  

UI /UX Designer & Front End Engineer  

773-454-5651  
www.atomgroom.com  

...........................................................................................