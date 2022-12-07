== CS 50 Final Project: The Peanut Gallery == 

Video Link: https://youtu.be/9G2D7fBOQbE

## Background Information ##

The Peanut Gallery is a website curated for music enthusiasts to rate and view rankings for various albums. Through a combination of factors, the Peanut Gallery provides albums with a “Peanut Score” that determines the overall ranking of the album. There are multiple avenues of exploration in the Gallery, all of which can be navigated through the guides down below. 

## Setting Up ## 

To set up, download the .zip file found in the Gradescope folder or the GitHub repository at bit.ly/cs50peanutgallery. After downloading the .zip file, unzip it on your computer. Open VSCode. Drag and drop the zip file into your VSCode. Make sure you are in your main directory and then unzip the file using by typing

unzip peanutgallery.zip

into the terminal. From here, you should allow time for the file to unpack fully. Make sure all the appropriate files are there. There should be two csv files, albums.db, app.py, helpers.py, DESIGN.md and README.md. In templates, you should see account.html, album.html, apology.html, home.html, layout.html, login.html, register.html, results.html, search.html, top.html. In static, you should see style.css. Now, move to the “running” instructions below. 


## Running the Peanut Gallery ## 

After launching VSCode, set your working directory to /peanutgallery. You can do this by typing

cd peanutgallery 

into the terminal. To launch the website, type

flask run

and proceed to the link it produces in the terminal. To navigate further portions of the website, read below!

The Peanut Gallery Website Navigation Manual

## How to Navigate the Peanut Gallery ##

Before we begin, navigation should be the same across all of the website’s sections. In order to navigate the website, look at the top of the website for a white rectangle. This contains different sections that you can go to on the website, such as Top Charts, Suggest an Album, Search, and more. Click on any of the sections you wish to go to – and you should be there. For specifics, view the rest of this README guide to utilize the website. 

## Navigating the Home Page ##

The home page is the default screen. You will arrive here upon opening the website and/or registering for an account. This website includes Today’s Top 100 albums & a “Try Something New!” section. You can scroll through to view these. Our homepage takes a long time to load. Please be patient and wait for it to run.

## How to Register ##

Through the navigation bar, press the “Register” button on the top right side of the screen. There are 4 boxes you must fill out: username, display name, password, and a confirmation of your password. These boxes are the white boxes that allow you to put text into them. To register, fill out all 4 boxes with your preferred registrations. When complete, press the blue “Register” button. If successful, you should be redirected to the home page and see a blue banner that says “Registered!” 

## How to Login In ##

If you have yet to make an account, please check the “How to Register” information section of this README file. Once you have completed making an account, login using your username and password. When you have typed them in, press the blue “Log In” button. 

## How to rate an album ##

Once logged in (if you have not, see the instructions above), you can click on an album via home and search page. Click on the album you wish to rank, then you need to fill out the ranking form. Once you click on the page, it will take you to the rating page, with 5 open text boxes: title, artist, your rating, your display name, and write your review here. Fill out the text boxes & complete the ranking. 

## How to view the Top 10 Albums per Genre ##
 
From any point on The Peanut Gallery, navigate your cursor to the top white bar (the navigation bar). On this bar, press "Top Charts" and allow the page to load entirely. Here you can explore the top 10 albums per genre, such as Hip Hop, Indie Rock, etc. On this page, there are 10 genres. 

## How to use the Search ## 

Through the navigation bar, press the “Search” button on the top left side of the screen. Here, you can look for a specific album to find the Peanut Score. To search, click on the white box that has the placeholder “Search…”. This is a temporary placeholder that will not show up in your final search results. Type the specific album you are looking for & press the blue “Go!” button. 
