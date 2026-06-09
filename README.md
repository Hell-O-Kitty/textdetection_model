
### 🗂️ 텍스트 탐지 모델 사용 데이터셋
- X(구 Twitter)에서 수집한 게시글 데이터를 활용하여 마약 관련 게시글 탐지 모델을 구축함. 데이터는 X 플랫폼에서 공개적으로 접근 가능한 게시글을 크롤링하여 수집하였으며, 총 2,431건의 게시글로 구성됨.
- 수집된 데이터는 마약 관련 여부에 따라 라벨링을 수행하였으며, 최종적으로 비마약 게시글 1,960건과 마약 관련 게시글 469건을 확보함. 데이터 라벨링의 신뢰성 확보를 위해 4명의 라벨러가 독립적으로 검토를 수행하였으며, Cohen's Kappa와 Fleiss' Kappa 계수를 활용하여 라벨링 일관성을 검증함.

---

### 🤖 텍스트 탐지 모델 사용 알고리즘
본 프로젝트에서는 한국어 SNS 게시글의 문맥을 효과적으로 분석하기 위해 KcELECTRA 기반 텍스트 분류 알고리즘을 사용함. KcELECTRA는 한국어 댓글 및 비정형 텍스트 데이터에 강점을 가지는 사전학습 언어모델로, X에서 수집한 게시글 내 은어, 축약어, 비정형 표현을 분석하는 데 적합함.

---

### 🚀 텍스트 탐지 모델 코드 확인 방법
1. 브랜치 전환
   저장소의 기본 브랜치인 main에서 개발용 브랜치인 drug_text_detection으로 전환함
<img width="1907" height="822" alt="image" src="https://github.com/user-attachments/assets/5fe283c4-1b01-4cc8-84d0-720707579db7" />

2. GitHub 저장소 Clone 및 로컬 환경 연동
   GitHub 저장소의 Code 메뉴에서 Open with GitHub Desktop을 선택하여 저장소를 로컬 환경으로 Clone함.
   <img width="1918" height="837" alt="image" src="https://github.com/user-attachments/assets/76b47bd8-98a6-4e7b-bffe-d379942915bd" />

3. Visual Studio Code를 이용한 프로젝트 실행
   GitHub Desktop에서 Open in Visual Studio Code 버튼을 선택하여 Clone한 저장소를 Visual Studio Code에서 열고 개발 환경을 구성함.
   <img width="1180" height="847" alt="image" src="https://github.com/user-attachments/assets/5a56584f-7b07-49b5-9ee7-18bd68c4b816" />

4. Jupyter Notebook 불러오기
   <img width="1875" height="960" alt="image" src="https://github.com/user-attachments/assets/13070f6f-c2f4-4376-9147-26615fce6912" />
