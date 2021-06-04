.. _doc_lecture09:


Lecture 9 - Scan Matching I
=============================================

**Overview:** 
	이 장은 3개 localization 강의 중에 하나다. 환경에 따라서 robot의 state를 결정하는 방법에 대해서 배워보자. 차량은 lidar를 이용해서 localize에 필요한 거리를 측정한다. iterative closest point 알고리즘과 fast correspondence search에 대해서 설명한다. 마지막 장은 Lab 5의 개요이다.

**다루는 주제:**
	-	Localization/SLAM
	- 	Scan Matching
	-	Iterative Closest Point
	-	Fast Correspondence Search

**과제:** 
	* :ref:`Lab 5: Scan Matching <doc_lab5>`

**Slides:**

	.. raw:: html

		<iframe width="700" height="500" src="https://docs.google.com/presentation/d/e/2PACX-1vSu7weo-N89tdp-ApB13l_BEOGb9iWAuqNhsKZmTtBMCqEG54dBn15EY00qAftRRfGeWm9dIqgi-J3a/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

.. 
	**Video:**

		.. raw:: html

			<iframe width="560" height="315" src="https://www.youtube.com/embed/zkMelEB3-PY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

**추가 자료:**
	- `An ICP variant using a point-to-line metric <https://censi.science/pub/research/2008-icra-plicp.pdf>`_
	- `Convex Optimization course <https://see.stanford.edu/Course/EE364A>`_