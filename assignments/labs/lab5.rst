.. _doc_lab5:


Lab 5 - Scan Matching
======================
.. note:: **그룹** 과제

.. tip:: 이번 실습을 진행하기 전에 :ref:`Lecture 9 <doc_lecture09>` 와 :ref:`Lecture 10 <doc_lecture10>` 에 대해서 알고 있어야 한다.

| **Goals:**
| 이번 실습은 localization에 대해서 다룬다. localization 입문 및 자율주행 stack에서 왜 중요한지를 알 수 있다. 이번 실습에서 가장 기본이 되는 localization 알고리즘 중에 하나인 *scan matching* 을 구현한다. 수업에서 배운 *Iterative Closest Point* 알고리즘을 사용한다. `Andre Censi PLICP paper <https://censi.science/pub/research/2008-icra-plicp.pdf>`_ 를 참고한다. 실습 마지막에는 주어진 환경에서 robot의 localization에 대한 전문적인 지식을 얻고 path planning과 trajectory tracking의 중요성을 알게된다.

| **학습 결과:**
| 이번 실습을 통해 다음과 같은 기본을 익히게 된다.:

	* Localization
	* Odometry Estimation
	* Convex optimization
	* C++ OOP
	* Quadratic Programming

**요구 기술:** ROS, Python/C++

**할당 시간:** 1 week

| **Repository:** `Github Repository <https://github.com/f1tenth/f1tenth_labs/tree/master/lab5>`_ 
|	이 repo에는 skeleton 코드와 latex source 파일을 포함하고 있다. latex 소스 파일을 컴파일해서 최신 내용을 확인하자.

.. raw:: html

	<iframe width="700" height="800" src="https://drive.google.com/file/d/1g27WUTeoxrznFozfY0Vj45V1evVw1uTA/preview" width="640" height="480"></iframe>