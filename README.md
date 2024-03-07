# Resume Hosting and Formatting

## Purpose
This README provides practical steps on how to host and format your resume using GitHub Pages. It also relates these steps to the general principles of current Technical Writing as explained in Andrew Etter's book "Modern Technical Writing".

# Prerequisites
Using lightweight markup simplifies the process of creating well-formed XML, which is necessary for constructing websites. Before proceeding with the instructions in this README, ensure that your resume is formatted in Markdown, the most widely used lightweight markup language known for its clean syntax. GitHub Flavored Markdown, a favored option for straightforward web-based help systems, is particularly suitable due to its compatibility with GitHub Pages.

## Instructions

### Step 1 : [Install Git](https://git-scm.com/)
Install Git on your computer, as it offers superior performance and is widely favored by technical writers as a distributed version control system (DVCS).
### Step2 : [Sign up for GitHub](https://github.com/)
You need to create GitHub account which is great option for managing remote repositories 
### Step3 : Create a New repository
Once you have successfully logged into Github, locate the "+" symbol situated in the upper right corner of the page. And from the options that appear, choose "new repository." It is essential to ensure that you tick the checkbox labeled "Initialize this repository with a README." Where you can store your documentation in the same repository as its corresponding product source code. 
### Step4 : Clone the Repository
After creating the repository, you need to clone it to your local machine. Click on the green "Code" button and copy the URL provided. Open a terminal or command prompt on your computer, which is prefered by many people due to it's advanced funtionality and even for basic and everyday operations. And use the following command to clone the repository:"git clone <location-url>" and Replace <location-url> with the URL you copied from GitHub. 

### Step5 : [Install Jekyll]( https://rubyinstaller.org/) and Create new Jekyll Site.
Jekyll which is most popular static site generator which can create a beautiful, functional documentation website. You need to Install it then open a command prompt and run the following command to install Jekyll: 
"gem install jekyll bundler".Once,Installed type "jekyll new ." to create a new jekyll site to location where you cloned repository.

### Step 6 : Customize Theme 
You can spare some time to Customize the theme with changing  colors,typefaces and many more.You can modify the '_config.yml' to configure site settings.
### Step 7 : Push Commands 
Once everything is changed and saved you need to add, commit your Markdown file and push them to your Github repository using following commands step by step.
- git add . 
- git commit -m "Initial commit" 
- git push origin main 
### Step 8 : GitHub Pages
Go to your GitHub repository's settings page and choose the branch as a "main" and save it.
### Step 9 : Site 
Once GitHub Pages has finished building your site which can take some time, you can access it at https://<your-username>.github.io/<repository-name>.

## Animated GIF Demo
![Resume Hosting and Formatting Demo](path_to_animated_gif.gif)

## More Resources
- [Markdown Tutorial](link_to_markdown_tutorial)
- [Additional Resource 1](link_to_resource_1)
- [Additional Resource 2](link_to_resource_2)
- [Additional Resource 3](link_to_resource_3)

## Authors and Acknowledgements
Credit to the template authors and group members who contributed to this README.

## FAQs
### Q: Why is Markdown better than a word processor?
Markdown provides a lightweight and simple syntax to format text and create structured documents. It allows for easy version control, compatibility across different platforms, and seamless integration with static site generators.

### Q: Why is my resume not showing up?
Make sure your resume file is properly formatted in Markdown and placed in the correct directory. Check if you have followed the hosting instructions correctly, including enabling GitHub Pages with the correct branch and repository settings.
