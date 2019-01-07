# Responsive-Portfolio
HW 2 Responsive Portfolio

Assignment Two Instructions - (No Bootstrap)


Copy the contents of Basic-Portfolio (your first homework solution) and paste the mentioned files into Responsive-Portfolio.

Note: Be sure not to include any dot files (e.g. .git, .gitignore) from the Basic-Portfolio repo.
If you chose the Wireframe exercise for your first homework assignment, talk to a TA, who will provide you with a template for your portfolio.
Inside your Responsive-Portfolio folder, find your styles.css file. You will write your media queries at the bottom of styles.css.
Use three @media screen tags, each with one of these max-widths: 980px, 768px and 640px.

You use 980px because you never want any of the content to be cut off. Since the desktop layout is about 960px wide, you want the media queries to kick in before your content gets cut off.
768px is about the width of a tablet and 640px is about the width of a phone in landscape.

Make the layout match the following screenshots:

index.html: 980px, 768px, 640px
portfolio.html: 980px, 768px, 640px
contact.html: 980px, 768px, 640px


Make the position of the header static (the default positioning) when the screen is 640px wide. The header design takes up a lot of room; you don't want it to stick to the top of a small screen and leave no room for the rest of your site.

Be sure to include the viewport tag in all your HTML files, otherwise your media-queries won't function as expected on mobile devices. (Hint: You won't need to use exact pixels for anything other than the container)

Protip: Use the Chrome extensions Window Resizer and Browser Width to see the browser dimensions in Chrome.
Deploy your new portfolio (now with media queries!) to GitHub Pages.



/*-------------------------------STEP BY STEP TODO LIST------------------------------------------*/


1) Copy Files from Basic  Portfolio 

2) Set up the Basic Frame for the 3 HTML Pages with 
    -local styles
    -meta viewport tag

3) Use three @media screen tags

--https://www.w3schools.com/cssref/css3_pr_mediaquery.asp
    each with one of these max-widths: 980px, 768px and 640px.
    add background color change to signal screen size during testing

4) header first - sticky header?  
    980px - probably as is
    768px - not sure
    640px - nav links should collapse and stack
    Make the position of the header static (the default positioning) when the screen is 640px wide. 

3) footer - 100% width should shrink and expand
    add min-width to match container min-width

4) About Me Page
    980px - probably as is
    768px - not sure
    640px - 
    Header and links should be centered
    text should break and clear underneath the image


   min width for container
   have text collapse to below image
   image shrink necessary?  image width is less than the smallest screen size

5) Contact Page
    980px - probably as is
    768px - not sure
    640px - 
    Header and links should be centered

    Form Elements

6) Portfolio Page
    980px - probably as is
    768px - not sure
    640px - 
    Header and links should be centered

    Floats should allow the portfolio images/links to collapse with resizing 
    media queries may be required for padding and spacing issues

7) Compare Responsive page to original Basic Portfolio page and tweak the differences in look i.e. padding, font etc.
    List differences here and correct one by one 

    Does the navbar collapse
    tab with name
    links - stacked on top of one another 

    image
    text beneath image
    footer

8) Eliminate any styles and links that are not being used - is there a tool for this?

BONUS


Incorporate CSS animations in your portfolio. More info here.

https://www.w3schools.com/css/css3_animations.asp