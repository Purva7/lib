<%@ page language="java" contentType="text/html; charset=ISO-8859-1"
    pageEncoding="ISO-8859-1"%>
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<script type="text/javascript" src="https://www.google.com/jsapi"></script>
<script type="text/javascript" src="http://code.jquery.com/jquery-latest.min.js"></script>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=ISO-8859-1">
<title> Kiva Recent loan Information</title>
</head>
<body>
<script type="text/javascript">
 $.getJSON("http://api.kivaws.org/v1/lending_actions/recent.json",function(loandata){
  document.write("Following are id and date of the 100 most recent loans made on Kiva by public lenders." + "<br>" )
  console.log(loandata);
  var i;
  for (i = 0; i < 100; i++) {
	
      document.write(i+1+"] "+" ID "+loandata.lending_actions[i].id  + " Date "+ loandata.lending_actions[i].date+ "<br>");
  }});
 
 </script>
</body>
</html>
