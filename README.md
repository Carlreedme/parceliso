# parceliso

Quick start

Installation:
Unzip the "Files" directory.
Open the application/config/database.php file and then:
Enter your DB connection settings and save the file.
Upload all the files inside the "Files" directory to your server. (including the modified database.php file)
Go to your browser and go to http://yourwebsite.com/install
Follow the installation steps.
When the installation has been finished you can login to the admin panel with the login details you entered.
When you are logged in you can change the settings to your need.
When everything is done you need to create a cron job the points to the url "http://yourdomain.com/cron" file.
       Tutorial from Tutsplus about how to setup cron jobs (http://code.tutsplus.com/tutorials/managing-cron-jobs-with-php--net-19428)
Upload file(s):
If you want to upload a file you need follow these steps:
Click the "Select file(s)" button and choose the files you want to upload.
Fill in the emails you want to send the file(s) to. (If you don't want to send via email skip to step 4)
Fill in your email address. (If you don't want to send via email skip to step 4)
Fill in the message you want to send to the recipients.
You can click the little "Gear" in the bottom right corner this will open a section with upload options.
Change max upload size:
You can change the maximum upload size of droppy in the admin panel go to:
Settings -> General settings and scroll down to "Max upload size (MB)".