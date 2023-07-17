# prac20230717
### 9. 글자 강조
일반 **굵은 글씨**
이텔릭체 *이텔릭*

### 8. 이미지 넣기
![cat]https://github.com/wjyhello/prac20230717/blob/main/cat.jpg

### 7. 하이퍼링크
[PCWK]https://cafe.daum.net/pcwk


### 6. 가로선
화면 전체를 가로지르는 가로선 : -,*을 3개 이상

---
***
---

### 5. 목록
#### 하위 목록
1.아이템1  
2.아이템2  
  1. 1단계 하위 아이템  
    1. 2단계 하위 아이템  


#### 순서 없는 목록
* 목록이름
- 목록이름
+ 몰골이름

#### 순서 있는 목록
1. 목록이름
1. 몰록이름
1. 목록이름

### 4. 코드블럭
```Python
from random import *

def main():
    totalCnt = 0
    for passenger in range(1,51):#1<=x<51
        #print(passenger)
        time_taken = randint(5,50)#5<=x<=50
        #print(time_taken)
        if 5 <= time_taken <=15:#5<=time_taken&&time_taken<=15
            print('[{0}]{1}번째 손님(소요시간 : {2}분'.format(0,passenger,time_taken))
            totalCnt+=1
        else:
            print('[{0}]{1}번째 손님(소요시간 : {2}분'.format('',passenger,time_taken))

    print("총 탑승객:{0}".format(totalCnt))

main()
```

### 3.인용상자
>여기에 인용할 내용을 넣으면 됩니다.
>빈 줄이 없으면 자동으로 인용 상자에 포함 됩니다.
식사 맛나게 하셨나요?

인용이 끝났습니다.
### 2.헤더
'''#을 1개부터 6개까지 6단계로 사용할 수 있습니다.'''

#Java
##Html
###CSS
####Javascript
#####Spring
######Python

### 1. 문단 구분을 위한 개행
여름 공원을 걸어 보아요.  
(개행: space 2개 느르면 가능)
여름을 만끽 하세요.
