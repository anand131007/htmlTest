htmlTest
========

/*CSS RESET 
--------------------------------------------------------------------------------------------------------------*/

@charset "utf-8";

/*--------------------------------------------------------------------------------------------------
CSS Styles for <PROJECT NAME>.

version:   1.0
--------------------------------------------------------------------------------------------------*/

/* =CSS Reset
--------------------------------------------------------------------------------------------------*/

/* http://meyerweb.com/eric/tools/css/reset/ 
   v2.0 | 20110126
   License: none (public domain)
*/
html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code, del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li,
fieldset, form, label, legend, table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed, figure, figcaption, footer, header, hgroup, 
menu, nav, output, ruby, section, summary, time, mark, audio, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure, footer, header, hgroup, menu, nav, section {
	display: block;
}
body {
	line-height: 1;
}
ol, ul {
	list-style: none;
}
blockquote, q {
	quotes: none;
}
blockquote:before, blockquote:after, q:before, q:after {
	content: '';
	content: none;
}
table {
	border-collapse: collapse;
	border-spacing: 0;
}

/* End CSS Reset
--------------------------------------------------------------------------------------------------*/

/* remember to define focus styles! */
:focus {
	outline: 0;
}
/* =Toolkit
--------------------------------------------------------------------------------------------------*/

/* Micro Clearfix Hack by Nicholas Gallagher (http://nicolasgallagher.com/micro-clearfix-hack/) */
/* For modern browsers */ 
.cf:before, .cf:after { content:""; display:table; }
.cf:after { clear:both; }
/* For IE 6/7 (trigger hasLayout) */
.cf { zoom:1; }

/* general purpose classes */
.nodisplay { display:none; }
.nodisplay_strict { display:none !important; }
.alignleft { float:left; }
.alignnone { clear:both;
	font-size:0;
	line-height:0;
	margin:0;
	padding:0;
	border:0;
	height:0;
	width:0;}
.alignright { float:right;}

/* End Toolkit
--------------------------------------------------------------------------------------------------*/

/* =Normalization - mostly derived from normalize.css (https://github.com/necolas/normalize.css/) but without comments and compressed to keep the file small
--------------------------------------------------------------------------------------------------*/

hr { display:block; height:1px; border:0; margin:1em 0; padding:0; border-top:1px solid #cccccc; /* change border colour to suit your needs */ }
audio, canvas, video { display: inline-block; *display: inline; *zoom: 1; }
audio:not([controls]) { display: none; }
[hidden] { display: none; }
html { overflow-y: scroll; font-size: 100%;  -webkit-text-size-adjust: none; -ms-text-size-adjust: none;}
body, button, input, select, textarea { font-family: sans-serif; }
a:focus { outline: none; }
a:hover, a:active { outline: none; }
h1 {}
h1, h2, h3, h4, h5, h6, p, pre, blockquote, form, fieldset, table, ul {}
dd { margin: 0px; }
nav ul, nav ol { list-style: none; list-style-image: none; }
ins {text-decoration: none;}
del { text-decoration: line-through; }
abbr[title] { border-bottom: 1px dotted; cursor:help; }
b, strong { font-weight: bold; }
dfn { font-style: italic; }
mark { background: #ff0; color: #000; }
pre, code, kbd, samp { font-family: monospace, serif; _font-family: 'courier new', monospace;}
pre { white-space: pre; white-space: pre-wrap; word-wrap: break-word; }
small { font-size: 100%; }
sub,sup { font-size: 100%; line-height: 0; position: relative; vertical-align: baseline; }
sup { top: -0.5em; }
sub { bottom: -0.25em; }
img { border: 0; -ms-interpolation-mode: bicubic; vertical-align:top;}
svg:not(:root) { overflow: hidden; }
figure { margin: 0; }
form { margin: 0; }
fieldset { border: none; margin: 0; padding: 0; }
legend { border: 0; padding: 0; white-space: normal; *margin-left: -7px;}
input, textarea {-webkit-appearance: none;}
button, input, select, textarea { font-size: 100%; margin: 0; vertical-align: baseline; *vertical-align: middle; outline:0;}
button, input { line-height: normal; }
button{ border: 0; padding: 0; }
button, input[type="button"], input[type="reset"], input[type="submit"] { cursor: pointer; -webkit-appearance: button; *overflow: visible; white-space: normal;}
input, select { vertical-align:middle; }
input[type="checkbox"], input[type="radio"] { box-sizing: border-box; padding: 0; *height: 13px; *width: 13px;}
input[type="search"] { -webkit-appearance: textfield; -moz-box-sizing: content-box; -webkit-box-sizing: content-box; box-sizing: content-box; }
input[type="search"]::-webkit-search-decoration { -webkit-appearance: none; }
button::-moz-focus-inner, input::-moz-focus-inner { border: 0;}
textarea { overflow: auto; vertical-align: top; resize: none; -webkit-appearance: none; }
::-moz-focus-inner {border: 0; outline: 0;}
/* End Normalization
--------------------------------------------------------------------------------------------------*/


/* =Typography
--------------------------------------------------------------------------------------------------*/

/* Setting up the fonts */
body {
  font: 14px/18px Arial, Helvetica, sans-serif;
  color:#000;
  background:#fff;
  -webkit-font-smoothing: antialiased;
}

/* End Typography
--------------------------------------------------------------------------------------------------*/


/* =Headings
--------------------------------------------------------------------------------------------------*/
h1 {}
h2 {}
h3 {}
h4 {}
h5 {}
h6 {}

/* End Headings
--------------------------------------------------------------------------------------------------*/


/* =Links
--------------------------------------------------------------------------------------------------*/
a {text-decoration:none; Color:#000; cursor:pointer !important; outline: 0;}
a:hover {text-decoration:underline;}

/* End Links
--------------------------------------------------------------------------------------------------*/


/* =Branding
--------------------------------------------------------------------------------------------------------*/
p {padding:0 0 10px 0; margin:0;}
html, body {}
#wrapper {width:960px; margin:0 auto;}
#header {background: #999; font-size: 16px;font-weight: bold; color: white; 
text-align: center; line-height: 40px; height: 40px; padding: 0 50px;
} 

#logo { display:inline-block; }
#logo a {
	display:block;
	width:248px;
	height:190px;
	text-indent:-9999px;
	text-decoration:none;
	background:url(../img/bgi/logo-name.png) left top no-repeat;
}
/* End Branding
--------------------------------------------------------------------------------------------------------*/


/* =Main Nav
--------------------------------------------------------------------------------------------------*/
.top-menu{}


#mainNavigation {}
#mainNavigation li {float:left;}
#mainNavigation li a {display:block;}
#mainNavigation li:hover a, #mainNavigation li.active a{text-decoration:none;}
/* End Main Nav
--------------------------------------------------------------------------------------------------*/


/* =Sub Nav
--------------------------------------------------------------------------------------------------*/
#subNavigation {}
#subNavigation li{float:left;}
#subNavigation li a{display:block;}
#subNavigation li:hover a, #subNavigation li.active a{text-decoration:none;}
/* End Sub Nav
--------------------------------------------------------------------------------------------------*/

/* =Breadcrumbs start
--------------------------------------------------------------------------------------------------*/
.breadcrumbs {}
.breadcrumbs a{display:inline-block;}
.breadcrumbs a:hover {text-decoration:none;}
/* =Breadcrumbs ends
--------------------------------------------------------------------------------------------------*/


/* =Main Content
--------------------------------------------------------------------------------------------------*/
#container { }
.content {padding:15px; }
.widecolumn {}
.narrowcolumn {}
.narrowcolumnLeft {}
.narrowcolumnRight {}
/* =End Main Content
--------------------------------------------------------------------------------------------------*/
.content{}

/* =Secondary Content
--------------------------------------------------------------------------------------------------*/

/* End Secondary Content
--------------------------------------------------------------------------------------------------*/


/* =Footer
--------------------------------------------------------------------------------------------------*/
#footer {}
.footer-link{}
.footer-link li{}
.footer-link li a{display:inline-block;}
.footer-link li a:hover{text-decoration:none;}
/* End Footer
--------------------------------------------------------------------------------------------------*/


/* =Forms
--------------------------------------------------------------------------------------------------*/
/* Removing fieldset borders (remove if you want to keep the defaults defined in Normalization) */
fieldset{border: none; margin: 0; padding: 0;}
fieldset p{}
.contactform{width:300px;}
.fieldgroup{display:block; margin-bottom:5px; border:1px solid #999; background:#efefef; padding:8px 10px; overflow:hidden;}
.fieldgroup input, .fieldgroup textarea{border:none; background:none; padding:0; width:100%;}
/* End Forms
--------------------------------------------------------------------------------------------------*/

/* =Tables
--------------------------------------------------------------------------------------------------*/

/* End Tables
--------------------------------------------------------------------------------------------------*/


/* =Misc 1
--------------------------------------------------------------------------------------------------*/
.menu{ font-size:12px; color:#333; text-decoration:underline; display:block; position:absolute; top:0; left:0;}
/* End Misc 1
--------------------------------------------------------------------------------------------------*/


/* =Misc 2
--------------------------------------------------------------------------------------------------*/

/* End Misc 2
--------------------------------------------------------------------------------------------------*/


/* =Additional 1
--------------------------------------------------------------------------------------------------*/

/* End Additional 1
--------------------------------------------------------------------------------------------------*/


/* =Additional 2
--------------------------------------------------------------------------------------------------*/

/* End Additional 2
--------------------------------------------------------------------------------------------------*/





















/* css - Media queies 
--------------------------------------------------------------------------------------------------------------*/


@media only screen and (max-width:1680px){}

@media only screen and (max-width:1440px){}

@media only screen and (max-width:1360px){}

@media only screen and (max-width:1280px){}

@media only screen and (max-width:1024px){}

@media only screen and (max-width:800px){}

@media only screen and (min-device-width:768px) and (max-device-width:1024px){}
@media only screen and (min-device-width:768px) and (max-device-width:1024px) and (orientation:landscape){}
@media only screen and (min-device-width:768px) and (max-device-width:1024px) and (orientation:portrait){}

@media only screen and (max-width:640px){}

@media only screen and (max-width:568px){}
@media only screen and (max-width:480px){}
@media only screen and (min-device-width:320px) and (max-device-width:480px){}
@media only screen and (min-device-width:320px) and (max-device-width:480px) and (orientation: portrait){}
@media only screen and (min-device-width:320px) and (max-device-width:480px) and (orientation: landscape){}

@media only screen and (max-width:320px){}




/* Responsive Design for Retina Displays on iPad and iPhone
--------------------------------------------------------------------------------------*/
/*@media only screen and (-webkit-min-device-pixel-ratio: 2){}*/
@media only screen and (-webkit-min-device-pixel-ratio: 2), only screen and (-o-min-device-pixel-ratio: 4/2), only screen and (min--moz-device-pixel-ratio: 2), only screen and (min-device-pixel-ratio: 2) {
#logo a {background:url(../img/logo.png) left top no-repeat; background-size:100% 100%;}	
}




/*ie*/

#test{behavior: url(pie.htc);position:relative;}
#test{ -pie-background: linear-gradient(top, #BAAF9F 50%, #B4A896 100%); }


