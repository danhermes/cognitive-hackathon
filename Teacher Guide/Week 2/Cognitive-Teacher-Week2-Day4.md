# Cognitive Hackathon: Week 1 - Teacher's Guide
## Day 4

Conduct a code walkthrough using Bing Spell Check API as an example to demo how to call the Cognitive Service APIs in Python and interpreting JSON output. Students will work on a related Lab: Spell Check Cognitive Service. Students will copy code into their Azure Notebook from the the Bing Spell Check API only. They needn't have a full understanding of  HTTP calls but need to know how to build data sets for analysis and how to parse and/or interpret resulting JSON.

## Important 

Warn students not to use other services yet due to license constraints. They need to wait until next week. If they do not wait until next week to active other licenses, they may not be able to complete the course project.


## Complete Python Lab

Allow the students to complete their Python Lab and spend some time experimenting with the language. See Azure Notebook: [Introduction to Python]("https://notebooks.azure.com/dan-bcwqcg/projects/teals-cogserv-examples"). This skill is critical to success in this course. These are the tasks in the Python Lab:

* Comments
* Data Types
* Lists
* Control Flow Tools
* Functions
* Classes
* Errors and Exceptions

After the students have completed their Python Lab, conduct a quick code review of Cognitive API.

## Cognitive API - Code Walkthroughs

At the beginning of the week we saw some of the cool things that cognitive computing can do. Then we looked at how to code in Python using Notebooks.

Now let's look at some Python code that implements those cognitive APIs!

### Text Analysis Demo
We'll begin with Text Analysis. Check out the notebook called cogservices_textanalytics in the Azure Notebooks folder with a project called TEALS Cognitive Services Examples. Walk through this code, demonstrating setup and execution of text analysis cognitive API calls. Explain the output. 

### Computer Vision Demo
 Next we'll look at a Computer Vision example. In the same TEALS project there's a notebook called cogservices_vision. Walk through the example, with special focus on API setup, parameters into the API, then the data it returns.

Once Text and Vision examples are explained, it's time to offer the students the fulcrum of this course, the student project.

## Student Project

The student project for the course is central to this curriculum and everything covered in Week 1 leads up to the project that begins in Week 2.  Here is the project high-level requirement: 

How would you change the world using cognitive computing? Think of a real-world application of the concepts we've covered. Imagine a design that will harness computer vision or text analytics to achieve a goal, help people, make money, advance science, entertain, heal, or inspire. Build a simple, working prototype of that idea.

## BONUS

## Compute tier
The Run drop-down list on the project dashboard is where you select the compute tier on which the project runs. By default, projects run on the Free Compute tier, which is limited to 4GB of memory and 1GB of data to prevent abuse:
https://docs.microsoft.com/en-us/azure/notebooks/configure-manage-azure-notebooks-projects