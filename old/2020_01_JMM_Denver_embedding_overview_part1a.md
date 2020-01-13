### Modulo some cosmetic tweaks you can use any webwork site (webwork-2.13 or higher) to render these problems IF it has a course named "daemon_course" with a user "daemon" with privileges greater than a student. 


#Examples of formative use of embedded problems. 

<hr/>

rendered by daemon_course

<iframe  width="800" height="400" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/Union/setIntFTC/sc5_4_13.pg&
	&problemSeed=123567&
	&courseID=daemon_course&
	&userID=daemon&
	&course_password=daemon&
	&showSummary=1&
	&displayMode=MathJax&
	&problemIdentifierPrefix=102&
	&language=en&
	&outputformat=sticky">
</iframe>

rendered by gage_course

<iframe  width="800" height="400" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/Union/setIntFTC/sc5_4_13.pg&
	&problemSeed=123567&
	&courseID=gage_course&
	&userID=daemon&
	&course_password=daemon&
	&showSummary=1&
	&displayMode=MathJax&
	&problemIdentifierPrefix=102&
	&language=en&
	&outputformat=sticky">
</iframe>


<hr/>
### same problem rendered on two different sites
##### rendered on demo.webwork.rochester.edu
<iframe  width="800" height="300" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/ma122DB/set12/s5_4_14.pg&
	&problemSeed=123567&
	&courseID=daemon_course&
	&userID=daemon&
	&course_password=daemon&
	&showSummary=1&
	&displayMode=MathJax&
	&problemIdentifierPrefix=102&
	&language=en&
	&outputformat=sticky">
</iframe>

##### rendered on webwork-ptx.aimath.org

* Notice that ptx uses "anonymous" instead of "daemon"

<iframe  width="800" height="300" 
src="https://webwork-ptx.aimath.org/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/ma122DB/set12/s5_4_14.pg&
	&problemSeed=123567&
	&courseID=anonymous&
	&userID=anonymous&
	&course_password=anonymous&
	&showSummary=1&
	&displayMode=MathJax&
	&problemIdentifierPrefix=102&
	&language=en&
	&outputformat=sticky">
</iframe>

<hr/>
