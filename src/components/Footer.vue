<template>
  <footer>
			<div class="container-fluid">
				<div class="row">
					<div class="col-12 col-sm-6 offset-sm-3 col-md-8 offset-md-2 col-lg-5 offset-lg-0">
						<div id="time">
						</div>
					</div>
					<div class="col-12 col-lg-7" id="ftcontact">
						<div class="row">
							<div class="col-12 col-sm-6">
								<div id="email">
									<i class="icon-mail"></i><span id="email-footer">kostkahubert@gmail.com</span>
								</div>
							</div>
							<div class="col-12 col-sm-6">
								<div id="phone">
									<i class="icon-call"></i> 884 675 003
								</div>
							</div>
						</div>
					</div>
				</div>

				<div class="row">
					<div class="col-12" id="copyright">
						<i class="icon-copyright">2019 Piotr Zięcina Wszelkie prawa zastrzeżone</i>
					</div>
				</div>
			</div>
</footer>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>
#subscript {
	width: 100%;
	height: 60px;
	background-color: blue;
}

#time {
	font-size: 100%;
	text-align: center;
	margin: auto 0px;
	color: gray;
}

#ftcontact {
	margin: auto 0;
}

#email {
	padding: 0px;
	text-align: center;
	color: gray;
	font-size: 20px;
}

#email-footer {
	padding-left: 10px;
}

#phone {
	text-align: center;
	color: grey;
	font-size: 20px;
	margin: auto 0;
}

#copyright {
	font-size: 10px;
	text-align: right;
}
</style>
