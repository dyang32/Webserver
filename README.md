## Researcher
My role:
* Creating the website with basic menu system
* Designing the homepage of the website
* Uploading and Updating the webpage to the server
***
I wanted to make a website with a menu system so that each group could have ther own section. Also, wanted it to be responsive and adjust to different screen/window sizes and the homepage should be a central location to find information. Decided to used Dreamweaver because it incorporates HTML, CSS, Javascript, Bootstrap, and many more into one application that's easy to use.
* **Dreamweaver** - Is an all-in-one visual development tool for creating, publishing, and managing websites and mobile content.
* **HTML** - (Hyper Text Markup Language) is the standard markup language for creating web pages.
* **CSS** - (Cascading Style Sheets) describes how HTML elements are to be displayed on screen, paper, or other media.
* **JavaScript** - JavaScript is the programming language of HTML Allows you to implement complex things on web pages.
* **Bootstrap** - Bootstrap is a free and open-source front-end library for designing websites and web applications. It contains HTML, CSS and JavaScrtipt.

I used FileZilla to transfer the files from the website's GitHub repository (https://github.com/taimaishuze/sootsplash.html) over to the Sootsplash server (https://sootsplash.csci2461.com). <br/>
I've also wrote a guide on how to install and configure FileZilla [here](https://github.com/dyang32/Webserver/blob/master/FileZilla-HowToInstall.md).
* **FileZilla** - Provides easy to use FTP and SFTP, for this project we used SFTP. 
* **SFTP** (SSH File Transfer Protocol) - Is a network protocol that does different types of file transfers, file acess, and file management over a reliable and secure connection. SFTP runs over an SSH session, usualy on TCP port 22.

Our website uses HTTPS to connect to the internet.
*  **HTTPS** (Hypter Text Transfer Protocol Secure) - Is a secure version of HTTP, is the protocol over which data is sent between the browser and the website you are connected to.
* The **S** in HTTPS stands for Secure, it means all communications between your browser and website is encrypted.
Once I had the website and Filezilla setup it was just a matter of getting people to update their information on the GitHub repository then uploading that information to the webserver.

### Issues and Problems:
| Problems | Solved |
|--------------|------------|
| After uploading files using FileZilla, files on the server would still not update | Changed file permissions in terminal and sometimes having to nano into a file to make changes |
| Some users changed/edited files on the server instead of using the GitHub | Ongoing issue could not solve |

