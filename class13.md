# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

+ **What I will refer to as “HTML5 Storage” is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons.** 

+ _Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.” The naming situation is made even more complicated by some related, similarly-named, emerging standards._
_What is html5 storage?_

+ _Simply put, it’s a way for web pages to store named key/value pairs locally within the client web browser._ 

+ Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you.

+ Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.

## we can use modernizer to detect support for html5 storage, insted of writing the function by ourself

1. if ( Modernizr.localstorage) {
2.  // window.localStorage is available!
3. } else {
4.  // no native support for HTML5 storage :(
5.  // maybe try dojox.storage or a third-party solution
6. }

+ **For using HTML5 storage is based on named key/value pairs**
1. _you can retrieve that data with the same key._
2. _The named key is a string._
3. _ The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats._
4. _// data stored as a string if you retrive any other type you may use:\\_
  + ParseInt()
  + parseFloat() to coerce your retrieved data into the expected JavaScript datatype.


+ var foo = localStorage["bar"];
+ // ...
+ localStorage["bar"] = foo;
_There are also methods for removing the value for a given named key, and clearing the entire storage area (that is, deleting all the keys and values at once)._

+ interface Storage {
+  deleter void removeItem(in DOMString key);
+  void clear();
+ };

Calling removeItem() with a non-existent key will do nothing.

**so we sould put the key value to interface storage area**

### if we make an game 
_How does it work? Every time a change occurs within the game, we call this function:_

1. function saveGameState() {
2.    if (!supportsLocalStorage()) { return false; }
3.    localStorage["halma.game.in.progress"] = gGameInProgress;
4.    for (var i = 0; i < kNumPieces; i++) {
5.	localStorage["halma.piece." + i + ".row"] = gPieces[i].row;
6.	localStorage["halma.piece." + i + ".column"] = gPieces[i].column;
7.    }
8.    localStorage["halma.selectedpiece"] = gSelectedPieceIndex;
9.    localStorage["halma.selectedpiecehasmoved"] = gSelectedPieceHasMoved;
10.    localStorage["halma.movecount"] = gMoveCount;
11.    return true;
12. }
