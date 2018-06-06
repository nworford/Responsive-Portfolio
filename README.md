
ABOUT Responsive Portfolio & Bootstrap Portfolio:

Responsive Portfolio & Bootstrap Portfolio were CSS and Boootstrap assignments. Instructions were as follows:

Instructions

1.Create two new GitHub repositories and name them Responsive-Portfolio and Bootstrap-Portfolio.

2.Clone these repositories to your computer.

3.Copy the contents of Basic-Portfolio (your first homework solution) and paste the mentioned files into Responsive-Portfolio.

4.Note: Be sure not to include any dot files (e.g. .git, .gitignore) from the Basic-Portfolio repo.

5.If you chose the Skeleton exercise for your first homework assignment, contact a TA, who will provide you with a template for your portfolio.

Assignment One Instructions - (No Bootstrap)

1.Inside your Responsive-Portfolio folder, find your styles.css file. You will write your media queries at the bottom of styles.css.

2.Use three @media screen tags, each with one of these max-widths: 980px, 768px and 640px.

-You use 980px because you never want any of the content to be cut off. Since the desktop layout is about 960px wide, you want the media queries to kick in before your content gets cut off.

-768px is about the width of a tablet and 640px is about the width of a phone in landscape.

1.Make the layout match the following screenshots:

2.index.html: 980px, 768px, 640px

3.portfolio.html: 980px, 768px, 640px

4.contact.html: 980px, 768px, 640px

5.Make the position of the header static (the default positioning) when the screen is 640px wide. The header design takes up a lot of room; you don't want it to stick to the top of a small screen and leave no room for the rest of your site.

6.Be sure to include the viewport tag in all your HTML files, otherwise your media-queries won't function as expected on mobile devices. (Hint: You won't need to use exact pixels for anything other than the container)

7.Protip: Use the Chrome extensions Window Resizer and Browser Width to see the browser dimensions in Chrome.

8.Deploy your new portfolio (now with media queries!) to GitHub Pages.


Assignment Two Instructions (Bootstrap)


1.Inside your Bootstrap-Portfolio repo, create index.html, portfolio.html and contact.html.

2.Using Bootstrap, recreate your portfolio site with the following items:

	-A navbar

	-A responsive layout (remember the grid, rows and columns are your friends)


		-eg. On xs and sm screens, each section should take up the entire grid. On m and larger screens, each 		section should take up 2/3 of the grid and the sidebar should take up 1/3 of the grid

	-Responsive images


BONUS
   Using Bootstrap, make a sticky footer and use sub-rows and sub-solumns on your portfolio site (Hint: Check out the Bootstrap documentation)

1.Your Bootstrap solution should minimize use of media queries.

2.Deploy your new Bootstrap-powered portfolio to GitHub Pages.

TECH USED: HTML, CSS, Bootstrap

HIGHLIGHT CODE:


Media Querries in CSS-

@media screen and (max-width: 980px){



  #logo {

    margin-left:5%;

  }

  

  nav {

   margin-right:10%;

  }



  .main-section {



    width:50%;

    margin-left:5%;

    margin-top:0%;

    margin-right:1%%;

    

  }



  .auth-image {

    width:100%;

  }

  

  .sidebar {

   

   float:right;

    margin-right:5%;

    margin-left:2%;



  }

Media Querries in Bootstrap(in HTML)

	<div class="row"> <!--row 1-->

          <div  class="col-xs-12 col-sm-12 col-md-8 col-lg-8">

              <div class="page-header">

              <h1 id="logo"> N. Worford <small></small></h1>

              </div>

          </div>



          <div class="col-xs-12 col-sm-12 col-md-4 col-lg-4"> <!--nav-->

            <nav class="navbar navbar-default navbar-static-top">

                <div class="nav">

                    <nav>

                        <a  href="index.html">About</a>

                        	<span>|</span>

                        <a href="contact.html">Contact</a>

                        	<span>|</span>

                        <a href="portfolio.html">Portfolio</a>

                      </nav>

                </div> <!-- class="nav"-->

            </nav>

          </div>

        </div> <!--row 1-->



CONCLUSION: 
	In completing this assignment, I got an introduction into how to use media queries in CSS and how to use Bootstrap. It was interesting to see the two different ways to make a website responsive

GRADE: A

INSTRUCTOR COMMENT:

from Dylan Acup 
November 15th, 9:06 pm

Nice job on the homework! I really liked the keyframes css you used and it looks like you hit all of the objectives. I don't have much for critiques except for minor things. For instance, it would have been good to have your footer in your bootstrap portfolio on the contact page be sticky with the bottom of the viewport and there are minor tweaks that could be made with your code indentation to make it more readable. Other than that solid job and keep up the good work!


FUTURE DEVELOPMENT:
