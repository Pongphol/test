<template>
	<div id="footer">
		<div class="Est-orci-lobortis">Est orci lobortis</div>
	</div>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style scoped>
#footer {
	position: relative;
	width: 100%;
	height: 50px;
	background-color: #333333;
}
.Est-orci-lobortis {
	margin-left: 80px;
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	width: 100%;
	font-family: Roboto;
	font-size: 14px;
	font-weight: normal;
	font-stretch: normal;
	font-style: normal;
	line-height: 1.36;
	letter-spacing: normal;
	text-align: left;
	color: #ffffff;
}
</style>