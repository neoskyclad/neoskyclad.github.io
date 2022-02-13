---
layout: post
title: 유니티 공부 2022.01.29
---

유니티 공부
1.	GameObject
-	상단 탭에 GameObject -> 3D Object -> Cube처럼 3D 물체를 소환할 수 있음.
-	Q W E R 단축키로 조작법을 정하고 마우스로 화면 및 물체 조작 가능
	Q: 드래그 하여 시점 전환, alt 누르면 물체를 중심으로 시점 전환
	W: 드래그 하여 물체의 위치 변경
	E: 드래그 하여 물체 회전
	R: 드래그 하여 물체 길이 변환
-	물체 삭제: Hierarchy에서 눌러서 delete or 그냥 키보드 delete
-	물체 복사: Ctrl + C, Ctrl + V (Hierarchy에 Cube (n) 생김)
-	Hierarchy에서 물체 이름 더블 클릭하면 자세히 볼 수 있음.
2.	Inspector
-	Transform: 위치, 회전, 크기의 X, Y, Z 축이 있으며 움직일 때마다 좌표가 수정됨.
-	Position
	좌표를 수정하여 움직이는 것도 가능
	X, Y, Z를 눌러서 드래그 하여 미세하게 수정 가능
-	Rotation, Scale 모두 Position과 같은 메커니즘으로 수정 가능
3.	Camera
-	유니티에서 게임이란, 물체(GameObject)들로 이루어진 세트장에서 배우(Player)가 보여주는(camera) 시점과 상호작용하는 것.
-	Camera가 보여주는 피라미드 안에서 Game뷰가 펼쳐짐
-	Camera도 다른 게임 오브젝트와 마찬가지로 Position을 변경할 수 있음.
4.	Light
-	Directional Light: 한 곳으로 빛을 조사함.

5.	Component
-	물체가 어떤 역할을 할 수 있게 하는 성질
ex) Main Camera가 카메라로써 기능할 수 있는 것은 component가 Camera이기 때문
-	Component 없애는 법: 톱니 누르고 remove component
-	Component 추가하는 법: Add Component -> 무슨 component있는지 공부하기
-	종류
	Mesh Renderer: 화면에 나타나는 렌더링

6.	Scene
-	모든 gameobject의 목록과 gameobject 각각의 component를 저장
-	저장: File -> Save as… 확장자는 unity

7.	물리엔진
-	RigidBody: component로써 물체에 중력을 가함
-	튀어 오르기
	Project내 Asset에서 Create -> Physics Material 만들기 Bounciness 1로 설정
	그 후 Physics Material을 Hierarchy내 GameObject에 드래그
-	Collider: 충돌체
	충돌이 발생했는지 판단하는 역할을 함
ex) Box collider, Sphere Collider
	바깥에 테두리로 표현됨
	위치와 크기를 설정할 수 있음

