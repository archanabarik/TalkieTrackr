# TalkieTrackr
##Create a Tracker using MEAN stack.

-The front-end is built using AngularJS and Bootstrap Sass.
-used AngularStrap Navbar instead of Bootstrap Navbar - the active class is applied automatically to <li> elements when you change routes. -Plus you get many other awesome directives that integrate with AngualrJS such as Alert, Typeahead, Tooltip, Tab and many more.
-Use Gulp to compile Sass stylesheets.
-Password Authentication with Mongoose - use bcrypt.js (for password hashing).
-Use xml2js parser for XML to JavaScript object converter (It normalize all tags to lowercase and disable conversion to arrays when there is only one child element.)
-Use async, for managing multiple aynsc operations. (async.waterfall).
-The poster are stored as Base64 images in MongoDB (although it has a disadvantage that each image is about 30% larger in the Base64 form).
-Use moment.js to output a more friendly date (like in 6 hours or in 5 days).
-Use ng-Messages for rending error messages in forms.
-Login with Facebook/Google.
-Use ngAnnotate instead of ngMin for AngularJS dependencies annotations.
-For sending email notifications - use Agenda, Sugar.js and nodemailer.
-Optimization of code using gulp.js Concatenate and minify the scripts, Minify the stylesheet and Cache AngularJS templates.
-The optimization creates 2 scripts which are app.min.js and templates.js
