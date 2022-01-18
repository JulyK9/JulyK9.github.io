---
layout: post
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



# true, false, null, undefined

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
