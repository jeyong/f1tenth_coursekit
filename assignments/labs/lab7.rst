.. _doc_lab7:


Lab 7 - Motion Planning (RRT)
=================================

.. tip:: Before starting this lab, review :ref:`Lecture 14 <doc_lecture14>` to ensure you are familiar with the material.

| **Goals:**
| 이번 실습에서는 레이싱 트렉에서 직접 레이싱을 하는데 필요한 도구를 제공한다. 이번 실습을 마치면 `this <https://www.youtube.com/watch?v=llHCRqwIllM>`_ 처럼 할 수 있다.

| **학습 결과물:**
| 이번 실습을 통해 다음과 같은 기본을 익히게 된다.:

	* Motion Planning 기본 개념

		* Configuration space vs. Workspace: configuration space와 workspace의 차이점을 이해해야만 한다. 그리고 각 planning의 장단점을 알아야만 한다.
		* Free space vs. Obstacle space: free space와 obstacle space의 차이점을 이해해야만 한다.
		* Occupancy grids 와 Costmaps: occupancy grids와 costmaps를 이해해야만 하고 사용 방법과 생성방법을 이해해야만 한다.

	* Motion Planning 알고리즘. 다음 planning 알고리즘들의 장단점 그리고 사용 방법에 대해서 알아야만 한다.

		* Grid-based search: Dijkstra’s, A*, 그리고 변형들
		* Sampling based algorithms: RRT과 그 변형들

**요구 기술:** ROS, Python/C++

**할당 시간:** 1.5 week

| **Repository:** `Github Repository <https://github.com/f1tenth/f1tenth_labs/tree/master/lab7>`_ 
|	이 repo에는 skeleton 코드와 latex source 파일을 포함하고 있다. latex 소스 파일을 컴파일해서 최신 내용을 확인하자.

.. raw:: html

	<iframe width="700" height="800" src="https://drive.google.com/file/d/1WhMGMSgIPCnXqsFap2ZtlTrTeKXJj1vZ/preview" width="640" height="480"></iframe>