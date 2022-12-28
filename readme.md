Step 1 - Create a .env in mysql folder
Set the following :  
MYSQL_ROOT_PASSWORD = <password>

Step 2 - Create a env.php in www folder

 <?php 
    define("HOST","mysql");
    define("USER","root");
    define("PASSWORD",<MYSQL_ROOT_PASSWORD>);
?>

Step 3 - npm install
Move to vue.js 
>> npm install