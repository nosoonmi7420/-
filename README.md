<html>
<meta name='viewport' content='width=device-width, initial-scale=1.0, user-scalable=no, maximum-scale=1.0, minimum-scale=1.0'>
<link href='https://hangeul.pstatic.net/hangeul_static/css/nanum-gothic.css' rel='stylesheet'>
<meta charset="utf-8">

<style>

body{
    margin: 0;
    margin-top: 0px;
    font-family: 'NanumGothicBold';
    font-size:14px;
}

a {
    text-decoration: none;
    color: inherit; 
}

#wrap{
    width:98%;
}

table {
    width:100%;
	
}

td:first-child{
    width:25%;
    text-align: center;
	background-color:#ececec;
}

td{
    padding: 10px;
    border-bottom: 1px solid #e0e0e0;


}

input[type='text'] {
width:95%;
	height:30px;
	border: 1px solid grey;
	font-size:1rem;
}

input[type='submit'] {
  border: 0px solid grey;
  cursor:pointer;
    margin-top: 10px;
    padding:10px;
    background-color: rgb(85, 90, 165);
    color:white;
    margin-left: 15px;
	font-size:0.8rem;
}

.notice_modify{
	float:left;
    margin-left: 10px;
    padding:5px;
    background-color: grey;
    color:white;
	font-size:0.8rem;
}

.cancle{
    margin-top: 10px;
    padding:10px;
    background-color: grey;
    color:white;
    margin-left: 15px;
	font-size:0.8rem;
}

</style>

<head>
    <title>호산나찬양대</title>
</head>
<body>

<div id="wrap">

	 <form name='song' method='post' enctype='multipart/form-data' action='song_add.php'>
<table>
    <tr><td>날 짜</td><td><input type="text" name="date"></td></tr>
	<tr><td>곡 명</td><td><input type="text" name="title"></td></tr>
	<tr><td>전 체</td><td><input type="text" name="alll"></td></tr>
	<tr><td>소프라노</td><td><input type="text" name="so"></td></tr>
	<tr><td>알 토</td><td><input type="text" name="al"></td></tr>
	<tr><td>테 너</td><td><input type="text" name="al"></td></tr>
	<tr><td>베이스</td><td><input type="text" name="al"></td></tr>
	<tr><td>악보(PDF)</td><td><input type='file' name='exfile' ></td></tr>
</table>
<br><br>
<center><input type='submit' value='추가하기'> <a href="admin.html"><span class="cancle">취소</span></a></center>
</form>
<br><br>



</div>

</body>
</html>
