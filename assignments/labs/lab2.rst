.. _doc_lab2:


Lab 2 - 자동 긴급 제동(Automatic Emergency Braking)
======================================
.. tip:: 이번 실습을 시작하기 전에, :ref:`Lecture 2 <doc_lecture02>` 를 보고 관련 자료를 숙지하자.

| **목표:**
| 이번 실습의 목표는 레이싱 카를 위한 안전기능 node를 개발하는 것이다. 이 기능은 빠른 속도로 주행할때 충돌할꺼 같으면 차량을 멈추는 것이다. 시뮬레이터에서 LaserScan 메시지를 사용해서 Collision에 대한 time을 구현하는 것이다.

| **학습 결과:**
| 다음 기본들은 이 실습을 완료하기 위해서 이해해야만 하는 것들이다.:

	* ROS에서 LaserScan 메시지 사용하기
	* Time to Collision (TTC)
	* Safety critical systems

**요구 기술:** Lab 1에서 ROS 기본, Python 혹은 C++ (프로그래밍 경험)

**할당 시간:** 1 week

| **Repository:** `Github Repository <https://github.com/f1tenth/f1tenth_labs/tree/master/lab2>`_ 
|	이 repo에는 skeleton 코드와 latex source 파일을 포함하고 있다. latex 소스 파일을 컴파일해서 최신 내용을 확인하자.


.. raw:: html

	<iframe width="700" height="800" src="https://drive.google.com/file/d/1qBCmMB54XrRZbU_A8IiBSO6TwAILfUO8/preview" width="640" height="480"></iframe>
