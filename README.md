# 이효정 포토폴리오

### 연락처
- Email : dpskfl04@naver.com
- Blog  : https://velog.io/@hjlee719
- Github : https://github.com/Naerumii
        
---

## 축제어때

- 목적

        1. 문화체육관광부 축제 데이터를 활용한 전국 축제 정보 소개
        2. 축제를 함께할 인원을 모집할 수 있는 서비스 구축
        3. 서비스 이용자들의 자유로운 커뮤니티 

- 기간 : 2022년 11월 30일 - 2022년 12월 29일 (4주)

- 팀 프로젝트\
        &nbsp;&nbsp;&nbsp;&nbsp;- 역할 : 리더\
        &nbsp;&nbsp;&nbsp;&nbsp;- 팀구성 : 5명
        
- 포트폴리오 : <a href="https://github.com/Naerumii/BestChoice">[링크]</a>

- 시연 영상 >> <a href="https://www.youtube.com/watch?v=PWlkFl4oawE">[링크]</a> <br>

- 배포 사이트 >> https://www.introvertcamp.shop/ <br>

- 핵심 담당 기능

        1. BeautifulSoup을 이용한 정적 크롤링으로 828건의 전국 축제 데이터베이스 구축
            a. 전국 축제 데이터 csv 파일 → SQLite에 저장하여 데이터 활용
        2. 각각의 축제에 대한 상세 정보 페이지, 축제 리뷰게시글 / 댓글 CRUD, 조회수 기능 구현
        3. 프로젝트 배포 및 지속적인 업데이트 경험
            a. NGIXN, Gunicorn을 활용한 이미지 빌드
            b. Docker 컨테이너 구조 이해, Dockerfile 작성 경험
            c. AWS EC2를 활용한 Django 기반의 배포 환경 구축, HTTPS 인증을 통한 보안강화
            d. AWS S3 이미지 업로드 및 CloudFront 활용한 HTTPS 배포
        4. 이미지 업로드시 2.5mb 이상인 경우 에러 발생하는 문제 해결
            a. nginx의 설정에 client_max_body_size 0; 을 추가하여 업로드 용량 제한 해제
        5. 사용자 피드백을 반영하여 로그인, 축제 검색 페이지에서 엔터(Enter)키 이벤트 활용

- 기술 스택

        - Python  |  Django  |  Django REST framework
        - Javascript  |  JQuery  |  HTML  |  CSS
        - SQLite |  PostgreSQL  |  Docker  |  Gunicorn  | NGIGX  |  AWS(EC2, S3, CloudFront, Route53)
 
---

# BlackMarket

- 목적

        - 유화 제작 인공지능 기술을 사용하여 이미지의 스타일을 변환하여 게시글을 생성
        - 회원 기능, 게시글, 댓글 기능을 구현
        
- 기간 : 2022년 11월 22일 - 2022년 11월 28일 (1주)

- 팀 프로젝트\
        &nbsp;&nbsp;&nbsp;&nbsp;- 역할 : 팀원\
        &nbsp;&nbsp;&nbsp;&nbsp;- 팀구성 : 5명
        
- 포트폴리오 : <a href="https://github.com/Naerumii/BlackMarket">[링크]</a>
- 시연 영상 >> <a href="https://www.youtube.com/watch?v=UzneqBcOHOY">[링크]</a> <br>

- 기여 활동

        1. OpenCV를 활용하여 업로드 된 이미지에 다양한 화풍을 적용하고 변환된 이미지 저장
        2. 게시글, 댓글 CRUD 기능 구현
        
- 기술 스택

        - Python  |  Django  |  Django REST framework  |  ML
        - Javascript  |  JQuery  |  HTML  |  CSS

---

# 내향인 맛집 탐방

- 목적

        - 망고플레이트 제주 식당 데이터를 크롤링하여 활용
        - 협업 필터링을 기반으로 사용자에게 제주 식당 추천
        - 회원 기능, 게시글, 댓글 기능을 구현
        - 처음으로 백엔드와 프론트엔드을 분리하여 프로젝트 진행
        
- 기간 : 2022년 11월 2일 - 2022년 11월 8일 (1주)

- 팀 프로젝트\
        &nbsp;&nbsp;&nbsp;&nbsp;- 역할 : 팀장\
        &nbsp;&nbsp;&nbsp;&nbsp;- 팀구성 : 5명
        
- 포트폴리오 : <a href="https://github.com/Naerumii/DRF_recommendation">[링크]</a>
- 시연 영상 >> <a href="https://www.youtube.com/watch?v=xTrNGh4_xM0">[링크]</a> <br>

- 기여 활동

        1. 많은 사용자들로부터 모은 취향 정보들을 기반으로 하여 스스로 예측하는 협업 필터링을 활용
            a. 사용자 별로 각 가게에 대한 평점을 랜덤하게 부여한 csv파일 생성
            b. 사용자 간 유사도를 산출해 가장 유사한 사용자가 평점을 좋게 준 가게들에 대해 현재 사용자가 아직 평점을 주지 않은 식당을 추천
        2. BeautifulSoup을 이용한 정적 크롤링으로 약 200건의 제주도 맛집 데이터베이스 구축
        
- 기술 스택

        - Python  |  Django  |  Django REST framework  |  협업필터링
        - Javascript  |  JQuery  |  HTML  |  CSS
