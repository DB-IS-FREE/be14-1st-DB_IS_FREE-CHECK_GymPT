# 📖 운동하는 사람들을 위한 올인원(All-in-One) 플랫폼 Check! GymPT

![readme_mockup2](https://user-images.githubusercontent.com/112460466/210706312-6a44b60d-a42e-4210-b334-9e5983f70fb3.png)

- 배포 URL : https://ohmycode-readme.netlify.app
- Test ID : readme@test.com
- Test PW : 123123

<br>

## 프로젝트 소개

-  최근 들어 건강과 피트니스에 대한 관심이 높아지면서 운동하는 사람들이 빠르게 증가하고 있다. 그러나 많은 사람들이 운동 기록 관리, 바디프로필 예약, 운동 관련 정보 검색, 운동 커뮤니티 참여, 운동 제품 구매, 그리고 운동 계획 작성 등을 위해 다양한 앱과 서비스를 번갈아 사용하는 불편함을 겪고 있다.

-  우리의 프로젝트는 이러한 불편함을 해결하기 위해, 운동하는 사람들을 위한 올인원(All-in-One) 플랫폼을 제공하고, 운동 관련 모든 기능을 한 곳에 통합하여 사용자가 보다 편리하게 건강 관리와 운동 목표를 달성할 수 있도록 도와준다.

---

주요 제공 기능:
- 🏋️ 운동 기록 저장: 사용자가 매일의 운동 일지를 작성하고, 통계 및 피드백을 통해 운동 진행 상황을 추적
- 📸 바디프로필 예약 관리: 바디프로필 스튜디오 예약 및 스케줄 관리
- 💬 운동 커뮤니티: 운동에 관심 있는 사용자들이 서로 정보를 공유하고 소통
- 🛍️ 운동 제품 추천: 운동 장비, 의류, 보조제 등 관련 상품을 운동 종류마다 확인 가능
- 📓 운동 다이어리: 개인 맞춤형 운동 및 식단 계획 작성과 체크리스트 관리
- 📚 운동 방법 및 정보 제공: 사용자들이 다양한 운동 방법, 피트니스 팁 등을 쉽게 학습할 수 있는 콘텐츠 제공
<br>

## 팀원 구성

<div align="center">

| **고성연** | **서민종** | **이상모** | **이청민** | **한석현** |
| :------: |  :------: | :------: | :------: | :------: |
| [<img src="https://avatars.githubusercontent.com/Gombo2" height=150 width=150> <br/> @Gombo2](https://github.com/Gombo2) | [<img src="https://avatars.githubusercontent.com/MJay1123" height=150 width=150> <br/> @MJay1123](https://github.com/MJay1123) | [<img src="https://avatars.githubusercontent.com/Morris235" height=150 width=150> <br/> @Morris235](https://github.com/Morris235) | [<img src="https://avatars.githubusercontent.com/Bluesky3125" height=150 width=150> <br/> @Bluesky3125](https://github.com/Bluesky3125) | [<img src="https://avatars.githubusercontent.com/Hancoal" height=150 width=150> <br/> @Hancoal](https://github.com/Hancoal) |

</div>

<br>

## 1. 개발 환경
- DBMS : <img src="https://img.shields.io/badge/mariadb-003545?style=for-the-badge&logo=mariadb&logoColor=white">
- 인프라 : <img src="https://img.shields.io/badge/vmware-607078?style=for-the-badge&logo=vmware&logoColor=white">
- 개발 환경 : <img src="https://img.shields.io/badge/intellijidea-000000?style=for-the-badge&logo=intellijidea&logoColor=white"> , HeidiSQL
- 버전 및 이슈관리 : <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
- 협업 툴 : <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white"><img src="https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white"> <img src="https://img.shields.io/badge/kakaotalk-FFCD00?style=for-the-badge&logo=kakotalk&logoColor=white">
<br>

## 2. 프로젝트 구조

```
main
├── README.md
├── .gitignore
├── create_tables.sql -- 테이블 생성
├── work_record -- 운동 기록 관련 기능
├── work_info -- 운동 정보 관련 기능
├── user -- 회원 관련 기능
├── studio -- 스튜디오 관련 기능
├── report -- 신고 관련 기능
├── product -- 제품 관련 기능
├── place -- 운동 장소 관련 기능
├── dummy -- 더미 데이터 생성
├── diary -- 다어어리 관련 기능
├── community -- 커뮤니티 관련 기능능
│     ├── post -- 게시글 관련 기능
│     └── comment -- 댓글 관련 기능
├── blacklist -- 블랙리스트 관련 기능
├── admin -- 관리자 관련 기능
└── StartingPackage -- 더미 데이터 백업
```
    
<br>

## 6. WBS

<br>

## 7. 요구사항 명세서

<br>

## 8. 모델링

<details>
  <summary>개념 모델링</summary>
  <img src = "https://github.com/user-attachments/assets/b19dd0a9-0ca0-41d1-8eab-e3b394ec5c07">
</details>

<details>
  <summary><b>논리 모델링</b></summary>
  <img src = "https://github.com/user-attachments/assets/84c869dd-c8fe-4103-8f84-b5d535a4cb9a">
</details>

<details>
  <summary><b>물리 모델링</b></summary>
  <img src = "https://github.com/user-attachments/assets/45570ca3-d9dc-43b3-a140-1b05d8323b5f">
</details>

<br>

## 9. 테스트 케이스

## 10. 프로젝트 후기

### 🍊 고성연

깃헙을 통한 협업에 익숙해지는 것, 서로 감정 상하지 않고 무사히 마무리하는 것이 1차적인 목표였어서 항상 이 부분을 명심하면서 작업했습니다.
각자 페이지를 작업하고 합치는 과정에서 마주친 버그들이 몇 있었는데, 시간에 쫓기느라 해결하기에 급급해서 제대로 트러블슈팅 과정을 기록하지 못한 게 살짝 아쉬운 부분으로 남습니다. 그래도 2022년 한 해 동안 가장 치열하게 살았던 한 달인 것 같습니다. 조원들 모두에게 고생했다고 전하고 싶습니다🧡

<br>

### 👻 서민종

여러모로 많은 것들을 배울 수 있었던 한 달이었습니다. 혼자서는 할 수 없었던 일이라는 것을 너무 잘 알기에 팀원들에게 정말 감사하다는 말 전하고 싶습니다. 개인적으로 아쉬웠던 부분은 기한 내에 기능을 구현하는 데에만 집중하면서 트러블 슈팅이나 새로 배웠던 것들을 체계적으로 기록하지 못했다는 점입니다. 이렇게 느낀 바가 있으니 이후의 제가 잘 정리하면서 개발할 거라 믿습니다… 하하 다들 수고하셨습니다!!!!

<br>

### 😎 이상민

팀 프로젝트 시작에 앞서 초기 설정을 진행하며 체계적인 설계의 중요성을 느꼈습니다. 앞으로는 점점 더 체계적이고 효율적으로 프로젝트를 진행할 수 있도록 발전하고 싶습니다.
정규 수업 직후에 프로젝트를 진행하면서 배운 내용을 직접 구현하는 과정이 어색했지만 어떤 부분이 부족한지 알 수 있는 기회였습니다. 스스로 최대한 노력해보고 팀원들과 함께 해결해 나가면서 협업의 장점을 체감할 수 있었습니다. 하지만 빠르게 작업을 진행하면서 팀원들과 함께 해결한 이슈가 어떤 이슈이며 어떻게 해결했는지에 대해 자세히 작성하지 못한 것이 아쉽습니다.
’멋쟁이 사자처럼’이라는 같은 목표를 가진 집단에서 프로젝트에 함께할 수 있는 소중한 경험이었습니다. 함께 고생한 조원들 모두 고생하셨습니다! 앞으로도 화이팅해서 함께 목표를 이뤄가고 싶습니다.

<br>

### 🐬 이청민

컨벤션을 정하는 것부터 Readme 파일 작성까지 전 과정을 진행하려니 처음 생각보다 많은 에너지를 썼어요. 좋은 의미로 많이 썼다기보다, 제 능력을 십분 발휘하지 못해서 아쉬움이 남는 쪽입니다. 개발한다고 개발만 해서는 안 된다는 것을 몸소 느껴보는 기간이었던 것 같습니다. 이번 기회로 프로젝트를 진행하면서, 제가 잘하는 점과 부족한 점을 확실하게 알고 가는 건 정말 좋습니다. 기술적인 부분에 있어서는 리액트의 컴포넌트화가 주는 장점을 알았습니다. 조금 느린 개발이 되었을지라도 코드 가독성 부분에 있어서 좋았고, 오류가 발생해도 전체가 아닌 오류가 난 컴포넌트와 근접한 컴포넌트만 살펴보면 수정할 수 있는 부분이 너무 편했습니다. 모두 고생 참 많으셨고 리팩토링을 통해 더 나은 프로젝트 완성까지 화이팅입니다.

<br>

### 🐬 한석현

컨벤션을 정하는 것부터 Readme 파일 작성까지 전 과정을 진행하려니 처음 생각보다 많은 에너지를 썼어요. 좋은 의미로 많이 썼다기보다, 제 능력을 십분 발휘하지 못해서 아쉬움이 남는 쪽입니다. 개발한다고 개발만 해서는 안 된다는 것을 몸소 느껴보는 기간이었던 것 같습니다. 이번 기회로 프로젝트를 진행하면서, 제가 잘하는 점과 부족한 점을 확실하게 알고 가는 건 정말 좋습니다. 기술적인 부분에 있어서는 리액트의 컴포넌트화가 주는 장점을 알았습니다. 조금 느린 개발이 되었을지라도 코드 가독성 부분에 있어서 좋았고, 오류가 발생해도 전체가 아닌 오류가 난 컴포넌트와 근접한 컴포넌트만 살펴보면 수정할 수 있는 부분이 너무 편했습니다. 모두 고생 참 많으셨고 리팩토링을 통해 더 나은 프로젝트 완성까지 화이팅입니다.
