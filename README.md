# kiosk

# 버튼, TextArea, Label 등록하기

![image](https://github.com/dbsgustj/kiosk/assets/126844596/0e1a163c-3a1f-42fa-aad4-546a2c75515b)

# 변수를 넣을 배열을 생성

![image](https://github.com/dbsgustj/kiosk/assets/126844596/10ea2d03-e410-42f0-b198-992780c75607)

# +를 누르면 COUNTM[n]을 +1

![image](https://github.com/dbsgustj/kiosk/assets/126844596/8e275f5a-d45c-4d49-a57b-ff7e6c870791)

![image](https://github.com/dbsgustj/kiosk/assets/126844596/9e3f2b40-b85a-4c3b-b2ac-1c0fb38f9934)

# -를 눌렀을때 COUNTM[n]의 수가 1이상이라면 -1

![image](https://github.com/dbsgustj/kiosk/assets/126844596/78ef72b6-a6ed-4ffa-b222-b29537f72bd4)

![image](https://github.com/dbsgustj/kiosk/assets/126844596/1ec1ef88-8de2-4353-b05e-53c95c7b614c)

# 초기화

![image](https://github.com/dbsgustj/kiosk/assets/126844596/5fccff3b-dedd-42f6-a1b0-8e19f4c96461)

![image](https://github.com/dbsgustj/kiosk/assets/126844596/d47af4c8-e873-44c6-ab81-6542b2d374c2)

취소버튼을 누르면 sumLabel(총 액)과 ListTextArea(통계) 창이 초기화 된다.

# 계산하기

![image](https://github.com/dbsgustj/kiosk/assets/126844596/7950072e-f6f7-418c-b0c0-894d153fbbf5)

계산버튼을 누르면 주문할 음료의 수 와 가격을 총합해 총 액에 금액을 나타낸다

![image](https://github.com/dbsgustj/kiosk/assets/126844596/10d57c1e-3f68-49f1-a5a9-baa189da52dc)

# 주문하기

![image](https://github.com/dbsgustj/kiosk/assets/126844596/37651c1e-c0a9-45e3-afc4-31ecb1ac2f1d)

주문하기를 눌러 주문을 하면 주문이 완료되었다는 메시지가 뜬다

![image](https://github.com/dbsgustj/kiosk/assets/126844596/f511f667-c3b5-48e9-84da-54eb3822f802)

게산하기를 누르지 않고 주문하기를 누르면 저런 메시지가 나온다

![image](https://github.com/dbsgustj/kiosk/assets/126844596/28242f32-b766-460c-9322-aa14e9a4e51c)

# 관리자 로그인창

![image](https://github.com/dbsgustj/kiosk/assets/126844596/da4d0caf-dee7-4d74-a107-f25377c1575f)

통계창의 오른쪽 위에있는 관리자 로그인 버튼을 눌러 관리자 로그인창을 열 수 있다

![image](https://github.com/dbsgustj/kiosk/assets/126844596/ec97cc64-ebe0-4125-b507-e52ec03938c5)

![image](https://github.com/dbsgustj/kiosk/assets/126844596/1f6a43c4-a28d-48c7-b940-0cfcc3e5693a)

잘못된 아이디와 비밀번호를 입력했을땐 취소버튼을 눌러 입력된 문자를 지우고 창을 닫고 싶다면 닫기버튼을 누른다.

로그인을 하고싶다면 정확한 아이디와 비밀번호를 입력후 로그인버튼을 누르면 된다.

# 관리자 BD조회창

DB관리자 창의 데이터는 주문한것들이 DB에 저장되어있는데 DB에 저장되어있는 데이터를 가져오기 위해 DB와 연결하여
날짜에 맞게 데이터를 가져올 수 있다

# DB연결코드

![image](https://github.com/dbsgustj/kiosk/assets/126844596/1441b2d4-437b-46bf-87d9-fdfa30aa6f99)

![image](https://github.com/dbsgustj/kiosk/assets/126844596/a7fbcc42-d79e-48dc-952e-95a90b9eeb99)

전체 조회를 누르면 지금까지 주문된 내역을 모두 볼 수 있다

![image](https://github.com/dbsgustj/kiosk/assets/126844596/dfecb16f-7001-4767-a481-9b3a7432312f)

날짜별 조회는 원하는 날짜를 선택해 그 날짜에 주문된 내역을 볼 수 있다

![image](https://github.com/dbsgustj/kiosk/assets/126844596/5e87f6e3-e4ed-43dd-8167-51f64051b104)

기간별 조회는 원하는 시작 날짜부터 종료 날짜를 입력하면 그 사이에 주문된 내역을 볼 수 있다

![image](https://github.com/dbsgustj/kiosk/assets/126844596/9d8b12e9-6514-4538-a7de-e393cef9012a)

# 관리자 DB조회창의 코드

![image](https://github.com/dbsgustj/kiosk/assets/126844596/c98a86b2-1234-4b17-b2d5-66f841f93ef3)

![image](https://github.com/dbsgustj/kiosk/assets/126844596/8f682304-a3b9-4ce0-8084-aa2d2c8be32d)

![image](https://github.com/dbsgustj/kiosk/assets/126844596/d9af04ba-2dca-4b3a-a6fa-a82f022524eb)

![image](https://github.com/dbsgustj/kiosk/assets/126844596/98082bc1-68bc-4518-acf3-ed75a95f6e07)


