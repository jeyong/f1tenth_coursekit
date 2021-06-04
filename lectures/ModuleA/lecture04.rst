.. _doc_lecture04:


Lecture 4 - Laplace Domain Dynamics & PID
===========================================
**Overview:** 
	vesc에 PID 제어 명령을 내리며 rpm 명령을 모터의 전류 출력으로 변환한다.(rpm -> 전류 -> 모터 제어) 명령으로 준 RPM에 대한 제대로된 전류 값을 얻기 위해서 pid를 사용한다.


1) vesc 튜닝
2) 벽 따라가기 (error는 벽까지의 거리(left 이나 right), 운전ㄷ 각도 제어) - lec

**Topics Covered:**
	-	Laplace Domain Dynamics
	-	PID Control
	-	testing

**관련 숙제:** 
	* :ref:`Lab 3: Wall Following <doc_lab3>`

**Slides:**

	.. raw:: html

		<iframe src="https://drive.google.com/file/d/1xQstTDhlttfc6icNHQ-VMswfhuGPDl_m/preview" width="640" height="480"></iframe>

.. **Video:**

	.. raw:: html

		<iframe width="560" height="315" src="https://www.youtube.com/embed/zkMelEB3-PY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


**추가 자료:**
	- `Ziegler-Nichols method of tuning a PID controller <https://en.wikipedia.org/wiki/Ziegler%E2%80%93Nichols_method>`_
