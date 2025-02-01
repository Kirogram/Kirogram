
프로그래머 **기정환**의 Git 저장소에 방문해 주셔서 감사합니다.  

## 보유 스킬
<table border="1"> <tr> <th rowspan="3">Front-End</th> <td>Language</td> <td>TypeScript, JavaScript</td> </tr> <tr> <td>Library & Framework</td> <td>React, Redux(RTK), Recoil, React-query, chart.js, bootstrap, Sass(SCSS)</td> </tr> <tr> <td>Build Tool & Compiler</td> <td>Webpack, ESBuild, Babel</td> </tr> <tr> <th>Back-End</th> <td>Library & Framework</td> <td>Java, Spring Framework, MyBatis, JPA</td> </tr> <tr> <th>Data Base</th> <td>DBMS</td> <td>Oracle D/B, PostgreSQL</td> </tr> <tr> <th rowspan="2">Cloud</th> <td>Cloud Service</td> <td>AWS(EC2, S3), IwinV</td> </tr> <tr> <td>Server</td> <td>Linux UBUNTU, CentOs</td> </tr> <tr> <th rowspan="3">DevOps & Tool</th> <td>Version Control</td> <td>GitHub, Bitbucket</td> </tr> <tr> <td>CI/CD</td> <td>GitHub Actions, Jenkins</td> </tr> <tr> <td>Project Management</td> <td>Jira, Notion, Slack, Figma, Zeplin</td> </tr> </table>


## 프로젝트

![더클린박스](https://coolcleaner.co.kr/fileDownLoad/1708113867996rr.jpg)
### 1. 공간케어 플랫폼 - 더클린박스
"50만 사용자와 160억의 누적신청액의 공간케어 플랫폼"

**프로젝트 소개**  
특수한 상황에서의 공간 케어가 필요한 고객들을 위해 정보와 서비스를 제공하는 플랫폼으로 편리한 인터페이스와 가입없이 모든 정보를 확인 할 수 있는 가벼운 구조로 설계되었습니다.  
확인하기 어려운 정보들을 시각적으로 제공하며 여러 업체를 동일한 조건에서 비교하여 본인에게 가장 잘 맞는 업체와 상담까지 진행해 볼 수 있는 구조로 많은 고객들의 선택을 받았습니다.  

---
**마이그레이션과 마이크로 서비스 아키텍처**  
프로젝트 품질관리를 위한 기술적 도전을 진행하였고 , 두번의 마이그레이션을 통해 기존 모놀리식 아키텍처에서 마이크로 서비스 아키텍처로의 전환을 성공적으로 이끌어내어 시스템의 유연성과 확장성을 향상시켰습니다.  


### 1. 두번의 마이그레이션 

### JSP to Angular
기능 구현 확인을 위한 프로토타입 개발에서 본서비스 운영을 위해 랜더링 퍼포먼스가 더 좋은 SPA 프레임워크로 전환을 진행하였고 기존 개발 경험이 있던 Angular를 채택 마이그레이션을 진행하였습니다.  

##### · SPA 전환  
페이지 이동간 사용자 이탈을 최소화 하기 위해 단일 페이지 어플리케이션 기술을 적용 방문부터 신청까지의 흐름이 하나의 스텝으로 흘러 갈 수 있도록 구성하였습니다.  


##### · 컴포넌트형 아키텍처  
Angular의 독립적인 컴포넌트 구성을 활용 각 기능들을 모듈화 하고 이를 조합하는 방식으로 시스템 복잡성을 낮췄습니다.
<br>
<br>
### Angular to React
Angular의 독립적이고 구조화된 컴포넌트가 장점에서 단점으로 바뀌게 되며 불필요한 오버헤드가 발생하는 것을 인지하여 개발 자유도가 높은 React로 전환하고 목적에 필요한 만큼의 사용을 통해
프로젝트 전체를 경량화 성능을 향상시켰습니다.  

##### · 컴포넌트 경량화를 통한 성능 최적화
컴포넌트의 코드 베이스 정리 및 불필요한 종속성을 제거, 실행 효율을 상승시키고 전반적인 성능을 최적화 시켰습니다.
  
##### · 장기적 확장을 고려한 마이그레이션  
글로벌하게 커뮤니티가 형성되고 국내 개발자들의 지지를 받는 React로의 마이그레이션을 통해 차후 업데이트되는 기능에 유연하게 대처하고 강력한 서드파티 라이브러리를 활용하여 프로젝트 품질을 관리하기 위한 부분도 변경의 큰 이유가 되었습니다.  

### 누적 성과
![image](https://github.com/user-attachments/assets/1864cf1c-4e55-4658-a503-7bf4a5a77119)

---
![BMC](https://coolcleaner.co.kr/fileDownLoad/1708117196450SSD.jpg)
### 2. 데이터 크롤링 & 인사이트 - Baemin Crawler  
“ 기본정보만으로 새로운 인사이트를 ”

**GitHub**  
[https://github.com/Kirogram/BaeminCrawler](https://github.com/Kirogram/BaeminCrawler)  

**주요 기술 스택**  
Angular , Typescript  
Bootstrap , chart.js , Material  
Java , Spring Framework , Selenium  


**프로젝트 소개** 
   
최소한의 정보로 다양한 인사이트를 추출 배달 사업장 운영에 도움을 주는 컨텐츠들을 구성하여
대시 보드 형식으로 정보를 제공해주는 사이트 입니다.

배달앱 에서 제공해주지 않는 가공 정보들을 제공하여 새로운 시각에서 고객을 파악 할 수 있도록 도와주고 사업장 운영에서 놓치고 있는 점을 한눈에 파악 할 수 있습니다.

![image](https://github.com/user-attachments/assets/97934ab2-3d11-4ca7-a999-6e7c5040078a)
![image](https://camo.githubusercontent.com/5f990677d18ff278ce2ab506f9d0909e10570283f2f289a35c8efed250918ad2/68747470733a2f2f636f6f6c636c65616e65722e636f2e6b722f66696c65446f776e4c6f61642f3137303639373432313337343163722e676966)


---
![COOL](https://camo.githubusercontent.com/f18d1072d5f3a74a57f1db5c2c7aa1b09d3b32765336b5d43038156c0a180a47/68747470733a2f2f636f6f6c636c65616e65722e636f2e6b722f66696c65446f776e4c6f61642f3137303832303130373837313634342e706e67)
### 3.업체 홍보 사이트 - CoolCleaner
“ 평범한 업체가 하나의 브랜드가 되어가는 과정”


 **라이브 사이트**  
[https://coolcleaner.co.kr](https://coolcleaner.co.kr)  

**GitHub**  
[https://github.com/Kirogram/CoolCleaner](https://github.com/Kirogram/CoolCleaner)  


**주요 기술 스택**  
React , Typescript  
Redux(RTK) , Jest , RTL , sass(scss)  
Java , Spring framework , JPA  

