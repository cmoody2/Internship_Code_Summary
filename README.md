# **Python Live Project**



## **Introduction**

During the last two weeks of my studies at the Tech Academy, I worked with my peers to develop an interactive website for managing one's collections of things related to various hobbies using the Django framework. I chose to create an application based on a personal hobby, mechanical keyboards. The app would keep track of user builds as well as give general information about keyboards and keyboard related resources. 


## **CRUD Functionality**

The beginning stories of this sprint revolved around creating our basic app and applying CRUD functionality. I started by setting up the basic elements of the project such as a base, homepage, navigation, and footer templates and mapping their corresponding URLs to their function-based views. During this step I also created the necessary URL routing for my homepage template and used template inheritance to connect all of my templates.

* **Create**
    
    To fullfill create functionality I set up a model that included fields for all of the necessary parts to a keyboard build as well as user specific information. This allowed me to make use of the different field types Django offers such as CharField, TextField, EmailField and the DateTimeField. With the keyboard specific fields, I utilized the Choices attribute to provide an extensive list of pre-entered choices. 


	![Model Fields](/images/Model_Fields.png)


    I then moved on to creating a form template and used the Django Model Form module to connect the two. The baked in form 
	validation made this task easier and faster to complete.
	

	![ModelForm](/images/story-2_model_form.png)


	![Model View Function](/images/story2_view-function.png)


* **Read**

	My next two stories involved adding an index table to display all objects within the database. To display individual details about each item, I added anchor tags for each cell withing an items row. I was also able to add search functionality and pagination for my index table.
	
	
	![Index and Search Views](/images/story3_search_index_views.png)


* **Update and Delete**

	To implement update functionality, I utilized my previous form template with a few small changes. Both update and delete has their own functions as well as a function for delete confirmation.
	
	
	![Index and Search Views](/images/story3_edit_delete_views.png)
	
	
## **Web Scraping**

With the following user stories, we were tasked with utilizing BeautifulSoup to scrape a web page for relevant information. I chose a well-known vendor within the keyboard community called KDBfans. Specifically, I scraped their group buy page for the latest products and displayed them as a 'Vendor Spotlight' on my application. My rationale behind this was that each month we could focus on different vendors within the community showcasing their offerings. This was a great exercise of understanding of how to navigate the data structure of this website and parsing through the html I decided to use.


![Index and Search Views](/images/story6-7_webscraping.png)


## **Front End Development**

I chose to use Bootstrap for front end work as it is a fairly robust and easy to use HTML and CSS framework. The color palette I worked with revolved around different greys, reds, black and white. I used paint 3d to create a fairly simple background to fill out the space of the page and Bootstrap components for most of the page elements.


![Index and Search Views](/images/website_home_page.png)
*App Homepage*

![Index and Search Views](/images/vendor_spotlight.png)
*Vendor Spotlight*

![Index and Search Views](/images/my_builds.png)
*Keyboard Build Index*


## **Skills Acquired**


* Working with Microsoft Azure Devops
* Working within an Agile environment
* Utilizing PyCharm as a powerful IDE
* Working with Django as a web development framework
* Using the console and PyCharm terminal
* Utilizing version control, specifically Git. Towards the beginning I had trouble understanding the correct way to use version 
control but with the help of the project leads I learned how to make proper pull requests and resolve merge conflicts correctly
* How to participate in sprint planning, daily standups and code retrospective meetings. These were very informative and useful 
for getting quick answers to roadblocks that surfaced the day prior and also to keep everyone accountable for the tasks we were 
assigned. This also allowed each of use to learn from each other's roadblocks without having to experience them ourselves
* The importance of using a virtual environment for each project worked on. Virtual environments allowed us to all be on the 
same version of the software we used and relief from disrupting the configurations we had on our systems prior to the project
* Working with the python Pip package management system
* A deeper understanding of the Bootstrap framework
* Importance of Debugging and what to look for, especially before submitting a pull request that could unnecessarily waste time 
for the project leads
* How to effectively communicate with my peers and project leads
* Knowing when to reach out for assistance if hitting a wall. I handle this fairly well but there is room for improvement as I 
felt there were some moments where my search for a solution was becoming counterproductive and I should have reached out sooner 
to save valuable time
* Utilizing all available resources to find a solution to a problem, particularly reviewing my peers code who may have already 
found a solution to a problem I was currently facing.


## **Closing Thoughts**


I am extremely grateful for the experiences I had during this sprint and I'm very proud of what I was able to accomplish. There were moments of frustration with getting my code to work, moments of relief when figuring out a problem, and moments of celebration when completing a task; All of which were invaluable learning lessons. I requested to pull my code from the codebase to work on this project myself following this sprint. I would like to bring this to a live state someday as there is nothing quite like it in the keyboarding community to my knowledge. This project was a true pleasure to work on and the skills I've acquired will be extremely useful to whichever project I am tasked with in the future.
