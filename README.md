## About
This Repo is a boiler plate for creating your own Visual Studio Code Color Theme.
Making a new color theme is super simple. Just changing JSON key value pairs to be your colors.

Although the process is very simple, there are many, many, many key value pairs to assign. To make things even more complicated, there are different theme sources for different languages. So your theme may look great in Python, but looks awful in C#, or Markdown, or javaScript, or whatever.

This Boiler Plate seperates main components, from the language specific attributes. Allowing you to have very specific  control over how your theme looks for each individual language. 

Additionally, there is a folder which contains sample files of many of the popular languages so you can easily view your theme for many different languages.

## Getting Started
To start editing yoru theme, instructions are found in vsc-extension-quickstart.md


## Publishing Tips
In the package.json, you will want to change the name, descriptions, and Display name to be your theme. 
Each time you make changes to your theme and want to publish those changes, you will need to increment the version number, rebuild, and publish.
The Readme will be displayed as the main page in the Visual Studio Extension store.

*Optionally* You may want to add an icon (logo), and repository. 
"icon": "images/logoUrl.png",
"repository": {
    "type": "git",
    "url": "Replace me with URL"
},

**Enjoy!**