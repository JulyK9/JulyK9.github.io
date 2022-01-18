---
layout: single
title:  "[JS] 2022-01-18"
---

# const, let, var 의 차이와 쓰임

variable (변수): 값을 저장하거나 유지하는 역할

- const (상수) : 바뀌지 않는 값, 계속 유지됨, 한번 설정하면 업데이트 불가
- let : const와 비슷해보이지만, cascade 방식에 따라 업데이트하면 변경됨
- var : const 와 let 구분 없이 예전에 썼던 방식


[정리]
 1. 기본적으로 const를 쓴다.
 2. 필요할 때만 let을 쓴다.
 3. var는 쓰지 않는다.


[예시]

vscode

![image](https://user-images.githubusercontent.com/97942837/149937206-c59610f5-2f5f-4aa1-bad5-cca52566f977.png)


console

![image](https://user-images.githubusercontent.com/97942837/149937328-27c13fa4-716a-4a04-9c4d-ab1dcc2e5460.png)



# Booleans : true, false, null, undefined

[정리]
- ture : 켜짐 1
- false : 꺼짐 0
- null : 비어있음 nothing
- undefined : variable이 메모리에 만들어졌고 인지하고 있지만 값이 없는 것


[예시]

vscode

![image](https://user-images.githubusercontent.com/97942837/149940005-342fe9e5-3676-4856-b889-b7639c2d33cf.png)


console

![image](https://user-images.githubusercontent.com/97942837/149940110-079701b9-90ce-49af-b322-562755d265e8.png)


# Array
 - 값을 리스트로 정리하는 것(살 것들, 할 일들..)
 - 유사한 개념의 범주에 있는 것들을 그룹화시키고 인덱스를 부여해서 자리값을 주는 걸로 보임
 - 대괄호 [ ] 를 사용하고 , 쉼표로 구분
 - 그룹안에 데이터 값을 추가할 수 있음 push
 - array 안에 접근해서 elements를 받아오기 (인덱스는 0부터 시작)
 - 사용자들의 할일 목록을 입력, 추가해서 불러오는 것에 활용할 수 있음


[예시]

vscode

![image](https://user-images.githubusercontent.com/97942837/149954578-3f642ac9-099c-481f-88a4-084e2e9c1058.png)

console

![image](https://user-images.githubusercontent.com/97942837/149954645-74c250e0-a909-4779-81fd-60065a59f64b.png)


# Objects
- 리스트화 해서 정리하기 어려운 것들
- 어떤 객체가 갖고있는 하위범주의 각각의 속성에 따르는 데이터를 정리하는 경우를 생각
- 예) 캐릭터의 이름과 다양한 속성과 능력치들
- 중괄호 { }로 작성, : 로 정의, 쉼표로 속성들 구분
- 속성 추가도 가능


[예시]

vscode

![image](https://user-images.githubusercontent.com/97942837/149960622-167696f0-cf0b-4246-913f-0106e7127041.png)


console

![image](https://user-images.githubusercontent.com/97942837/149960698-546b100b-56d1-4617-bd60-d9415cb92599.png)


※ const 로 정의했는데 값이 업데이트 되는 이유?
  - constant 전체를 하나의 값으로 업데이트 할때 에러가 발생됨
  - constant 안의 무언가를 업데이트 할때는 문제 없음
