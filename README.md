# Hi-Lo
Higher/lower guessing game implemented with JavaScript, focus on jQuery. 
* [View the Angular version here](https://github.com/evwilkin/hi-lo-angular "Hi-Lo Game w/Angular") 

### Rules:
 - The dealer will draw a card from the deck. Your goal is to guess if the next card will be higher or lower than that card.
 - Guess correctly 3 times in a row and you can choose to pass play to the other player or keep guessing.
 - If you guess incorrectly you get a point for each card in the discard pile, then those cards are cleared.
 - Winner is the person with the fewest points when the cards run out.
#### Notes:
 - Aces are low (they count as "1").
 - Drawing the same card as the previous card doesn't count as a correct or incorrect guess, but does add one point to the discard pile.

### Technologies:
 - HTML5
 - CSS3
 - JavaScript
 - jQuery (focus)
 - Flexbox (focus)

I utilized this exercise as a chance to build an app completely with jQuery, as a refresher for myself as it has been a while since I fully utilized jQuery instead of a more modern tool such as Angular or simply plain vanilla JavaScript.

I also wanted a chance to utilize Flexbox in my page layout, and found it useful through this entire app.  I have plenty of practice with Flexbox but little practical usage, and found applying it as easy as I had hoped - I find it truly a valuable tool for quick and easy responsive layouts without having to load an external library or framework.

### Process
I started by creating a mobile-first wireframe in Adobe Xd to plan out the positioning of items to ensure everything fits on one page, and from there utilized media queries to take advantage of progressive enhancement.
![Image of Hi-Lo wireframe]
(https://raw.githubusercontent.com/evwilkin/hi-lo/master/iPhone%2067%20%E2%80%93%201.png)

### Next Steps
 I plan to recreate this game using both Angular and React.  There were many many times when changing variables that I wished jQuery would take care of updating the view, but had to create an extra step to handle this.  I look forward to comparing the Angular code to the jQuery code to see how it compares in length, though I know the convenience of two-way data binding will be a welcome convenience.

React has been next on my "to-learn" list for some time, and while I've had some classroom study and workshops on it I look forward to confirming my knowledge in recreating a simple and familiar game with it.

### Bugs
 - Sweetalert loads too wide on mobile.