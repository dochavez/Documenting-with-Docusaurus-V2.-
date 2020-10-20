# Documenting-with-Docusaurus-V2. 
## Installation and Configuration for Beginners 🚀 <br>
## Autor: **Danny Chávez**<br>

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

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |




