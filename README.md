## 프로젝트 클론
```
git clone --recursive https://github.com/SiliconValley22-Blossom/docker.git
```

## 서브모듈 동기화 시 develop 브랜치로 변경

```
git config -f .gitmodules submodule.frontend.branch develop
git config -f .gitmodules submodule.backend.branch develop
```

## 서브 모듈 업데이트
```
git submodule update --remote
```

# clone 후 처음 실행
## frontend yarn 받기 (node 업데이트 권장)
```
cd frontend
yarn install
```

## 프로젝트 루트로 이동 후 빌드
```
cd ../
docker compose up --build
```

## 그 이후 실행
```
docker compose up
```

# 배포 환경 실행
```
docker-compose -f docker-compose.prod.yml --env-file settings/prod.env  up --build
```

## 프로젝트 개요


## 프로젝트 아키텍처
![image](https://user-images.githubusercontent.com/55674648/182015290-475222f1-9a9d-4d0d-916d-2d775421f7b5.png)


## 아키텍처 디자인 패턴
### 프론트 아토믹 디자인
### 백 레이어 패턴

## AI 트레이닝 설명

## 기능 구성 (프론트 페이지 GIF)

## API DOCS

## 모니터링 툴

## 프로젝트 참여자
<table width="950">
    <thead>
    </thead>
    <tbody>
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
            frontend<br>
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
            <a href="https://github.com/zyooniverse">
                <img src="http://img.shields.io/badge/zyooniverse-green?style=social&logo=github"/>
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
