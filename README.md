# satoshinu3104のページ



<html>
	<body>
		<style>
			.game_img {
			position: relative;
			}
			.game_img p {
			position: absolute;
			top: 50%;
			left: 2%;
			-ms-transform: translate(0%,-50%);
			-webkit-transform: translate(0%,-50%);
			transform: translate(0%,-50%);
			margin:0;
			paddin:0;
			/*文字の装飾は省略*/
			}			
			.profile_img {
			position: relative;
			}
			.profile_img p {
			position: absolute;
			top: 50%;
			left: 2%;
			-ms-transform: translate(0%,-50%);
			-webkit-transform: translate(0%,-50%);
			transform: translate(0%,-50%);
			margin:0;
			paddin:0;
			/*文字の装飾は省略*/
			}			
			.blog_img {
			position: relative;
			}
			.blog_img p {
			position: absolute;
			top: 50%;
			left: 2%;
			-ms-transform: translate(0%,-50%);
			-webkit-transform: translate(0%,-50%);
			transform: translate(0%,-50%);
			margin:0;
			paddin:0;
			/*文字の装飾は省略*/
			}
			body {
			background-image: url(../../B92EA61B-786F-4166-9212-10BBE723DCBD.gif);
			}
			/*タブ切り替え全体のスタイル*/
			.tabs {
			margin-top: 50px;
			padding-bottom: 40px;
			background-color: #fff;
			box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
			width: 700px;
			margin: 0 auto;
			}
			/*タブのスタイル*/
			.tab_item {
			width: calc(100%/3);
			height: 50px;
			border-bottom: 3px solid #5ab4bd;
			background-color: #d9d9d9;
			line-height: 50px;
			font-size: 16px;
			text-align: center;
			color: #565656;
			display: block;
			float: left;
			text-align: center;
			font-weight: bold;
			transition: all 0.2s ease;
			}
			.tab_item:hover {
			opacity: 0.75;
			}
			
			/*ラジオボタンを全て消す*/
			input[name="tab_item"] {
			display: none;
			}
			
			/*タブ切り替えの中身のスタイル*/
			.tab_content {
			/*display: none;*/
			padding: 40px 40px 0;
			clear: both;
			overflow: hidden;
			}
			
			/*選択されているタブのコンテンツのみを表示*/
			#game:checked ~ #game_content,
			#profile:checked ~ #profile_content,
			#blog:checked ~ #blog_content {
			display: block;
			}
			
			/*選択されているタブのスタイルを変える*/
			.tabs input:checked + .tab_item {
			background-color: #5ab4bd;
			color: #fff;
			}
			
			
		</style>
		<input id="game" type="radio" name="tab_item" checked>
		<label class="tab_item" for="game">ゲーム</label>
		<input id="profile" type="radio" name="tab_item" >
		<label class="tab_item" for="profile">プロフィール</label>
		<input id="blog" type="radio" name="tab_item" >
		<label class="tab_item" for="blog">ブログ</label>
		
		<div class="tab_content" id="game_content">
			<div class="game_img" >
				<img src="750FB9D6-E39D-4F3E-8BB4-093F5BB3D644.gif" alt="">
				<p>
					<font color="white">
						ゲーム
					</font>
				</p>
			</div>
			<img src="A301821D-EDD4-4194-96DB-E244DD3B5B57.gif" alt=""><a href="/typing_game" >タイピングのゲーム</a>
		</div>
	</body>
</html>

