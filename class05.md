# Images in HTML

**first of all if any body wants to build a website from a scratch , its a best practice to create folder that will contains whole your pictures uses in the site**

_to put an image in my website i should do these things :_
1. **should put < img > tag element .**
2. **i should put the source of the image in img tag which is src :**
+  _This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site._
+ **its done by putting uniform resource locator that is the path pf the image**
3. _i should put altrenative proparity to put an altrenative shwon on the page if the url is not typed well_
+ **as like that alt="this is image" if the url is not valid the previous massage will shown insted of image**
4. _image contains hieght and width proparities the hieght spacifies the hieght of the image in pixles and the width as the same_

**< img src = "images/quokka.jpg" alt ="A family of quokka" width="600" height="450" />**

## color 
**colors applied to HTML elements by three ways :**
+ rgb values **rgb red, green ,blure vlaues takes three values for the three colors to get the wanted color**
+ hex values **uses hexadecimal code for the wanted color : like this #f1f1f1.**
+ by color name **done by putting the name of the wanted color in the css rule**

**In the back-ground color this will happend CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.**

### opacity we use opacity to make the color not that much appears so we can see two tags ubove each other and both of them will appears in a fabulous way to showen to the user.


## Text 
_typeface termenology_
+  Serif fonts have extra details on the ends of the main strokes ofthe letters. These details are known as serifs.
+ Sans-Serif
Sans-serif fonts have straight
ends to letters, and therefore
have a much cleaner design.
+ Monospace
Every letter in a monospace (or
fixed-width) font is the same
width. (Non-monospace fonts
have different widths.)

**we can use font-family to make the text in defferant status :**
_so it provide three font families in the same css rule cause browser sometimes dosent support one of them so it will take the other that suitable to it setting_
