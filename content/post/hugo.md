+++
title = "Creating your first website using Hugo & GitHub Pages"
date = "2020-05-25"
author = "~10 min read"
tags = ["website", "hugo" ,"github pages"]
cover = "/blog/img/hugocover.jpg"
description = "Making websites is fun again !"
+++

While creating a website from scratch and deploying it can seem daunting at the first glance , using the help of frameworks like `Hugo` you can build your static websites for your personal use / blog / portfolio and deploy it using `GitHub Pages` . Making websites is fun again ! 

Here , I will give a step by step process to build your website and to deploy it . Bear with me till the end :p 

- # *Step 1 : Download Hugo*
I will be showing the process for Windows . If you are a Linux / macOS user the process is pretty much same .  
Download the latest 32 bit / 64 bit version according to your system from [here](https://github.com/gohugoio/hugo/releases)  
Create directory `Hugo\bin` in any of your disk and extract your download in this path . Add this path in your `PATH VARIABLE` so that you can access Hugo commands from your terminal later . If you are not familiar with adding path variable , don't worry . Check it from [here](https://docs.telerik.com/teststudio/features/test-runners/add-path-environment-variables) .  

- # *Step 2 : Creating your new site*
Open `Command Prompt` and go to your directory using `cd` command . Type `hugo new site YOUR_SITE_NAME` 

- # *Step 3 : Download your theme*
Go [here](https://themes.gohugo.io/) . Find a theme according to your preference . This will make your life easy to get your website up and running in no time . Download your theme and extract your theme in the `\theme` directory that has been created in step 2 .  

- # *Step 4 : Learn Markdown*
Don't worry if you have no idea what markdown is . Markdown is a lightweight markup language which won't take more than 5 minutes to learn . Here's [basic syntax](https://www.markdownguide.org/basic-syntax/) and here's a [cheat sheet](https://www.markdownguide.org/cheat-sheet/)

- # *Step 5 : Test your site*
Almost all theme comes with a `\exampleSite` directory in themes . Replace the `\content` , `\static` , `config.toml` in your actual site directory with the ones in exampleSite .  
Run `hugo server` command from your terminal . And you will find a localhost link . Hopefully you will be able to see your website :D  
All of the themes comes with a `ReadMe` in their GitHub Repo . Read them to learn about how to modify and tweak your theme and create your content .

- # *Step 6 : Deploy your site* 

Now that you have created your site . It's time for you to deploy and let the world know about your next big thing :p  
Make a public repository `YOUR_USERNAME.github.io` and clone that repository locally . Now go to your site and type `hugo` in command prompt . This will create a `\public` directory in your site folder . Now copy all the contents from your directory to the repository you created in this step .   
Commit your changes and go to GitHub . Go to repository settings and scroll down to `GitHub Pages` .  
Hopefully you will find the link where your website is deployed . 

Now that you know how to create and deploy your site , the opportunities are endless !  


---


