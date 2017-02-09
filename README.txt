Instructions:

To create your own HTML document that will work with this script 
instead of using the supplied “index.html”, you must ensure the following:



1. You must copy the provided “css”, “fancybox”, and “js” folders into in the same directory as your HTML form document.



2. In the <head></head> tags at the top of your web page you must copy and paste the following four lines of script:



<script type="text/javascript" src="http://code.jquery.com/jquery-latest.min.js"></script>

<script type="text/javascript" src="js/send.js"></script>

<script type="text/javascript" src="fancybox/source/jquery.fancybox.pack.js?v=2.1.5"></script>

<script type="text/javascript" src="fancybox/source/helpers/jquery.fancybox-thumbs.js?v=1.0.7"></script>



3. The form in your document must have an ID attribute of “subscribe-form” 

e.g. 

<form id=“subscribe-form”> 



Any extra attributes such as “method” or “action” will be ignored.



4. There should be three input fields inside this form element, 
with name attributes of “firstname”, “lastname”, and “email”
 
e.g.

<input type=“text” name=“firstname”>
<input type=“text” name=“lastname”>
<input type=“text” name=“email”>



These must be spelled exactly as they are here.



5. Optionally, you can include your own submit button. 
If not, a default one with a value of “Submit” will be added automatically.


Additional Notes:
1: The validation on the form will check for the presence of an '@' symbol. This can be removed or made more of a feature for a lesson.

2: The heading styles h3 and h4 are used in the JavaScript file for the simulated database styles. If either of these heading selectors are used in the main website, their styles will be superseded by those in the JavaScript.