# ![PurpleLogo-BOutline](https://user-images.githubusercontent.com/78634177/182301688-36ef5a94-8fff-4c76-a35d-45b685071022.png)

흑백 사진을 컬러 사진으로 복원할 수 있다면?

흑백 사진을 편집 프로그램 없이 자동으로 컬러 사진으로 복원할 수 있습니다.


---
## 아키텍처
![image](https://user-images.githubusercontent.com/55674648/182015290-475222f1-9a9d-4d0d-916d-2d775421f7b5.png)

---
## 기술스택

<div align =center> 
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> 
  <img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=for-the-badge&logo=amazon%20ec2&logoColor=black">
  <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=amazon%20s3&logoColor=black">
  <img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=for-the-badge&logo=amazon%20rds&logoColor=black">
  <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=black">
  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/styled components-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=black">
  <img src="https://img.shields.io/badge/Font Awesome-528DD7?style=for-the-badge&logo=fontawesome&logoColor=white">
  <img src="https://img.shields.io/badge/gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=black">
  <img src="https://img.shields.io/badge/flask-000000?style=for-the-badge&logo=flask&logoColor=white">
  <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/rabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white">
  <img src="https://img.shields.io/badge/celery-37814A?style=for-the-badge&logo=celery&logoColor=black">
  <img src="https://img.shields.io/badge/redis-DC382D?style=for-the-badge&logo=redis&logoColor=black">
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/pytorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white">
  <img src="https://img.shields.io/badge/google colaboratory-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black">
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=black">
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=black">
  <img src="https://img.shields.io/badge/swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black">
  <img src="https://img.shields.io/badge/Git-73398D?style=for-the-badge&logo=git&logoColor=white">
</div>

---
## 디렉토리 

<details><summary>서브모듈 디렉토리 구조</summary>

```
frontend
├── Dockerfile
├── README.md 
├── package.json 
├──src
    ├── App.css
    ├── App.js
    ├── components
    │   ├── atom
    │   │   ├── Button.jsx
    │   │   ├── Display.jsx
    │   │   ├── DownloadButton.jsx
    │   │   ├── Input.jsx
    │   │   ├── Loading.jsx
    │   │   ├── MenuItems_colorize.jsx
    │   │   ├── MenuItems_mypage.jsx
    │   │   ├── MenuList.jsx
    │   │   └── TextLink.jsx
    │   ├── molecule
    │   │   ├── DropDown
    │   │   │   ├── DropDown.css
    │   │   │   ├── DropDown_colorize.jsx
    │   │   │   └── DropDown_mypage.jsx
    │   │   ├── NavBar
    │   │   │   ├── NavBar_colorize.css
    │   │   │   ├── NavBar_colorize.jsx
    │   │   │   ├── NavBar_mypage.css
    │   │   │   └── NavBar_mypage.jsx
    │   │   └── User_info.jsx
    │   ├── organisms
    │   │   ├── AdminWrapper.jsx
    │   │   ├── ChangeInfoWrapper.jsx
    │   │   ├── ColorizeFinishWrapper.jsx
    │   │   ├── ColorizeWrapper.jsx
    │   │   ├── FindPWWrapper.jsx
    │   │   ├── HomeWrapper.jsx
    │   │   ├── LoginWrapper.jsx
    │   │   ├── MyPageWrapper.jsx
    │   │   ├── MyProfileWrapper.jsx
    │   │   ├── OthersUserWrapper.jsx
    │   │   └── SignUpWrapper.jsx
    │   └── page
    │       ├── Admin.jsx
    │       ├── ChangeInfo.jsx
    │       ├── Colorize.jsx
    │       ├── ColorizeFinish.jsx
    │       ├── FindPW.jsx
    │       ├── Home.jsx
    │       ├── Login.jsx
    │       ├── MyPage.jsx
    │       ├── MyProfile.jsx
    │       ├── OthersUser.jsx
    │       └── SignUp.jsx
    ├── fonts
    │   ├── Cormorant-Bold.ttf
    │   ├── Cormorant-BoldItalic.ttf
    │   ├── Cormorant-Italic.ttf
    │   ├── Cormorant-Light.ttf
    │   ├── Cormorant-LightItalic.ttf
    │   ├── Cormorant-Medium.ttf
    │   ├── Cormorant-MediumItalic.ttf
    │   ├── Cormorant-Regular.ttf
    │   ├── Cormorant-SemiBold.ttf
    │   ├── Cormorant-SemiBoldItalic.ttf
    │   └── font.css
    ├── index.css
    ├── index.js
    ├── logo-4.svg
    ├── logo-5.svg
    ├── reportWebVitals.js
    └── setupTests.js
```
</details>

<details>
<summary>아토믹 디자인으로 구현</summary>

```
backend
├── Dockerfile
├── README.md
├── myapp
│   ├── __init__.py
│   ├── configs
│   │   ├── AiServerConfig.py
│   │   ├── DatabaseConfig.py
│   │   ├── JwtConfig.py
│   │   ├── S3Config.py
│   │   ├── __init__.py
│   ├── controller
│   │   ├── AdminController.py
│   │   ├── ApiRouter.py
│   │   ├── LoginController.py
│   │   ├── LogoutController.py
│   │   ├── PhotoController.py
│   │   ├── RefreshController.py
│   │   ├── UserController.py
│   │   ├── __init__.py
│   ├── entity
│   │   ├── Entity.py
│   │   ├── __init__.py
│   ├── service
│   │   ├── AdminService.py
│   │   ├── LoginService.py
│   │   ├── PhotoService.py
│   │   ├── TokenService.py
│   │   ├── UserService.py
│   │   ├── __init__.py
│   ├── util
│   │   ├── EncryptManager.py
│   │   ├── __init__.py
│   └── wsgi.py
└── requirements.txt
```
</details>

<details><summary>여기 제목</summary>
```
colorization-AI
├── Dockerfile
├── README.md
├── app.py
├── requirements.txt
├── service
│   ├── __init__.py
│   ├── baseColor.py
│   └── generator.py
└── util
    ├── __init__.py
    └── imageLoader.py
```
</details>

---
## 프로젝트 결과물

- 프론트 gif
- api doc
- grafana


---
## 프로젝트 참여자
<table width="950">
    <thead>
    </thead>
    <tbody>
    <tr>
        <th>사진</th>
         <td width="100" align="center">
            <a href="https://github.com/phjppo0918">
                <img src="https://user-images.githubusercontent.com/13298429/132939286-3aa06019-e474-4f42-b164-1813a925d624.png" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/SEONMl">
                <img src="https://user-images.githubusercontent.com/55674648/182297878-50251278-10f6-4cfd-9438-38cef6f1bf7b.png" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/asyooniverse">
                <img src="https://user-images.githubusercontent.com/55674648/182299290-6bd80a63-37f0-48da-ae95-5c0ac73ec1fe.png" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/yjshin229">
                <img src="https://user-images.githubusercontent.com/55674648/182299415-8eb9d968-324f-4c89-8ef5-94d15c338d24.png" width="60" height="60">
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/hamin924">
                <img src="https://user-images.githubusercontent.com/55674648/182299720-f57a2c02-f28c-4b4b-bb8c-181dc32f04ab.png" width="60" height="60">
            </a>
        </td>
    </tr>
    <tr>
        <th>이름</th>
        <td width="100" align="center">박현준</td>
        <td width="100" align="center">박선미</td>
        <td width="100" align="center">김지윤</td>
        <td width="100" align="center">신영진</td>
        <td width="100" align="center">김하민</td>
    </tr>
    <tr>
        <th>역할</th>
        <td width="150" align="center">
            backend<br>
            devops<br>
            AI<br>
        </td>
        <td width="150" align="center">
            backend<br>
            devops<br>
        </td>
        <td width="150" align="center">
            frontend<br>
            backend<br>
        </td>
        <td width="150" align="center">
            frontend<br>
            AI<br>
        </td>
        <td width="150" align="center">
            frontend<br>
        </td>
    </tr>
    <tr>
        <th>GitHub</th>
        <td width="100" align="center">
            <a href="https://github.com/phjppo0918">
                <img src="http://img.shields.io/badge/phjppo0918-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/SEONMl">
                <img src="http://img.shields.io/badge/SEONMl-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/asyooniverse">
                <img src="http://img.shields.io/badge/asyooniverse-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/yjshin229">
                <img src="http://img.shields.io/badge/yjshin229-green?style=social&logo=github"/>
            </a>
        </td>
        <td width="100" align="center">
            <a href="https://github.com/hamin924">
                <img src="http://img.shields.io/badge/hamin924-green?style=social&logo=github"/>
            </a>
        </td>
    </tr>
    </tbody>
</table>

## Reference
---
- [AI 트레이닝](https://github.com/richzhang/colorization)

# 프로젝트 빌드 방법
### 1. 프로젝트 클론
```
git clone --recursive https://github.com/SiliconValley22-Blossom/docker.git
```

### 2. settings폴더 하위에 prod.env 설정
```
FRONTEND_HOST=frontend
FRONTEND_PORT=3333  
BACKAND_HOST=backend
BACKAND_PORT=5000
AI_HOST=colorization-ai
AI_PORT=5555
RDS_ENDPOINT=
RDS_PORT=3306
RDS_DATABASE=blossom 
RDS_NAME=
RDS_PASSWORD=

S3_BUCKET_NAME=
S3_ID=
S3_SECRET_KEY=
S3_PUBLIC_ACCESS_URL=

RABBITMQ_HOST=rabbit
RABBITMQ_PORT=5672
RABBITMQ_USER=
RABBITMQ_PASSWORD=

JWT_KEY=

MAIL_PASSWORD=
MAIL_SERVER=smtp.gmail.com
MAIL_PORT=465
MAIL_USERNAME=
```

### 3. 배포 환경 실행
```
docker-compose -f docker-compose.prod.yml --env-file settings/prod.env up --build
```

<div>

</div>