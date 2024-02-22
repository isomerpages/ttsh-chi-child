---
title: Accordion Guide
permalink: /permalink/
description: ""
---
<!--REQUIRED CODE must copy for accordion to work. the "design of the accordion box and content is in this code as well. if wanna edit/change the accordion design can use this website https://www.w3schools.com/w3css/w3css_accordions.asp./\-->
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
  content: url("/images/chevron-down.svg");
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
  content: url("/images/chevron-up.svg");
  transform: translateY(-50%) rotateZ(180deg);
}

input + label + .accordion-content {
  display: none;
}

input:checked + label + .accordion-content {
  display: block;
}

</style>
<!--END OF REQUIRED CODE.\-->


<!--ENTIRE ACCORDION CODE-->

<div class="container">
<!--ONE BOX. Must match the <label> code with the id code -->
<div>
	<input id="title1" type="checkbox"><label for="title1">	Healthcare Management Associate Programme (HMAP)   </label>
	<div class="accordion-content">
	<div class="para">HMAP started in 2009, aimed at grooming graduates with outstanding leadership qualities for a challenging and fulfilling career ahead in the National Healthcare Group (NHG). HMAP represents a collaborative effort with other healthcare institutions within the NHG, cultivating the growth of a collective programme to expand the range of learning and network building opportunities. 
</div>
</div>
<!--ONE BOX END-->
<!--2ND BOX-->
<input id="title2" type="checkbox"><label for="title2">Management Executive Programme (MEP) </label>
	<div class="accordion-content">
	<div class="para">MEP started in 2012, aimed at building capabilities of high performing executives to take on managerial roles.  
</div>
</div>
<!--2ND BOX END-->
<!--3RD BOX-->
<input id="title3" type="checkbox"><label for="title3">Management Fellowship Programme (MFP)</label>
	<div class="accordion-content">
	<div class="para">MFP started in 2009, aimed to develop and nurture high performing managers and clinicians to take on future healthcare leadership roles.  
</div>
	</div>
<!--3RD BOX END-->
</div>
<!--ACCORDION END--></div>