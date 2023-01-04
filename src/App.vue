<template>
	<div class="content">
		<img src="./assets/frog.png" alt="froggy" class="background-image">
		<div class="left"/>																
		<div class="center">
			<img class="image" src="./assets/kek.jpg">
			<div class="image-shadow"/>
			<div class="info">
				<div class="name">
					[ALDIYAR AMIROV]
				</div>
				<div class="position">
					[golang dev.]
				</div>
			</div>
			<div class="links">
				<a class="link" href="https://github.com/AmirovAldiyar">
					{github}
				</a>
				<a class="link" href="https://t.me/AmirovAldiyar">
					{telegram}
				</a>
				<a class="link" href="https://www.linkedin.com/in/aldiyar-amirov-b04037197/">
					{linked.in}
				</a>
				<a class="link" href="https://www.instagram.com/aldeeyar/">
					{instagram}
				</a>
				<a class="link" href="mailto:amirovaldiar@gmail.com">
					{e-mail}
				</a>
			</div>
		</div>
		<div class="right"/>																
	</div>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Courier+Prime&display=swap');
body {
	font-family: 'Courier Prime', monospace;
}
.content {
	font-size: 24px;
	width: 360px;
	height: 450px;
	display: flex;
	flex-direction: row;
	position: absolute;
	left: 50%;
	top: 50%;
	transform: translate(-50%, -50%);
}
.left {
	width: 30px;
	height: 450px;
	border-bottom: 4px solid black;
	border-left: 4px solid black;
	border-top: 4px solid black;
}
.right {
	width: 30px;
	height: 450px;
	border-bottom: 4px solid black;
	border-right: 4px solid black;
	border-top: 4px solid black;
}
.center {
	width: 390px;
	height: 450px;
	display: flex;
	flex-direction: column;
}
.info {
	display: flex;
	flex-direction: column;
	align-items: center;
	gap: 8px;
}
.links {
	display: flex;
	flex-direction: column;
	align-items: center;
	gap: 12px;
	margin-top: 28px;
}
.link {
	text-decoration: none;
	color: black;
}
.image {
	width: 113px;
	height: 113px;
	border-radius: 50%;
	margin: 18px auto;
}
.image-shadow {
	position: absolute;
	top: 18px;
	left: 50%;
	transform: translate(-50%, 0);
	border-radius: 50%;
	width: 113px;
	height: 113px;
	box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.5) inset;
}
.background-image {
	position: absolute;
	bottom: -10px;
	right: 0;
	height: 100px;
	width: 100px;
}
body {
	margin: 0;
}
#app {
	min-height: 100vh;
}
</style>
