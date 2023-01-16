<template>
	<div class="resources">

		<div class="digital-divide">
			<div class="head">Digital divide definition:</div>
			<div class="head-1">“To alleviate the digital divide - we collect used devices, fix them up, and give them
				to
				those in need!
				If you or someone you know is in need of a laptop, desktop, printer, or any other technology, please
				fill out the form below.” </div>
			<a class="button"
				href="https://docs.google.com/forms/d/e/1FAIpQLSeoitlT7tDgHHum4dsxym_qUBThFTuL9hTE-WyVtN1t-NfRAw/viewform ">Apply
				Here!</a>

		</div>

		<div class="about-coding">
			<div class="head">About Coding and Computer Science: </div>

			<iframe class="video" src="https://www.youtube.com/embed/jIsqG8qOD4g" title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
				allowfullscreen></iframe>
			<br>
			<iframe class="video" src="https://www.youtube.com/embed/Nc31NAujTkA" title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
				allowfullscreen></iframe>
			<br>
			<iframe class="video" src="https://www.youtube.com/embed/-xFJM3QQ3TE" title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
				allowfullscreen></iframe>

			<div class="head">Inspiration:</div>

			<iframe class="video" src="https://www.youtube.com/embed/7u-AAlD5SIQ " title="YouTube video player"
				frameborder="0"
				allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
				allowfullscreen></iframe>

		</div>

		<div class="why-cs">
			<div class="head">Why Choose Computer Science?</div>
			<img id="image" src="../assets/cs1.jpg" alt="">
			<img id="image" src="../assets/cs2.jpg" alt="">
			<img id="image" src="../assets/cs3.jpg" alt="">
			<img id="image" src="../assets/cs4.jpg" alt="">
			<img id="image" src="../assets/cs5.jpg" alt="">
		</div>

	</div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
* {
	font-family: 'Montserrat', sans-serif;
}

.head {
	margin-bottom: 20px;
	padding: 20px;
	background: #ffd23f;
	color: #540d6e;
	border-radius: 15px;
	font-size: 20px;
}

.head-1 {
	margin-bottom: 20px;
	padding: 20px;
	background: #0ead69;
	color: green;
	border-radius: 15px;
	font-size: 18px;
}

.resources {
	background: #bde0fe;
	display: flex;
	flex-direction: column;
	justify-content: center;
}

.digital-divide {
	background: #bde0fe;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	margin: 20px;
	padding: 20px;
	background: #ffd23f;
	border-radius: 15px;
}

.about-coding {
	background: #bde0fe;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	margin: 20px;
	padding: 20px;
	background: #ffd23f;
	border-radius: 15px;

}

.video {
	width: 90%;
	height: 600px;
	margin: 10px 20px;
	border-radius: 15px;
}

.why-cs {
	background: #bde0fe;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	margin: 20px;
	padding: 20px;
	background: #ffd23f;
	border-radius: 15px;
}

#image {
	max-width: 100%;
	height: auto;
}

.button {
	margin: 20px;
	padding: 5px 15px;
	text-align: center;
	text-decoration: none;
	transition: 0.5s;
	background-size: 200% auto;
	color: white;
	border-radius: 30px;
	display: block;
	border: 1px solid red;
	font-weight: 700;
	font-size: 25px;
	box-shadow: 0px 0px 14px -7px green;
	background-image: linear-gradient(45deg, #ee4266 0%, rgb(240, 157, 94) 51%, #ee4266 100%);
	cursor: pointer;
	user-select: none;
	-webkit-user-select: none;
	touch-action: manipulation;

}

.button:hover {
	margin-top: 20px;
	font-weight: 700;
	background-position: right center;
	color: white;
	font-size: 30px;
	text-decoration: none;
}

@media screen and (max-width:1024px) {
	.video {
		width: 95%;
		height: 400px;
	}
}

@media screen and (max-width:700px) {
	.video {
		width: 100%;
		height: 200px;
	}
}
</style>