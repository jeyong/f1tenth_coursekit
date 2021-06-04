.. _doc_lab8:


Lab 8 - Perception 과 Planning
=================================

.. tip:: 이번 실습을 진행하기 전에  :ref:`Lecture 17 <doc_lecture17>` 과 :ref:`Lecture 18 <doc_lecture18>` 에 대해서 알아야 한다.

| **Goals:**
| 레이싱 경기의 특징은 단일 트랙을 여러 차량이 동시에 경쟁하면서 달리는 것이다. 다른 차량이 있는 상태로 안전하게 추월하고 네비게이션하는 것이 가장 중요하다. 다른 차량의 전략에 대해서 미리 알 수 없기 때문에 다른 차량의 제약을 확률에 기반하여 반응해야한다. 이번 실습의 목표는 다른 차량의 pose를 추적하고 예상하는 것이다.

| **학습 결과:**
| 이번 실습을 통해 다음과 같은 기본을 익히게 된다.:
	
	* Vision 과 Perception
		
		* *Camera model 과 parameters:* 실제 카메라 모델과 핀홀 카메라 모델이 어떤 관계가 있는지 어떻게 앞뒤로 이동할때 어떻게 되는지 이해해야만 한다.
		* *Transformations:* 3차원 transformation과 transformation의 표현을 알아야 한다.
		* *Single View Geometry:* single view geometry와 동작을 이해해야만 한다. world coordinate frame point를 camera coordinate frame point로 변환하는 방법을 알아야 한다.
		* *Homography:* homography처리 및 world 좌표가 주어지면 카메라의 pose를 계산하는데 어떻게 사용하는지 알아야 한다.

	* 프로그래밍 기술

		* ROS에서 image 처리
		* tf를 사용한 transformation과 AprilTags와 유사한 library의 구현
		* ROS에서 nodelets 구현과 장점

**필요한 기술:** ROS, Python/C++

**할당된 시간:** 1 week

| **Repository:** `Github Repository <https://github.com/f1tenth/f1tenth_labs/tree/master/lab8/latex>`_ 
|	이 repo에는 skeleton 코드와 latex source 파일을 포함하고 있다. latex 소스 파일을 컴파일해서 최신 내용을 확인하자.

.. raw:: html

	<iframe width="700" height="800" src="https://drive.google.com/file/d/1hdSzR9inLNZMwRetuXCdFf70WNbzry-B/preview" width="640" height="480"></iframe>
