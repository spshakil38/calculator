<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="css/index.css"/>
  <title>overflow and tooltip</title>
</head>
<body>
	  <h1>Calculator </h1>
	  <div class="card">
	   <div class="cal-h">
	  <input id="result" type="text"maxlength="8">
	  </div>
	  <div class="Cal-c">
	    <div>
	    <input class="btn" type="button" value="MC">
	    <input class="btn" type="button" value="M+">
	    <input class="btn" type="button" value="M-">
	    <input class="btn-style" type="button" value="MR">
	     </div>
	    <div>
	    <input class="btn" type="button" value="AC">
	    <input class="btn" type="button" value="Back">
	    <input class="btn" type="button" value="+/-">
	    <input class="btn-style" type="button" value="÷">
	     </div>
	     <div>
	    <input class="btn" type="button" value="7">
	    <input class="btn" type="button" value="8">
	    <input class="btn" type="button" value="9">
	    <input class="btn-style" type="button" value="×">
	     </div>
	     <div>

	    <input class="btn" type="button" value="4">

	    <input class="btn" type="button" value="5">
	    <input class="btn" type="button" value="6">
	    <input class="btn-style" type="button" value="-">
	     </div>
	     <div>

	    <input class="btn" type="button" value="1">

	    <input class="btn" type="button" value="2">
	    <input class="btn" type="button" value="3">
	    <input class="btn-style" type="button" value="+">
	     </div>
	     <div>

	    <input class="btn" type="button" value="%">

	    <input class="btn" type="button" value="0">
	    <input class="btn" type="button" value=".">
	    <input class="btn-style2" type="button" value="=">
	     </div>
	     
	    
	    
	  </div>
	</div>
</body>
</html>
*{
  margin: 0px;
  padding: 0px;
}
h1{
  text-align: center;
  
}
.card{
  width:300px;
  height:500px;
  text-align: center;
  margin: auto;
  box-shadow: 0px 4px 8px 0px rgba(0,0,0,2);
  transition: 3s;
  font-size: 0px;
 
}
.cal-h #result{
 width: 250px;
 text-align: right;
 height:100px;
 padding: 5px;
 letter-spacing: 2px;
 font-size: 25px;
font-weight: bold;
margin-top:40px;
}
.btn{
  width: 66px;
  height:50px;
  padding: 1px;
  font-weight:bold;
  font-size:16px;
  background:#1f2326 ;
  color:white;
}
.btn-style{
 background:#5F4BB6;
  width:66px;
  height:50px;
  padding:1px;
  font-size:16px;
  color:white;
}
.btn-style2{
  background:orange;
  width:66px;
  height:50px;
  padding: 1px;
  font-size: 16px;
  color: white;
}
.btn:hover{
  background: pink;
}
.btn-style:hover{
  background: pink;
}
.btn-style2:hover{
  background:pink;
}
