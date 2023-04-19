<template>
	<div class="wrapper">
		<div class="resume_design">
			<div class="resume_left">
				<div class="about_sec">
					<div class="button">About Me</div>
					<p>I am Rymbrent Maximillian L, Rabano a student at Holy Angel University currently 21.
            A gamer with a experience of 10 years of being a gamer. but also has a simple exprience in 
            in webdesign. Can also do some back end codes. but my prefer work is being a fornt end and a designer.

          </p>
				</div>
				<div class="exp_sec">
					<div class="button">Objective</div>
					<ul>
						<li>
							<div class="item">
								<p class="content">My objective is to be graduate in collage and be come a fulltime webdesigner.
                  and to be a one of the best webdesigner in the country. and create my own company and also create my own 
                  websites. 
                </p>
							</div>
						</li>
					</ul>
				</div>
				<div class="edu_sec">
					<div class="button">Specialization</div>
					<ul>
						<li>
							<div class="item">
                <p class="content">GAMER</p>
                  <p class="content">DESIGNER</p>
                  <p class="content">STREAMER</p>
                  <p class="content">EDITOR</p>
              </div>
						</li>
					</ul>
				</div>
        <div class="exp_sec">
					<div class="button">Education</div>
					<ul>
						<li>
							<div class="item">
								<div class="item_grp">
									<p class="title">2006-2014 graduate at Cabelitcan Elementary School</p>
                </div>
							</div>
						</li>
            <li>
							<div class="item">
								<div class="item_grp">
									<p class="title">2015-2018 School from grade 7 to 9 at Madapdap High school</p>
								</div>
							</div>
						</li>
            <li>
							<div class="item">
								<div class="item_grp">
									<p class="title">2019-2023 School at Holy Angel University</p>
								</div>
							</div>
						</li>
					</ul>
				</div>
			</div>
			<div class="resume_right">
				<div class="profile_sec">
					<div class="img_holder">
						<img src="rymbrent.jpg" alt="profile image">
					</div>
					<div class="profile_info">
						<p class="first_name">RYMBRENT MAXIMILLIAN L</p>
						<p class="last_name">RABANO</p>
						<p class="role">WEB DESIGNER</p>
					</div>
				</div>
				<div class="contact_sec">
					<div class="button">Contact US</div>
					<ul>
						<li class="item">
							<div class="icon">
								<i class="fas fa-phone"></i>
							</div>
							<div class="content">
								<p class="title">Phone</p>
								<p class="subtitle">+63 09685800111</p>
							</div>
						</li>
						<li class="item">
							<div class="icon">
								<i class="fas fa-envelope"></i>
							</div>
							<div class="content">
								<p class="title">Email</p>
								<p class="subtitle">rymbrent03@gmail.com</p>
							</div>
						</li>
						<li class="item">
							<div class="icon">
								<i class="fas fa-map-signs"></i>
							</div>
							<div class="content">
								<p class="title">Address</p>
								<p class="subtitle">12th cross, Townhall, NY, USA</p>
							</div>
						</li>
					</ul>
				</div>
				<div class="skills_sec">
					<div class="button">Skills</div>
					<ul>
						<li class="item">
							<div class="content">HTML/CSS</div>
							<div class="bar_wrap">
								<p class="bar" style="width: 100%"></p>
							</div>
						</li>
						<li class="item">
							<div class="content">Javascript</div>
							<div class="bar_wrap">
								<p class="bar" style="width: 70%"></p>
							</div>
						</li>
						<li class="item">
							<div class="content">PHP</div>
							<div class="bar_wrap">
								<p class="bar" style="width: 50%"></p>
							</div>
						</li>
						<li class="item">
							<div class="content">SQL</div>
							<div class="bar_wrap">
								<p class="bar" style="width: 80%"></p>
							</div>
						</li>
						<li class="item">
							<div class="content">Github</div>
							<div class="bar_wrap">
								<p class="bar" style="width: 100%"></p>
							</div>
						</li>
					</ul>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@100;300;400;900&display=swap');

:root{
   --bgcolor: #f4f4f4;
   --resume-left-bgc: #fff;
   --resume-right-bgc: #232941;
   --green: #0ea73a;
   --white: #fff;
   --primary: #232941;
}

*{
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	font-family: 'Lato', sans-serif;
	list-style: none;
	text-decoration: none;
}

body{
	background: var(--bgcolor);
	font-size: 14px;
	color: var(--primary);
}

.wrapper{
	display: flex;
	align-items: center;
	justify-content: center;
	padding: 20px;
}

.resume_design{
	width: 700px;
	max-width: 100%;
	display: flex;
	box-shadow: 0 0 2px rgba(0,0,0,0.2);
}

.resume_design .resume_left{
	background: var(--resume-left-bgc);
	width: 400px;
	padding: 30px;
}

.resume_design .resume_right{	
	background: var(--resume-right-bgc);
	color: var(--white);
	width: 300px;
}

.resume_design .resume_left > div{
	margin-bottom: 30px;
}

.resume_design .resume_left > div:last-child{
	margin-bottom: 0;
}

.resume_design .resume_left .button{
	margin-bottom: 10px;
	text-transform: uppercase;
	border: 2px solid var(--green);
	color: var(--green);
	display: inline-block;
	padding: 5px 10px;
	border-radius: 20px;
	font-weight: 900;
	letter-spacing: 2px;
	font-size: 12px;
}

.resume_design .resume_left .about_sec p{
	margin-bottom: 10px;
}

.resume_design .resume_left .about_sec p:last-child{
	margin-bottom: 0;
}

.resume_design .resume_left ul li{
	padding-left: 20px;
	padding-bottom: 20px;
	position: relative;
}

.resume_design .resume_left ul li:last-child{
	padding-bottom: 0;
}

.resume_design .resume_left ul li{
	border-left: 1px solid var(--green);
}

.resume_design .resume_left ul li:before{
	content: "";
	position: absolute;
	top: 0;
	left: -5px;
	width: 8px;
	height: 8px;
	background: var(--green);
	border-radius: 50%;
}

.resume_design .resume_left ul li .title{
	font-weight: 900;
	font-size: 16px;
}

.resume_design .resume_left ul li .sub_title{
	margin: 3px 0;
}

.resume_design .resume_left ul li .content{
	font-weight: 300;
}

.resume_design .resume_left ul li .item_grp{
	position: relative;
}

.resume_design .resume_left ul li .item_grp .timeline{
	position: absolute;
	top: 0;
	right: 0;
	font-size: 10px;
	color: var(--green);
	font-weight: 900;
}

.resume_design .resume_right .profile_sec,
.resume_design .resume_right .contact_sec,
.resume_design .resume_right .skills_sec{
	padding: 30px;
}

.resume_design .resume_right .profile_sec img{
	width: 125px;
}

.resume_design .resume_right .profile_sec .profile_info{
	margin-top: 20px;
}

.resume_design .resume_right .profile_sec .profile_info .first_name,
.resume_design .resume_right .profile_sec .profile_info .last_name{
	font-size: 26px;
	text-transform: uppercase;
	font-weight: 300;
}

.resume_design .resume_right .profile_sec .profile_info .last_name{
	font-weight: 900;
}

.resume_design .resume_right .profile_sec .profile_info .role{
	margin-top: 10px;
	text-transform: uppercase;
	font-size: 12px;
	letter-spacing: 2px;
}

.resume_design .resume_right .contact_sec,
.resume_design .resume_right .skills_sec{
	position: relative;
}

.resume_design .resume_right .contact_sec{
	background: var(--green);
}

.resume_design .resume_right .button{
	text-transform: uppercase;
	background: var(--white);
	color: var(--primary);
	display: inline-block;
	padding: 5px 10px;
	border-radius: 20px;
	font-weight: 900;
	letter-spacing: 2px;
	font-size: 12px;
	position: absolute;
	top: -13px;
	left: 50%;
	transform: translateX(-50%);
}

.resume_design .resume_right .contact_sec ul li{
	display: flex;
	align-items: center;
	margin-bottom: 10px;
}

.resume_design .resume_right .contact_sec ul li:last-child{
	margin-bottom: 0;
}

.resume_design .resume_right .contact_sec ul li .icon{
	margin-right: 10px;
}

.resume_design .resume_right .contact_sec ul li .content .title{
	margin-bottom: 3px;
	font-weight: 900;
}

.resume_design .resume_right .skills_sec ul li{
	display: flex;
	align-items: center;
	margin-bottom: 10px;
}

.resume_design .resume_right .skills_sec ul li:last-child{
	margin-bottom: 0;
}

.resume_design .resume_right .skills_sec ul li .content{
	width: 100px;
}

.resume_design .resume_right .skills_sec ul li .bar_wrap{
	width: calc(100% - 100px);
	height: 10px;
	border-radius: 20px;
	position: relative;
	overflow: hidden;
}

.resume_design .resume_right .skills_sec ul li .bar_wrap .bar{
	position: absolute;
	top: 0;
	left: 0;
	height: 100%;
	background: var(--white);
}

</style>
