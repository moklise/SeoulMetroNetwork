####Seoul Subway Network###
본 저장소는 서울-수도권 지하철의 binary interaction으로 구성된 네트워크 제작을 위하여 만들어졌습니다

_ _ _

###Lines###
본 저장소는 다음과 같이 구성되어 있습니다.

| Folder Name | Line|
|--------|--------|
|  Line 1  |  1호선   |
|  Line 2  |  2호선   |
|  Line 3  |  3호선   |
|  Line 4  |  4호선   |
|  Line 5  |  5호선   |
|  Line 6  |  6호선   |
|  Line 7  |  7호선   |
|  Line 8  |  8호선   |
|  Line 9  |  9호선   |
|  Line Bundang  |  분당선   |
|  Line NewBundang  |  신분당선   |
|  Line Ever |  에버라인   |
|  Line_IC_1  |  인천 1호선   |
|  Line_IC_2  |  인천 2호선   |
|  Line_IC_A  |  공항철도   |
|  Line_KC  |  경춘선  |
|  Line_KK  |  경강선   |
|  Line_KU  |  경의선   |
|  Line_Maglev  |  인천 자기부상철도   |
|  Line_SI  |  수인선   |
|  Line_U  |  의정부 경전철   |

- - -
###Line's Files###

모든 노선는 두가지 파일로 구성되어있습니다.

| File Name | Content |
|--------|--------|
|  Station_ID.txt  |  역 이름과 고유식별번호   |
|  Interaction.txt  |  역 간의 인터렉션   |

- - -
###Interaction###
인터렉션의 구분자는 ```\t```를 사용하며, 각 인터렉션은 방향성과 가중치는 부여되지 않았고, 오직 연결의 여부를 나타냅니다.

**역 이름과 고유식별번호**는 다음과 같이 표기됩니다.

```역_고유식별번호\t역이름```

**역 간의 인터렉션**은 다음과 같이 표기됩니다.

`역1_고유식별번호\t역2_고유식별번호`


업데이트 17.01.18
_ _ _

일부 가중치 임시 추가 (100m 단위)
업데이트 17.01.19