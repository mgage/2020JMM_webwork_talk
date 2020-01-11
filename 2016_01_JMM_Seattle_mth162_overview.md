# Math 162, Second semester Calculus

Here are some remarks on the topics we will cover this semester with examples 
of the kinds of homework questions we'll ask you to work on in each homework set.



## Review: 0. Fundamental theorem of Calculus, Integration by Substitution, Indefinite integration

<iframe  width="800" height="600" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/FortLewis/Calc1/06-01-Antiderivatives-graphically/AF1/AF1.pg&
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

Play with the Geogebra applet above to get a feeling for the relationship between $f$, the height
of the upper boundary of the region at $x$, and $F$, the area of the region to the left of $x$.

$f$ is the derivative of $F$ and $F$ is an anti-derivative of $f$. A visual image of this 
relationship is useful.  (Why did I write **an** antiderivative?)

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

<iframe  width="800" height="400" 
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

## 1.  **Topics**: , Areas Between Curves

<iframe  width="800" height="600" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/Rochester/setIntegrals19Area/ns6_1_1.pg&
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

The example above is simple  once you draw the picture! We'll see how
this can be reduced to integrating $f(x)-g(x)$. To make this visually
obvious imagine that the region is composed of vertical tooth picks and
then slide them so their butts all rest on the $x$-axis. The tooth picks
haven't changed length or thickness so the area hasn't changed either.
(look up [Cavalieri](https://en.wikipedia.org/wiki/Bonaventura_Cavalieri) and his principle !)

## 2.  **Topics**: Volumes, Work 
<iframe  width="800" height="600" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/Rochester/setIntegrals20Volume/osu_in_20_2/osu_in_20_2.pg&
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

Visualizing and describing the region whose area or volume you want to find is often the hardest part of the problem.  You'll get lots of practice visualizing as with the example above and the one below.

<iframe  width="800" height="600" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/UMN/calculusStewartCCC/s_6_3_6.pg&
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

This problem is harder (at first). You first have to visualize the region, then understand the volume of each of the thin vertical cylinders it's made up of, (cylinders are what you get if you rotate vertical toothpicks around the $y$ axis), and then add these 
volumes together (the Riemann sum).

The Riemann integral is simply the 'one and only' value (mathematicians say 'unique' value) you get when the toothpicks are thin enough.  BUT the integral has the enormous advantage that you can calculate it using anti-derivatives instead of doing lots and lots of addition of volumes.

## 3.  **Topics**: Integration by Parts, Trig Integrals 
In some ways this section is more technical -- a bunch of challenges, like solving cross-word puzzles -- some people find this really fun.  
As an analyst and a geometer I can tell you that integration by parts also has REALLY important theoretical uses as well. 
I can't explain the theoretical importance to you yet however, maybe next semester if we get to Stoke's theorem in multivariable calculus. :-)

## 4.   **Topics**: Trig Substitution, Partial Fractions 
More technical challenges. For me, when I took calculus, these challenges were one of the most fun parts of the course. 

But I have admit, particularly now-a-days, that Mathematica or Maple or Sage (or you guys) can solve these faster than I can. 

These challenges do illustrate one larger concept however.  These antidifferentiation techniques are the simplest example of **Inverse Problems**. We can differentiate most functions $F$ mechanically --it's much harder to do the reverse -- to guess the function $F$ given the function $f$  (and then check your guess by differentiating $F$). And yes guessing (then checking) plays a **big** role in Inverse Problems.

"Integration techniques" are just advanced, efficient methods of guessing of anti-derivatives.  (And usually it is worth your while to validate your answer by  differentiating.

Another inverse problem is solving differential equations, and inverse problems just get more and more interesting from there.  

Given the shape of a drum one can calculate what it will sound like relatively easily.  If you hear  a drum can you predict its shape from the sound alone? Well??   What do you think?

## 5  **Topics**: Improper Integrals, Arc Length 

These two topics don't fit together that well.  We'll talk about about improper integrals more later.  The arc length problem is simply calculating the length of a rope when it is not straight.  You do it by approximating by straight lines and then adding everything up of course.  Here is an example.

## 6.  **Topics**: Surface Area, Curves defined by parametric equations

## 7.   **Topics**: Calculus of parametric curves
This is the beginning of a topic which is really important to physicists and engineers -- how to describe things that don't go in straight lines. It's also important for video game designers (oh yes and mathematicians like them as well.)  Here is a sample problem -- don't try to calculate the area yet just see why the formula makes sense. (You can try visualizing as the sum of two vectors that change with time.)

<iframe  width="800" height="400" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
    &sourceFilePath=Library/UCSB/Stewart5_10_2/Stewart5_10_2_74/Stewart5_10_2_74.pg&
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

## 8.  **Topics**: Polar coordinates: Areas and lengths, Sequences 
Physicists and differential geometers have a magic weapon. They  choose the right coordinate system to describe the problem. If you get the coordinate system right the problem becomes much simpler.  Here is an example.
<iframe  width="800" height="400" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/WHFreeman/Rogawski_Calculus_Early_Transcendentals_Second_Edition/11_Parametric_Equations_Polar_Coordinates_and_Conic_Sections/11.4_Area_and_Arc_Length_in_Polar_Coordinates/11.4.9.pg&
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
## 9  **Topics**: Series, Integral test
Now we get to series. A topic that most students think is impossible at first and then up wondering what they thought was so hard about it. The hidden trick here -- which is not immediately apparent from the cookbook methods -- is the art of approximation -- finding inequalities that give you useful information.
This is not widely taught in high schools but its a very creative and interesting skill to acquire -- usually through lots of practice.  The squeeze principle which you used in the first semester to find limits is an example of this type of thinking. Here is an example of a series question.


Below is an example (one from the power series chapter) where you can glimpse it's importance.  A power series defines a function which is  just a **really** long polynomial. If the first 10 decimal points of $f$
are completely determined by say the first 20 terms of the series then in that case you might as well just deal with the polynomial, which you understand concretely (and computers can calculate with). "Functions are just long polynomials." This isn't strictly true but it's 90% true and thinking this way gets you started in the right direction. 

To get started solving the problem below just plug in some values. You can use the convention that $0^0=1$ --it's defined that way because it makes these sigma summation formulas easy to write.

Don't be worried by the sigma notation -- get someone to show you how to write it out in long string ... or look it up on the web. 
<iframe  width="800" height="400" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/ma123DB/set12/s11_9_10.pg&
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
## 10  **Topics**: Comparison tests, Alternating series
Positive series (where each term is positive) have two choices. Each term is like a derivative (the speed) and the sum is how far you have traveled.  Since the speed is positive either you travel all the way to infinity along the $x$ axis or you travel up to some finite bound (Think $1/2 + 1/4 +1/8 +...$ can you ever get beyond $1$ when each term is slowing down that fast?  Once you realize this, the trick is to find a known series that goes only a finite distance but is larger than your series (which proves your series converges) or find a known series that is smaller and travels off to infinity, pushing your series ahead of it.  Everything else is just details of finding one or the other of these known series.

## 11  **Topics**: Ratio and Root tests, Absolute convergence

These are the details -- we'll talk about them when the time comes.
## 12  **Topics**: Power series 

More details -- specialized for power series "really long polynomials". 

## 13  **Topics**: Representation of functions as power series, Taylor series
As I said above there is a sense in which every reasonable function is just a long polynomials. Talyor series come at the end of this course but they are the foundation of most applications and a lot of theory.  Just ask anyone taking MTH280 (numerical analysis) or MTH285(applied mathematics) or MTH282 (Complex analysis).  They model reality, they solve differential equations. Of course there are a few functions which are much weirder and don't behave much like long polynomials and mathematicians (and some physicists) get excited about understanding those if for no other reason that they are a challenge to figure out. 
##   **Topics**: Application of power series
Power series are very useful.  Here is an example.
<iframe  width="800" height="400" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/Union/setSeriesTaylor/ur_sr_9_6.pg&
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

## For the JMM presentation

Here is the magic code for embedding these problems.
```
&lt; iframe  width="800" height="400" 
src="https://demo.webwork.rochester.edu/webwork2/html2xml?
	&answersSubmitted=0&
	&sourceFilePath=Library/Union/setSeriesTaylor/ur_sr_9_6.pg&
	&problemSeed=123567&
	&courseID=daemon_course&
	&userID=daemon&
	&course_password=daemon&
	&showSummary=1&
	&displayMode=MathJax&
	&problemIdentifierPrefix=102&
	&language=en&
	&outputformat=sticky">
&lt; /iframe>
```