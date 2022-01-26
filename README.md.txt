tble = document.getElementById("age-table")
<table id=​"age-table">​…​</table>​


label = document.getElementById("age-list")
<td id=​"age-list">​…​</td>​


a = document.getElementsByName("info[0]")
NodeList [input]
a[0]
<input type=​"text" name=​"info[0]​">​


s = document.getElementsByName("info[1]")
NodeList [input]
s[0]
<input type=​"text" name=​"info[1]​">​


d = document.getElementsByName("info[2]")
NodeList [input]
d[0]
<input type=​"text" name=​"info[2]​">​


b = document.getElementsByTagName("td")
HTMLCollection(4) [td, td#age-list, td, td, age-list: td#age-list]
b[0]
<td>​Age:​</td>​


c = document.querySelectorAll("input")
NodeList(9) [input, input, input, input, input, input, input, input, input]
c[8]
<input type=​"submit" value=​"Search!">​

c[0]
<input type=​"text" name=​"search">​

c[7]
<input type=​"text" name=​"info[2]​">​