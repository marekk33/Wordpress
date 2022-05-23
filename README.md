# Wordpress
# Technical documentary for website wordpress

Wordpress is a free software designed to create and maintain blogs and websites without any coding knowledge. It's greatest advantage it's easy and simplicity of use. Thanks to it, without having any programming knowledge, you can achieve a lot on the Internet.

## 1. Installing a new backup 

To install WordPress you need:
- have a server where you will put your wordpress website (for example, we will use a local server using the XAMPP package)
- have a database (XAMPP)
- wordpress files to install

## 1.1 Installing a XAMPP and WordPress download

To install the XAMPP package, we need the installer. We download from the site https://www.apachefriends.org.
Select the appropriate version for your computer and download the installer.

![Screenshot_1](https://user-images.githubusercontent.com/105982073/169693388-fc322a61-02b3-423f-be37-6bebe9e470c7.png)

After downloading our installer, run and install it. Here we select all options and move on next.

![Screenshot_2](https://user-images.githubusercontent.com/105982073/169693715-0ce4d8ce-a50a-4520-b3bd-39fa426f8418.png)

Here we decide in which folder the XAMPP should be stored. After a moment's thought, we move on.

![Screenshot_3](https://user-images.githubusercontent.com/105982073/169693966-bc7cf4d8-af09-417e-b8b2-f91c5b7f8f1b.png)

Next and install.

![Screenshot_4](https://user-images.githubusercontent.com/105982073/169693997-0f440dfa-647b-4a6e-ba3c-af59de1123ed.png)

Now you've installed XAMPP (it's our server www), it's time to download Wordpress. You can find it at https://pl.wordpress.org/download/ or you can dowload from this repo.

![Screenshot_5](https://user-images.githubusercontent.com/105982073/169694247-8852fa8f-e664-49b3-9d07-250f68208630.png)

## 1.2 Making the website on a local server

We have everything ready to run our Wordpress. There are some important steps you need to take for the website to work.

Launch XAMPP and start Apache and MySQL.

![Screenshot_6](https://user-images.githubusercontent.com/105982073/169696111-3d41bad5-88c2-4872-82fa-9bebea06a1ec.png) 
![Screenshot_7](https://user-images.githubusercontent.com/105982073/169696118-404d5b5d-d740-4d8c-bd27-2244b8c3fc62.png)

First, let's take a look at our database. Select **admin** from the MySQL module.
You are now in the main phpmyAdmin dashboard which is a database management tool. In it, we will create a database for WordPress.
Go to the database tab and then in the database name field enter the name of your database (**Wordpress** is given here) and then click **create**.

![Screenshot_8](https://user-images.githubusercontent.com/105982073/169697304-81265d53-58ba-493e-8f6f-c67531c9de9c.png)

Once we have the database in place, we need to take care of the files on the server. Go to the XAMPP folder (Where you saved the path before installing) ---> **htdocs** and create a folder for WordPress files.

![Screenshot_9](https://user-images.githubusercontent.com/105982073/169699965-c4bfa458-0c5e-4953-97ec-50a9b882d6da.png)

Now we are ready to install our WordPress. Go to the XAMPP panel and click **Admin** from the Apache module. A browser opens with a welcome text from XAMPP. In the browser address, change the address from **localhost:dashboard/** to **localhost:your_file_name/**.

![Screenshot_10](https://user-images.githubusercontent.com/105982073/169700349-e8b76173-9d7d-4b8b-bbc5-c0974386b10c.png)

We are currently in the WordPress installer, so we are starting the installation. Click **Start** and move on next.

Now we need to provide the database connection details:
- Database name: **we put there the name of the previously created table** (We type wordpress)
- User name: **root**
- Password: **none**
- Database server address: **localhost**
- Table prefix: **without changes**

Then click **Submit**.

![Screenshot_11](https://user-images.githubusercontent.com/105982073/169700777-c1a93fd5-be09-40fa-a79c-0c0e18265383.png)

We click until the form pops up. We fill in the fields at our discretion and click **Install WordPress**.

Now we have to log in.

![Screenshot_12](https://user-images.githubusercontent.com/105982073/169701478-61ed092b-d3c0-4b95-b8b5-6b4a72b388bc.png)

Voilà! We now have WordPress installed and we can start working :tada:. 

## 2. How to start? WordPress options available.

WordPress is easy to use. This software gives us a lot of possibilities and options to use.

![Screenshot_14](https://user-images.githubusercontent.com/105982073/169702304-69116ece-fbea-4579-9a5c-a6cae44c7ea6.png)

## **2.1 Dashboard**

- **Home**: Here you will find the main information about the site. news, events, site activity, site health status.
- **Updates**: Here you can find information about updates, set auto-updates and see what plugins or themes need updating.

## **2.2 Posts**

This option is used to publish a blog post. You can view your posts as well as publish them.

After going to the option **add post**, we go to the post creator. 

![Screenshot_15](https://user-images.githubusercontent.com/105982073/169705334-6590e1fa-2ca0-49f2-a651-1a72e392d6cc.png)

There are a lot of tools here that we can use to publish our post. In addition to writing any text, we have options like:
- **Visibility**: We can decide who sees our post
- **Publish**: planed publication of the post
- **Author**: Possibility to include the author's name in the text
- **Permalink**: Just link for post
- **Categories, Tags, Featured image, Discussion**: They increase user access and interest

Once you have finished writing your post, you can publish it by the blue button **Publish** and see it.

![Screenshot_16](https://user-images.githubusercontent.com/105982073/169705601-311b8dcc-3a16-4a2c-a713-ec488cb3545e.png)

To add your first post, you can also go to the **Add New** tab.

Here we can enter the title of the article and we can write the text that we want to present on the blog. We can choose the mode in which we will write:

- **Visual** - writing in document style with selection of typography and text formatting (like Word or LibreOffice)
- **Text** - post writing style is encoding (HTML)

![Screenshot_25](https://user-images.githubusercontent.com/105982073/169765689-0aa59ed1-8a3f-4871-a6a1-3472b53e678c.png)

## **2.3 Media**

Library of photos, videos, sounds. By uploading files to it, we can use them later to publish pages.

![Screenshot_20](https://user-images.githubusercontent.com/105982073/169706802-c1124e0c-8793-4ec2-b66f-2f72749f0b10.png)

## **2.4 Pages**

Adding pages looks a lot like adding posts.

![Screenshot_17](https://user-images.githubusercontent.com/105982073/169706318-d5a35f1b-c367-4aed-a7ec-8ecb880b5f2c.png)

## **2.5 Comments**

It presents comments posted by users, authors of pages or posts and admins.

![Screenshot_18](https://user-images.githubusercontent.com/105982073/169706445-10d18005-fb86-44b9-bbe5-9b4138748bcd.png)

## **2.6 Appearance**

Customize the theme for our site. We can choose the theme from around 5,000 available from WordPress.

![Screenshot_19](https://user-images.githubusercontent.com/105982073/169706872-4e0e4c70-54da-4e6b-9dee-86d171d08c44.png)
![Screenshot_21](https://user-images.githubusercontent.com/105982073/169706900-e90eb839-80e1-4491-81b3-964c36b93d88.png)
![Screenshot_22](https://user-images.githubusercontent.com/105982073/169706944-f14e13f6-48ac-4a4a-8712-941c5d79281b.png)

## **2.7 Plugins**

WordPress plugins are small web applications (functions and routines) that run in a WordPress environment. Plugins can extend the functionality of the WordPress system, change the standard operation of this system, optimize its operation or automate the performance of certain works.

![Screenshot_23](https://user-images.githubusercontent.com/105982073/169707115-07c27c0b-3891-468c-a8dc-cf880bc78c96.png)
![Screenshot_24](https://user-images.githubusercontent.com/105982073/169707117-c0bd527c-08b6-49ce-a9a6-c325a6db4623.png)

## **2.8 Users**

User roles is a WordPress functionality whose task is to grant or revoke permissions to a specific user. With the help of user roles, you can define which features of your website you will grant access to a new (or existing) user. You can also personalize the user profile

## **2.9 Tools**

In the available tools you can import different pages or export your own. In addition, you have a site status preview and you can export or delete your personal data for other purposes. Additionally, there is a file editor available.

## **2.10 Settings**

The settings are used to set the final appearance of the page. There you have the option to change:

- website name, address
- time zone
- date and time format
- home page selection
- modifications to entries, posts, comments
- media sizes
- tag alias
- link settings




