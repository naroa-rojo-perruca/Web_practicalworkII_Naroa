# Naroa´s website (Practical work II)

The aim of this work is to showcase everything that I learned in this subject specifically in the matter of HTML and CSS, as well as on GitHub. It consists of a website with different pages, a repository in GitHub, where the different versions of the work are collected and this document that will describe my work on detail. The tools used for this project were: GitHub and Visual Studio Code. While the coding languages used were HTML and CSS.

---

## Description of the website
The website created follows the following structure:

* **Home page (indext.html):** where a brief description of the work is provided, as well as the contents of the website, explaining the different sections. It also includes, a photo, my name and some details.
* **About me page (about.html):** where a description of my academic context is provided. It includes a section with my skills, another with some links to my social media (LinkedIn and GitHub) and lastly a link to my CV(PDF).
* **Contact Me page (contact.html):** provides a form to include the user’s name, email, phone number and a message (this form is not functional).

* **Degree (degree.html):** includes an overview of my degree with all the subjects divided by years and the optatives, as well as it specifies the category and credits of each subject. The page is also focused on the Diploma of AI applied to robotics and includes a link to the subject of Fundamentals of Computer Engineering.

* **Fundamentals of Computer Engineering (fce.html):** where a description of the subject is provided, the different blocks with their respective units and the practical works done in the subject.

* **Net (net.html):** includes four links to other classmate´s websites.

* **Topic (topic.html):** includes information on a topic researched, in this case: AI on Spotify.

---

## Description of the repository in Git Hub and the structure of the project:
Git Hub was used to save different versions of the project and record the process of it. 

It includes:
* **Readme file (which is this document)** describing in detail the project.
* **gitignore.**
* **License (Apache-2.0).**
* **Docs folder.** Inside of it there is:
    * **CSS folder** with the style of all pages (styles.css).
    * **Image folder** with all the images used.
    * **index.html**
    * **Public folder** with all the rest of the pages: about.html, contact.html, degree.html, fce.html, net.html and topic.html.
 
---

## Software description: 
As mentioned before, the languages used were HTML and CSS. And, as it can be appreciated there is one css file(styles.css) and a html file for every page. 
In the CSS file the styles of the pages are specified and design; whereas in the html files the structure of the page is defined. 

### HTML files: 
All the pages use the same structure:
Firstly, the language is defined and in the head the optimization to mobile phones is defined, as well as the title (which is different for each page), the connection to the styles file and a font reference (to include the Open Sans font which I used in the h1 texts).
In the body there is all the content of the page. To organize it I used classes, therefore I created different classes that suits my needs in every page. 
Lastly, the footer that includes the copyright specifications.

### CSS file:
Divided in sections by comments, the CSS file first it includes the general settings that are applied and used in all pages followed by specific settings for each page. This solved a problem that I had which will later be explained.
In the general settings, common to all pages I included the body, the header, the navigation for the menu, text settings, links settings and the footer settings.

---

## Process of the work:
This work was based on other activities made in class, especially Activity III. I started by following the structure made in that activity to do the header, the menu and the footer. Then, I personalized it as it shows on my web with the header on top and the personalization of the menu and footer. 

To create the structure of the website, as I already mentioned I used classes, such as the classes used on Activity III which used Flexbox that has helped me throughout my work to help me change the position of the different blocks. 
Another resource that I used in this project where the test websites made in class, specifically the one were the floating items was teached, which I used in the About Me page.

---

## Main problems:
Throughout the building of the website a great number of problems arose, however I did my best to solve them. 

* **How to structure the website and align the items.**
At the beginning of the project, I had doubts on how to align the items. However, as it has already been mentioned I used flexbox and classes to align the items and personalize         everything.

* **Styles.**
After creating the styles of the index, the problem was that everything written was applying to the other pages. My idea was to create a CSS file for each HTMLL file. However, then, I came to the realization that the project had to include only one style file. That is the reason why, the styles file is divided by comments in sections with the specifications of different classes used on each page.

* **Unorganized lists (UL)**
To create the menu for every page I changed the settings of the unorganized list. However, that also means that for every unorganized list created, the same settings will apply which is not ideal. To solve it, the rest of the lists were written with `<p>` instead of `<ul>`.

* **Git Hub**
When I first published my website I could only see the Readme file when I clicked on the link. The problem was that I had to select the branch main and the folder docs. This way, Git Hub would find the index.html file.

---


## Conclusion:
With this project I have learned to develop my skills on HTML, CSS and Git Hub, as well as learning how to create a web site of my own. It also helped me to realize how engineer projects must be structured and the process followed, as well as learning to organize and meet with the deadlines. I would love to further explore how to use Flexbox as well as how to enhance my website.











