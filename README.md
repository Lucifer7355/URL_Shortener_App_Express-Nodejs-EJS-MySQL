# URL_Shortener_App_Express-Nodejs-EJS-MySQL
This is a URL shortener web application for shortening long urls to shorter ones so that they can be shared easily and are easy to access. I have created it using Express js, Nodejs, EJS Template Engine and MySQL database. It can be deployed further on a cloud service provider for global access.


## Installation

Just clone the repository locally and run npm install to install all the required dependencies to run the application. The command will automatically install all required dependencies from package.json file and store it in node_modules folder.
```bash
  - git clone https://github.com/Lucifer7355/URL_Shortener_App_Express-Nodejs-EJS-MySQL.git
  - cd URL_Shortener_App_Express-Nodejs-EJS-MySQL
  - npm install
```
The default port for testing is 7002. It can be changed further or supplied via environment variables as per the requirements.

# Demo
Before shortening https://www.youtube.com URL, database is like this.
![An initial glimpse of database](https://github.com/Lucifer7355/URL_Shortener_App_Express-Nodejs-EJS-MySQL/blob/main/images_for_demonstration/Screenshot%20(254).png)
Putting youtube.com in textarea and clicking on convert
![Putting youtube.com in textarea](https://github.com/Lucifer7355/URL_Shortener_App_Express-Nodejs-EJS-MySQL/blob/main/images_for_demonstration/Screenshot%20(256).png)
Shortened Link is generated 
![Shortened Link is generated](https://github.com/Lucifer7355/URL_Shortener_App_Express-Nodejs-EJS-MySQL/blob/main/images_for_demonstration/Screenshot%20(257).png)
Copying and pasting the link which is of the format http://localhost:7002/9-letters-hashcode
![Pasting the generated link on next chrome tab](https://github.com/Lucifer7355/URL_Shortener_App_Express-Nodejs-EJS-MySQL/blob/main/images_for_demonstration/Screenshot%20(258).png)
The URL (youtube.com) which was shortened is substituted and redirected to that page.
![Page Redirection](https://github.com/Lucifer7355/URL_Shortener_App_Express-Nodejs-EJS-MySQL/blob/main/images_for_demonstration/Screenshot%20(259).png)
The full url, shortened url and the number of times the same url has been asked to shorten is stored in database. In this case its youtube.
![Database after generating the shortened url](https://github.com/Lucifer7355/URL_Shortener_App_Express-Nodejs-EJS-MySQL/blob/main/images_for_demonstration/Screenshot%20(260).png)



