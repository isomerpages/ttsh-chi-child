---
title: FAQs
permalink: /about-child/faqs/
description: ""
---
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

<div class="container">


<div>
	<input id="title1" type="checkbox"><label for="title1">Hosting of 3rd Party Content</label>
	<div class="accordion-content">
	<div class="para">CHI/ CHILD provides a platform and merely **hosts content** submitted by Content Providers, allowing users of CHILD to tap on the knowledge and insights of the wider healthcare community.
		
</div>
	</div>
	<input id="title2" type="checkbox"><label for="title2">Submissions</label>
	<div class="accordion-content">
	<div class="para">All content hosted on this site are voluntary submissions by content providers. By submitting content to CHI, the content provider acknowledges that it does not contain any sensitive or confidential information such as patients details, detailed financial data and etc.; and that the submitter has ensured his/ her Institution has deemed it suitable for public visibility.&nbsp;
</div>
	</div>
	<input id="title3" type="checkbox"><label for="title3">Accessibility</label>
	<div class="accordion-content">
	<div class="para">The content provider grants CHI and users of CHILD a non-exclusive, transferable, worldwide license to: access, view and modify the content; store the content and any modified content; share and distribute the content.
</div>
	</div>
<input id="title4" type="checkbox"><label for="title4">Removal of Rights</label>
	<div class="accordion-content">
	<div class="para">CHI reserves the right to remove any content without prior notice if properly notified that the content infringes on another Party's Intellectual Property (IP) rights.
</div></div>
<div>
	<input id="title5" type="checkbox"><label for="title5">Intellectual Property</label>
	<div class="accordion-content">
	<div class="para">All IP matters arising from the projects shared on CHILD are the properties of the respective Institutions. CHI is not responsible for any IP that may arise from collaborations borne out of CHILD. Any further IP arising from collaborations between the Institutions or its employees or any other person shall be managed by the respective parties.
</div>
	</div>
<div>
	<input id="title6" type="checkbox"><label for="title6">Citation</label>
	<div class="accordion-content">
	<div class="para">Should you use any of the content shared on this site, please credit or cite source of content, such that due acknowledgement of effort can be given to the content owner/ institution.
</div>
	</div>

</div></div>



</div></div>