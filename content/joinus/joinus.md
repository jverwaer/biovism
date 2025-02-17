---
widget: blank
headless: false

# ... Put Your Section Options Here (title etc.) ...
title: 
subtitle:
weight: 10  # section position on page
design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'
---

<style>
.content {
  display: flex;
  align-items: center;
}

.contact {
	display: grid;
    grid-auto-flow: row;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(2, 1fr);
	width: 1500px;
	align-items: center;
	align-content: center;
	justify-content: center;
	place-items: center;
	grid-gap: 30px;
}

.title {
   margin: 20px 0;
}

.titleContact {
   margin-top: 50px;
   margin-bottom: 25px;

}
   
.content img {
  margin-right: 10px;
  display: block;
}

.content h3,
.content p {margin: 0;}

h3 {
  font-size: 20px;
}

body {
	margin-top: 50px;
}

p {
  font-size: 16px;
}

.site-footer {
	position: absolute; 
	margin-top: -45px;
	left: 50%;
	transform: translateX(-50%); 
}


</style>

<div class="title"><h2><strong>Prospective Students</strong></h2></div>
<div class='students'>
	<div class='phd'>
		<div class="title">
			<h3><strong>PhD students</strong></h3>
		</div>
		<div class="content">
			<img src="phd.png" style="height: 100px; width:100px;">
			<div class="text">
				<p> Interested in joining the team as a PhD student? Check the following vacancies:
				 <ul>
				   <li>We have a PhD Position on Hybrid water quality forecasting using sensor data and mechanistic models. If you hold a master degree with in (bio-)engineering, computer science and are interested developing new water quality forecasting models, hybrid modeling and working with live sensor-data, then have a look at  <a href="https://jobs.vito.be/o/phd-position-hybrid-water-quality-forecasting-using-sensor-data-and-mechanistic-models">this vacancy</a>! </li>
				   <li>Interested in a PhD position that focuses on the mathematical aspects of computer vision, feel free to send a letter of motivation, CV and a recent publication (such as for instance your masterthesis) to <a href = "mailto: jan.verwaeren@ugent.be">jan.verwaeren@ugent.be</a>  </li>
				 </ul> 
			    </p>
			</div>
		</div>
	</div>
	<div class='graduate'>
		<div class="title">
			<h3><strong>Bachelor students | Master students </strong></h3>
		</div>
		<div class="content">
			<img src="grad.png" style="height: 100px; width:100px;">
			<div class="text">
				<p>Thank you for your interest in participating in our research. Master and bachelor thesis topics can be found at <a href="https://www.ugent.be/bw/nl/voor-studenten#Curriculumsamenstellen"> here </a>. </p>
			</div>
		</div>
	</div>
</div>


<!-- Contact Information -->

<div class="titleContact"><h2><strong>Contact Information</strong></h2></div>

<div class="contact">
	<div><img src="address.png" style="height: 100px; width:100px;"></div>
	<div><img src="phone.png" style="height: 100px; width:100px;"></div>
	<div><img src="email.png" style="height: 100px; width:100px;"></div>
	<div><a href="https://goo.gl/maps/i8HWBFsRyHHMwRN4A">Campus Coupure, Block A 1st floor 110.079, Coupure links 653, B-9000 Ghent, Belgium</a></div>
	<div><a href="tel:+32 9 264 59 33">+32 9 264 59 33</a> </div>
	<div><a href="mailto:Jan.Verwaeren@UGent.edu">Jan.Verwaeren@UGent.edu</a></div>
</div>
