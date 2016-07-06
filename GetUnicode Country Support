<%@ page language="java" contentType="text/html; charset=utf-8"%>
<%@ page import="java.util.Locale" %>
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
  <head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <title>GetUnicode Country Support</title>
</head>
<body>
	<table>
		<th>Locale</th>
		<th>Country</th>
		<th>Display Country</th>
		<th>Language</th>
		<th>Display Language</th>
		<th>Variant</th>
	<%
		Locale[] availableLocales = Locale.getAvailableLocales();
		for(Locale locale : availableLocales){
			out.println("<tr>");
			out.println(" <td>"+locale.getDisplayName()+"</td>");
			out.println(" <td>"+locale.getCountry()+"</td>");
			out.println(" <td>"+locale.getDisplayCountry()+"</td>");
			out.println(" <td>"+locale.getLanguage()+"</td>");
			out.println(" <td>"+locale.getDisplayLanguage()+"</td>");
			out.println(" <td>"+locale.getVariant()+"</td>");
			out.println("</tr>");
		}
	%>
	</table>
</body>
</html>
