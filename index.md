# 프로젝트명: 운도 실력이다

>[ 목차 ]
### 1. [컨셉](#컨셉)
### 2. [관련 이미지와 동영상](#관련-이미지--동영상)
### 3. [대표 이미지 그리고 컨셉과 대표이미지 기반 작품 묘사](#대표-이미지)
### 4. [구성 요소](#구성-요소)
   - [메커니즘](#1-메커니즘)
   - [이야기](#2-이야기)
   - [미적요소](#3-미적요소)
   - [기술](#4-기술)

### 5. [구성 요소 분석](#구성-요소-분석)
   - [게임 오브젝트 분해](#1-게임-오브젝트-분해)
   - [파라미터(속성) 뽑아 보기](#2-파라미터속성-뽑아-보기)
   - [행동 뽑아 보기](#3-행동-뽑아-보기)
   - [상태 뽑아 보기](#4-상태-뽑아-보기)
   - [플레이어 캐릭터 속성(파라미터)](#5-플레이어-캐릭터-속성파라미터)
   - [게임의 규칙](#6-게임의-규칙)
### 6. [요구 사항](#요구-사항)
### 7. [스토리 보드](#스토리-보드)
### 8. [프로토타입 개발 요구사항(6주 개발)](#프로토타입-개발-요구사항6주-개발)

# [컨셉]

## 메인컨셉 :

- 운
  - 설명: 제가 생각한 게임 특성상 주사위를 굴리는 것이 8~90%는 차지 할꺼라 보여 '운'이 중요한 메인 컨셉으로 생각 됩니다.

### 서브 컨셉 1 :

- 숫자 싸움
  - 설명: 전체적으로 봤을 때 숫자를 이용한 전투가 메인이 될것이기에 서브 컨셉을 숫자 싸움이라고 정했습니다

### 서브 컨셉 2 :

- 산술 능력
  - 설명: 특수 숫자를 맞출 기회가 왔을 때 적절한 연산을 사용 하여 그 기회를 잡기 위해선 간단한 산술 능력은 필요하다 생각 되어 서브 컨셉을 산술 능력이라고 정했습니다.

### 서브 컨셉 3 :

- 육성
  - 설명: 운이 강력하게 적용되며 반복된 싸움을 하는데 있어 유저들은 지루함을 느끼기 마련이라고 생각합니다. 거기서 그나마 지루함과 승률을 올려주는데 '육성'이 필요하다고 생각 됩니다.

### 서브 컨셉 4 :

- 전투 임팩트
  - 설명: 단순히 숫자로만 높은 데미지를 넣어 주는 것 보다는 어느 정도의 임팩트가 있는 것이 더 쌔게 때렸다는 느낌을 주기에 있어 전투 임팩트 또한 중요하다고 생각 합니다.

### 서브 컨셉 5 :

- 도감
  - 설명: 다양한 몬스터와 거기서 나오는 다양한 전리품, 그리고 다양한 무기들을 얻을 때 마다 도감에 등록이 되며 그걸 채워간다는 또 다른 목적을 만들어 주기 위해서 입니다.

<br><br>

# [관련 이미지 & 동영상]

- 이미지  

 >### 전투 jpg
  
  <img src="./img/관련이미지.jpg">

  출처 게임: '던전 앤 걸스: 카드 배틀 RPG'

 >### 로비 jpg

  ![](./img/관련이미지2.jpg)
  
  출처 게임: '퀸즈 블레이드 리미트 브레이크'

 >### 육성 관련 jpg

  ![](./img/관련이미지3-1.jpg)

  출처 게임: 'DUNGREED(던그리드)'

  ![](./img/관련이미지3-2.jpg)

  출처 게임: 'Skul: The Hero Slayer(스컬 더 히어로)'

 >### 동영상

  [![](./img/관련이미지.jpg)](https://youtu.be/QHESxycEyZs)

<br><br>

# [대표 이미지]

![그림](./img/MainIMG.png)

<br><br>

# [컨셉 & 대표이미지 기반 작품묘사]

> ### 대표이미지 기반 : 주사위를 돌려서 나온 숫자들의 합을 이용해 적들을 처치하는 방식
&nbsp;
> ### 컨셉 기반: 1/6 확률인 주사위 2개 이상을 돌려 나온 숫자 사이에 원하는 사칙연산을 써서 나온 숫자를 이용하여 적들을 처치함

<br><br>

# [구성 요소]
<br>

## 1. 메커니즘

[도전 과제]

1. 보스의 보물 창고를 털고 살아서 나가기
2. 상대방 보다 높은 숫자로 공격 혹은 방어
3. 특수 숫자와 같은 숫자 맞추기
4. 던전을 돌며 다양한 무기 수집

[재미 요소]

1. 상대보다 높은 숫자 만들어서 화려한 임팩트 보기
3. 활, 검, 방패 등으로 이루어진 상성 차이
4. 가끔 보이는 보물 획득과 가끔 만나는 행상인에게서 아이템 구매
5. 다양 아이템을 상점에 팔아 돈을 모으것

<br>

## 2. 이야기

[만들게 된 배경]  

여러 로그라이크 형식의 게임을 하다 보니 대부분의 게임 들이 운적이 요소가 들어가 있다는 걸 체감 하고 나서
'아 나는 그저 운으로만 이루어진 게임을 한번 만들어 봐야지'라는 생각으로 갖게 되고 이번을 기회로
실천해보기 위해 제작을 생각했습니다. 최종 목표는 플레이스토어에 판매!

[게임 속 기본 배경]

어느 날 갑자기 세계 곳곳에서 땅 속에서 던전이 솟아 올라 오게 되었고
해당 던전에서 돈이 될게 많을꺼라고 생각 하게 된 주인공이 그 던전을 깨러 들어가게 된다.

[카메라 관점]  

플레이어의 1인칭 시점으로 공격 임팩트와 적들만 보이게 할 생각입니다.

<br>

## 3. 미적요소

[맵 디자인 & 컬러]  

가장 흔한 던전이라는 느낌으로 대충 쌓은 돌로 이루어진 벽과 위로는 끝을 알 수 없는 어두움
앞은 횟불이 설치 되어 있어야 보이는 정도

[아이템 디자인]

중세 판타지 느낌의 다양한 무기들

[음향]  

아무것도 없어 보이는 동굴을 걷는 다는 느낌의 메아리 섞인 발소리, 
검을 휘두르는 소리와 활 시위를 당기는 소리, 방어에 성공 했을 때의 소리, 마법구 날라가는, 적이 맞는 소리
<br>

## 4. 기술

원터치 방식의 흔한 모바일 게임. Unity 엔진에 Aseprite를 이용한 도트 그림

# [구성 요소 분석]

## 1. 게임 오브젝트 분해

|연번|오브젝트 이름|오브젝트 이미지|
|:----:|:----:|:----:|
|1|슬라임|<img src="./img/Slime.png" width="300">|
|2|고블린|<img src="./img/Goblin.png" width="300">|
|3|스켈레톤|<img src="./img/Skeleton.png" height="300">|
|4|데몬|<img src="./img/Demon.png" height="300">|
|5|무기|<img src="./img/Weapon.png" height="300">|
|6|주사위|<img src="./img/dice_4.png" height="300">|
|7|숫자|<img src="./img/13.png" height="300">|
|8|방향키|<img src="./img/Up.png" height="300">|
|9|더하기|<img src="./img/Plus.png" height="300">|


## 2. 파라미터(속성) 뽑아 보기

1. 몬스터들

|속성|영문명칭|설명|
|:----:|:----:|:----:|
|체력|Hp|몬스터들의 체력|
|턴|Turn|몬스터들의 공격까지 남은 시간|
|이름|Name|몬스터 명|
|장비|Equip|몬스터가 지금 착용 하고 있는 장비|
|공격력|Monster_Power|몬스터의 기본 공격력|

2. 행상인& 상점 주인

|속성|영문명칭|설명|
|:----:|:----:|:----:|
|가격|Price|아이템 가격|
|할인율|Sale|아이템들의 할인율|
|숫자|Dice_Number|할인에 사용될 행상인& 상점 주인의 주사위의 숫자(3)|


3. 무기들

|속성|영문명칭|설명|
|:----:|:----:|:----:|
|공격력|Weapon_Power|무기 기본 공격력|
|등급|Rank|무기의 등급|
|품질|Quailty|무기의 품질|

## 3. 행동 뽑아 보기

1. 플레이어

|행동|영문명칭|설명|
|:----:|:----:|:----:|
|공격|Player_Attack|원하는 무기를 이용하면 몬스터 공격|
|방어|Player_Defense|방패를 사용 하면 활을 든 공격 상대로 무조건 방어, 근접 공격은 50% 데미지 감소|
|이동|Player_Move|화면 아래 화살표를 눌러 해당 방으로 이동|

2. 몬스터들

|행동|영문명칭|설명|
|:----:|:----:|:----:|
|공격|Monster_Attack|몬스터의 턴이 끝나면 플레이어를 공격|
|방어|Monster_Defense|몬스터가 방패를 들고 있으면 플레이어의 활 공격을 무조건 방어, 근접 공격은 50% 데미지 감소|
|이동|Monster_Move|플레이어의 공격이 끝나면 공격까지 남은 턴이 1턴씩 감소|

## 4. 상태 뽑아 보기

1. 플레이어

|현 상태|전이 상태|전이 조건|
|:----:|:----:|:----:|
|정지|공격|원하는 무기를 선택 후 타겟 선택|
|정지|방어|공격을 당하기 전에 방패 선택|
|정지|이동|화면 아래 화살표를 눌러 이동 (미니맵 상에서만 이동 확인 가능)|
|일반|사망|체력이 0이 되면 사망|

2. 몬스터들

|현 상태|전이 상태|전이 조건|
|:----:|:----:|:----:|
|정지|공격|턴이 모두 끝나면 플레이어를 들고 있는 무기로 공격|
|정지|방어|몬스터가 방패를 들고 있을 때 플레이어가 활로 공격시 무조건 방어, 근접 공격은 50% 데미지 감소|
|정지|이동|플레이어의 턴이 끝나면 1턴씩 감소|

## 5. 플레이어 캐릭터 속성(파라미터)

|속성|영문 명칭|설명|
|:----:|:----:|:----:|
|체력|Hp|턴이 모두 끝나면 플레이어를 들고 있는 무기로 공격|
|장비|Sheild, Sword, Bow, Wand|플레이어가 선택 가능한 무기들|
|상태 이상|Debuff|출혈, 회복 불가, 독, 환영 등을 알려줄 상태 이상 표시|
|특수 숫자|Special_Number|특수 공격을 가능하게 해줄 특수한 숫자|
|가방|Bag|소모품들을 들고 다닌수 있게 해주는 가방|
|공격력|Player_Power|플레이어의 기본 공격력(로비에서 강화 가능)|

## 6. 게임의 규칙

1) 핵심 규칙
   -승리 규칙
      던전을 탐색 하다가 만나는 몬스터를 주사위 2개를 굴려서 나온 숫자에 사칙연산을 대입해 나온 숫자로 추가 공격력을 얻어서 나오는 몬스터들을 모두 죽이면서 최종 20층까지 도달하기
      20층에선 죽지 않고 최대한 많은 양의 보물 훔쳐 오기

   -패배 규칙
      플레이어의 체력이 0이 됐을 경우 마을로 돌아와짐 (획득한 골드의 일부를 소모 대략 10~60%)


2) 보조 규칙
   -그외 규칙들
      죽지 않기 위해 적당한 층에서 걸어서 탈출 가능(일부 금액을 내면 바로 탈출)
      마을에서 캐릭터 육성 및 무기 강화
      몬스터들은 플레이어의 공격이 끝난 후에 1턴씩 소모(플레이어의 선 공격)
      플레이어가 근접 공격시 남은 몬스터들의 턴은 모두 1로 변경
      
      
## 7. 게임에서 사용될 공식

1. 플레이어의 기본 체력은 100
2. 플레이어의 기본 공격력은 10
3. 주사위 숫자 1당 추가 기본 공격력 +1
4. 플레이어의 주사위 숫자의 결과 값이 몬스터의 주사위 수 보다 클 경우 그 차이 만큼의 추가 공격력 획득
5. 플레이어의 주사위 숫자의 결과 값이 몬스터의 주사위 수 보다 작을 경우 그 차이 만큼의 공격력 저하
6. 본인이 더 낮음 공격력 있는 상태에서 공격을 하면 그 차이 만큼의 데미지를 본인이 입음
7. 방패 사용시 상대방의 활 공격은 무조건 방어, 근접 공격은 50%의 데미지 감소, 마법 공격은 데미지 감소 없이 무조건 피해
8. 플레이어가 사망 할 경우 해당 던전에서 얻은 골드는 주사위를 돌려 10~60% 감소 하고 마을로 복귀

# [요구 사항]

> 마을
- 1. 처음 게임 접속시 마을에 상점, 도감, 업적, 훈련장,던전 입구를 만든다.
- 2. 상점에 들어가면 6개 정도의 아이템과 주사위 숫자 3를 보여주고 옆에 주사위를 돌리는 칸에서 주사위를 돌린다음 나오는 숫자에 따라 1,2 = 10 ~ 0퍼 가격 상승, 3 = 정가, 4 ~ 6= 10 -- 30% 할인
- 3. 그리고 아래쪽엔 구매와 판매가 나뉘는데 판매쪽에선 들고 있는 전리품 및 무기나 소모품들을 판매 할수 있습니다.
- 4. 도감에 들어가면 지금까지 만난 몬스터, 얻은 무기들을 보여준다.
- 5. 업적을 들어가면 지금까지 깬 업적들과 아직 못깬 업적을 보여주고 업적을 눌렀을시 깨기 위한 조건들을 보여준다.
- 6. 훈련장을 들어가면 가지고 있는 골드로 기본 능력치 및 기술들을 배울수 있게 해줍니다.
- 7. 마을의 전반적인 그래픽 제작 및 다듬기 후 적용하기까지

>던전
- 8. 던전 입구를 누르면 1층을 시작에서 시작
- 9. 던접 입장시 왼쪽 위에는 현재 위치하고 있는 방을 표시해주고 갈수 있는 방을 보여준다.
- 10. 화면 아래에는 화살표를 보여줘 원하는 방으로 이동을 할 수 있게 해줍니다.
- 11. 방을 이동 하면 전투 or 상자 or 행상인이 확률 적으로 나온다.
- 12. 전투 화면은 중간을 기준으로 아래로 보면 무기들, 특수 넘버, 플레이어 체력, 주사위, + x, 가방을 보여 줍니다.
- 13. 위쪽 화면에는 몬스터와 몬스터의 피, 주사위 숫자, 턴수를 보여준다.
- 14. 아래쪽 화면을 터치하면 먼저 주사위 1개가 돌아가고 한번 더 눌러 2번째 주사위까지 다 굴렸다면, 그 아래에 있는 사칙연산을 이용하여 최종 숫자를 만들어 줍니다.
- 15. 최종 숫자는 보기 편하게 주사위 모양 안에 숫자를 적어서 보여줍니다.
- 16. 최종 숫자가 나왔다면 위에 있는 무기들을 선택하고 나서 공격 하기 원하는 몬스터를 터치 해줍니다.(단. 방패는 무조건 자기 방어)
- 17. 만약 최종 숫자가 특수 넘버와 같게 나온다면 원하는 무기 공격이 특수 공격을 시도 합니다.
- 18. 몬스터의 턴이 모두 끝났다면 들고 있는 무기로 플레이어를 공격 합니다.
- 19. 가방을 누르면 들고 있는 소모품을 보여주고 해당 소모품을 눌르면 사용과 취소 창이 뜨며 사용을 누를시 해당 소모품의 효과를 얻을수 있고, 취소를 누르면 그냥 아이템 창이 닫히게됩니다.
- 20. 플레이어의 체력이 0이 된다면 주사위를 굴리는 화면이 뜨고 거기서 나온 주사위 수 만큼 10~60%의 던전에서 얻은 골드를 잃은 상태로 마을로 돌아가게 됩니다.
- 21. 던전 탐색을 하다가 원할 때 마을로 돌아 갈수 있으며, 걸어서 다시 나가거나 층수에 따른 특정 금액을 지불하여 마을로 돌아 갈수 있게 됩니다.
- 22. 상자를 발견 하게 되면 랜덤하게 골드, 무기, 소모품, 전리품 등을 얻을수 있습니다.
- 23. 행상인을 발견 하게 되면 마을 상점이랑 전체적인 시스템은 똑같되 가격은 전체적으로 층수에 비례해 10~40% 더 비쌉니다.

# [스토리 보드]

|스토리 보드 4컷 만화||
|:----:|:----:|
|<img src="./img/1cut.png" height="300">|<img src="./img/2cut.png" height="300">|
|어느날 갑자기 알수 없는 탑이 올라오더니 지상에 자리를 잡았다.|그리고 우리의 주인공은 생계를 유지 할 돈이 부족하게 되어 돈을 벌 곳을 찾고 있었는데|
|<img src="./img/3cut.png" height="300">|<img src="./img/4cut.png" height="300">|
|어느날 길을 걷가가 마을의 한 광고판을 보고선 돈을 벌 방법을 찾게 되었다|그것은 던전을 내부에 있는 전리품들의 가격이 비싸다는 것이다. 그리고 주인공은 돈을 벌기 위해 던전을 가게 되었다.|

# [프로토타입 개발 요구사항(6주 개발)]

### 마을
   - 1주차  
      - 처음 게임 접속시 마을에 상점, 도감, 업적, 훈련장,던전 입구를 만든다. 
   - 2주차  
      - 도감에 들어가면 지금까지 만난 몬스터, 얻은 무기들을 보여준다.  
   - 3주차  
      - 업적을 들어가면 지금까지 깬 업적들과 아직 못깬 업적을 보여주고 업적을 눌렀을시 깨기 위한 조건들을 보여준다  

### 던전
   - 4주차  
      - 던전 입구를 누르면 1층을 시작에서 시작.
      - 전투 화면은 중간을 기준으로 아래로 보면 무기들, 특수 넘버, 플레이어 체력, 주사위, + x, 가방을 보여 줍니다.
      - 위쪽 화면에는 몬스터와 몬스터의 피, 주사위 숫자, 턴수를 보여준다.
      - 아래쪽 화면을 터치하면 먼저 주사위 1개가 돌아가고 한번 더 눌러 2번째 주사위까지 다 굴렸다면, 그 아래에 있는 사칙연산을 이용하여 최종 숫자를 만들어 줍니다.
      - 최종 숫자는 보기 편하게 주사위 모양 안에 숫자를 적어서 보여줍니다.
   - 5주차 
      - 던접 입장시 왼쪽 위에는 현재 위치하고 있는 방을 표시해주고 갈수 있는 방을 보여준다.
      - 화면 아래에는 화살표를 보여줘 원하는 방으로 이동을 할 수 있게 해줍니다.
      - 방을 이동 하면 전투 or 상자 or 행상인이 확률 적으로 나온다.
   - 6주차  
      - 전체적으로 보고 완료 못한 작업 마무리, UI 좀 더 직관적으로 보기 편하게 교체 할 부분들 
