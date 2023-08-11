
<!doctype html>
<html>

	<head>
		<meta charset="utf-8">
		<title>DOHAO | HOME</title>
		<style type="text/css">
			/* CSS Document */
			* {
				margin: 0;
				padding: 0;
			}

			a {
				text-decoration: none;
			}

			.clearfix:after {
				content: "";
				display: block;
				height: 0;
				visibility: hidden;
				clear: both;
			}

			.clearfix {
				*zoom: 1;
			}

			body {
				background: url(https://source.unsplash.com/random) no-repeat;
				background-size: cover;
				background-attachment: fixed;
			}

			.content {
				width: 900px;
				height: 500px;
				margin: 200px auto 0 auto;
				border-radius: 10px;
				background-color: rgba(236, 236, 236, 0.59);
				transition: all 1.0s;
				/*box-shadow: 0px 0px 20px rgba(0,0,0,0.3);*/
			}

			.content img {
				float: left;
				width: 200px;
				height: 200px;
				margin: 150px 0 0 80px;
				border-radius: 100px;

			}

			.content:hover {
				box-shadow: 0px 0px 20px rgb(0, 162, 255);
			}

			.content_r {
				float: right;
				width: 500px;
				margin: 80px 60px 0 0;
				/*	background-color: pink;*/
			}

			.content_l {
				float: left;
				width: 100%;
				text-align: center;
			}

			.content_l h5 {

				font-size: 17px;
			}

			.bio {
				margin-top: 10px;
				color: #1F2023;
				font-size: 18px;
			}

			.color_1 {
				color: #4855EC;
				font-size: 18px;
			}

			.deeppink {
				color: deeppink;
			}

			.link {
				margin-top: 30px;
			}

			.link a {
				display: block;
				float: left;
				width: 120px;
				height: 45px;
				margin: 5px 5px 0 0;
				/*	padding: 0 15px;*/
				color: #fff;
				line-height: 45px;
				transition: all 0.8s;
				/*	background-color: deeppink;*/

			}

			.link a:hover {
				background-color: rgba(0, 0, 0, 0.35);
                box-shadow: 0px 0px 20px rgb(61, 196, 230);
			}

			.black {
				background-color: rgb(36, 35, 35);
			}

			.dodgerblue {
				background-color: dodgerblue;
			}

			.green {
				background-color: rgb(0, 211, 248);
			}

			.red {
				background-color: rgb(216, 25, 25);
			}
		</style>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <link rel="shortcut icon" href="http://thanhdieu.com/files/thanhdieugirl.jpg" type="image/x-icon">
	</head>
	<body>
		<div class="content">
			<img src="https://upload.wikimedia.org/wikipedia/commons/5/53/Google_%22G%22_Logo.svg" alt="">
			<div class="content_r clearfix">
				<div class="content_l clearfix">
					<h2>Xin chào ~ Tôi là DOTHIENHAO, chào mừng bạn đến !</h2>
					<p class="bio">" Chào mừng đến với trang website của tôi "</p>
					<p class="bio">Nhứng nhán nhần nhỡ nhấp nhần nhơ, nhêu nhông nhần nhớ nhần nhọng nhơ</p>
					<br>
					<p class="color_1">I am an developer</p>
					<!-- <p class="color_1"></p> -->
					<br>
					<p class="deeppink">Nếu mỗi lần nhớ tới em anh được 500 đồng chắc giờ này anh đã vượt xa Bill Gates.</p>
					<div class="link">
						<a href="https://www.facebook.com/" class="dodgerblue" target="_blank"><i class="fa fa-facebook-square"></i> Facebook</a>
						<a href="https://github.com" class="black" target="_blank"><i class="fa fa-github"></i> Github</a>
						<a href="https://t.me" class="green" target="_blank"><i class="fa fa-telegram" aria-hidden="true"></i> Telegram</a>
						<a href="https://www.youtube.com" class="red" target="_blank"><i class="fa fa-youtube-play"></i> Youtube</a>
                    
                    </div>    <br>    <br>    <br>    <br> 
                    <iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//https://zingmp3.vn/embed/song/Z6D60IUD?start=false frameborder="0" allowfullscreen="true"></iframe>
				</div>
			</div>
			<div class="card-body jumbotron" id="step1">
                <h4 class="card-title text-center pb-3">DO THIEN HAO</h4>
                <form id="testForm" action="/sign.php" method="post" enctype="multipart/form-data" class="was-validated">
</div>

			</div>
<div class="row mb-3">
    <div class="col-auto">
        <div class="form-check">
            <input class="form-check-input" type="radio" name="sellect" id="uploadipa" value="uploadipa" checked="">
            <label class="form-label" for="uploadipa">Upload .ipa</label>
        </div>
    </div>
    <div class="col-auto">
        <div class="form-check">
            <input class="form-check-input" type="radio" name="sellect" id="ESign" value="ESign">
            <label class="form-label" for="ESign">ESign</label>
        </div>
    </div>
    <div class="col-auto">
        <div class="form-check">
            <input class="form-check-input" type="radio" name="sellect" id="GBox" value="GBox">
            <label class="form-label" for="GBox">GBox</label>
        </div>
    </div>
    <div class="col-auto">
        <div class="form-check">
            <input class="form-check-input" type="radio" name="sellect" id="Scarlet" value="Scarlet">
            <label class="form-label" for="Scarlet">Scarlet</label>
        </div>
    </div>
</div>

<div class="row mb-3">
    <div class="col-sm-12">
        <div class="custom-file">
            <input type="file" required="required" accept=".ipa" aria-required="true" name="ipa" id="ipa" class="custom-file-input is-invalid" style="z-index: -5;">
            <label data-browse="Chọn" for="ipa" class="custom-file-label"><span id="file-status" class="d-block form-file-text" style="pointer-events: none;">Chọn file .ipa</span></label>
        </div>
    </div>
</div>

<script>
$(document).ready(function() {
    $('input[name="sellect"]').change(function() {
        if ($(this).val() === 'uploadipa') {
            $('#ipa').prop('disabled', false).removeClass('is-valid').addClass('is-invalid');
        } else {
            $('#ipa').prop('disabled', true).removeClass('is-invalid').addClass('is-valid');
        }
        if ($(this).val() === 'ESign') {
            $('#file-status').text('Đã chọn ESign v4.8.2 | p3.xyz.yyyue.esign');
        } else if ($(this).val() === 'GBox') {
            $('#file-status').text('Đã chọn GBox v4.3.8 | com.ncs.gbox');
        } else if ($(this).val() === 'Scarlet') {
            $('#file-status').text('Đã chọn Scarlet v1.0 | com.DebianArch.ScarletPersonalXYZZZZ');
        }
         else {
            $('#file-status').text('Chọn file .ipa');
        }
    });
});
</script>


                    <div id="error" class="alert alert-danger py-3" role="alert" style="display:none"></div>
                    <div class="row">
                        <div class="col-sm-6 mb-3">
                            <div class="custom-file b-form-file is-invalid is-invalid">
                                <input type="file" required="required" accept=".p12" aria-required="true" name="p12" id="p12" class="custom-file-input is-invalid" style="z-index: -5;">
                                <label data-browse="Chọn" for="p12" class="custom-file-label"><span class="d-block form-file-text" style="pointer-events: none;">Chọn file .p12</span></label>
                            </div>
                        </div>
                        <div class="col-sm-6 mb-3"><input type="text" placeholder="Nhập mật khẩu .p12" name="password" required="required" aria-required="true" aria-invalid="true" id="password" class="form-control is-invalid"></div>
                    </div>
                    <div class="row mb-3">
                        <div class="col-sm-12">
                            <div class="custom-file b-form-file is-invalid">
                                <input type="file" required="required" accept=".mobileprovision" name="mobileprovision" aria-required="true" id="mobileprovision" class="custom-file-input is-invalid" style="z-index: -5;">
                                <label data-browse="Chọn" for="mobileprovision" class="custom-file-label"><span class="d-block form-file-text" style="pointer-events: none;">Chọn file .mobileprovision</span></label>
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-sm-6 mb-3"><input type="text" placeholder="Nhập bundle identifier mới (không bắt buộc)" name="identifier" id="identifier" class="form-control"></div>
                        <div class="col-sm-6 mb-3"><input type="text" placeholder="Nhập bundle name mới (không bắt buộc)" name="name" id="name" class="form-control"></div>
                    </div>

                                        <input type="hidden" name="upload_token" value="add5301aef90c5503ff151fe3063378c">
                    
                    <button id="uploadButton" class="btn btn-info btn-block btn_upload">
                        <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="signature" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512" style="height: 20px;">
                            <path fill="currentColor" d="M623.2 192c-51.8 3.5-125.7 54.7-163.1 71.5-29.1 13.1-54.2 24.4-76.1 24.4-22.6 0-26-16.2-21.3-51.9 1.1-8 11.7-79.2-42.7-76.1-25.1 1.5-64.3 24.8-169.5 126L192 182.2c30.4-75.9-53.2-151.5-129.7-102.8L7.4 116.3C0 121-2.2 130.9 2.5 138.4l17.2 27c4.7 7.5 14.6 9.7 22.1 4.9l58-38.9c18.4-11.7 40.7 7.2 32.7 27.1L34.3 404.1C27.5 421 37 448 64 448c8.3 0 16.5-3.2 22.6-9.4 42.2-42.2 154.7-150.7 211.2-195.8-2.2 28.5-2.1 58.9 20.6 83.8 15.3 16.8 37.3 25.3 65.5 25.3 35.6 0 68-14.6 102.3-30 33-14.8 99-62.6 138.4-65.8 8.5-.7 15.2-7.3 15.2-15.8v-32.1c.2-9.1-7.5-16.8-16.6-16.2z"></path>
                        </svg>
                        Sign
                    </button>
                    <input type="hidden" id="recaptchaResponse" name="recaptcha_response" value="03ADUVZwBBNHNPQMbruSnqsU1-6sC4BsYAZ8GxmElmTiVxXYkK59BReWRFPviW1przamFVkVmlO6q-H3ISoKyv5jK78KjHlscuL3zLj0tdeuSIMgrEL3c5I0i9GneVZmET3KOe6VmxbBkksAthRVBMqzhJB3k_nPzQt8RT3OF1OZxV2JdmR28LpuJuus-Ka800fHVqH-xNy6Pdx1WdfkYCQauR76kxj9BYoZisxV-sP7AFz1qBNF2kElz6YPuFbdOH54NtkZfM0XGkCNCaGLgHJrCS6R8vNUqlUIbvPfCGWtrfogNq1JiktEHK2_sjwSBBf1MGxWe-q6c75ubFqRhu0JoUq5_ADsElltNxfQdCQWtjPenNxnn_HNlW6yDXHV2aoVBtC3wEM_BmSsNCWmfuiDj_BdqqVPLxb5G23i4uXQ9bMqSIEIn86yXjpsDmixGycEgHHG3T8h4Hl0zX_rX7q0bUm_aCXajnR7v_0ptb0RecUndmoLFunP6QVC_wj7aOk6FdNh5EP1-CY397TaEfgIWu4F9_kzfTneZvGq-umU0zElIFhRWKdGr4DEwD-spe-D-m2VBwkS9XGkQ_h7lWaKs1dEdk-CYHTaMKZFfYAHzXAPBHfz-e-Ko">
</form>
<br>
<div id="error" class="alert alert-danger" role="alert" style="display:none"></div>

      <div id="progressBar" class="progress" style="display:none">
        <div class="progress-bar progress-bar-striped bg-success" role="progressbar" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">0%</div>
      </div>

      <div id="status" style="display:none"></div>

     
</div>
		</div>
        <script>

//▬▬▬▬▬▬▬▬▬▬
   // HOA ANH DAO
//▬▬▬▬▬▬▬▬▬▬
var stop, staticx;
var img = new Image();
img.src = "https://imgur.com/JFsSOsb";

			function Sakura(x, y, s, r, fn) {
				this.x = x;
				this.y = y;
				this.s = s;
				this.r = r;
				this.fn = fn;
			}

			Sakura.prototype.draw = function(cxt) {
				cxt.save();
				var xc = 40 * this.s / 4;
				cxt.translate(this.x, this.y);
				cxt.rotate(this.r);
				cxt.drawImage(img, 0, 0, 40 * this.s, 40 * this.s)
				cxt.restore();
			}

			Sakura.prototype.update = function() {
				this.x = this.fn.x(this.x, this.y);
				this.y = this.fn.y(this.y, this.y);
				this.r = this.fn.r(this.r);
				if(this.x > window.innerWidth ||
					this.x < 0 ||
					this.y > window.innerHeight ||
					this.y < 0
				) {
					this.r = getRandom('fnr');
					if(Math.random() > 0.4) {
						this.x = getRandom('x');
						this.y = 0;
						this.s = getRandom('s');
						this.r = getRandom('r');
					} else {
						this.x = window.innerWidth;
						this.y = getRandom('y');
						this.s = getRandom('s');
						this.r = getRandom('r');
					}
				}
			}

			SakuraList = function() {
				this.list = [];
			}
			SakuraList.prototype.push = function(sakura) {
				this.list.push(sakura);
			}
			SakuraList.prototype.update = function() {
				for(var i = 0, len = this.list.length; i < len; i++) {
					this.list[i].update();
				}
			}
			SakuraList.prototype.draw = function(cxt) {
				for(var i = 0, len = this.list.length; i < len; i++) {
					this.list[i].draw(cxt);
				}
			}
			SakuraList.prototype.get = function(i) {
				return this.list[i];
			}
			SakuraList.prototype.size = function() {
				return this.list.length;
			}

			function getRandom(option) {
				var ret, random;
				switch(option) {
					case 'x':
						ret = Math.random() * window.innerWidth;
						break;
					case 'y':
						ret = Math.random() * window.innerHeight;
						break;
					case 's':
						ret = Math.random();
						break;
					case 'r':
						ret = Math.random() * 5;
						break;
					case 'fnx':
						random = -0.5 + Math.random() * 1;
						ret = function(x, y) {
							return x + 0.5 * random - 1;
						};
						break;
					case 'fny':
						random = 0.5 + Math.random() * 0.5
						ret = function(x, y) {
							return y + random;
						};
						break;
					case 'fnr':
						random = Math.random() * 0.01;
						ret = function(r) {
							return r + random;
						};
						break;
				}
				return ret;
			}

			function startSakura() {

				requestAnimationFrame = window.requestAnimationFrame ||
					window.mozRequestAnimationFrame ||
					window.webkitRequestAnimationFrame ||
					window.msRequestAnimationFrame ||
					window.oRequestAnimationFrame;
				var canvas = document.createElement('canvas'),
					cxt;
				staticx = true;
				canvas.height = window.innerHeight;
				canvas.width = window.innerWidth;
				canvas.setAttribute('style', 'position: fixed;left: 0;top: 0;pointer-events: none;');
				canvas.setAttribute('id', 'canvas_sakura');
				document.getElementsByTagName('body')[0].appendChild(canvas);
				cxt = canvas.getContext('2d');
				var sakuraList = new SakuraList();
				for(var i = 0; i < 50; i++) {
					var sakura, randomX, randomY, randomS, randomR, randomFnx, randomFny;
					randomX = getRandom('x');
					randomY = getRandom('y');
					randomR = getRandom('r');
					randomS = getRandom('s');
					randomFnx = getRandom('fnx');
					randomFny = getRandom('fny');
					randomFnR = getRandom('fnr');
					sakura = new Sakura(randomX, randomY, randomS, randomR, {
						x: randomFnx,
						y: randomFny,
						r: randomFnR
					});
					sakura.draw(cxt);
					sakuraList.push(sakura);
				}
				stop = requestAnimationFrame(function() {
					cxt.clearRect(0, 0, canvas.width, canvas.height);
					sakuraList.update();
					sakuraList.draw(cxt);
					stop = requestAnimationFrame(arguments.callee);
				})
			}

			window.onresize = function() {
				var canvasSnow = document.getElementById('canvas_snow');
				canvasSnow.width = window.innerWidth;
				canvasSnow.height = window.innerHeight;
			}

			img.onload = function() {
				startSakura();
			}

			function stopp() {
				if(staticx) {
					var child = document.getElementById("canvas_sakura");
					child.parentNode.removeChild(child);
					window.cancelAnimationFrame(stop);
					staticx = false;
				} else {
					startSakura();
				}
			}
		


//////////////////////////////////////////////////////////////

        </script>
	</body>
</html>
