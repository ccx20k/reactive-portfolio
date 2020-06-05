# responsive-portfolio

The goal was to create a responsive portfolio website that implemented flexbox, bootstrap, the grid system, semantic tags, and bootstrap utilities. 

##About page##
This page was difficult to start but worked out pretty well in the end
* nav bar had button removed and was styled to have the blue block with my name in it sitting on the left.
* the content card is divided out into 2 columns that stack ontop of eachother for >sm screens
* the image size is fixed but its position is responsive - having it change for every size did not make sense to me as a requirement
* used media query to style <sm viewport
* use of margin to dictate fixed spacing between elements
* issues with sticky footer accenting color stripe on top to match photos.  I left this in here for feedback so I can understand how to change it. 
* container used to manage content and body

##Portfolio page##
This page I used more utilities and custom css to accomplish my goals rather that copy/paste code from bootstrap
*instead of having the img buttons with description on top, I thought to put a cleaner looking p tag underneath each with a view button 
	**if this were a complete portfolio page with links to follow for 'view' button there would be thumbnail previews of each application i was showcasing
	the thumbnail imaegs are solely anecdotal for the homework. 
*the container for the thumb nails was made with css and html writen somewhat custom 
	**the header was stolen from the card to save time i didnt change the name or css just kept it the same for time saving 
	**the thumbnails are organized in two rows and 3 equal columns 
	**padding was also added to clean up the aesthetic of the content

##Contact##
this page felt the easiest and went the quickest
*the form was taken from the bootstrap content which originally had two selection areas and one less text area
*text areas 'name' and 'email' are identical aside from copy 
*the submit button was added as well - using bootstrap code
*the header was also copied over from the card header on the about page exactly like the portfolio page 

