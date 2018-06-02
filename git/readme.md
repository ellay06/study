#Git study

##기본 개념
- Working Directory : 로컬 저장소
- Index (Staging Area) : 버전 관리 대상 파일 로컬 임시 저장소
- Local Repository : 로컬 깃 저장소
- Remote Repository : 원격 깃 저장소

##기본 명령어 (로컬)
- git init
- git status
- git add
  - 전체 파일 : git add * | git add .
- git commit
  -  
- git log
- git reset
- git rm --cached : git add 삭제, --cached 옵션이 없는 경우 실제 파일도 삭제


##기본 명령어 (원격)
- git remote add origin [github url] : 원격 저장소 추가
- git remote -v : 원격 저장소 정보
- git remote push 
- git pull origin master : 원격 저장소에서 프로젝트를 가져온다.


##브런치

