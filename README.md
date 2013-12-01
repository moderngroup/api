About
===
This git repository gives you examples of using, need files to use of our API.
For example quick registration on your site by calling our auth servers,
search engine api gives you a chanse to create your own search engine powered by our stable
servers in Paris datacenter....

Using auth api
===
It's simple! Just write this code in the header of php content:
include "http://api.kadirov.pp.ua/site/user.php";
include "http://api.kadirov.pp.ua/site/static.php";

and in page content insert:
<code>
<?php
if  ($user){
print "Welcome back, " $user "!";
print "You can <a href='http://api.kadirov.pp.ua/site/logout.php' target='_blank'>logout</a>";
}else{
print "Sorry, but i don't know who are you! Please, <a href='http://api.kadirov.pp.ua/site/login.php' target='_blank'>Login</a>";
}
?>
</code>
