---
title: Accordion Guide
permalink: /permalink/
description: ""
---
**./REQUIRED CODE./**
<style>
.button {
  background-color: white;
  cursor: pointer;
  padding: 5px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 20px;
  transition: 0.4s;
}

.panel {
  padding: 0 18px;
  display: none;
  background-color: white;
  overflow: hidden;
}

img {
  width: 150px;
  height: 180px;
}

.active,
.button:hover {
  background-color: white;
}

input {
  display: none;
}

label {
  position: relative;
  display: block;
  padding: 8px 22px;
  margin: 0 0 5px 0;
  cursor: pointer;
  background: #F0F4F6;
  border-radius: 3px;
  width: 100%;
  color: #484848;
  transition: height 0.4s;
  font-size: 1.5em;
}

label:hover {
  background: #BD2D37;
  color: #FFF;
}

.accordion-content {
  padding: 10px 0px 30px 30px;
  margin: 0 0 1px 0;
  border-radius: 3px;
	font-size: 1.25em;
	line-height: 2.2rem;
}

input + label::before {
  content: url("https://d33wubrfki0l68.cloudfront.net/2726d99e678e7823e23532634fdd6e83dfe96a99/c39dd/images/chevron-down.svg");
  font-weight: 400;
  font-size: 1.25em;
  line-height: 1.1rem;
  padding: 0;
  position: absolute;
  right: 0.5rem;
  top: 50%;
  transform: translateY(-50%);
  transition: transform 0.4s ease-in-out;
}

input:checked + label::before {
  content: url("https://d33wubrfki0l68.cloudfront.net/7468164d2fc2ad4fdea648e6cf2de622c2f70892/1819b/images/chevron-up.svg");
  transform: translateY(-50%) rotateZ(180deg);
}

input + label + .accordion-content {
  display: none;
}

input:checked + label + .accordion-content {
  display: block;
}

</style>
**./END OF REQUIRED CODE./**


&gt;ENTIRE ACCORDION CODE&lt;

<div class="container">
&gt;ONE BOX&lt;
<div>
	<input id="title1" type="checkbox"><label for="title1">	Healthcare Management Associate Programme (HMAP)   </label>
	<div class="accordion-content">
	<div class="para">HMAP started in 2009, aimed at grooming graduates with outstanding leadership qualities for a challenging and fulfilling career ahead in the National Healthcare Group (NHG). HMAP represents a collaborative effort with other healthcare institutions within the NHG, cultivating the growth of a collective programme to expand the range of learning and network building opportunities. 
</div>
	</div>
&gt;ONE BOX END&lt;
	<input id="title2" type="checkbox"><label for="title2">Management Executive Programme (MEP) </label>
	<div class="accordion-content">
	<div class="para">MEP started in 2012, aimed at building capabilities of high performing executives to take on managerial roles.  
</div>
	</div>
		</div>
	<input id="title3" type="checkbox"><label for="title3">Management Fellowship Programme (MFP)</label>
	<div class="accordion-content">
	<div class="para">MFP started in 2009, aimed to develop and nurture high performing managers and clinicians to take on future healthcare leadership roles.  
</div>
	</div>

</div>