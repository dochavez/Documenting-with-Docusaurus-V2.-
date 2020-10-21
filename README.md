# Documenting-with-Docusaurus-V2. 
## Installation and Configuration for Beginners 🚀 <br>
## Autor: **Danny Chávez**<br>

[![Build Status](https://twitter.com/docusaurus/photo)](https://twitter.com/docusaurus)

* ## Abstract. 📔

This repository was created in order to make available a tutorial that is useful for all those people who are lovers of Information Technologies. The tutorial provides the steps to work with Docusaurus version 2. Addressing topics from the preparation of the necessary requirements to proceed with the installation. Then we will address aspects of the project description, identification of the main components. And finally we will conclude with the deployment of our work locally to create a github page.

Documenting is a way of showing what is done so that other people can learn, modify, create, design and share. Although it is important to mention that documenting can be a complicated task. Which can trigger a project to reach its full potential. But thanks to Docusaurus our task can be greatly simplified.
With Docusaurus you help us create and maintain websites where we can display our documentation. Thanks to the implementation of React.js, we can have support for blogs, pages with custom designs with very elegant and dynamic styles.

* ## Preparation of the environment. 🧰

- [x]  Verify that you have installed on your computer <a href="https://nodejs.org/es/" target="_blank">**Node.js**</a>
- [x]  Verify that you have installed on your computer <a href ="https://classic.yarnpkg.com/en/docs/install/#windows-stable "target="_ blank">**Yarn**</a>
- [x]  Verify that you have installed on your computer <a href ="https://www.npmjs.com/get -npm "target="_ blank">**Node Package Manager (NPM)**</a>, 
- [x]  Verify that you have installed on your computer <a href="https://git-scm.com/downloads" target="_blank">**Gitbash**</a>(optional depending on the operating system you use) and finallly, 
- [x]  Verify that you have installed on your computer a source code **editor** (in our case we will use <a href ="https://code.visualstudio.com/" target="_ blank ">** Visual Studio Code**</a>)

* ## Installation of Docusaurus version 2. 🔧

1. Create a directory to download Docusaurus. In our case we created a folder called **project_docusauv2**. 
2. Enter the folder created from the preferred terminal (Gitbash, cmd, etc.)
3. Execute the **npx @docusaurus/init@next init [name] "[template]"** instruction, where [name] should be replaced by whatever name we want and [template] by classic to use the page for default to be uploaded to the website. Docusaurus has the availability of using various templates such as: facebook, bootstrap and so on.

![installation](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/installation.jpg)

* ## Deploying the Application. 📦

5. To run Docusaurus we use the following command from the terminal: ** npm run start ** and our project will be displayed in our web browser with the address **http://localhost:3000**. If you want, you can also run this other command from the terminal: **yarn run start**. In either case, the two commands performing the same operation of displaying our website in the browser that we have by default. Although if you wish you can also use any other browser.

![command_terminal](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/Command%20from%20the%20terminal.jpg)

![Deploy the website](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/deploy.jpg)

* ## Analyzing the structure of the installed project.📜

The **/blog/** folder: contains the blog's Markdown files, which are used to display different types of content presented by different users. for
• The **/docs/** folder: contains the Markdown files for the documents section. <br>
• The **/src/** folder: contains source files with **.js** extension and style sheets (CSS). It is important to mention that any file that is within the path **/src/pages** will be converted within the web page. for
• The **/static/** folder: it is nothing more than a Static Directory. Any content within here will be copied to the root of the final build directory. Which will be used to display our website on the internet. for
• The **/docusaurus.config.js** file: is a configuration file that contains the complete configuration of the site. for
• The **/package.json** file: It is a React application. You can install and use any npm package you want on them. for
• The **/sidebar.js** file: used by the documentation to specify the order of the documents in the sidebar. <br>

* ## Time to customize our site.📜

Docusaurus allows us great flexibility and adaptation to our needs. That is why in the file named **docusaurus.config.js** you can modify the ** title ** and ** tagline ** directives by putting any name you want. In the case of **favicon** you must add an image with a **.ico** extension. A good resource you can use to create these types of files is by accessing the <a href="https://favicon.io/favicon-converter/" target="_blank">favicon.io</a> website. Once you have the new file, you should copy and replace it inside the **static\img** folder. You can now test the changes by starting the project with the **npm run start** command or you can use **yarn run start** from the terminal. Remember to be inside the folder of the directory that you created in step **number 1** of this tutorial. Go to **http://localhost:3000** to see the changes made.

![title_tagline_favicon](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/title_tagline_favicon.jpg)

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

### Table 1. List of the most Common HTML Color Codes

![Colores css](https://github.com/dochavez/DocusaurusV2/blob/main/colores%20css.jpg)

*  ## Navigation bar && Footer. 🗄️

The navigation bar known as **navbar** allows you to add links to other pages within the same site. For this, we must provide a path, although it can also be a URL that takes us to an external link. To modify the navigation bar, we must locate ourselves within the file called **docusaurus.config.js**.Once we are in said file, we locate the corresponding section where all the sections that we wish to incorporate in the navigation bar must be declared.

On the other hand, like the navigation bar, the **footer** component can be modified. Which is inside the **docusaurus.config.js** file. Links can be added that lead us to other information of interest within the site or they can be external links. Finally, we can say that we can also add text related to copyright at the bottom of the page. This can be found in the section ```copyright: `Copyright © ${new Date().getFullYear()} My Project, Inc. Built with Docusaurus.`,```
inside the file **docusaurus.config.js**.

![navbar and footer](https://github.com/dochavez/Documenting-with-Docusaurus-V2.-/blob/main/Navbar%20%26%20Footer.jpg)

* ## Organizing our Documents. 📚

If we want to add a section so that our documents appear organized by categories, we must add a special section for them. Therefore, all of them will be presented as an organized structure, allowing easy navigation between them. If we want to add new sections we must locate ourselves within the **sidebar.js** file. One of the great features that Docusaurus provides is that we can provide a wide variety of documents that contain different information topics. These documents are stored within the folder named docs. To create documents we must create files that contain the extension **.md**. Once we create our document, Docusaurus will show them instantly. The structure that we must follow to create a document is:

It is very important to keep in mind that every document has a unique **id**. By default, a document id is the name of the document (without the extension) relative to the root docs directory. For example, we will find the next structure in our project like

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




*  ## Controlando las versiones de nuestro proyecto. 🧬



