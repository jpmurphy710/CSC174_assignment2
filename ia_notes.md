# Alex's Notes Regarding Information Architecture of Assignment 2

## CSC174_assignment2-master  Folder Contents:
	* 3 Folders containing the Sub-Sites of cmarti21, jhuo3, and jngene
	* homepage.php  file, which is the homepage for the entire Assignment 2 Smash Site
	* "inc" Folder : Containing file "menu.php", which acts as the eyebrow menu pasted into the top right corner of each page on each person's subsite (the php include statement for 'menu.php' is already written in each page of each of the sub-sites)
	* "css" Folder : Containing the file "home_styles.css" , which is the css stylesheet for the homepage of Assignment 2. The css stylesheets for each person's individual sub-site are still in css folders within the folders containing their sub-site files. 


## html-top Includes within inc Folders of each Sub-Site:
	Each of the subsites is using their own "html-top" file to easily re-paste the header to each of the four pages in their sub-site. Contained within these html-top files are:
	
	 	* Personal picture
	 	* their name (rotated h1)
	 	* the list of 3 attributes about them 
	 	* links to their personal css style sheets
	 	* title of the currently displaying page. 
	The html-top files for each sub-site are found within the "inc" folder for that person's sub-site.

	*** It should be noted that the html-top files open the <body> tag, but do not close it (the tag is closed on each of the four  .php files in the sub-sites). Keep this in mind when coding css

