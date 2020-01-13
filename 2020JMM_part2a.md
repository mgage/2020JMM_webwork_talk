
# summative (i.e. graded) presentation of embedded problems 

##### The second problem in the homework set Demo in the course UR102 for student jdoe

<iframe  width="800" height="400" 
			src="https://demo.webwork.rochester.edu/webwork2/UR102/Demo/5?
	&effectiveUser=jdoe&
	&user=jdoe&
	&passwd=jdoe&
	&templateName=simple&">
</iframe>


The grades for this problem will be recorded in jdoe's gradebook for the Demo homeworkset. 

##There is a big problem here.  
jdoe's password is printed right out in the open for all 
to see!!!!!

* That's ok for daemon or anonymous but it's not ok for a regular student in the course.
* We use sessionStorage (a version of cookies) to solve this problem. Before starting the sheet jdoe logs in. 
  
options["userID"]=sessionStorage.getItem("userID");
	    options["course_password"]=sessionStorage.getItem("course_password");
		
<iframe  width="800" height="400" 
			src="https://demo.webwork.rochester.edu/webwork2/UR102/Demo/5?
	&effectiveUser=options["userID"]&
	&user=options["userID"]&
	&passwd=options["course_password"]&
	&templateName=simple&">
</iframe>