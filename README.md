# CodersLab FinalProject: cowork LandingPage

This is the first part of final project - a simple landing page, which will be expanded in the second phase.
The main purpose of this page is to hold a survey.

##URL address
Website is available at: http://nmkedziora.github.io/cowork_landingPage/

##Technology stack:
1. HTML5
2. CSS3
3. jQuery
4. Skeleton (with normalize reset) - a mobile first CSS framework
5. Sass
6. Gulp (gulp-sass, gulp-jshint, browser-sync)
7. Fontawesome


##Development
For Development I used:
- to serve project on mobile: Python SimpleHTTPServer module;
- to serve project on desktop: browser-sync to automatically serve .html, .css and .js after each change.

Site was developed using Chrome desktop Version 50.0.2661.75 (64-bit).
It works well also on mobile devices (I used Moto X Play 5.5" for development checkups), both on portrait and landscape views.
Checks were done also on latest versions of desktop Safari and Firefox.


###Header
The movement on header is done using parallax effect. Each picture is moving in different pace.
The header doesn't scale on page zooming.
For mobile back and fore pictures are switched off.

Logo is just a sample logo. It needs to be revised, so it is more visible on the background.


###Our Team
On this section parallax is used to animate teams' pictures.


###Survey
Since precise questions are not known yet, form validation is done only for optional fields, meaning name and email.
Form/survey design assumption is that a user doesn't have to give it's name or email to submit his opinion.

####To test form validation:
1. Check "I would like to receive updates" checkbox.
2. Put your name and email, and submit the form.

**Notice:** There is no back-end side for the survey, so the animation is only action imitation/ visualization.
