**STEP 1 – INSTALLING THE NGINX WEB SERVER**

- `verify that nginx was successfully installed and is running as a service in Ubuntu`

![verify.ngix](./verify-ngix.PNG)

- `Test how our Nginx server can respond to requests from the Internet.`

![Nginx response](./ngix%20webresult.PNG)

---

**STEP 2 — INSTALLING MYSQL**

- `Mysql Secure Installtion ,Interactive Script`

![interactive script](./interactive%20script.PNG)




---

**STEP 3 – INSTALLING PHP**

- Install php-fpm and php-mysql

![install php](./php.fpm.PNG)

---
**STEP 4 — CONFIGURING NGINX TO USE PHP PROCESSOR**

- `Test your configuration for syntax errors`

![test config](./test%20config.PNG)


- `Create an index.html file in that location so that we can test that our new server block works as expected`

![index file](./index%20file.PNG)


---

**STEP 5 – TESTING PHP WITH NGINX**

- `We test it to validate that Nginx can correctly hand .php files off our PHP processor.`

	![php test](./php%20test.PNG)

---

**STEP 6 – RETRIEVING DATA FROM MYSQL DATABASE WITH PHP**

- `Create new database & new user and grant it full priviledges on the database we just created`

![new datsbase](./new%20user.PNG)

- `Confirm the example_user have access to example_database`

![confirm database](./confirm%20database.PNG)

- `We create a test table named todo_list. From the MySQL console`

![create test table](./test%20table.PNG)

- `Create a PHP script that will connect to MySQL and query for our content`

![php conne](./php%20connect.PNG)









