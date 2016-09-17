Userium is a responsive Drupal 8 theme.

THEME FEATURES
--------------------------------
Uses Bootstrap v3.3.6
SASS / Compass
Responsive menu
Google Font - Oswald
Jumbotron images are hidden on small displays
Tested with Firefox 44.0.2, Google Chrome 51.0, Safari 9.1.2

THEME REGIONS
--------------------------
content: 'Main Content'
header: 'Header'
footer_first: 'Footer First'
footer_second: 'Footer Second'
sidebar: 'Sidebar'
sidebar_blog: 'Sidebar Blog' 
about: 'About' 

INSTALLATION
------------
1. Drupal 8 site
2. Place the "Userium" folder to the root /themes directory.
3. Login to the site and click on "Appearance" in the Administration menu.
4. Click on "Install and set as default" next to the Userium theme.

HOW TO INSTALL FONT AWESOME
------------------------
1. Uncomment lines from userium.libraries.yml
2. Create a vendor folder (userium/vendor)
3. Download Font Awesome (http://fontawesome.io/), unzip the file, and place the css and fonts folder in the newly created vendor folder. 
4. Clear Drupal cache

USE OF SASS / COMPASS 
------------------------
This theme uses Sass, which will not compile automatically without Compass. It's configured in userium/config.rb
Compass runs on any computer that has ruby installed (http://compass-style.org/install/)
More information on Sass: http://sass-lang.com/
On the terminal, you need to be in the userium folder, to run "compass watch" which will compile your Sass to CSS.
The "sass" folder (userium/sass) contains all the styling, separated in different files.

DEMO
----
http://192.254.249.110/kota
