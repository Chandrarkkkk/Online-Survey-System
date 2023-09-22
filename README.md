.dhtmlx_message_area{
	position:fixed;
	right:5px;
	margin-top:20px;
	width:250px;
	z-index:1000;
}

.dhtmlx-info{
	min-width: 120px;
	min-height:20px;
	padding:4px 4px 4px 20px;
	font-family:Tahoma;
	z-index: 10000;

	margin:5px;
	margin-bottom:10px;

	-webkit-transition: all .5s ease;
    -moz-transition: all .5s ease;
    -o-transition: all .5s ease;
    transition: all .5s ease;
}
.dhtmlx-info.hidden{
	height:0px;
	min-height: 0px;
	padding-top:0px;
	padding-bottom:0px;
	border-width:0px;
	margin-top:0px;
	margin-bottom:0px;
	overflow:hidden;
}

.dhtmlx_modal_box{
	overflow:hidden;
	display: inline-block;
	min-width: 300px;
	width: 300px;
	text-align: center;
	position:fixed;

	background-color: #fff;
	background:-webkit-linear-gradient(top, #ffffff 1%, #d0d0d0 99%);
	background:-moz-linear-gradient(top, #ffffff 1%, #d0d0d0 99%);
	box-shadow: 0px 0px 14px #888;

	font-family: Tahoma;

	z-index:20000;

	border-radius:6px;
	border: 1px solid #ffffff;
}

.dhtmlx_popup_title{
	border-top-left-radius:5px;
	border-top-right-radius:5px;

	border-width:0px;
	
	background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAAoCAMAAAAIaGBFAAAAhFBMVEVwcHBubm5sbGxqampoaGhmZmZlZWVjY2NhYWFfX19dXV1bW1taWlpYWFhWVlZUVFRSUlJRUVFPT09NTU1LS0tJSUlHR0dGRkZERERCQkJAQEA+Pj49PT09PT0+Pj5AQEBBQUFDQ0NERERGRkZHR0dJSUlKSkpMTExMTEw5OTk5OTk5OTkny8YEAAAAQklEQVQImQXBCRJCAAAAwKVSQqdyjSPXNP7/QLsIhA6OTiJnF7GrRCpzc/fw9PKW+/gqlCq1RqvTG/yMJrPF6m/bAVEhAxxnHG0oAAAAAElFTkSuQmCC);
	background-image: -webkit-linear-gradient(top, #707070 1%, #3d3d3d 70%, #4c4c4c 97%, #393939 97%);
	background-image: -moz-linear-gradient(top, #707070 1%, #3d3d3d 70%, #4c4c4c 97%, #393939 97%);
}

.dhtmlx-info, .dhtmlx_popup_button, .dhtmlx_button{
	user-select: none;
	-webkit-user-select: none;
	-moz-user-select:-moz-none;

	cursor:pointer;
}

.dhtmlx_popup_text{
	overflow:hidden;
}

.dhtmlx_popup_controls{
	border-radius:6px;
	padding:5px;
}

.dhtmlx_popup_button, .dhtmlx_button{
	height: 30px;
	line-height:30px;

	display: inline-block;
	margin: 0 9px;
	border-radius: 6px;

	color:#FFF;
}
.dhtmlx_popup_button{
	min-width: 120px;
}

div.dhx_modal_cover {
	background-color:#000;
	cursor:default;

	filter:alpha(opacity = 20);
	opacity: 0.2;

	position: fixed;
	z-index:19999;
	left: 0px;		top: 0px;
	width: 100%;	height: 100%;

	border: none;
	zoom: 1;
}

.dhtmlx-info img, .dhtmlx_modal_box img{
	float:left;
	margin-right:20px;
}

.dhtmlx-alert-error .dhtmlx_popup_title, .dhtmlx-confirm-error .dhtmlx_popup_title{
	background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAAsCAIAAAArRUU2AAAATklEQVR4nIWLuw2AMBBDjVuQiBT2oWbRDATrnB0KQOJoqPzRe3BrHI6dcBASYREKovtK6/6DsDOX+stN+3H1YX9ciRgnYq5EWYhS2dftBIuLT4JyIrPCAAAAAElFTkSuQmCC);
}
.dhtmlx-alert-error, .dhtmlx-confirm-error {
	border: 1px solid #ff0000;
}

/*Skin section*/
.dhtmlx_button, .dhtmlx_popup_button{
	box-shadow: 0px 0px 4px #888;
	border:1px solid #838383;
}
.dhtmlx_button input, .dhtmlx_popup_button div{
	border:1px solid #FFF;
	background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAAeCAMAAADaS4T1AAAAYFBMVEVwcHBtbW1ra2toaGhmZmZjY2NhYWFeXl5cXFxaWlpXV1dVVVVSUlJQUFBNTU1LS0tJSUlGRkZERERBQUE/Pz88PDw9PT0+Pj5AQEBCQkJDQ0NFRUVHR0dISEhKSkpMTEzqthaMAAAAMklEQVQImQXBhQ2AMAAAsOIMlwWH/8+kRSKVyRVKlVrQaHV6g9FktlhFm93hdLk9Xt8PIfgBvdUqyskAAAAASUVORK5CYII=);
	background-image: -webkit-linear-gradient(top, #707070 1%, #3d3d3d 70%, #4c4c4c 99%);
	background-image: -moz-linear-gradient(top, #707070 1%, #3d3d3d 70%, #4c4c4c 99%);

	border-radius:6px;
	font-size:15px;
	font-weight:normal; 
	-moz-box-sizing:content-box;
	box-sizing:content-box;

	color:#fff; padding:0px; margin:0px;
	vertical-align:top;

	height:28px;
	line-height:28px;
}

.dhtmlx_button input:focus, .dhtmlx_button input:active, .dhtmlx_popup_button div:active, .dhtmlx_popup_button div:focus{

	background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAAeCAMAAADaS4T1AAAAXVBMVEVwcHBubm5tbW1sbGxra2tpaWloaGhnZ2dmZmZlZWVjY2NiYmJhYWFgYGBfX19dXV1cXFxbW1taWlpZWVlXV1dWVlZVVVVUVFRTU1NRUVFQUFBPT09OTk5NTU1LS0tT9SY0AAAAMUlEQVQImQXBhQGAMAAAIGxnx2z9/00BiVQmVyhVakGj1ekNRpPZYhVtdofT5fZ4fT8hpwG05JjexgAAAABJRU5ErkJggg==);
	background-image: -webkit-linear-gradient(top, #707070 1%, #4c4c4c 99%);
	background-image: -moz-linear-gradient(top, #707070 1%, #4c4c4c 99%);	
}
.dhtmlx_popup_title{
	color:#fff;
	text-shadow: 1px 1px #000;
	height:40px; line-height:40px;
	font-size:20px;
}
.dhtmlx_popup_text{
	margin:15px 15px 5px 15px;
	font-size:14px;
	color:#000;
	min-height:30px;
	border-radius:6px;
}


.dhtmlx-info, .dhtmlx-error{
	font-size:14px;
	color:#000;
	box-shadow: 0px 0px 10px #888;
	
	padding:0px;
	
  	background-color:#FFF;
	border-radius:3px;
	border:1px solid #ffffff;
}
.dhtmlx-info div{
	padding:5px 10px 5px 10px;
	background-color: #fff;

	border-radius:3px;
	border:1px solid #B8B8B8;
}
.dhtmlx-error{
	background-color: #d81b1b;
	border:1px solid #ff3c3c;
	box-shadow: 0px 0px 10px #000;
}
.dhtmlx-error div{
	background-color: #d81b1b;	
	border:1px solid #940000;
	color:#FFF;
}



html, body, div, span,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend {
	background: transparent;
	border: 0;
	margin: 0;
	padding: 0;
	vertical-align: baseline;
	font-family:'Helvetica Neue', Helvetica, Arial, sans-serif;
}
body
{webkit-touch-callout: none;-webkit-user-select: none;-khtml-user-select: none;-moz-user-select: -moz-none;-ms-user-select: none;user-select: none;-moz-user-select: none;-webkit-user-select: none;
}
body.login { background: url(../bg.png); }
h2 { font-size: 30px; line-height:38px; font-weight:normal; }
.loginbox { background: #FBFCFD; padding: 10px; width: 490px; margin: 4% auto 0 auto; position: relative; }
.loginboxinner { 
	background: #FBFCFD; padding: 5px; position: relative; border: 1px solid #FBFCFD;
	-moz-box-shadow: inset 0 1px 0 #FBFCFD; -webkit-box-shadow: inset 0 1px 0 #FBFCFD; box-shadow: inset 0 1px 0 #FBFCFD;
}
.loginheader { height: 20px; }
.loginform { margin: 4px auto; text-align:center; }

.loginbox h1 { font-size: 30px; letter-spacing: 1px; color: #555; font-weight: normal; padding-top: 10px; }
.loginbox p { margin: 7px 0 5px 0; }
.loginbox label { display: block; color: #666; letter-spacing: 1px; font-size: 18px; }
.loginbox input.mini { width:195px; }
.loginbox input { 
	padding: 12px 10px; color: #000; 
	font-family: Arial, Helvetica, sans-serif; margin-top: 8px; font-size: 15px; border: 1px solid #ccc; width: 420px;  outline: none; 
}
.loginbox a.button { 
	background: #5870A8; 
	background-image:-webkit-linear-gradient(top, #637BAD, #4F67A4); 
	padding: 10px 20px; 
	font-size: 18px; 
	border: 1px solid #1D3871;
	 letter-spacing: 1px; color: #fff; width: 440px; line-height:30px; font-family:	'Helvetica Neue', Helvetica, Arial, sans-serif;
	-moz-box-shadow: 1px 1px 3px #1D3871; -webkit-box-shadow: 1px 1px 3px #1D3871; box-shadow: 1px 1px 3px #1D3871; cursor: pointer;
}

.radius { -moz-border-radius: 5px; -webkit-border-radius: 5px; border-radius: 5px; }
.radius1 { -moz-border-radius: 3px; -webkit-border-radius: 3px; border-radius: 3px; }
.title { font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif; color:#8E989E; line-height:28px; font-weight:normal; text-align:center; font-size:16px; }


@media screen and (max-width: 430px) {
	
	body { font-size: 11px; }
	button, input, select, textarea { font-size: 11px; }
	
	.loginbox { width: auto; margin: 10px; }
	.loginbox input { width: 95%; }
	.loginbox button { width: 100%; }
}	


#cse-Bar {
	background:#45619D;
	border-bottom: 1px solid #0053A6;
	box-shadow: 0 0 2px rgba(0, 0, 0, 0.52);
	min-width: 1000px;
	width: 100%;
	z-index: 1000;
}
#cse-Frame {
	margin-left:auto;
	margin-right:auto;
	max-width:1000px;
	height:70px;
	display:block;
}
/*-------LOGO-----------*/
#logo {
	float: left;
	height: 70px;
	position: relative;
	width: 160px;
}
#logo a {
	position: absolute;
	top: 20px;
	font-size:23px; font-weight:bold; color:#FFF;
	text-decoration:none;
	font-family:"Lucida Sans Unicode", "Lucida Grande", sans-serif;
}

/*-------Login-----------*/
#header-main-right {
	float: right;
	height: 68px;
	position: relative;
	top:5px;
}
#header-main-right-nav {
	padding: 4px 6px 4px 4px;
	position: absolute;
	right: 0;
}
#login_form .inputtext {
	background-color: #FFFFFF;
	height:16px;
	font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
	font-size: 13px;
	margin: 0;
	padding: 5px 8px 5px 8px;
	width: 166px;
	border:1px solid #3A518A;
}
#login_form .inputtext:hover {
	border-color: #A0A0A0 #B9B9B9 #B9B9B9;
	border-image: none;
	border-style: solid;
	border-width: 1px;
	box-shadow: 0 1px 2px rgba(0, 0, 0, 0.1) inset;
}

#login_form table tr td {
	padding: 0 0 0 5px;
}
#login_form table tr td label {
	color: #fff;
	cursor: pointer;
	font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
	font-size: 12px;
	font-weight: normal;
	padding-left: 1px;
	text-align: left;
	vertical-align: middle;
}
.fbbutton { border:1px solid #1D3871; width:94px; background-image:-webkit-linear-gradient(top, #637BAD, #4F67A4); font-size:14px; line-height:25px; font-weight:normal; color:#fff; }

#customers {
    font-family: "Trebuchet MS", Arial, Helvetica, sans-serif;
    width: 90%;
    border-collapse: collapse;
    text-align:center;
}

#customers td, #customers th {
    font-size: 1em;
    border: 1px solid #98bf21;
    padding:7px;
}

#customers th {
    font-size: 1.1em;
    text-align: left;
    padding-top: 5px;
    padding-bottom: 4px;
    background-color: #A7C942;
    color: #ffffff;
    text-align:center;
}

#customers tr.alt td {
    color: #000000;
    background-color: #EAF2D3;
}


.btn {
  font-size: 3vmin;
  padding: 0.35em 0.5em;
  background-color:#BDB76B;
  border: 1px solid #bbb;
  color: #333;
  text-decoration: none;
  display: inline;
  border-radius: 4px;
  -webkit-transition: background-color 1s ease;
  -moz-transition: background-color 1s ease;
  transition: background-color 1s ease;
}

.btn:hover {
  background-color: #ddd;
  -webkit-transition: background-color 1s ease;
  -moz-transition: background-color 1s ease;
  transition: background-color 1s ease;
}

.btn-small {
  padding: .75em 1em;
  font-size: 0.8em;
}

.my-button {
	text-transform:capitalize;
	cursor:pointer;
	padding:7px 15px;
	margin:7px 0 0;
	line-height:25px;
	display:inline-block;
	border:none;
	color:#fff;
	font-weight:bold;
	-webkit-text-shadow:0 -1px 0 rgba(0,0,0,0.2);
	-moz-text-shadow:0 -1px 0 rgba(0,0,0,0.2);
	text-shadow:0 -1px 0 rgba(0,0,0,0.2);
}
.my-button:hover { color:#fff; }
.small,.small:hover {
	line-height:12px;
	font-size:11px;
	-webkit-box-shadow:0 -5px 5px rgba(0,0,0,0.1) inset,0 1px 0 rgba(255,255,255,0.3) inset;
	-moz-box-shadow:0 -5px 5px rgba(0,0,0,0.1) inset,0 1px 0 rgba(255,255,255,0.3) inset;
	box-shadow:0 -5px 5px rgba(0,0,0,0.1) inset,0 1px 0 rgba(255,255,255,0.3) inset;
}
.medium,.medium:hover {
	line-height:18px;
	font-size:13px;
	-webkit-box-shadow:0 -10px 10px rgba(0,0,0,0.15) inset,0 1px 0 rgba(255,255,255,0.3) inset;
	-moz-box-shadow:0 -10px 10px rgba(0,0,0,0.15) inset,0 1px 0 rgba(255,255,255,0.3) inset;
	box-shadow:0 -10px 10px rgba(0,0,0,0.15) inset,0 1px 0 rgba(255,255,255,0.3) inset;
}
.large,.large:hover {
	line-height:24px;
	font-size:14px;
	padding:9px 17px;
	-webkit-box-shadow:0 -10px 15px rgba(0,0,0,0.15) inset,0 1px 0 rgba(255,255,255,0.3) inset;
	-moz-box-shadow:0 -10px 15px rgba(0,0,0,0.15) inset,0 1px 0 rgba(255,255,255,0.3) inset;
	box-shadow:0 -10px 15px rgba(0,0,0,0.15) inset,0 1px 0 rgba(255,255,255,0.3) inset;
}
.blue {
	background-color:#01afe7;
	border:1px solid #009bcd;
}
.blue:hover {
	background-color:#15c6ff;
}
.slate {
	background-color:#838B8E;
	border:1px solid #767c7f;
}
.slate:hover {
	background-color:#939c9f;
}
.pink {
	background-color:#ea3271;
	border:1px solid #d72160;
}
.pink:hover {
	background-color:#FD5D94;
}
.lamb {
	background-color:#e6c470;
	border:1px solid #d5b462;
}
.lamb:hover {
	background-color:#F7D683;
}
.red {
	background-color:#D54336;
	border:1px solid #c5392c;
}
.red:hover {
	background-color:#f4695d;
}
.green {
	background-color:#8EC63F;
	border:1px solid #79ab34;
}
.green:hover {
	background-color:#a5e151;
}
.terra {
	background-color:#ef6658;
	border:1px solid #ec6a5d;
}
.terra:hover {
	background-color:#ff7f72;
}
.grey {
	background-color:#bdbdbd;
	border:1px solid #acacac;
}
.grey:hover {
	background-color:#CFCFCF;
}
.brown {
	background-color:#b0a066;
	border:1px solid #998b57;
}
.brown:hover {
	background-color:#C5B475;
}
.dark {
	background-color:#457D97;
	border:1px solid #35667c;
}
.dark:hover {
	background-color:#5695b3;
}
.white {
	background-color:#dddddd;
	border:1px solid #c7c7c7;
	color:#555;
}
.white:hover {
	background-color:#eee;
}
.black {
	background-color:#555;
	border:1px solid #333;
}
.black:hover {
	background-color:#757575;
}
.purple {
	background-color:#c215d5;
	border:1px solid #790186;
}
.purple:hover {
	background-color:#e034f3;
}
.orange {
	background-color:#FC9B0F;
	border:1px solid #e58700;
}
.orange:hover {
	background-color: #fcc10f;
}
.my-button span {
	float:left;
	display:inline-block;
	margin-top:3px;
	margin-right:5px;
}

