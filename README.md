<html><head><style> @import url(https://weloveiconfonts.com/api/?family=entypo|fontawesome);
/* entypo */
[class*="entypo-"]:before {
  font-family: 'entypo', sans-serif;
}
/* fontawesome */
[class*="fontawesome-"]:before {
  font-family: 'FontAwesome', sans-serif;
}

/* Utils */

.clear {
	clear: both;
}
.purple {
	color: #837c9a;
}

.block {
	margin: 25px 30px;
}
.first.block{
  margin-top  :30px 50px;}
	.block h1 {
		margin-left: -5px;
		font-weight: 400;
	}

.last.block {
	margin-bottom: 110px;
}

.horizontal_list {
	margin: 0;
	padding: 0;
	list-style-type: none;
}
	.horizontal_list li {
		float: left;
	}
	.horizontal_list li:before {
		content: none;
	}
	.horizontal_list li { 
		padding-left: 0; 
		text-indent: 0;
	}

.horizontal_line{
	margin: 34px 0 0 30px;
	height: 26px;
	position: relative;	
}
	.line_left,
	.line_right{
		border-top: 1px solid #434247;
		width: 305px;
		margin-top: 13px;
	}
	.line_left{
		float: left;
	}
	.line_right {
		float: right;
	}
	.left_circle, 
	.central_circle, 
	.right_circle {
		background: rgb(69,68,73);
		background: rgba(255,255,255, 0.15);
		position: absolute;
		border-radius: 50px;
	}
	.left_circle, 
	.right_circle {
		width: 13px;
		height: 13px;
		top: 7px;
	}
	.left_circle{
		left: 314px;
	}
	.central_circle{
		width: 26px;
		height: 26px;		
		top: 0px;
		left: 322px;
	}
	.right_circle{
		left: 343px;
	}
	
/* Main tags */

body {
	background: url(data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBw8PDw8PDw8PFQ8PDw8VFRUPFRUPFRUPFRUWFhUVFRUYHSggGBolHRUVITEhJSkrLi4uFx8zODMtNygtLisBCgoKDQ0NFQ8PFS0dHR0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLS0tLf/AABEIALcBEwMBIgACEQEDEQH/xAAWAAEBAQAAAAAAAAAAAAAAAAAAAQf/xAAWEAEBAQAAAAAAAAAAAAAAAAAAEQH/xAAXAQEBAQEAAAAAAAAAAAAAAAAAAQUC/8QAFhEBAQEAAAAAAAAAAAAAAAAAABEh/9oADAMBAAIRAxEAPwDGAVoOABQAUAABQABQAAAAAAAAAAAAAARRBAAAEAAARQQBBQFAFUEUAAUAAAAAAAAVFRQAQAAAAAAEUQQVAAEAAARQAFAFAAUAAAAAAFEABQAFBFQABAAAAAAABEAABUEoAACoooCgAAAAKKAAAAIsAEFAEVABQEAQBUAAAAQQACqiggCAAooAACgqYAogooAAAAAAAIogKCAAIAAAAACCAAKiggCAAoKigAKCoAAAKCgAAAAAAAAACCoAQEAAEVBBUAAFBAEABQVFAAUAAFRQBFUAAAAAAAAAAEBAAAAARUQAAAEARQAAFRVABQAAAABVAEBQAAABAFQAAEAAAEQAAAAAEwBFQBFUAFBUAUBQAAAAAAUFEVBBUAAAAAAAEAQAAAEAAEAQURVAAABRRAFEUABQAAAAAAAAAQAQAAAAABABAUQQABQARQFAAABQAoKIAoigCAKIAogAKgAAAAACAAAgICoAAIoAqAAKAoAAAAAAAAAACiiGAAAlAUUQBAAAABBRBAAf/9k=) repeat;
	margin: 0;
}


h1,h2,h3, h4 {
	font-family: 'Lato', Helvetica, sans-serif;
	font-weight: 300;
	color: #48DA9B;
}
	h1 {
		font-size: 48px;
		font-weight: 300;
		margin: 20px 0;
	}
	h2 {
		font-size: 28px;
		margin: 32px 0 24px;
	}
	h3 {
		font-size: 24px;
	}
	h4 {
		font-size: 18px;
		font-weight: 400;
	}
	.resume.func.skills-prog {
  clear: both;
  background: $darker-blue;
  padding: 15px;
}
.resume.func.skills-prog ul {
  margin-left: 15px;
}
.resume.func.skills-prog ul li {
  margin-bottom: 8px;
  display: flex;
  align-items: center;
  transition-duration: 0.3s;
}
.resume.func.skills-prog ul li:hover {
  color: yellow;
}
.resume.func.skills-prog ul li:hover .skills-bar.bar {
  background: yellow;
  box-shadow: 0 0 0 1px yellow;
}
.resume.func.skills-prog ul li span {
  display: block;
  width: 120px;
}
.resume.func.skills-prog ul li .skills-bar {
  background: white;
  height: 2px;
  width: calc(100% - 120px);
  position: relative;
  border-radius: 2px;
}
.resume.func.skills-prog ul li .skills-bar.bar {
  position: absolute;
  top: -1px;
  height: 4px;
  background: orange;
  box-shadow: 0 0 0 orange;
  border-radius: 5px;
}

blockquote {
	font-style: italic;
	margin: 25px 0;
	padding-left: 30px;
	border-left: 2px solid #48DA9B;
}
	
blockquote, p , a, li ,table{
	font-family: 'Lato', Helvetica, sans-serif;
	font-weight: 300;
	font-size: 30px;
	color: #e4e3e8;
}

a:focus { 
    outline: none;
}

ul {
    list-style: none;
    padding:0;
    margin:0;
}
	li { 
		padding-left: 1em; 
		text-indent: -.7em;
	}
	li:before {
		content: "• ";
		color: #837c9a;
		font-size: 20px;
		padding-right: 8px;
	}

/* Containers size */

#main_container {
	width: 960px;
	margin: 0 auto;
}
	#header {
		height: 130px;
		border-bottom: 1px solid #403F44;
	}
		.header_logotype_container {
			width: 260px;
			height: 130px;
			border-right: 1px solid #403F44;
			float: left;
		}
		.header_menu_container {
			height: 130px;
			width: 699px;
			float: left;
		}
			.header_menu_container a {
				font-family: 'Lato', Helvetica, sans-serif;
			}
	#left_col {
		width: 260px;
		float: left;
	}
	#content_container {
		width: 699px;
		border-left: 1px solid #403F44;
		float: left;
	}
	#footer {
		width: 960px;
		height: 60px;
		border-top: 1px solid #403F44;
		display: inline-block;
	}

/* HEADER */

.logotype_name{
	text-transform: uppercase;
	font-size: 40px;
	margin: 43px 0 0;
}
.logotype_occupation{
	text-transform: uppercase;
	margin-top: 5px;
	color: #5ce2af;
	font-size: 30px;
	letter-spacing: 2px;
	padding-left: 7px;
}

.download_print_buttons {
	width: 225px;
	height: 45px;
	float: right;
}
	.download_print_buttons a {
		text-decoration: none;
		font-size: 18px;
		font-family: 'Lato', Helvetica, sans-serif;
		font-style: italic;
		line-height: 45px;
		padding: 16px 17px;
		background: #353638;
	}
		.download_print_buttons a:hover {
			background: #020609;
		}
		.download_print_buttons .icon {
			color: #02070a;
			padding-right: 6px;
			font-style: normal;
			font-size: 12px;
		}
		.icon-angle-double-right {
			position: relative;
			top: 2px;
		}
			.download_print_buttons a:hover .icon {
				color: #e4e3e8;
			}
			
.header_menu {
	width: 699px;
	margin-top: 40px;
	margin-left: 5px;
}
	.header_menu a{
		text-decoration: none;
		padding: 0 20px;
		border-left: 1px solid #e4e3e8;
		font-size: 20px;
		font-weight: 400;
	}
	.header_menu a.no_border{
		border-left: none;
	}
		.header_menu a:hover {
			color: #837c9a;
		}
		
/* LEFT NAV */

#left_nav h2 {
	margin: 0;
	font-size: 24px;
}

.profile_frame{
	width: 230px;
	height: 260px;
	background: black;
	border: 1px solid #403F44;
	margin-top: 30px;
}
	.profile_picture{
		width: 210px;
		height: 240px;
		margin:10px;
		background-color:no-repeat;
	}

.hello_content,
.contact_details_content {
	margin-top: 25px;
}

.hello_content{
	width: 230px;
}
.contact_details_content h2 + p.purple{
	margin-top: 10px;
}
.contact_details_content p{
	margin: 0;
}
.contact_details_content p.purple{
	margin-top: 25px;
}

.send_message_button,
.special_button {
	margin-top: 25px;
	display: block;
	background: #48DA9B;
	width: 230px;
	height: 50px;
	position: relative;
	z-index: 1;
}
	.cut1:after {
		content: "";
		position: absolute;
		bottom: -19px;
		left: -20px;
		width: 30px;
		height: 30px;
		z-index: 9;
		background: url(https://www.toptal.com/designers/subtlepatterns/patterns/dark_wall.png) repeat;
    transform: rotate(45deg);
	}
	.cut2:before {
	    content: "";
	    position: absolute;
	    top: -19px;
	    right: -20px;
	    width: 30px;
	    height: 30px;
	    z-index: 9;
	    background: url(https://www.toptal.com/designers/subtlepatterns/patterns/dark_wall.png) repeat;
      transform: rotate(45deg);
	}
	.content {
	    text-align: center;		
	    color: #04080b;
	    width: 100%;
	    height: 40px;
	    position: absolute;
	    z-index: 2;
	    font: 18px 'Lato', Arial, sans-serif;
	    margin: 0;
	    padding: 16px 0 0;
        top: -4px;
        bottom: 10px;
	    border-top: 1px solid #403F44;
	    border-bottom: 1px solid #403F44;
	}
	.send_message_button:hover,
	.special_button:hover {
		background: #29C782;
	}

.get_social_content {
	margin-top: 15px;
}
  .get_social_content h2{
    margin-bottom: 8px;
  }
	.social_icons {
		margin-left: -8px;
	}
	.social_icons a {
		font-size: 35px;
		text-decoration: none;
		color: #000507;
		padding: 0;
		padding: 0 5px;
	}
		.social_icons a span.invisible {
			display:none;
		}
		.social_icons .facebook:hover{
			background: #3b5998;
			color: #dfe3ee;
			border-top-right-radius: 50px;
			border-bottom-left-radius: 50px;
		}
		.social_icons .twitter:hover{
			background: #00B0ED;
			color: #fff;
			border-top-left-radius: 50px;
			border-bottom-right-radius: 50px;
		}
		.social_icons .linkedin:hover{
			background: #007bb6;
			color: #fff;
			border-top-right-radius: 50px;
			border-bottom-left-radius: 50px;
		}

.footer_name {
	font-style: italic;
	margin-top: 20px;
}

/* Profile Content */

.profile_quote {
	position: relative;
	/* margin-left: 5px; */
}
	.profile_quote p {
		font-size: 30px;
		width: 455px;
	}
	.profile_quote  .entypo-quote {
		color: #3d3a41;
		font-size: 80px;
    font-style: normal;
		position: absolute;
		top: -20px;
		right: 70px;
		cursor: default;
	}
	.Education_content{
	margin-top:20px;}
	.Education_content{
	width:350px;
	float:left;}
	.Education_content ul{float:left;  padding-bottom:20px;}
	    

.philosophy_content {
	margin-top: 20px;
}
	.philosophy_content p {
		margin: 0;
		width: 370px;
		float: left;
	}
	.philosophy_content ul {
		float: left;
		padding-left: 40px;
	}</style>
<link href='https://fonts.googleapis.com/css?family=Lato:300,300italic,400,400italic' rel='stylesheet' type='text/css'>
</head><body>
<!-- MAIN CONTAINER -->
		<div id="main_container">
      <!-- HEADER -->
      <div id="header">
        <!-- LOGOTYPE/NAME -->
        <div class="header_logotype_container">
          <h1 class="logotype_name">AREEBA<span class="purple">SHAHBAZ</span></h1>
          <h2 class="logotype_occupation">BEGINNER Web Developer</h2>
        </div>
        <!-- MAIN MENU -->
        <div class="header_menu_container">
          <ul class="download_print_buttons horizontal_list">
            <li><a href="#"><span class="icon entypo-download"></span>Download CV</a></li>
            <li><a href="#"><span class="icon entypo-print"></span>Print CV</a></li>
          </ul>
          <div class="clear"></div>
          <ul class="header_menu horizontal_list">
            <li><a class="no_border purple" href="#">Profile</a></li>
            <li><a href="#">Education</a></li>
            <li><a href="#">Skills</a></li>
            <li><a href="#">Work Experience</a></li>
            <li><a href="#">Featured Projects</a></li>
          </ul>
        </div>
      </div><br><br><br><br><br><br><br><br><br>
	  <div class="horizontal_line">
          <div class="line_left"></div>
          <div class="left_circle"></div>
          <div class="central_circle"></div>
          <div class="right_circle"></div>
          <div class="line_right"></div>
        </div>
		<div class="first.block">
		<h2>EDUCATION</h2>
		<p> My academic life shows my hard work and dedication towards my future.</p>
		<div class=Education_content>
		<p>Education in a persons life is very important. It helps a person achieve goals and understand his/her interests.
		The detail of my academic life is as follows:</p>
		<h3>MATRIC</h3>
		<p>I did my matric with A+ grades in 2019 with following subjects:</p>
		<ul>
		<li>Computer Science</li>
		<li>Mathematics</li>
		<li>Physics</li>
		<li>chemistry</li>
		<ul>
		<h3>INTERMEDIATE</h3>
		<p>I did my Intermediate with A+ grades in 2021 with following subjects:
		<ul>
		<li>Computer science</li>
		<li>Mathematics</li>
		<li>Statistics</li>
		<ul>
		<h3>BACHELORS</h3>
		<p>I am doing my Bachelors in INFORMATION TECHNOLOGY.<p>
		<div class="clear"></div>
		</div>
		</div>
		
      <!-- LEFT COL -->
      <div id="left_col">
        <div class="profile_frame">
		    <img src="me.jpeg" alt="profile picture" height="100%"width="100%">
          <div class="profile_picture"></div>

        </div>
        
		
		<div class="hello_content">
          <h2>Hello!</h2>
          <p>I am a19 years old Student and passionate about programming and web developing.I am hardworking and a fast-learner.</p>
        </div>
        <div class="contact_details_content">
          <h2>Contact details</h2>
          <p class="purple">Phone:</p>
        <a href="tel:+927434136">  <p>+92 324 7434136</p></a>
          <p class="purple">Email:</p>
       <address> <a href="mailto:lizareeba@gmail.com"><p>lizareeba@gmail.com</p></a></address>
          <p class="purple">Adress:</p>
          <p>Someplace, 5</p>
          <p>Sargodha,Pakistan</p>
          <p>23001</p>
        </div>
        <a href="mailto:jlalovi@gmail.com" class="send_message_button">
          <span class="cut1"></span>
          <span class="cut2"></span>
          <span class="content">Send me a message <span class="fontawesome-double-angle-right"></span></span>
        </a>
        <div class="get_social_content">
          <h2>Get social</h2>
          <ul>
            <li><a class="facebook" style="color:springgreen" font="size:13px"href="https://www.facebook.com"><span class="entypo-facebook-circled"></span>Facebook</span></a></li>
            <li><a class="twitter" style="color:springgreen" href="https://twitter.com"><span class="entypo-twitter-circled"></span>Twitter</span></a></li>
            <li><a class="linkedin" style="color:springgreen" href="https://www.linkedin.com"><span class="entypo-linkedin-circled"></span>LinkedIn</span></a></li>
          </ul>
        </div>
      </div>
      <!-- PROFILE CONTENT -->
      <div id="content_container">				
        <div class="block">
          <h1>Profile</h1>
          <blockquote class="profile_quote">
            <p font-size:20px>"I am a student in  <abbr title="UNIVERSITY OF SARGODHA">UOS</abbr> and I am doing my bachelors in <abbr title="INFORMATION TECHNOLOGY">IT</a>. I am very much interested in pursuing my career in this field. And i can prove my worth through my Hardwork and Skill.And being a part of such a prestigious comapnay would help me increase my quality and skill and I would like to be part of such Organization which is looking for true skills and would like to contribute my hardwork and efforts to its progress."</p>
 
            <span class="entypo-quote"></span>
          </blockquote>
        </div>
        <div class="block">
          <h2>A few words about me</h2>
          <p>Until now, in my life, I change from active moments with a lot of variety, challenges and improvisations, to moments of tranquility and stability, being difficult to stay in a place during a long time. I consider myself a tolerant and respectful person with open mind and quite honest. I really like to listen people stories and backgrounds and their different experiences around the world.As expriences can teach us lessons that no other thing can. I like to learn new things which evolve my personality nd it also helps to broaden one's perspective of life and world.</p>				
        </div>
        <div class="horizontal_line">
          <div class="line_left"></div>
          <div class="left_circle"></div>
          <div class="central_circle"></div>
          <div class="right_circle"></div>
          <div class="line_right"></div>
        </div>
        <div class="block">
          <h2>Philosophy</h2>
          <p>I belive in ethic and moral not in imposed rules that you "have to" do or follow.</p>
          <div class="philosophy_content">
            <p>I believe life is made from different shades of grey, not from black and white. Furthermore, as a human being with rationality, I think it is our duty to take care of the world and treat others as one would like others to treat oneself. This way of perceiving reality affects my beliefs and my way of behaving. Summarizing on several points:</p>
            <ul>
              <li>Pragmatic</li>
              <li>Honest</li>
              <li>Respectful</li>
              <li>Open-minded</li>
              <li>Coherent</li>
			  <li>Hard Working
			  <li>Fast-learner</li>
            </ul>
            <div class="clear"></div>
          </div>
        </div>
		<div class="horizontal_line">
          <div class="line_left"></div>
          <div class="left_circle"></div>
          <div class="central_circle"></div>
          <div class="right_circle"></div>
          <div class="line_right"></div>
        </div>
		<div class=" block">
      
      <h2>Programming Skills</h2>
	  
    <ul>
	<li style="font-size:30px"
		>
		<span>HTML5</span>

        </li></td>
		
		<li style="font-size:30px"
		>
		<span>C++ </span>

        </li>
        <li style="font-size:30px"
		><span>JavaScript</span>
          <div class="skills-bar">
            <div class="bar"></div>
          </div>
        </li>
        <li style="font-size:30px"
		><span>MySQL</span>
          <div class="skills-bar">
            <div class="bar"></div>
          </div>
        </li>
      </ul> </table>
    </div>
	<div class="clear"></div>
	<div class="horizontal_line">
          <div class="line_left"></div>
          <div class="left_circle"></div>
          <div class="central_circle"></div>
          <div class="right_circle"></div>
          <div class="line_right"></div>
        </div>
		<div class=" block">
	<table cellspacing=3 cellpadding=5 border=3 style=font-size:25px font=color:white;><legend><h2>ABILITIES(THINGS I AM  GOOD IN)</h2>  <legend>
  <tr><th>SKILLS</th></font>
	<th>QUALITY</th></tr>
	<tr><td>MS WORD</td>
	<td>EXCEPTIONAL</td></tr>
	<tr><td>MS EXCEL</td>
	<td>EXCEPTIONAL</td></tr>
	<tr><td>MS ACCESS</td>
	<td>EXCEPTIONAL</td></tr>
	<tr><td>MS POWERPOINT</td>
	<td>EXCEPTIONAL</td></tr>
	<tr><td>PHOTOSHOP</td>
	<td>GREAT</td>
	</tr>
	

	</table>
	<div class="clear"></div> </div>
        <div class="horizontal_line">
          <div class="line_left"></div>
          <div class="left_circle"></div>
          <div class="central_circle"></div>
          <div class="right_circle"></div>
          <div class="line_right"></div>
        </div>
        <div class="last block">
          <h2>Interests & Hobbies</h2>
          <p>I'm passionate about technology and learning new things about this world, both determine almost all my interests and hobbies:</p>
          <ul>
            <li>Visiting new places</li>
            <li>Meeting people</li>
            <li>Having new experiences</li>
            <li>Hiking and Biking</li>
            <li>Web Developing</li>
            <li>Manga and Anime</li>
			<li>Book reading</li>
			<li>Programming</li>
			<li>Learning about different Cultures</li>
			<li>Music</li>
        </div>
      </div>
	  <div class="clear"></div>
	  
	
      <!-- FOOTER -->
      <div id="footer">
        <p class="footer_name">Areeba Shahbaz CV 2022</p>
      </div>
		</div>
