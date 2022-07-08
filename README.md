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

## clone 후 처음 실행
```
docker compose up --build
```

## 그 이후 실행
```
docker compose up
```
