# Public Bike Rent Inquiry Program

이 프로젝트는 서울시 공공자전거 대여 현황을 조회 및 문의사항을 등록 및 조회하는 프로그램입니다.

<details>
<summary>프로젝트 소개</summary>
<div markdown="2">
현재 구성한 Layout은 아래 Screenshot과 같으며 현재는 서울시 공공자전거 대여소의 현황을 조회 할 수 있습니다.

- 자전거 대여소 조회

![publicBikeRentInquiryLayout](https://github.com/JinSungYoon/Public-Bike-Rent-Inquiry-Program/blob/master/img/publicBikeRentInquiryLayout.jpg)

- 고장신고 리스트
  ![breakdownReportLayout](https://github.com/JinSungYoon/Public-Bike-Rent-Inquiry-Program/blob/master/img/breakdownReportLayout.JPG)
- 고장신고 등록,수정,삭제
  ![breakdownReportLayout](https://github.com/JinSungYoon/Public-Bike-Rent-Inquiry-Program/blob/master/img/breakdownReportDetailLayout.JPG)

현재 구현된 기능은 서울시 공공데이터 현황을 조회하여 조회된 자전거 대여소의 위치를 지도에 보여주고 있습니다.

- 사용된 API
  - 서울시 공공공공자전거 실시간 대여정보(http://data.seoul.go.kr/dataList/OA-15493/A/1/datasetView.do)
  - 네이버 지도 API(https://www.ncloud.com/product/applicationService/maps)	

현재 구현된 기능

- 서울시 자전거 대여소 위치 정보 지도에 표시
- 검색을 통한 위치 이동 및 가까운 대여소 조회 
- 고장신고 게시판 기능 추가
- 고장신고 게시글 첨부파일 기능 추가

향후 추가 예정 기능

- 현 위치를 기반으로 한 가장 가까운 자전거 대여소 조회
- 대여소 선택시 게시글 등록 및 수정
<summary>개발 환경설정</summary>    
<div markdown="1">
1. JDK 설치


   - https://www.oracle.com/java/technologies/javase-downloads.html에 접속하여 JDK 1.8버전 다운로드

     ![image-20210722052308775](C:\Users\User\AppData\Roaming\Typora\typora-user-images\image-20210722052308775.png)
     실제로 설치된 JDK 버전은 아래와 같으나 1.8 버젼이면 상관없다.
     ![image-20210722052603618](C:\Users\User\AppData\Roaming\Typora\typora-user-images\image-20210722052603618.png)

   - 환경변수 설정
     내PC에서 [우클릭]-[속성] -> 고급 시스템 설정 클릭 -> [고급] -> [환경변수] -> 시스템변수에 새로만들기
     변수 이름 : JAVA_HOME
     변수값 : JDK 설치경로 입력
     ![image-20210722053245174](C:\Users\User\AppData\Roaming\Typora\typora-user-images\image-20210722053245174.png) 

2. Tomcat 다운로드
   http://tomcat.apache.org/에 들어가서 9.0 이상의 버젼 설치

   버젼 : 9.0 version
   Eclipse에서 Window>Preferenes Server>Runtime Environment에서 Apache Tomcat 9를 선택하고 설치된 경로 지정<img src="C:\Users\User\AppData\Roaming\Typora\typora-user-images\image-20210722054131780.png" alt="image-20210722054131780" style="zoom: 50%;" />
   <img src="C:\Users\User\AppData\Roaming\Typora\typora-user-images\image-20210722053848141.png" alt="image-20210722053848141" style="zoom: 50%;" /><img src="C:\Users\User\AppData\Roaming\Typora\typora-user-images\image-20210722054045814.png" alt="image-20210722054045814" style="zoom: 50%;" />




    </div>

</details>