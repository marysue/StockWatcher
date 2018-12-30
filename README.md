# StockWatcher
A pre-interview project for ForeUp

The challenges in this project:

1.  Finding an API that will provide stock quotes -- and understanding the values that were returned.
2.  Using div's in such a way that we can hide, resize, and reorganize the divs based upon screen size.
3.  Finding a way to create an arrow that indicates where on a vertical line the current stock value resides.
4.  Finding a way to insert a graphic up-caret or down-caret to reside next to text. (See Font Awesome, free edition);
5.  Creating this site 99% in javascript.

The lessons learned:

1.  Internet Explorer blows chunks.  I just abandoned making it work.  My system was totally blocking javascript, no matter what various settings I used.
2.  Reaching out to the community at Learn.co, especially front-end-design and nerdy_learn_neighbors channels was awesome!  I struggled horribly the first 80% of the project.  Once I discovered these channels, I posted and viola! Within 24-hours I got some amazing responses.  Some of the responses included explicit code -- but I wanted this to be a learning project.  So rather than copy their code I would read their suggestions and see if I could implement with the direction they provided. They provided me just the push I needed in the right direction.
3.  Using the Chrome and Firefox dev tools -- especially to see what the margins of the divs were doing, and what the styles applied were.  I certainly became much better versed in the dev tools.  Also - the networking tools checking what the API was returning was instrumental when I thought I wasn't getting an API return as I was getting a CORS error advertised in the console.
4.  CORS errors aren't always CORS errors.  When I had the input fields surrounded by <form> tags, I got CORS errors on my api calls in the callback from the input submit button.  Removing the form tag did nothing to the formatting or behavior -- except that now the CORS errors disappeared.  Also, interestingly, I didn't get the CORS errors when I made the API call directly -- outside of any function.  However, putting the API call within *any* function I would get a CORS error.  This was a major setback in time!
5.  Before doing any coding, really understanding how the layout would have to be made.  I made a lot of changes to classes, id's, and divs -- about 5 renditions -- before I finally got the layout correct to easily create a responsive design.
