<br>

![header](https://capsule-render.vercel.app/api?type=Waving&color=0:B2CCFF,100:D1B2FF&height=250&section=header&text=🏠ZIP_POP&desc=FIIIIIVE&descSize=20&descAlign=68&descAlignY=70&fontSize=100&animation=fadeIn&fontColor=ffff)

> **[플레이 데이터] 한화시스템 BEYOND SW캠프 / 🖐🏻 Team : FIIIIIVE 🖐🏻**

<br>

### 👩🏻‍💻‍ 팀원
<br>

<div align="center">
<table>
 <tr>
        <td align="center">
            <a>
            </a>
	<img src="./img/sungjoon.png" width=100, height=100>
 </td>
        <td align="center">
            <a>
	<img src="./img/hyejeong.png" width=100, height=100>
	</a>
        </td>
        <td align="center">
            <a>
	<img src="./img/jongsung.png" width=100, height=100>
 	</a>
        </td>
        <td align="center">
            <a>
	<img src="./img/nakyung.png" width=100, height=100>
	</a>
        </td>
        <td align="center">
            <a>
	<img src="./img/suyeon.jpg" width=100, height=100>
 	</a>
        </td>
    </tr>
    <tr>
 <td align="center">
            <b>박성준</b>
        </td>
        <td align="center">
            <b>강혜정</b>
        </td>
        <td align="center">
            <b>박종성</b>
        </td>
        <td align="center">
            <b>송나경</b>
        </td>
        <td align="center">
            <b>정수연</b>
        </td>
    </tr>
    <tr>
        <td align="center"">
            <b>Team Leader</b>
        </td>
        <td align="center">
            <b>Backend</b>
        </td>
        <td align="center">
            <b>Backend</b>
        </td>
        <td align="center">
            <b>Backend</b>
        </td>
        <td align="center">
            <b>Backend</b>
        </td>
    </tr>
</table>
</div>
<br>


---
<br>


### 👨🏻‍🏫 프로젝트 기본 소개
<br>

&nbsp;&nbsp;&nbsp;&nbsp; 최근에는 화장품이나 의류를 넘어 드라마, 음악, 게임, 영화, 애니메이션 등 상관없이 각 업계에서 팝업스토어를 활용하고 있다. 팝업스토어에서는 기존 매장과의 차별점을 두기 위해 한정판 굿즈를 판매하고, 이를 구매하기 위해 장시간 대기하는 현상이 급증하는 추세다.  
&nbsp;&nbsp;&nbsp;&nbsp; **🏠ZIP_POP**은 사전예약을 통해 기존의 팝업스토어 대기 시스템을 개선하고 밤샘 대기 또는 장시간 대기로 인한 고객과 해당 팝업 주변 거주민의 불편을 해소하는 서비스를 제공한다. 매장 입성에 성공했음에도 재고 소진 등의 이유로 원하는 물품을 구하지 못하는 상황을 방지할 수 있도록 사전예약자에 한해 굿즈를 선구매할 수 있는 서비스 또한 제공한다. 예약 기능 없이 정보 제공을 목적으로 하는 유사 사이트와 달리, **🏠ZIP_POP**은 하나의 사이트에서 팝업스토어와 관련된 정보 파악뿐만 아니라 예약 및 굿즈 구매까지 가능하다는 차별점이 있다.

<br>


---
<br>


### 💡 프로젝트 배경
<br>

<div align="center">
<figure class="half">
 <img src="./img/기사1.png" width=500, height=310>
</figure>
<br/>
</div>


<br>

- 대학원생 한지선씨(30)는 인기 유튜버 '침착맨'의 팝업스토어에 방문하기 위해 치열한 예약 경쟁을 뚫었다. 침착맨 팬 커뮤니티에서 예약 팁도 전수받았지만 "인기 상품이 모두 품절돼 아쉬워 아침 일찍 다시 방문해 볼까 생각 중이다"라고 말했다.

<br>

<div align="center">
<figure class="half">
<img src="./img/기사2.png" width=420, height=300>
</figure>
<br/>
</div>

<br>

- 더현대서울은 2021년 2월 개점 후 2023년 11월 중순까지 약 460회의 팝업스토어를 운영했다. 이틀에 한 개꼴로 새로운 팝업스토어를 연 셈이다. ‘임시 매장’의 이미지였던 팝업스토어가 ‘한정판 전문 매장’으로 진화했다고 본다. 운영 기간 제한이라는 팝업스토어의 특징이 ‘이때 아니면 못 산다’는 인식을 주게 되었다.

<br>


<details>
  <summary>출처</summary>  

- 기사1 : [https://news.mt.co.kr/mtview.php?no=2024051609573785999]  

- 기사2 : [https://www.donga.com/news/Economy/article/all/20231201/122446644/1]
</details>
<br>


---
<br>


### 📌 시스템 아키텍처

<br>
<div align="center">
<figure class="half">
<img src="./img/systemarch.PNG">
</figure>
<br/>
</div>

<br>


---
<br>


### ⚙ ERD

<br>
<div align="center">
<figure class="half">
<img src="./img/erd.png">
</figure>
<br/>
</div>

<br>


---
<br>


### 🛠 재난 복구 계획
<br>

#### &nbsp;　예상 장애 발생 지점  
- 특정 시간대에 트래픽이 몰리는 경우  
- 예약 대기 중 장애  
- 결제 진행 중 장애  

<br>

#### &nbsp;　시스템 구성
&nbsp;&nbsp;&nbsp;&nbsp; 해당 서비스는 특정 시간대별로 트래픽이 몰릴 수밖에 없는 특징이 있고, 인기 있는 팝업스토어의 사전예약 같은 경우에는 과도한 트래픽이 몰리게 되어 서버 과부하로 인해 다운될 가능성이 있습니다. 만약 결제 정보가 DB에 동기적으로 저장되지 않는다면 사용자에게 금전적 손해를 입힐 수 있다는 문제가 발생할 수 있기 때문에 갈레라 클러스터링을 통하여 정보의 동기 방식 동기화를 적용할 계획입니다.  

<br>


---
<br>


### 🥽 SQL 실행 결과
<br>

#### &nbsp;　핵심 기능 성능 테스트
<br>

- 성능 테스트 전
<div align="center">
<figure class="half">
<img src="./img/pointskill_before_test.png">
</figure>
<br/>
</div>

<br>
<br>

- 인덱스 적용
<div align="center">
<figure class="half">
<img src="./img/pointskill_index.png">
</figure>
<br/>
</div>

<br>
<br>

- 스토어 프로시저 적용
<div align="center">
<figure class="half">
<img src="./img/pointskill_storep.png">
</figure>
<br/>
</div>

<br>
<br>

<details>
  <summary>고객 회원</summary>  
<div align="center">
<figure class="half">
<img src="./img/sql_customer.png">
</figure>
<br/>
</div>
<br>
- 회원 가입 시 ID, 패스워드, 이름을 필수로 입력해야 한다. (주소, 휴대전화번호, e-mail는 선택사항)
</details>
<br>
<br>
<details>
  <summary>기업 회원</summary>  
<div align="center">
<figure class="half">
<img src="./img/sql_company.png">
</figure>
<br/>
</div>
<br>
- 회원 가입 시 ID, 패스워드, 이름을 필수로 입력해야 하고, 기업 email인증을 해야 한다.
</details>
<br>
<br>
<details>
  <summary>팝업스토어</summary>  
<div align="center">
<figure class="half">
<img src="./img/sql_popup_store.png">
</figure>
<br/>
</div>
<br>
- 팝업스토어 등록 시 팝업스토어의 이름, 진행 장소, 진행 날짜, 사전 예매 인원수, 상세페이지, 배너를 기입한다.<br>
-  상세페이지와 배너는 이미지 파일로 업로드 가능하다. 
</details>
<br>
<br>
<details>
  <summary>팝업스토어 굿즈</summary>  
<div align="center">
<figure class="half">
<img src="./img/sql_popup_goods.png">
</figure>
<br/>
</div>
<br>
- 굿즈를 등록할 때 굿즈의 이름과 가격, 상세 내용, 사진을 기입한다.<br>
- 재고 굿즈 등록의 경우 굿즈의 수량을 추가로 등록해야 하며 굿즈의 잔여 수량을 알 수 있다.<br>
- product_status를 통해 굿즈가 판매 중인지, 품절되었는지, 재고 굿즈인지 확인 가능하다.
</details>
<br>
<br>
<details>
  <summary>취소표 예매대기자 조회</summary>  
<div align="center">
<figure class="half">
<img src="./img/sql_cancel_waiting_mem.png">
</figure>
<br/>
</div>
<br>
- 취소표 예매를 대기하고 있는 회원의 아이디를 조회할 수 있다.<br>
- 예매대기자는 대기하고있는 팝업스토어의 대기 번호를 알 수 있다.<br>
</details>
<br>
<br>
<details>
  <summary>장바구니</summary>  
<div align="center">
<figure class="half">
<img src="./img/sql_cart.png">
</figure>
<br/>
</div>
<br>
- 마음에 드는 재고 굿즈를 장바구니에 담을 수 있다.
</details>
<br>
<br>
<details>
  <summary>장바구니 굿즈 목록</summary>  
<div align="center">
<figure class="half">
<img src="./img/sql_cart_goods.png">
</figure>
<br/>
</div>
<br>
- 담아놓은 재고 굿즈의 목록을 조회할 수 있다.
</details>
<br>
<br>
<details>
  <summary>커뮤니티 게시글 등록 및 조회</summary>  
<div align="center">
<figure class="half">
<img src="./img/sql_posts.png">
</figure>
<br/>
</div>
<br>
- 커뮤니티에 게시글을 작성할 수 있다.
</details>
<br>
<br>
<details>
  <summary>커뮤니티 댓글 등록 및 조회</summary>  
<div align="center">
<figure class="half">
<img src="./img/sql_comment.png">
</figure>
<br/>
</div>
<br>
- 커뮤니티에 등록되어있는 게시글에 댓글을 작성할 수 있다.
</details>
<br>
<br>
<details>
  <summary>팝업스토어 사전예매 내역 조회</summary>  
<div align="center">
<figure class="half">
<img src="./img/sql_popup_customer.png">
</figure>
<br/>
</div>
<br>
- 회원은 사전예매한 팝업스토어의 목록을 모아볼 수 있다.
</details>
<br>
<br>
<details>
  <summary>팝업 굿즈 사전구매</summary>  
<div align="center">
<figure class="half">
<img src="./img/sql_popup_customer_goods.png">
</figure>
<br/>
</div>
<br>
- 팝업을 예매한 회원은 굿즈를 사전구매 할 수 있다.
</details>
<br>
<br>
<details>
  <summary>결제수단</summary>  
<div align="center">
<figure class="half">
<img src="./img/sql_payment.png">
</figure>
<br/>
</div>
<br>
- 총 금액을 결제한다.<br>
- 결제시각은 DB에 저장한다.
</details>
<br>
<br>
<details>
  <summary>리뷰 등록 및 조회</summary>  
<div align="center">
<figure class="half">
<img src="./img/sql_review.png">
</figure>
<br/>
</div>
<br>
- 사전굿즈 구매자는 구매한 굿즈에 대한 리뷰를 등록할 수 있다.<br>
- 리뷰는 별점등록과 코멘트로 남길 수 있다.<br>
- 리뷰를 등록한 시각은 DB에 저장한다.<br>
</details>
<br>
<br>
<details>
  <summary>위시리스트 등록</summary>  
<div align="center">
<figure class="half">
<img src="./img/sql_wishlist.png">
</figure>
<br/>
</div>
<br>
- 관심있는 팝업을 위시리스트로 등록할 수 있다.
</details>
<br>
<br>
<details>
  <summary>위시리스트 조회</summary>  
<div align="center">
<figure class="half">
<img src="./img/sql_wish_popup.png">
</figure>
<br/>
</div>
<br>
- 등록한 위시리스트의 목록을 조회할 수 있다.
</details>
<br>


---
<br>


### 💻 기술 스택


<br>

#### &nbsp;　[ DB ]

&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/MariaDB-003545?style=flat&logo=MariaDB&logoColor=white"/></a>

#### &nbsp;　[ Backend ]


#### &nbsp;　[ Frontend ]


#### &nbsp;　[ CI/CD ]

&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=white&color=black"></a></a>
&nbsp;&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=Git&logoColor=white&color=ffa500"></a></a>

<br>
