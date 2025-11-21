# DeBugging2

This repository is intended for you to practice debugging skills.  There are several errors across this flask site for you to find, and debug.  

# Setup & Installation

As we did before with our flask website, we will need to create a virtual environment, activate that environment, and install flask before running the website. See the steps below:  

Open the site in a new Visual Studio window
Open the terminal and type the following to set up a virtual environment: 
>`python3 -m venv .venv`

You should now have a .venv folder in your project. 

In your terminal prompt lets activate the virtual environment: 
>`. .venv/bin/activate`

and now lets install flask, so we can run our site: 
>`pip install flask`

Because we are using the OpenAI API, and an environment variable in this repo, we should install openai, and dotenv. The line below should do both at once.  

>`pip install openai dotenv`

Copy the .env file from your Flask practice site into the root of this folder -> next to your app.py file. 

Now try running the site by having Visual Studio run your app.py file. 

# Debugging Exercise

This site contains a host of errors in the JavaScript code.  When debugging JS, it is helpful to use the developer tools in your browser to view the errors in the console. 

Open DevTools 
> Mac: Cmd + Option + I 
> Windows/Linux: F12 or Ctrl + Shift + I

When you find a bug, you should: 
1. Change that line into a comment to show the error
2. Correct the line of code so that the page works properly

