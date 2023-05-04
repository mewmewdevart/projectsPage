<h1 align="center">
 projectsPage
</h1>


<p align="center">
	<b><i>Just an experiment using "excel" as a database for hosting my projects.</i></b><br>
</p>


<p align="center">
	<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/mewmewdevart/projectsPage?color=6272a4" />
	<img alt="Main language" src="https://img.shields.io/github/languages/top/MEWMEWDEVART/projectsPage?color=6272a4"/>
	<img alt="License" src="https://img.shields.io/github/license/mewmewdevart/projectsPage?color=6272a4"/>
</p>

## 💡 About the project
This project is an experimental website that uses Google Spreadsheet as a database to host information about various projects. The website displays project cards that contain information about each project, including the project's category, title, description, photo, and URL. <br> <br>
⚠️ | This project was created for study purposes and as to be a fun project, and I dont recommend using an "excel" to store your data. Instead, try using a database like MySQL or others. The performance, scalability, and security will be much better!


<p align="center">
	<a href="https://mewmewdevart.github.io/projectsPage/">🔗 Click here to acess the page of project</a> 
</p>


## 📁 Structure/
* ```index.html```  Responsible for controlling the basic structure of the project.
* ```sources/``` Folder where the card images, CSS and JavaScript files of the project are located
* ```LICENSE```  License for use and distribution of the project.

## 🛠️ Usage

### Prerequisites
To access the website, all you need is an internet connection and a web browser (preferably Google Chrome browser). To make changes and interact with the code, it is necessary to have basic knowledge of JavaScript (with API) , HTML, and CSS, and the corresponding extensions installed on your local machine. <br>

❗️| Make sure you have all the required tools and knowledge installed on your local machine, then continue with these steps."

### Instructions for running and creating your own Projects Page:
**0. Download the archives**

```bash
# Clone the repository
$ git clone git@github.com:mewmewdevart/projectsPage.git

# Enter into the directory
$ cd projectsPage
```

**1. Do the changes in the sources/main.js code**
- Replace the ```id_spreadsheet``` variable with the ID of the user's Google Sheets.
- Ensure that the data in the user's Google Sheets is structured in the same way as the example code (with columns for category, title, description, photo, and url).
   - Example : Use my Google spreadsheets as a reference : <a href="https://docs.google.com/spreadsheets/d/1rgK9dfoR8HpingaLhTtk_8FSB0aiOLlx1LeEXBYP0-o/edit?usp=sharing">🔗 Click here to see my Google Sheet</a> <br>
- Update the ```new_table.push()``` function to extract the data from the appropriate columns in the user's Google Sheets. <br>
#### 📄 Note
This project use the jQuery AJAX API to make a GET request to a Google Spreadsheet and retrieve data in JSON format. It then parses the JSON data to create a table using the Sheetsee.js library. The code also includes functionality to filter the table by category and display pagination buttons. It uses the Jquery library to handle DOM manipulation and event handling. Understand the basics of how the code works to make modifications more easily.


## 🦾 Technologies
- HTML, CSS, and JavaScript, and utilizes the jQuery and Sheetsee.js libraries.
- [VS CODE](https://www.eclipse.org/downloads/) |  I'm a fan of Vim, but due to the web project, I decided to use VS Code.
- Aseprite to edit the banner images of the project.
- A classic notebook to take some notes about the project.

## 🔗 References
- [Markdown](https://www.markdownguide.org/basic-syntax/) | Documentation on how to use Markdown.
- Internet forums and blogs to address my doubts related to the language (Alura, Stack Overflow, and Geeks for Geeks).
- Google Translate to translate some parts of content that were in another language.


## 📋 Issues
Feel free to open an issue if you find a bug or have a suggestion, so we can discuss the best way to improve or fix it.

## 👋 Contributing
You're always welcome to contribute to this project, just create your pull request, and wait for the review.

## 📜  License
This project is made under the MIT license, for more information about its possible use, modification, and sharing, [click here](LICENSE).


<p align="center"> Developed with love 💜 by Larissa Cristina Benedito (Mewmew/Larcrist). </p>
