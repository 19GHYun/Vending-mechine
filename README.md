# Vending-mechine

## Vending-mechine 1
![20194546_Vending_Mechine1](https://user-images.githubusercontent.com/94778099/145588284-4f7e0691-1396-41f7-9bce-6eef5b2bd05d.png)

상태 = idle / F / H / HF

각각 0원 / 50원 / 100원 / 150원 이상 을 뜻함.

FC 와 HC는 각각 50원, 100원이 투입 되었을 때를 뜻함.



## Vending_mechine 2 ~ 5
[20194546_Vending_Mechine2~5.xlsx](https://github.com/19GHYun/Vending-mechine/files/7693331/20194546_Vending_Mechine2.5.xlsx)

### 2~4

현재 상태가 0원, 50원, 100원, 150원 일때 각각 00 / 01 / 10 / 11 로 하였음.

입력 50원과 100원은 각각 0과 1로 하였음.


### 5

그렇게 만들어진 표를 이용하여 회로를 설계.
(제대로 못 만든 것 같습니다.)


## 6~7
[FSM.docx](https://github.com/19GHYun/Vending-mechine/files/7693366/FSM.docx)

[FSMSpec.docx](https://github.com/19GHYun/Vending-mechine/files/7693367/FSMSpec.docx)

위에서부터 FSM 파일(6번) FSM 테스트 파일(7번) 입니다.

FSM 파일 같은 경우엔, 상태 변화를 일으키는 FC 와 HC, 그리고 현재 상태인 idle, f, h, hf를 사용 하였습니다.

그리고 새로 추가된 출력값 y를 추가 하였습니다.


FSM 테스트 파일 7번은 수정을 해 보았으나, 테스트를 통과하지 못 했습니다.

제가 잘 안된 부분은, 테스트를 할때 y이 맞는지 출력하는 부분인 것 같습니다.


***

보고서를 이렇게 github에서 작성하여 제출해도 되는지 사전에 허락 안받은 점 죄송합니다.

commit 시간과 제출하면서 보고서 내용 pdf 파일로 추가로 제출 하겠습니다.
