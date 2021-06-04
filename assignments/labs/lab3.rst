.. _doc_lab3:


Lab 3 - Wall Following
=======================

.. tip:: 이번 실습을 진행하기 전에, :ref:`Lecture 4 <doc_lecture04>` 을 보고 관련 자료에 익숙해져야 한다.

| **목표:**
| 이번 실습에서 PID 제어기를 구현해서 고정 거리로 복도의 벽에 평형해서 차량을 운행한다. Hokuyo LiDAR로 laser scan 거리 수집, 필요한 조향 각도, 속도(drive 파라미터)를 계산항 이를 VESC에 publish하여 차량을 운행한다.

| **학습 결과물:**
| 다음 기본 내용들은 이 학습을 완료하기 위해서 이해가 필요하다.:

	* PID 제어기
	* 벽을 따라 자동을 차량 운행

**필요 기술:** ROS, Python/C++

**할당 시간:** 1 Week

| **Repository:** `Github Repository <https://github.com/f1tenth/f1tenth_labs/tree/master/lab3>`_ 
|	이 repo에는 skeleton 코드와 latex source 파일을 포함하고 있다. latex 소스 파일을 컴파일해서 최신 내용을 확인하자.

.. raw:: html

	<iframe width="700" height="800" src="https://drive.google.com/file/d/1tzyfGYq3JjvLlYHIiSTyvoNq4kcPf53n/preview" width="640" height="480"></iframe>
