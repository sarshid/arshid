# arshid
<?php
$db_name="app";
$mysql_username="root";
$mysql_password="";
$server_name="localhost";
$con= mysqli_connect($server_name,$mysql_username,$mysql_password,$db_name,3308);

if(!$con)
{
   echo"connection unsuccessful..." . mysqli_connect_error();
}
else
{
echo "<h3> Database connection successful...</h3>";
}
