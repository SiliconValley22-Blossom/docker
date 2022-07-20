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
