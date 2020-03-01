# Images
_you can control the size of an image using hieght and width proparities in css rule_

+ **Specifying image sizes helps pages to load more smoothly because the HTML and CSS code will often load before the images, and telling the browser how much space to leave for an image allows it to render the rest of the page without waiting for the image to download.**
+ **the float property can be used to move an element to the left or the right of its containing block, allowing text to flow around it.**
+ **The background-image property allows you to place an image behind any HTML element. This could be the entire page or just part of the page. By default, a background image will repeat to fill the entire box. The path to the image follows the letters url, and it is put inside parentheses and quotes.**
 1. _we can controlling the repeat of the back-ground image by :_
   + **repeat-x**
      _The image is repeated horizontally only (as shown in the first example on the left)._
   + **repeat-y**
     _The image is repeated vertically only._

    + **no-repeat**
    _The image is only shown once. The background-attachment property specifies whether a background image should stay in one position or move as the user scrolls up and down the page. It can have one of two values:_
      1. fixed
         The background image stays in the same position on the page.
      2. scroll The background image moves up and down as the user scrolls up and down the page
    _Example_
      1. _body {
      2. background-image: url("images/tulip.gif");
      3. background-repeat: no-repeat;
      4. background-attachment: fixed;
      5. }
      
      3. **When an image is not being repeated, you can use the background-position property to specify where in the browser window the background image should be placed.**
      + This property usually has a pair of values. The first represents the horizontal position and the
        second represents the vertical.
        + left top
        + left center
        + left bottom
        + center top
        + center center
        + center bottom
        + right top
        + right center
        + right bottom
      4. _Using CSS, it is possible to create a link or button that changes to a second style when a user moves their mouse over it (known as a rollover) and a third style when they click on it._
         + **This is achieved by** _setting a background image for the link or button that has three different styles of the same button ( but only allows enough space to show one of them at a time ).You can see the image we are using in this example on the right._ 
         It actually features two buttons on the one image.
        + When the user moves their mouse over the element, or clicks on it, the position of the background image is moved to show the relevant image.
        + When a single image is used for several different parts of an interface, it is known as a sprite.
You can add the logo and other interface elements, as well as buttons to the image. 

## Search Engin optimization 
_optmization SEO:is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics In every page of your website there are seven key places where keywords_
1. Page Title
2. URL / Web Address
3. Headings
4. Text
5. Image Alt Text 

+ **meta data is used for search engin optimization cause the description of the web site and the inatial info that describe it will get the website one of the first result of the web page**