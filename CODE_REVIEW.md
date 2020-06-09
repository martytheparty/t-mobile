# Code Review 
## June 9th, 2020
###### Thank you for this well crafted code.  I have a few thoughts...
- In book-search.component.ts the searchExample() name is a click handler.  Handlers typically start with "on" ie onClickSearchExample() 
- Light text on dark background text can be problematic for color blind people. 
- When the page gets very narrow it would be nice if there was one column instead of two.
- A loading indicator would be helpful
- Making the router search term sensitive would be helpful for bookmarking and back/forward navigation (ie http://localhost:4200/searchterm/javascript)