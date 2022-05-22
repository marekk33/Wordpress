# Wordpress
# Technical documentary for website wordpress

Wordpress is a free software designed to create and maintain blogs and websites without any coding knowledge. Its greatest advantage is its ease and simplicity of use. Thanks to it, without having any programming knowledge, you can achieve a lot on the Internet.

## 1. Installing a new backup 

To install wordpress you need:
- have a server where you will put your wordpress website (for example, we will use a local server using the XAMPP package)
- have a database (XAMPP)
- wordpress files to install

1.1 Installing a XAMPP and wordpress download

To install the XAMPP package, we need the installer. We download from the site https://www.apachefriends.org.
Select the appropriate version for your computer and download the installer.

![Screenshot_1](https://user-images.githubusercontent.com/105982073/169693388-fc322a61-02b3-423f-be37-6bebe9e470c7.png)

After downloading our installer, run it and install it. Here we select all options and move on next.

![Screenshot_2](https://user-images.githubusercontent.com/105982073/169693715-0ce4d8ce-a50a-4520-b3bd-39fa426f8418.png)

Here we decide in which folder the XAMPP should be stored. After a moment's thought, we move on.

![Screenshot_3](https://user-images.githubusercontent.com/105982073/169693966-bc7cf4d8-af09-417e-b8b2-f91c5b7f8f1b.png)

Next and install.

![Screenshot_4](https://user-images.githubusercontent.com/105982073/169693997-0f440dfa-647b-4a6e-ba3c-af59de1123ed.png)

Now that you've installed XAMPP, it's time to download Wordpress. You can find it at https://pl.wordpress.org/download/.

![Screenshot_5](https://user-images.githubusercontent.com/105982073/169694247-8852fa8f-e664-49b3-9d07-250f68208630.png)

## 1.2 Making the website on a local server

We have everything ready to run our Wordpress. There are some important steps you need to take for the website to work.

Launch XAMPP and start Apache and MySQL.

![Screenshot_6](https://user-images.githubusercontent.com/105982073/169696111-3d41bad5-88c2-4872-82fa-9bebea06a1ec.png) 
![Screenshot_7](https://user-images.githubusercontent.com/105982073/169696118-404d5b5d-d740-4d8c-bd27-2244b8c3fc62.png)

First, let's take a look at our database. Select **admin** from the MySQL module
You are now in the main phpmyAdmin dashboard which is a database management tool. In it, we will create a database that will work with wordpress
Go to the database tab and then in the database name field enter the name of your database (**Wordpress** is given here) and then click **create**.

![Screenshot_8](https://user-images.githubusercontent.com/105982073/169697304-81265d53-58ba-493e-8f6f-c67531c9de9c.png)

Once we have the database in place, we need to take care of the files on the server. Go to the XAMPP folder (Where you saved the path before installing) ---> **htdocs** and create a folder for wordpress files.

![Screenshot_9](https://user-images.githubusercontent.com/105982073/169699965-c4bfa458-0c5e-4953-97ec-50a9b882d6da.png)

Now we are ready to install our wordpress. Go to the XAMPP panel and click **Admin** from the Apache module. A browser opens with a welcome text from XAMPP. In the browser address, change the address from **localhost:dashborad/** to **localhost:your_file_name/**.

![Screenshot_10](https://user-images.githubusercontent.com/105982073/169700349-e8b76173-9d7d-4b8b-bbc5-c0974386b10c.png)

We are currently in the wordpress installer, so we are starting the installation. Click **Start** and move on next.

Now we need to provide the database connection details:
- Database name: **we put there the name of the previously created table**
- User name: **root**
- Password: **none**
- Database server address: **localhost**
- Table prefix: **without changes**

Then click **Submit**.

![Screenshot_11](https://user-images.githubusercontent.com/105982073/169700777-c1a93fd5-be09-40fa-a79c-0c0e18265383.png)

We click until the form pops up. We fill in the fields at our discretion and click **Install WordPress**.

Now we have to log in.

![Screenshot_12](https://user-images.githubusercontent.com/105982073/169701478-61ed092b-d3c0-4b95-b8b5-6b4a72b388bc.png)

Voilà! We now have wordpress installed and we can start working :tada:. 

