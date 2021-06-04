.. _doc_lecture13:


Lecture 13 - Pure Pursuit
===========================

**Overview:** 
	이 강의에서 자율주행 차량의 control stack에 대해서 알아보고 pure pursit 알고리즘을 통해서 path planning하는 방법을 알아보자. 차량은 follow할 waypoint의 순서가 주어지면 이 waypoint들을 따라가기 위해서 path를 plan을 어떻게 할까? particle filter 알고리즘과 비슷하게 pure pursuit은 parameter 튜닝이 필요한데 이것도 이번 강의에서 알아보자.

**Topics Covered:**
	-	Pure pursuit

**Associated Assignment:** 
	* :ref:`Lab 6: Pure Pursuit <doc_lab6>`

**Slides:**

	.. raw:: html

		<iframe width="700" height="500" src="https://docs.google.com/presentation/d/e/2PACX-1vRXFX2P4z6bkkgZmQPL-qDM45kGbfNbCEKsbhMqDrOF4OcvsnO_G6UTk262ouvJLf0IJAvNzzHUIRDj/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

..
	**Video:**

		.. raw:: html

			<iframe width="560" height="315" src="https://www.youtube.com/embed/zkMelEB3-PY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


**관련 주제:**
	- `Implementation of the Pure Pursuit Path Tracking Algorithm  <https://www.ri.cmu.edu/pub_files/pub3/coulter_r_craig_1992_1/coulter_r_craig_1992_1.pdf>`_
	- `Automatic Steering Methods for Autonomous Automobile Path Tracking <https://www.ri.cmu.edu/pub_files/2009/2/Automatic_Steering_Methods_for_Autonomous_Automobile_Path_Tracking.pdf>`_