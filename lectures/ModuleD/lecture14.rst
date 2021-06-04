.. _doc_lecture14:


Lecture 14 - Rapidly-exploring Random Tree (RRT)
====================================================

**Overview:** 
	이번 강의에서는 좀더 복잡한 path planning 알고리즘에 대해서 알아보자. 차량의 현재 위치에서 desired goal position까지의 path를 planning할때 장애물 회피를 고려한다. best first search, A*, Dijkstra와 같은 다양한 graph/tree 알고리즘에 대해서 배워보자.

**Topics Covered:**
	-	Occupancy grids
	-	RRT
	-	Search algorithms
	-	A*, Dijkstra's, BFS

**과제:** 
	* :ref:`Lab 7: Motion Planning (RRT) <doc_lab7>`

**Slides:**

	.. raw:: html

		<iframe width="700" height="500" src="https://docs.google.com/presentation/d/e/2PACX-1vSh6oTk6DFZYlWyHT8Rks-X9PFzirVznPZY5ZQM9VL1EqBhunePWQyEMSJlAWaHub1Ck4RfX_MIO6sW/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="629" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

..
	**Video:**

		.. raw:: html

			<iframe width="560" height="315" src="https://www.youtube.com/embed/zkMelEB3-PY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


**관련주제:**
	- `Sampling-based Algorithms for Optimal Motion Planning <https://arxiv.org/pdf/1105.1186.pdf>`_
		- Sections 3.1 and 3.2, and Algorithms 3, 3.3, and 6