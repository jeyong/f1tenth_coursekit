.. _doc_lecture03:


Lecture 3 - Rigid Body Transformation
============================================================

**Overview:** 
	실세계에서 point는 관점에 따라 여러가지로 표현할 수 있다. lidar를 차량에 붙이고 장애물을 검출하는데 실제 세상에서 장애물의 position을 알아야 할 수도 있다. 차량이 공간을 돌아다니면서 환경 지도를 생성하는 것은 차량에 탑재된 알고리즘은 실제로 여러 submap을 생성하고 이 submap들을 합쳐서 global 솔루션을 생성하게 된다. 이 2가지 어플리케이션에서 reference frame과 frame transformation을 이해하고 사용할 수 있어야 한다.

**다루는 주제:**
	-	Coordinate Frames 과 Reference Frames
	-	Rigid Body Transformations
	-	Frames and Transformations in ROS

**Slides:**

	.. raw:: html

		<iframe width="700" height="500" src="https://docs.google.com/presentation/d/e/2PACX-1vQQhIoepwcijdxhWZXgYIIaofFuv4sG5oIu0BwYFP3vgEH-a-Iptkzk6ox29FmoHMMBVyuoRsQbi2qQ/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

.. **Video:**

	.. raw:: html

		<iframe width="560" height="315" src="https://www.youtube.com/embed/zkMelEB3-PY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


**추가 자료:**
	- `Robot Modeling and Control <https://www.amazon.com/Robot-Modeling-Control-Mark-Spong/dp/0471649902/ref=sr_1_1?keywords=Robot+Modeling+and+Control&link_code=qs&qid=1583440764&sr=8-1>`_
	- `tf2_ros <http://wiki.ros.org/tf2_ros>`_