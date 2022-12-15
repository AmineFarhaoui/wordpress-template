A complete docker environment template for WordPress with NGINX and and MYSQL.
----------------------------------------------------------------------------------------------
First copy/rename the .env.example file to .env and configure the variables if needed. <br>
Then simply run ``` docker-compose up -d ```, visit **localhost:8000** and stand developing your website.

The MYSQL volume is store in a folder called mysql/ in your project to make sure you never lose your database data. Ofcourse this can be changed to your prefered destination in the docker-compose.yml file.
