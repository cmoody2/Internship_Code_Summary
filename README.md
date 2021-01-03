# **Python Live Project**



## **Introduction**

During the last two weeks of my studies at the Tech Academy, I worked with my peers to develop a interactive website for managing one's collections of things related to various hobbies using the Django framework. I chose to create an application based on a personal hobby, mechanical keyboards. The app would keep track of user builds as well as give general information about keyboards and keyboard related resources. 


## **CRUD Functionality**

The beginning stories of this sprint revolved around creating our basic app and applying CRUD functionality. I started by setting up the basic elements of the project such as a base, homepage, navigation, and footer templates and mapping their corresponding URLs to their function-based views. During this step I also created the necessary URL routing for my hompage template and used Template inheritance to connect all of my templates.

* **Create**
    
    To fuflfill create functionality I set up a model that included fields for all of the necessary parts to a keyboard build as well as other user specific information. This allowed me to make use of the different field types django offers such as CharField, TextField, EmailField and the DateTimeField. With the keyboard specific fields, I utilized the Choices attribute to provide a extensive list of pre-entered choices. 


	![Model Fields](/images/Model_Fields.png)


    I then moved on to creating a form template and used the django ModelForm module to connect the two. The baked in form 
	validation was very useful during this task.
	

	![ModelForm](/images/story-2_model_form.png)


	![Model View Function](/images/story2_view-function.png)


* **Read**

	My next two stories involved adding a index table to display all objects within my database. To display individual details about each item, I added anchor tags for each cell withing an items row. I was also able to add search functionality and pagination for my index table.
	
	
	![Index and Search Views](/images/story3_search_index_views.png)


* **Update and Delete**

	To add update functionality I utilized my previous form template with a few small changes. Both update and delete has their own functions as well as a function for delete confirmation.
	
	
	![Index and Search Views](/images/story3_edit_delete_views.png)
