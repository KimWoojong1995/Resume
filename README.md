# 김우종
'생각을 코드로, 상상을 현실로' <br />
Front-End 개발자 김우종입니다.
## 소개
<img alt="resume pic" src="https://user-images.githubusercontent.com/65944245/99877290-4d385a80-2c40-11eb-9cb1-cd0d0c93f787.jpg" width="250" height="250"> <br><br>

* 김우종 <br />

* 1995.07.30 / Male <br />

* PortFolio : https://kimwoojong1995.github.io/PortFolio <br />

* E-mail : woojong1995@gmail.com <br />

* Phone : 010-5551-5479 <br />

* GitHub : https://github.com/KimWoojong1995 <br />

* Blog : https://woojong-develop.tistory.com <br /><br />

개발자를 위한 개발이 아닌 모두를 위한 개발자, <br />
스스로 학습하며 업무에서 실력을 발휘하는 개발자 <br />

## 경험
* 구공팩토리 4기
  * 코딩 부트캠프 / Front-End
  * 2020년 6월~2020년 10월 <br /><br />
* eat around / 지붕 뚫은 친구들
  * 여행 관련 스타트업 / Front-End 인턴
  * 2020년 9월~2020년 10월 <br /><br />
* 나노다이아몬드
  * Diamond 개발 및 가공 / 주임
  * 2014년 10월~2020년 3월 <br /><br />
  
# 보유기술 및 사용도구
<img alt="javascript" src="https://user-images.githubusercontent.com/65944245/99964230-552a0300-2dd6-11eb-9113-cd88b6d93463.png" width="100" height="100"><img alt="typescript" src="https://user-images.githubusercontent.com/65944245/99964243-5824f380-2dd6-11eb-870f-a72cc3ed7ba5.png" width="100" height="100"><img alt="react" src="https://user-images.githubusercontent.com/13250888/62798586-90d58680-bb19-11e9-9a82-9762725abede.png" width="100" height="100"><img alt="sass" src="https://user-images.githubusercontent.com/13250888/53627368-a2059780-3c4b-11e9-95e3-9058d6a8afc7.png" width="100" height="100"><img alt="css" src="https://user-images.githubusercontent.com/65944245/99964244-58bd8a00-2dd6-11eb-8c67-91c57fa83ed3.png" width="100" height="100"> <br />
<img alt="html" src="https://user-images.githubusercontent.com/13250888/53627363-a16d0100-3c4b-11e9-8238-56153fb041e4.png" width="100" height="100"><img alt="webpack" src="https://user-images.githubusercontent.com/65944245/99964234-565b3000-2dd6-11eb-88d7-194306bc935a.png" width="100" height="100"><img alt="nodejs" src="https://user-images.githubusercontent.com/65944245/99966292-6fb1ab80-2dd9-11eb-9f24-a234a5677855.png" width="100" height="100"><img alt="mysql" src="https://user-images.githubusercontent.com/65944245/99964238-578c5d00-2dd6-11eb-86d1-fd5bd341c766.png" width="100" height="100"><img alt="mongodb" src="https://user-images.githubusercontent.com/65944245/99964237-56f3c680-2dd6-11eb-8361-56f3c44bdef2.png" width="100" height="100"> <br /><br />

## 학력 및 병역
* 대입검정고시
   * 2013년 8월 <br />
* 육군 제 23사단 수색대대
   * 2016년 8월~2018년 5월 <br /> <br />
## 프로젝트
### 주차장 무인 결제 시스템
영상 - https://www.youtube.com/watch?v=-h1pGnmmUes <br /><br />
GitHub - https://github.com/KimWoojong1995/ParkingSystem <br />
![관리자주차기록](https://user-images.githubusercontent.com/65944245/101732267-49417f00-3b00-11eb-91db-1ef80a0339b2.png)<br /><br />
평소 주차장 이용 시 무인 결제 시스템의 원리와 구조가 궁금했습니다.<br />
단순한 호기심으로 시작해 UML을 작성해보고 MySQL DB 구조를 만들었습니다.<br />
<img width="584" alt="주차장EERDiagram" src="https://user-images.githubusercontent.com/65944245/101730741-ebac3300-3afd-11eb-80ad-6e453cfe1fae.png"><br /><br />
View는 Nunjucks를 사용해 만들었으며 latout.html을 상속해서 전체적인 구조 틀과 로그인, 회원가입, 로그아웃, 정기권 만기일, 관리자 페이지를 보여줍니다.<br />
정규표현식을 사용해 input 값의 차량번호를 입력할 수 있으며 숫자 2~3자리,한글 한 글자,숫자 4자리 조합으로 입력 가능합니다.<br />
결제는 Front에서 현금과 카드결제 로직을 만들었습니다. 현금 결제시 거스름돈을 돌려주고 카드 결제시 실제 카드 결제 작동처럼 setTimeout을 사용하였습니다.<br />
결제는 Front에서 현금과 카드결제 로직을 만들었습니다. 현금 결제시 거스름돈을 돌려주고 카드 결제시 실제 카드 결제 작동처럼 setTimeout을 사용하였습니다.<br />
서버는 Node.js의 express를 사용하였습니다.<br />
비밀번호는 bcrypt를 사용해 DB에 저장되어 안전하게 암호화할 수 있게 하였습니다.<br />
express-session과 express-cookie를 사용해 로그인 상태를 관리합니다.<br />
DB는 Sequelize를 사용하며 해당 유저에 대한 테이블을 체크 후 관리자와 회원, 정기권 만료일 등 조건에 따라 view 상단에 표시합니다.<br />
차량 주차 시 주차기록 테이블의 해당 차량 번호와 주차시간, 결제 유무를 체크하며 이미 주차한 차량인지 판별 후 결과 값을 view에 보여줍니다.<br />
차량 출차 시 주차기록 테이블의 출차 시간 유무와 회원 판별, 정기권 보유를 체크 후 이미 출차한 차량인지, 회원 할인 차량인지 일반 차량인지 판별 후 결과 값을 view에 보여줍니다.<br />
정기권 등록 시 회원 테이블의 정기권 만기일을 확인 후 정기권을 보유한 사람이라면 선택한 개월 수 만큼 연장하고 신규라면 선택한 개월 수 만큼 등록 하도록 하였습니다.<br />
관리자의 아이디는 회원 테이블의 admin 유무를 체크 후 로그인 시 view 상단에 관리자 메뉴가 생성되며 관리자 메뉴 선택 시 주차 기록과 회원 기록을 볼 수 있습니다. 관리자의 차량 번호는 11가1111이며 비밀번호는 1111입니다.<br />
주차기록과 회원기록은 페이징 기능을 구현하였으며 해당 row 삭제 시 DB에서 삭제되고 삭제 시 접속되있던 페이지로 redirect합니다.<br /><br />
페이징 처리 기능을 구현하면서 Front에서의 처리와 Back에서의 처리에 대한 고민을 많이 하였고 코드를 수 없이 지우고 반복했습니다. 잦은 에러와 코드의 문제점 등을 경험하면서 더 많은 학습과 경험이 필요하다 느꼈습니다.
이번 프로젝트로 개발 초기 단계의 구상부터 웹 개발의 전체적인 흐름을 알 수 있었으며 정규표현식의 이해와 session과 cookie에 대한 학습을 하게 되었습니다.<br />
MySQL을 사용함으로써 DB의 작동 순서와 원리, 쿼리 등 많은 경험을 얻었고 앞으로의 개발 시 큰 원동력이 될 것이라 생각합니다.<br /><br /><br />
