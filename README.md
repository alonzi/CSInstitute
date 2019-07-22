# CS Institute workshop on Data Science
This repository contains presentation information and demo material for the CS Institute

## Intro to Data Science
* Workshop Leader: Pete Alonzi, Data Scientist (UVA Data Science Institute)
* Grades: 9-12
* Description: Explore Project Jupyter as a way to introduce data science explorations in your classroom.

## Today's Plan
1. Terminology
2. Discuss goals
3. Get our hands dirty and have some fun

# Terminology
One of the toughest thing about data science is that no one agrees on what it means.
* "The term “data scientist” was coined as recently as 2008 when companies realized the need for data professionals who are skilled in organizing and analyzing massive amounts of data." ~ https://datascience.berkeley.edu
* "Data science continues to evolve ... " ~ https://datascience.berkeley.edu/about/what-is-data-science/
* "Data science is a multi-disciplinary field that uses scientific methods, processes, algorithms and systems to extract knowledge and insights from structured and unstructured data." ~ Wikipedia

## Extract knowledge and insights from structured and unstructured data
Let's talk about knowledge and insights.
![](https://github.com/alonzi/CSInstitute/blob/master/Blooms-Taxonomy-History.png)
I'll believe you can write a program that extracts knowledge. But I won't go so far with regards to insights.

## Pete's definition of Data Science
![](https://github.com/alonzi/CSInstitute/blob/master/researchFlowchart.png)
What we face today is data on a global scale. Megabytes have become Gigabytes have become Terabytes and so on. Now we must use computers to aid our science. But we cannot forget that the human brain is where the magic happens. In fact the most advanced machine learning techniques are nambed after the brain, we call them artificial neural networks.

### "Data Science is the process of uploading data into the human brain." ~ Pete Alonzi

## Example and Questions
Let's play a game: How long would it take to drive from here (799 Faulconer Drive) to Mas Tapas (904 Monticello Road)?

When I was a kid
![](https://github.com/alonzi/CSInstitute/blob/master/charlottesville_map.jpg)

Today
![](https://github.com/alonzi/CSInstitute/blob/master/googleDirections.png)

My qestions to you: 
* Why does google give us three options? (hint: think back to Bloom's Taxonomy and my definition)
* Which was more helpful, the map or the text directions?
* Look at how much info you could absorb quickly through the image / if you already know the town then the text directions are all you need. [ not a question ] 

## Last tidbit (totally a bonus)
* One more piece of terminology: When I said "already know the town", there is a machine learning analog, that is called training a model. If I didn't know Charlottesville I would have no idea how to get anywhere (you should see my parents when they visit, they are from Chicago, they are used to a grid). In the same way, if google maps was not trained then it would have about as much luck as my parents.


# Goals
Whenever I present I always have exactly three goals. And they are always the same. Here we go:
1. Make sure you have access to the resources
2. Get comfortable with the subject
3. Know how to get help
    * first on your own (eg: read the manual)
    * second to a trusted resource (eg: a good online reference)
    * third a knowledgeable person (eg: email pete, datascientist@virginia.edu)
    
  ## Your goals!
  What do you want to learn?
  
  
# The Fun Part
1. Show everyone how to access Project Jupyter
2. Tour of the system
3. Demos, demos, demos

## Part 1: Access to project Jupyter
One of the challenges in data science is accessing computational resources, accessing data resources, performing analysis, coding, etc. All at the same time. The cognitive load is through the roof.

![](https://github.com/alonzi/CSInstitute/blob/master/cogload.jpg)

Project Jupyter is a system developed at Berkeley that eliminates many of these difficulties and enables the data scientist to focus on just doing their science. I have had great sucess with it in the classrooom as well as the laboratory. I went to a conference about Jupyter back in 2018 (https://github.com/UVA-DSI/conferences/tree/master/JupyterCon18).

### Getting to Jupyter
1. Install it on your computer via: https://www.anaconda.com/distribution/#download-section
    * NB: Make sure you pick the right operating system
    * NB: use the big green button that says "Download"
    * NB: use version 3.x (the x just means the newest, inthis case 3.7)

![](https://github.com/alonzi/CSInstitute/blob/master/download.png)

2. Access through the cloud via: https://open-data-lab.signin.aws.amazon.com/console
    * Requires a username and password (I have them for you)

![](https://github.com/alonzi/CSInstitute/blob/master/awsLogin.png)

### Tour of the system
Let's start by learning our way around Jupyter. We will have a little divergence as people get to Jupyter but once we are in then it will be the same for all. There are too many things to screen shot so I'll just do one big one.

![](https://github.com/alonzi/CSInstitute/blob/master/SAMPLEJupyter.png)

![](https://github.com/alonzi/CSInstitute/blob/master/jupyterlab.png)

1. Quit - upper right corner
2. New - right hand side, near the top
3. List of files - main part of the screen
    * .ipynb - file extension for jupyter notebooks (a tool we will use)
    * .txt - file extension for text
    * to access a file click on it
    
What's cool about jupyter is that it connects all of the computer power to the user through this since interface. It is based in the webbrowser so it is familiar to anyone who uses a web browser.

### Tour of a Jupyter Notebook ( .ipynb )
1. cell (and new cell icon)
2. save button
3. play button (and shortcut key)
4. the kernel - upper right corner, this one is conda_python3, but you can use many others

### Demo 2
Now we get into the really fun part! I am going to give instructions in english and you get to make it happen with your notebook.

Tip #1: If you are new at this you may get the 'deer in the headlights'. That is a good thing! It is a response that tells you, "oh man, I'm about to learn something!". It says you are out of the comfort zone. When you feel it, take a moment, take a breath, and then learn.

