
# Azure Notebooks
Computational Notebooks as a Service. https://notebooks.azure.com/

##Write and Share Your Ideas with Jupyter Notebooks!

![banner](https://github.com/Microsoft/AzureNotebooks/blob/master/.github/aznb_github.png "banner")

**Express with Notebooks:** We all have ideas. With Azure Notebooks, you can write down your ideas using words and pictures, and you can make them come alive with code that you write in Python or R. Azure Notebooks are powered by the Jupyter Open Source project, which currently has over 3 million users.

**Share Notebooks:** Azure Notebooks also makes it easy for you to share your ideas with your colleagues or even with anyone who has access to the web. But we go further than that: we make it easy for them to build their own ideas starting from yours! 

##About this Repo

This GitHub repo is intended for reporting, discussing, and tracking customer issues. We don't have product code on it yet, but we do have a product roadmap below that we'll keep up-to-date. 

##Product Roadmap - subject to change

The Azure Notebook Service is in public review for the next few quarters. Our focus is key data science scenarios and education. 

**Fall 2016 (Q3-2016)** - Initial preview with basic notebook features and sharing using Libraries.  
**Winter 2016 (Q4-2016)** - Store data files in libraries, import from Github, private libraries, and collaboration in libraries.  
**Spring 2017 (Q1-2017)** - More collaboration & security features.  

##Current Release
[Thursday, Oct 13, 2016](https://github.com/Microsoft/AzureNotebooks/blob/master/RELEASES/Thursday%2C%20October%2013%2C%202016.md)

We ship a new release every two weeks. See our [release notes](https://notebooks.azure.com/releasenotes) for details.

##Give it a try
We have a suite of sample notebook libraries. These are real life notebooks that we have used these for our own data science work and training at Microsoft. Some of them are examples from the work we have done with customers of our machine learning services. A welcome notebooks gives you a quick tour of Jupyter. 
* [Welcome to Azure Notebooks](https://notebooks.azure.com/library/samples/html/Azure%20Notebooks%20-%20Welcome.ipynb)
* [Data Science Fundamentals with Pyhton](https://notebooks.azure.com/library/PythonForDS)
* [Discover Sentiments in Tweets](https://notebooks.azure.com/library/samples/html/Discover%20Sentiments%20in%20Tweets.ipynb)

Note: You dont need an account to view notebooks - click the "eyeball"  If you want to run/edit a notebook. You will need a Microsoft account (Outlook, Hotmail, Xbox, etc). You'll be prompted to create one. 

##Get involved! 
* [File an issue](https://github.com/Microsoft/AzureNotebooks/issues/new) for bugs, feature requests, etc.  If you need immediate assistamce, ping nbhelp@microsoft.com 
* Have a cool notebook you want to share?  Upload & tweet with #Azurenotebooks!
* Are you teacher giving a large class or want to give webinar?  Test drive the site and if possible a heads up on the date & number of users: nbhelp@microsoft.com 

##[Filing Issues](https://github.com/Microsoft/AzureNotebooks/issues/new)
Knowing the context of your issues will help us solve it faster. Please include as much of the following as you can while creating issues:
* Whether the issue is related to Jupyter Notebooks or the Libraries feature.
* The Jupyter Kernel (Python2, Pyhton3, or R) in case of problems with a Jupyter Notebook.
* Time of occurrence.
* Web browser the issue occurred in.
* If the issue occurred once or can be reproduced (with steps to repro it).
* LibraryID and Notebook Name
* Logs (!cat .nb.log Or: New/Terminal, $cat .nb.log)
* Usage scenario: teaching a class, doing homework, evaluating results for research.
* Add template to root. 

##FAQs

###What is Jupyter? 

Jupyter (formerly IPython), is a multi-lingual REPL on steroids. This is a free service that provides Jupyter notebooks along with supporting libraries as a service. It means you can just login and use, no installation/setup is necessary. Instructors can also use the service by easily sharing a notebook.  Students get their own private copies that can be run.  The service is provided by the Python team @ Microsoft, which is part of the Data Group.  

###What environemnts are supported and how can I install packages?

Python 2.7.11 (Anaconda 4.1.0) and Python 3.5.1 (Anaconda 4.1).
- You can install packages in Python: `!pip install <pkg name>`
- You can also install packages using conda: `!conda install --name root <pkg name> -y`

We also support R (3.3.0 running MRO)
- You can install packages in R: `install.packages(“pkg name")`

[Full FAQs](https://notebooks.azure.com/faq)

##Resources
* [Jupyter Project](https://jupyter.org/)
* [Azure Notebook Help](nbhelp@microsoft.com)


