# **Python Live Project**



## **Introduction**

During the last two weeks of my studies at the Tech Academy, I worked with my peers to develop a interactive website for managing one's collections of things related to various hobbies using the Django framework. I chose to create an application based on a personal hobby, mechanical keyboards. The app would keep track of user builds as well as give general information about keyboards and keyboard related resources. 


## **CRUD Functionality**

The beginning stories of this sprint revolved around creating our basic app and applying CRUD functionality. I started by setting up the basic elements of the project such as a base, homepage, navigation, and footer templates and mapping their corresponding URLs to their function-based views. During this step I also created the necessary URL routing for my hompage template and used Template inheritance to connect all of my templates.

* **Create**
    
    To fuflfill create functionality I set up a model that included fields for all of the necessary parts to a keyboard build as well as other user specific information. This allowed me to make use of the different field types django offers such as CharField, TextField, EmailField and the DateTimeField. With the keyboard specific fields, I utilized the Choices attribute to provide a extensive list of pre-entered choices. 

