# more-less-box-2
And expandable box for news article created for City's MA Interactive Journalism course

The box has a click button that allows to open and close it.

You need to include some text (<h1>for example a Lorem Ipsum text </h1>) to check how the box will look like.  

Create an h1 headline and add a title 

Create paragraphs p in wich is included some text like Lorem Ipsum. 

Create a div class for your 'more-less box'. div class="more-less-box"

Inside div class create a h3 and give it a name. 

Then create a 'p classe' called "more-less-area collapsed". p class="more-less-area collapsed" and put some text which will be the one of your fact box.

Now you need a button so create an 'a classe' called "more-less button". a class= "more-less-button" 

Add this href: "javascript:void(0);"onclick="toggleMoreLess('.more-less-area')">Show/Hide
 
 Don't forget to close /a and /div
 
Now you need to operate on your javascript writing this function: 
toggleMoreLess(areaClass){
$(areaClass).toggleClass('collapsed');
 
}
Then you can edit your fact box on CSS
