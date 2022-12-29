- 👋 Hi, I’m @kwongwangjae
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
kwongwangjae/kwongwangjae is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---!>

span {color : blue; font-size : 20px;} /* span 태그 스타일 선언 */  //선택자 {속성 : 값; 속성 : 값;} 스타일 구성 
<style>태그로 스타일 만들기 
-반드시 <head>태그 내에서만 작성 가능하다, 여러번 작성 가능하며 스타일 시트들이 합쳐 적용된다, 작성된 스타일 시트는 웹 페이지 전체에서 적용된다. 
 ex)
  <style>
  body{ 
  background-color: linen;
  color:bluevoilet;}
  h3{
  text-align : center;
  color : darked;}
  </style>
<p style = "color : meganta; font-size: 30px"> </p>
 
<link>태그로 CSS불러오기
mystyle.css 
body{ background-color:linen; color:blueviolet;
          margin-left:30px; margin-right:30px;}
h3{ text-align:center; color:darked;}

<!DOCTYPE html>
<html>
<head><title>link</title>
       <link type="text/css" rel="stylesheet" href="mystyle.css">
</head>

//@import url(mystyle.css)로 똑같이 불러오기 가능 

<em>태그는 <p>태그의 자식 

class셀렉터 
.warning{color :red;}
body.main{background : aliceblue;}

<body class="main"> 
<div class="warning">60점이하는 f</div>
</body>

id셀렉터
#list {background : black;}

<ul id="list">
   <li>HTML5</li>
   <li><strong>CSS</strong></li>
   <li>JAVASCRIPT</li>
</ul>

전체셀렉터 
* { color : green; } 

속성 셀렉터
input[type=text] {color : red; } 

h3:first-letter { color : red; }
li: hover { background : yellowgreen; }      //hover마우스가 올라갈 때 스타일 적용  

<h3>Web Programmer</h3> 

<ul>
     <li>HTML5</li>
     <li><strong>CSS</strong></li>
     <li>JAVASCRIPT</li>

color : 색(텍스트), background-color : 색(배경), border-color : 색(테두리) 

div { 
     margin-left : 30px;    //왼쪽 여백
     margin-right : 30px;   //오른쪽 여백 
     margin-bottom : 10px; //사이 여백
     color : white;
} 

<hr> 
<div style="background-color:deepskyblue">
     deepskyblue(#00BFFF)</div>
</hr> 

text-indent : <length>|<percentage>;   //들여쓰기 
text-align  : left|right|center|justify; //정렬 
text-decoration : none|underline|over line| line-throught; //텍스트 꾸미기 

font-family : Arial, "Times New Roman", serif:
font-size : 40px;  //40픽셀 크기
font-size : mediun //중간 크기, 크기는 브라우저마다 다름
font-size : 1.6em; //현재 크기의 1.6배 크기 
font-style : italic; //이탤릭 스타일로 지정 
font-weight: 300; //굵기
font-weight: bold; //700

단축 프로퍼티, font 
font : font-style font-weight font-size font-family 
font : italic bold 20px consolas, sans-serif;

div.box{
width : 150px;
height : 50px;
margin : 40px;
border-width : 30px;
padding: 20px; //메인 width와 height의 테두리 }

div.box {             //p와 같은 수로도 가능 
background : yellow;
border-style : solid; //직선 
border-color : peru;
margin : 40px;
border-width:30px;
padding: 20px}

border-radius : 0px 20px 40px 60px//테두리 변경 원형    border-image : url("border.png") 30 round ; //이미지 주소를 변경 

스펀지밥 출력 
div{
background-color: skyblue;
background-size: 100px 100px;
background-image : url("media/spongebob.png");
background-repeat : no-repeat;
background-position : left center;}
