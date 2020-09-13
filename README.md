<html>
<head>
	<style> 
		.header img {
			float: left;
		}
		.toMain_img_name {
			padding-top: 15px;
		}
		.upbutton {
			background-color: DodgerBlue;
			color: white;
			border-radius: 8px;
			font-size: 20px;
			padding: 12px 28px;
			margin-top: 40px;
			margin-right: 10px;
			cursor: pointer;
		}
		.upbutton:hover {
			background-color: white;
			color: black;
			border: 2px solid DodgerBlue;
		}
		.footer_row {
			float: left;
			margin-left: 100px;
			line-height: 150%;
		}
		.footer_inside {
				list-style:none;
		}
		.school_structure {
			margin-right: 0;
			margin-left: auto;
			width: 80%;
		}
		.description_box{
			border: 1px solid;
			padding: 10px;
			width: 40%;
			border-radius: 8px;
			background-color: rgba( 0, 0, 0, 0.8 );
			position: absolute;
			top: 50%;
			left: 78%;
			transform: translate(-50%, -50%);
			font-size: 18px;
		}
		.des_title{
			color: white;
			font-weight: bold;
			font-size: 20px;
		}
		.des_script{
			color: white;
			font-size: 12px; 
		}
		.loc_map{
			position: absolute;
			top: 110%;
			left: 78%;
			transform: translate(-50%, -50%);
			width: 40%;
		}
		.arrow{
			position: absolute;
			top: 112%;
			left: 63%;
			transform: translate(-50%, -50%);
			width: 2%;
		}
	</style>
	<!-- 맨위 주소창 부분 -->
	<link rel="shortcut icon" type="image/x-icon" href="https://github.com/defaultgroup/PathFinder_imgs/blob/master/title_img_square.jpg?raw=true">
	<title>길잡이</title>
</head>
<!-- 메인화면 이미지 저장 -->
<script type="text/javascript">
	var img_count = 0;
	var imgArray = new Array('baerd_hall', 'intel_science', 'HyeongNam')
</script>
<body>
	<div class = "header">
		<a href="https://defaultgroup.github.io/PathFinder_main/">
			<img src="https://github.com/defaultgroup/PathFinder_imgs/blob/master/title_img_small.png?raw=true" alt="길잡이 로고" width="120" height="150">
			<img class="toMain_img_name" src="https://github.com/defaultgroup/PathFinder_imgs/blob/master/path_finder_name.png?raw=true" alt="길잡이 이름" width="200" height="120">
		</a>
		<button class = "upbutton" onclick="click_school_notice()">학교 공지사항</button>
		<button class = "upbutton" onclick="click_department_notice()">학과 공지사항</button>
		<button class = "upbutton" onclick="click_department_graduate()">학과 졸업요건</button>
		<button class = "upbutton" onclick="click_department_learning()">학과 교육과정</button>
		<button class = "upbutton" onclick="click_today_menu()">오늘의 식단</button>
		<button class = "upbutton" onclick="click_campus_map()">캠퍼스 맵</button>
	</div>
	<br><br><br>
	<div class="img_container">
		<img class="school_structure" src="https://github.com/defaultgroup/PathFinder_imgs/blob/master/SoongDuk2_2.jpg?raw=true" alt="학교 내부 사진">
		<div class="description_box">
			<p class="des_title">숭덕경상관</p>
			<p class="des_script">규모 : 지하 2층 / 지상 6층</p>
			<p class="des_script">시설 : 경제통상대학, 경영대학 강의실, 일반 강의실, 행정실, 교수실</p>
			<p class="des_script">특징 : 경상대학 건물로 이용</p>
			<p class="des_script">스토리 : 철거된 경상관 공간을 대체하는 건물로서 2019년에 신축되었음. 경영·경통대 학생회실도 갖추고 있음</p>
			<p class="des_script">소개 : 숭덕경상관은 2019년 신축된 건물이다. 1964년 캠퍼스 공간 설계에 의해 세워졌던 경상관을 허물고</p>
			<p class="des_script">신축된 건물로서, 경영·경통대 수업 공간과 교수들의 연구동으로 주로 이용되고 있다. 학생 휴게 공간 및</p>
			<p class="des_script">편의시설이 충분히 갖춰져 있고, 특히 외국이 유학생들의 고충을 상시 도울 수 있는 외국인 유학생</p>
			<p class="des_script"> 전용 사무실도 마련되어 있다.</p>
		</div>
		<img class="loc_map" src="https://github.com/defaultgroup/PathFinder_imgs/blob/master/school_loc_small.jpg?raw=true" alt ="학교 이미지">
		<img class="arrow" src="https://github.com/defaultgroup/PathFinder_imgs/blob/master/arrow.png?raw=true" alt="화살표">
	</div>
	<hr>
	<footer class="lowest">
	  <div class="row">
	    <div class="footer_row">
	      <h5>Contact with Developer</h5>
	      <ul class="footer_inside">
	        <li><a class="text-muted">심상현 - 5338095@gmail.com</a></li>
	        <li><a class="text-muted">김한주 - kihaju3188@gmail.com</a></li>
	        <li><a class="text-muted">이재원 - unknown@gmail.com</a></li>
	      </ul>
	    </div>
	    <div class="footer_row">
	      <h5>Donate to Developer</h5>
	      <ul class="footer_inside">
	        <li><a class="text-muted">우리 은행 : 1002-659-539074(심상현)</a></li>
	        <li><a class="text-muted">우리 은행 : ??????</a></li>
	      </ul>
	  </div>
	</footer>
	  <!-- click fuction은 맨위에서 선택했을 경우 저장 -->
	  <script type="text/javascript">
	  	function click_school_notice(){
	  		location.href="school_notice.html"
	  	}
	  	function click_department_notice(){
	  		location.href="department_notice.html"
	  	}
	  	function click_department_graduate(){
	  		location.href="department_graduate.html"
	  	}
	  	function click_department_learning(){
	  		location.href="department_learning.html"
	  	}
	  	function click_today_menu(){
	  		location.href="today_menu.html"
	  	}
	  	function click_campus_map(){
	  		location.href="campus_map.html"
	  	}
	  </script>
</body>
</html>
