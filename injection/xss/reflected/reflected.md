<h1>xss reflected</h1>
reflected xss is xss that shows a user input into the site eithou validation allowing user to run malicisous scripty on the client <br>
<img src="https://i.postimg.cc/bJrrgX8V/Screenshot-2026-08-05-125829.png">
in this example it demonestrates a simple form for a ecommerce site<br>
we need to find the vulnerable fields<br>
we have two fields that accept string values
<img src="https://i.postimg.cc/cL5fNcH8/Screenshot-2026-08-05-131130.png">
<br> the credit card number and the access code<br>
lets submit the form to see which  values are rendered
# <img src="https://i.postimg.cc/t4mFHzTF/Screenshot-2026-08-05-131206.png"><br>
credit card number value is the one reflected <br>
so it is the one that can be vulnerable to reflected xss
<br>
lets see how it is represented
<img src="https://i.postimg.cc/YCyQwx9g/Screenshot-2026-08-05-131239.png">
its is in a paragraph tags <p></p>
now we can craft our paylod to get outb of the paragraph and open a script tag and inject the script<br>
like that <code> < /p>< script>alert()< /script></code> remove the spaces
<img src='https://i.postimg.cc/XYD90gJ5/Screenshot-2026-08-05-131331.png'>and submit<br><img src="https://i.postimg.cc/wjbDdkvL/Screenshot-2026-08-05-131339.png" >
