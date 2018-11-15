---

layout: page
title: "Thank You!" 
permalink: "thanks"
icon: mail-box.png

---

<p> <!--Thank you for getting in touch<span id="userName"></span>! <br>-->Your message has been sent, and we will reply You soon.</p>

<script> 

$(document).ready(function(){
	var userName = window.location.hash.substr(1);
	userName = userName.replace('--', ' ');
	console.log(userName);

	/*$('#userName').html( ', '+userName );*/
	$('.page-header__title > h1').html( 'Thank You, '+userName +'!');
})

</script> 