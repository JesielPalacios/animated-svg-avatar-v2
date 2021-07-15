# Animated SVG Avatar v2

A Pen created on CodePen.io. Original URL: [https://codepen.io/dsenneff/pen/2c3e5bc86b372d5424b00edaf4990173](https://codepen.io/dsenneff/pen/2c3e5bc86b372d5424b00edaf4990173).

Created a login form with an SVG avatar that responds to the input in the email field. Used the GSAP TweenMax library + GSAP's MorphSVG plugin for the animating. 

Here's what I changed/fixed/added in v2:

-Added "show/hide" password functionality. This is a nice user experience improvement, as a lot of users, especially on mobile, prefer to see their password as they type it due to the rate at which we mistype on our mobile devices. The password is displayed by default on mobile, and hidden by default on desktop.

-Added a random eye blink

-Added secondary animation of the shoulders when the avatar raises its arms.

-Fixed a bug where the arms would appear in front of the face for a split second when the page first loads

-Fixed a bug where entering a really long email address would mess up where the avatar would look

-Fixed a bug where pasting text into the email input wouldn't update where the avatar looked

-Fixed a bug that caused the avatar to look in the wrong place when going from the password field back to the email field

-Fixed a bug in Safari where one of the arms rotated incorrectly

-Fixed a bug where the avatar's chin would flip upside down sometimes

-Fixed a bug where changing browser tabs or windows then coming back would screw up the avatar's animation

-Fixed a bug in Safari where the border around the avatar got distorted when the arms animated

-Fixed a bug where clicking on an input's label while that input already had focus would trigger the blur animations

-Implemented a fix for Chrome/Firefox that didn't allow the position of the text cursor to be calculated within an input type of "email", only an input type of "text". So now the user will get the proper "email" keyboard displayed on a mobile device when they click into that field.

-Fixed a bug where clicking and holding the show/hide checkbox would cause the hands to drop down


Link repo: https://codepen.io/dsenneff/pen/2c3e5bc86b372d5424b00edaf4990173