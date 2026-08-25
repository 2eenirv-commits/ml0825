# 새 폴더 & 새 레포지터리
## 1. Git 로컬 저장소 초기화 및 기본 브랜치 지정
git init -b main

## 2. GitHub 저장소 생성 + 원격 연결
gh repo create my-app --public --source=. --remote=drigin

# 파일 작성후 
## 1. 당겨 내려 받기(깃허브 저장소->내 컴퓨터 폴더)
git pull

## 2. 밀어 올림(내 컴퓨터 폴더->깃허브 저장소)
git add.
git commit -m "Add new feature"
git push

## 위아래 방향키: 이전 명령어 선택
