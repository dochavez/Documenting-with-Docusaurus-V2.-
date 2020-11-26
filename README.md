# Documenting-with-Docusaurus-V2. 
## Installation and Configuration for Beginners 🚀 <br>
## Autor: **Danny Chávez**<br>

[![Twitter Follow](https://img.shields.io/twitter/follow/docusaurus.svg?style=social&label=Follow)](https://twitter.com/docusaurus)
[![npm](https://img.shields.io/npm/v/npm?style=plastic)](https://github.com/npm)
[![yarn](https://img.shields.io/badge/yarn-download-blue)](https://classic.yarnpkg.com/en/docs/install/#windows-stable)
[![gitbash](https://img.shields.io/badge/gitbash-download-blue)](https://git-scm.com/downloads)
[![nodejs](https://img.shields.io/badge/nodejs-download-blue)](https://nodejs.org/en/)
[![visualstudio](https://img.shields.io/badge/visual%20studio%20code-download-blue)](https://code.visualstudio.com/)
[![Docusaurus](https://img.shields.io/badge/docusaurus-download-green)](https://github.com/facebook/docusaurus)

## Tabla de contenido

- [Abstract](#Abstract).
- [Preparation of the environment](#Preparation-of-the-environment).
- [Installation of Docusaurus version 2](#Installation-of-Docusaurus-version-2).


* ## Abstract. 📔

This repository was created to make available a tutorial  that is useful for all those people who are lovers of Information  Technologies. The tutorial provides the steps to work with Docusaurus  version 2. Addressing topics from the preparation of the necessary  requirements to proceed with the installation. Then we will address  aspects of the project description, identification of the main  components. And finally we will conclude with the deployment of our work  to create a github page.

Documenting is a way of showing what is done so that other people can  learn, change, create, design and share. Although it is important to  mention that documenting can be a complicated task. Which can trigger a  project to reach its full potential. But thanks to Docusaurus our task  can be simplified. With Docusaurus you help us create and maintain websites where we can  display our documentation. Thanks to the implementation of React.js, we  can have support for blogs, pages with custom designs with very elegant  and dynamic styles.

* ## Preparation of the environment. 🧰

- [x]  Verify that you have installed on your computer <a href="https://nodejs.org/es/" target="_blank">**Node.js**</a>. To do that, we must go to our terminal and type: **node -v**. The previous command will give us the version that we have installed.
- [x]  Verify that you have installed on your computer <a href="https://www.npmjs.com/get-npm" target="_blank">**Node Package Manager (NPM)**</a>, Likewise, in the previous step we are going to execute the command npm -v and it will provide us with the version that we have installed. In case it is necessary to update the NPM packages, we can do it as follows: if we are working on windows we will execute the command **npm install -g npm**, and if we are working on MAC we can execute the command **sudo npm install -g npm**
- [x]  Verify that you have installed on your computer <a href="https://classic.yarnpkg.com/en/docs/install/#windows-stable" target="_blank">**Yarn**</a> 
- [x]  Verify that you have installed on your computer <a href="https://git-scm.com/downloads" target="_blank">**Gitbash**</a>(optional depending on the operating system you use) and finallly, 
- [x]  Verify that you have installed on your computer a source code **editor** (in our case we will use <a href="https://code.visualstudio.com/" target="_blank">**Visual Studio Code**</a>)

![verificacion](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/verificacion%20de%20version.jpg)
###### Figure 1. Checking our environment using Gitbash.

![verificacion en windows](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/verificacion%20en%20windows.jpg)
###### Figure 2. Checking our environment in windows.

* ## Installation of Docusaurus version 2. 🔧

1. Create a directory to download Docusaurus. In our case we created a folder called **project_docusauv2**. 
2. Enter the folder created from the preferred terminal (Gitbash, cmd, etc.)
3. Execute the **npx @docusaurus/init@next init [name] "[template]"** instruction, where [name] should be replaced by whatever name we want and [template] by classic to use the page for default to be uploaded to the website. Docusaurus has the availability of using various templates such as: facebook, bootstrap and so on.

![installation](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/installation.jpg)
###### Figure 3. Downloading the dependencies for the installation.

* ## Deploying the Application. 📦

5. To run Docusaurus we use the following command from the terminal: **npm run start** and our project will be displayed in our web browser with the address **http://localhost:3000**. If you want, you can also run this other command from the terminal: **yarn run start**. In either case, the two commands performing the same operation of displaying our website in the browser that we have by default. Although if you wish you can also use any other browser.

![command_terminal](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/Command%20from%20the%20terminal.jpg)
###### Figure 4. Running our application in the terminal.

![Deploy the website](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/deploy.jpg)
###### Figure 5. Deployment of our application in our browser through localhost.

* ## Analyzing the structure of the installed project.📜

The **/blog/** folder: contains the blog's Markdown files, which are used to display different types of content presented by different users. for
• The **/docs/** folder: contains the Markdown files for the documents section. <br>
• The **/src/** folder: contains source files with **.js** extension and style sheets (CSS). It is important to mention that any file that is within the path **/src/pages** will be converted within the web page. for
• The **/static/** folder: it is nothing more than a Static Directory. Any content within here will be copied to the root of the final build directory. Which will be used to display our website on the internet. for
• The **/docusaurus.config.js** file: is a configuration file that contains the complete configuration of the site. for
• The **/package.json** file: It is a React application. You can install and use any npm package you want on them. for
• The **/sidebar.js** file: used by the documentation to specify the order of the documents in the sidebar. <br>

* ## Time to customize our site.📜

Docusaurus allows us great flexibility and adaptation to our needs. That is why in the file named **docusaurus.config.js** you can modify the **title** and **tagline** directives by putting any name you want. In the case of **favicon** you must add an image with a **.ico** extension. A good resource you can use to create these types of files is by accessing the <a href="https://favicon.io/favicon-converter/" target="_blank">favicon.io</a> website. Once you have the new file, you should copy and replace it inside the **static\img** folder. You can now test the changes by starting the project with the **npm run start** command or you can use **yarn run start** from the terminal. Remember to be inside the folder of the directory that you created in step **number 1** of this tutorial. Go to **http://localhost:3000** to see the changes made.

![title_tagline_favicon](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/title_tagline_favicon.jpg)
###### Figure 6. Modifying our title, tagline and favicon of our main page.

* ## What is the index.js file for?🏠

The **index.js** file is the home page of our website. In it, the React components that are presented between the navigation bar and the footer of the page are exported. You can create your own components inside the **index.js** file. Since the template includes Style Sheets (CSS) created by the Docusaurus team under a structure named <a href="https://facebookincubator.github.io/infima/" target="_blank">Infima</a>.

Basically, all the content that we put in this file will be viewed by the users who will access our website. It is for that reason, that when deciding what type of information and images we want to show, we must have the detail and the precaution that it is relevant and serves as a presentation of our main page.

* ## Color Palette. 🍭

As we mentioned earlier, **Infima** supports Style Sheets (known as CSS) to make any color changes to our website. This action can be applied within the path **src /css/custom.css**. It is important to note that the color values must be added in hexadecimal (HEX) format. What does hexadecimal colors mean? Color codes are ways of representing the colors we see everyday in a format that a computer can interpret and display. Commonly used in websites and other software applications, there are a variety of formats, including Hex color codes, RGB and HSL values, and HTML color names, amongst others. The most popular are Hex color codes; three byte hexadecimal numbers (meaning they consist of six digits), with each byte, or pair of characters in the Hex code, representing the intensity of red, green and blue in the color respectively. 

| Color Name        | HEX Color           | RGB Color                  |
| ----------------- | ------------------- | -------------------------- |
| White             | #FFFFFF             |rgb(255, 255, 255)          |
| Silver            | #C0C0C0             |rgb(192, 192, 192)          |
| Gray              | #808080             |rgb(128, 128, 128)          |
| Black             | #000000             |rgb(0, 0, 0)                |
| Red               | #FF0000             |rgb(255, 0, 0)              |
| Maroon            | #800000             |rgb(128, 0, 0)              |
| Yellow            | #FFFFFF             |rgb(255, 255, 0)            |
| Olive             | #C0C0C0             |rgb(128, 128, 0)            |
| Lime              | #808080             |rgb(0, 255, 0)              |
| Green             | #008000             |rgb(0, 128, 0)              |
| Aqua              | #00FFFF             |rgb(0, 255, 255)            |
| Teal              | #008080             |rgb(0, 128, 128)            |
| Blue              | #0000FF             |rgb(0, 0, 255)              |
| Navy              | #000080             |rgb(0, 0, 128)              |
| Fuchsia           | #FF00FF             |rgb(255, 0, 255)            |
| Purple            | #800080             |rgb(128, 0, 128)            |

##### Table 1. List of the most Common HTML Color Codes

![Colores css](https://github.com/dochavez/DocusaurusV2/blob/main/colores%20css.jpg)
###### Figure 7. Changing colors using hex codes in custom.css file.

*  ## Navigation bar && Footer. 🗄️

The navigation bar known as **navbar** allows you to add links to other pages within the same site. For this, we must provide a path, although it can also be a URL that takes us to an external link. To modify the navigation bar, we must locate ourselves within the file called **docusaurus.config.js**.Once we are in said file, we locate the corresponding section where all the sections that we wish to incorporate in the navigation bar must be declared.

On the other hand, like the navigation bar, the **footer** component can be modified. Which is inside the **docusaurus.config.js** file. Links can be added that lead us to other information of interest within the site or they can be external links. Finally, we can say that we can also add text related to copyright at the bottom of the page. This can be found in the section ```copyright: `Copyright © ${new Date().getFullYear()} My Project, Inc. Built with Docusaurus.`,```
inside the file **docusaurus.config.js**.

![navbar and footer](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/Navbar%20%26%20Footer.jpg)
###### Figure 8. Identification of the navigation bar and footer on the main page of our site.

* ## Organizing our Documents. 📚

If we want to add a section so that our documents appear organized by categories, we must add a special section for them. Therefore, all of them will be presented as an organized structure, allowing easy navigation between them. If we want to add new sections we must locate ourselves within the **sidebar.js** file. One of the great features that Docusaurus provides is that we can provide a wide variety of documents that contain different information topics. These documents are stored within the folder named docs. To create documents we must create files that contain the extension **.md**. Once we create our document, Docusaurus will show them instantly. The structure that we must follow to create a document is:

```
---
id: part1
title: Guide to organize your trip to Disney World
---
INPUT YOUR INFORMATION IN THIS LINE
```

It is very important to keep in mind that every document has a unique **id**. By default, a document id is the name of the document (without the extension) relative to the root docs directory. For example, we will find the next structure in our project like:

```
website # Root directory of your site
└── docs
   ├── vacation.md
   └── guide
      └── local.md
      └── international.md
```
where, vacation.md **id** is **greeting** and guide/local.md **id** is **guide/hello** and lastly, guide/internacional.md **id** is **guide/international**

**Why the ID´s are important?** Because the ID's are what we will use to identify each document that we will use to keep our information organized. Which will be shown to users on our site in the documents section and in the **sidebar**.However, it is important to emphasize that IDs can also be named in a different way according to what the user put into their structure. For example, if guide/local.md's content is defined as below, its final **id** is **guide/part1**.

```
---
id: part1
title: Guide to organize your trip to Disney World
---
INPUT YOUR INFORMATION IN THIS LINE
```
There are other **fields** that we can add within our .md file, among which we can highlight the following:

- **id:** A unique document id. If this field is not present, the document's id will default to its file name (without the extension).<br>
- **title:** The title of your document. If this field is not present, the document's title will default to its id.<br>
- **hide_title:** Whether to hide the title at the top of the doc. By default it is false.<br>
- **hide_table_of_contents:** Whether to hide the table of contents to the right. By default it is false.<br>
- **sidebar_label:** The text shown in the document sidebar and in the next/previous button for this document. If this field is not present, the document's sidebar_label will default to its title.<br>
- **custom_edit_url:** The URL for editing this document. If this field is not present, the document's edit URL will fall back to editUrl from options fields passed to docusaurus-plugin-content-docs.<br>
- **keywords:** Keywords meta tag for the document page, for search engines.<br>
- **description:** The description of your document, which will become the <meta name="description" content="..."/> and <meta property="og:description" content="..."/> in <head>, used by search engines. If this field is not present, it will default to the first line of the contents.
- **image:** Cover or thumbnail image that will be used when displaying the link to your post.
  
```
---
id: disney
title: Membership to theme parks
hide_title: false
hide_table_of_contents: false
sidebar_label: Markdown :)
custom_edit_url: https://github.com/facebook/docusaurus/edit/master/docs/api-doc-markdown.md
description: Earn free membership for one year.
keywords:
  - disney
  - world
  - parks
image: https://i.imgur.com/mErPwqL.png
---
```
#### PRO-TIP📢: 

If you don't know how to create files with the extension **.md** on the website called <a href="https://dillinger.io/" target="_blank">**Dillinger**</a> you can create this type of file online. Best of all, once you have all your content ready, you can download it to your computer locally and then just add it inside the **/docs** folder of your project. That way you can create a lot of content easily and quickly.

Another way to create **.md** files is to copy one of the files found inside the **/docs** folder, place it in another path to edit it both in name and content, and then place it inside the folder **/docs**.


![creating our blog](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/Blogs.jpg)
###### Figure 9. Creating the file called doc4 for the section of our Documents.

![visualizing](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/Visualizing%20Blogs.jpg)
###### Figure 10. Viewing our created file.

* ## Controlling the versions of our project. 🧬

Version control is important to keep our work up to date. That means that many changes or updates can happen every day. Thus, it is important to keep a good control of the versions that are presented to us or in which we are working. It is important to keep in mind that the updates about version control must be in correspondence with the needs of our documents or our project in general. In other words, only if it is necessary to make a change, we can carry out a series of operations so that everything that we have created in our project and documents is updated as the last version made. To carry out a version control we must locate ourselves within the **package.json** file and add, for example, the following script:
```"version": "docusaurus doc:version"```, then we can execute the following command ```npm run version <version>``` where **"<version>"** is the new version number that will be added both for the control of our documents and their structure. That is, our **sidebar**
   
```
# Directory structure applying version control. Reference: https://v2.docusaurus.io/docs/versioning

website
├── sidebars.json        
├── docs                 
│   ├── foo
│   │   └── bar.md       
│   └── hello.md         
├── versions.json        
├── versioned_docs
│   ├── version-1.1.0
│   │   ├── foo
│   │   │   └── bar.md   
│   │   └── hello.md
│   └── version-1.0.0
│       ├── foo
│       │   └── bar.md   
│       └── hello.md
├── versioned_sidebars
│   ├── version-1.1.0-sidebars.json
│   └── version-1.0.0-sidebars.json
├── docusaurus.config.js
└── package.json

```
   
* ## Creating Blogs with Docusaurus.📰

If all the above seemed very interesting, there is still something else that you should know. Docusaurus allows you to create a **Blog** section for your content. To create a **blog** what you need to do is create a file with a **.md** extension and place it in the folder called **blog**. It is important to mention that the format to establish the file name must be **{date}-{name}.md**. For example: **/blog/2020-10-05-virtual-disney-world.md**

```
---
title: My trip to Virtual Disney World
author: Danny Chavez
author_title: Virtual Boy
author_url: https://github.com/JoelMarcey
author_image_url: https://graph.facebook.com/611217057/picture/?height=200&width=200
tags: [hello, docusaurus-v2]
description: This is my first virtual Disney World.
image: https://i.imgur.com/mErPwqL.png
hide_table_of_contents: false
---
Welcome to my first virtual trip to the theme parks of Disney World. This is a new way of making magic come to your home through the use of virtual application glasses. The experience has been unique because you can interact with your favorite characters.

<!--truncate-->

This is my first blog on Docusaurus 2.

```
![editing our blog](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/Editing%20our%20Blog.jpg)

###### Figure 11. Editing the parameters for our blog.

![our blog in web](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/visualizing%20our%20blog%20in%20the%20web%20browser.jpg)
###### Figure 12. Viewing our blog in the browser

* ## From local to the world. 🌎

**IMPORTANT NOTE**⚠️ : before transferring your files locally to your Github repository you must add certain information in the **docusaurus.config.js** file. in the parameters related to **organizationName**, ** projectName **, **url**, **baseUrl**

```
module.exports = {
  // ...
  url: 'https://endiliey.github.io', // Your website URL
  baseUrl: '/',
  projectName: 'endiliey.github.io',
  organizationName: 'endiliey',
  // ...
};
```
Where:<br>
**organizationName**: The GitHub user or organization that owns the repository.<br>
**projectName**: The name of the GitHub repository.<br>
**url**: URL of the user or organization page of your GitHub page. Generally it is: "**https: //_username_.github.io.**"<br>
**baseUrl**: base URL for your project. For projects hosted on GitHub pages, follow the format "**/projectName/**".<br>

![final settings](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/final%20settings.jpg)
###### Figure 13. Adjustment of configuration parameters to build our file locally

Before moving your entire project to a **github** repository and create a **github pages** for many users to access from anywhere in the world, you must first build the static files on the computer where you are working. To do that you must execute the following command from the console **npm run build** or **yarn run build**. What any of the above commands does is create a folder with the name "**build**" inside your folder where you have all your project. After that, you must execute the following instruction in the same terminal:

![execution of our build](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/build_execution.jpg)
###### Figure 14. Creating our directory called "build"

```GIT_USER=<GITHUB_USERNAME> yarn deploy```

where, "**GITHUB_USERNAME**" is the username that you use directly on Github. Therefore, you should replace it. In case you are using the windows console (cmd) you can execute the following instruction:

```cmd /C "set "GIT_USER=<GITHUB_USERNAME>" && yarn deploy ```

And if you are using **powershell** you can execute the following instruction:
```cmd /C 'set "GIT_USER=<GITHUB_USERNAME>" && yarn deploy' ```

And lastly, if you are using **windows** you can execute the following instruction:
```cmd /C "set "GIT_USER=<GITHUB_USERNAME>" && yarn deploy"```

![final result](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/live%20_site.jpg)
###### Figure 15. Final result of passing our files locally to our repository.

* ## Hurrah...! We finished the tutorial.😊😊😊😊😊

Congratulations! 🎉🎊🎉, you now know the basics of Docusaurus and have all the tools you need to create a great documentation website. We covered how to create basic documentation, manage different versions, create custom pages, customize the default website, and create blogs. Docusaurus is very flexible and customizable, which allows us to have a wide variety of integrations, search functions, tools for image optimizations, adding embedded videos, and many other things. Thanks to the advantages that Github offers us, you can create your own websites and share them with many users worldwide. If you want to see how my site looks in my repository, you can visit the following link: https://dochavez.github.io/Documenting-with-Docusaurus-V2.-/

Thank you very much for reading this guide and I hope it will be very useful for your future projects. Animate, Learn and Share.

* ## License Notice. 📜
This repository and all its content is licensed by MIT. You can access to read it in this <a href="https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/LICENSE">LINK</a>
