<h1 align="center">Culture_Place</h1>
<center>서울시 문화예술 정보 공유 플랫폼</center>

<br><br>

## 📌 목차
1. [프로젝트 소개](#-프로젝트-소개)
2. [팀원 소개](#-팀원-소개)
3. [개발 환경](#-개발-환경)
4. [다이어그램](#-다이어그램)
5. [기능 설명](#-기능-설명)
6. [개선 사항](#-개선-사항)

<br>

## 📄 프로젝트 소개
**Culture Place**는 서울시의 문화예술 정보를 제공하고 관람평 게시판을 통해 사용자들이 원하는 문화예술을 선택할 수 있도록 돕는 플랫폼입니다.
  * 서울시에서 진행되고 있는 모든 문화예술 정보를 확인할 수 있습니다.
  * 관람평 게시판에서 실제 관람객들이 남긴 관람 후기를 보고 다른 사용자가 원하는 문화예술을 선택할 때 도움을 받을 수 있습니다.
  * 관람평 게시판의 댓글을 통해 다른 사용자와 소통하며 문화적 경험을 넓힐 수 있습니다.

개발 기간 : 2025.05.19 ~ 2025.05.23

<br>

## 🙋 팀원 소개
<table>
 <tr>
  <th>노유경</th>
  <th>오세희</th>
  <th>차누리</th>
 </tr>
 <tr>
  <td align="center"><img src="images/profile_image.png" width="150px"></td>
  <td align="center"><img src="images/profile_image.png" width="150px"></td>
  <td align="center"><img src="images/profile_image.png" width="150px"></td>
 </tr>
 <tr>
  <td>공연·행사 목록 페이지<br>관람평 목록 페이지</td>
  <td>관람평 상세/수정/삭제<br>댓글 기능</td>
  <td>공연·행사 상세/수정/삭제<br>관람평 등록</td>
 </tr>
</table>

<br>

## 🔧 개발 환경
<div> 
  <h4>Back-End</h4>
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white">
  <img src="https://img.shields.io/badge/MyBatis-222222?style=for-the-badge&logoColor=white">
  <img src="https://img.shields.io/badge/JSP-F7DF1E?style=for-the-badge&logoColor=black">
  <br>
  
  <h4>Front-End</h4>
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css&logoColor=white">  
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
  <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white">
  <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
  <br>

  <h4>DB</h4>
  <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white">
  <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
  <br>

  <h4>Tool</h4>
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  
</div>

<br>

## 📊 다이어그램
<details>
  <summary>Usecase Diagram</summary>
  <div markdown="1">
    <img src="/images/Diagram/Usecase.png" >
  </div>
</details>
<details>
  <summary>ERD</summary>
  <div markdown="1">
    <img src="/images/Diagram/ERD.png" >
  </div>
</details>
<details>
  <summary>Class Diagram</summary>
  <div markdown="1">
    <h4>1. 공연·행사 정보 페이지</h4>
    <img src="/images/Diagram/Class Diagram/List.jpg" >
    <img src="/images/Diagram/Class Diagram/Details.jpg" >
    <hr>
    <h4>2. 관람평 페이지</h4>
    <img src="/images/Diagram/Class Diagram/Review_List.jpg" >
    <img src="/images/Diagram/Class Diagram/Review_Details.jpg" >
    <img src="/images/Diagram/Class Diagram/Review_register.jpg" >
  </div>
</details>

<br>

## 🔍 기능 설명
<details>
  <summary>공연·행사 목록 페이지</summary>
  <div markdown="1">
    <h4>목록 페이지(main 페이지)</h4>
    <img src="/images/Pages/main_List.png" >
    <p><br>공공 데이터 API를 활용하여 서울시에서 진행되고 있는 공연·행사 정보를 확인할 수 있습니다.<br>공연/행사명, 분류, 장소에 따라 원하는 공연·행사를 검색할 수 있습니다.</p>
    <br>
    <h4>공연·행사 상세 페이지</h4>
    <img src="/images/Pages/Details.png" >
    <p><br>공연·행사에 대한 상세 정보를 확인할 수 있습니다.<br>'리뷰 작성' 버튼 클릭 시 해당 공연·행사에 대한 관람평을 작성할 수 있습니다.</p>
   <br>
  </div>
</details>
<details>
  <summary>관람평 페이지</summary>
  <div markdown="1">
    <h4>관람평 목록 페이지</h4>
    <img src="/images/Pages/Review_List2.png" >
    <p><br>사용자들이 작성한 관람평 목록 페이지입니다.<br>공연/행사명, 작성자, 카테고리에 따라 원하는 공연·행사 관련 관람평을 검색할 수 있습니다.</p>
    <br>
    <h4>관람평 상세 페이지</h4>
    <img src="/images/Pages/Review_Details.png" >
    <table>
     <tr>
     <td><center><img src="/images/Pages/Reply_register.png" width="300px" ></center></td>
     <td><center><img src="/images/Pages/Reply_modify.png" width="300px" ></center></td>
      </tr>
    </table>
    <p><br>관람평에 대한 상세 정보를 확인할 수 있습니다.<br>하단에 댓글을 통해 사용자 간의 소통 공간을 구현하였습니다.<br>댓글은 AJAX 요청으로 구현하였고, 등록/수정/삭제는 modal창으로 구현하였습니다.<br>버튼을 클릭하면 게시글 수정/삭제 가능합니다.</p>
    <br>
    <h4>관람평 수정/삭제 페이지</h4>
    <img src="/images/Pages/Review_modify.png" >
    <p><br>기존의 관람평의 공연/행사명과 내용을 수정할 수 있습니다.</p>
    <br>
    <h4>관람평 등록 페이지</h4>
    <img src="/images/Pages/Review_register.png" >
    <p><br>'공연 선택' 버튼 클릭 시 공연/행사명과 장소, 분류가 자동으로 입력됩니다.</p>
    <br>
  </div>
</details>

<br>

## ⏳ 개선 사항
  * 진행상황, 코드리뷰 등 원활한 소통을 위한 협업 공간 (Notion, Slack 등) 필요
