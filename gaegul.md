# git bash



## 기본 사용법

### 	폴더 안의 파일 돌려주기

​		ls 를 사용한다



### 	파일 생성 및 삭제

​		touch 파일이름.확장자

​		rm 파일이름.확장자



### 	폴더 생성 및 삭제

​		mkdir 폴더이름

​		rm -r 파일명



### 	이동 및 수정 관련

​		cd 폴더명 : '폴더명'으로 이동

​		cd .. : 현재 폴더 기준, 상위 폴더로 이동

​		mv 파일명.확장자 폴더명 : '파일명'이 '폴더명'으로 이동

​		mv 파일명 바꿀파일명 : 바꿀 파일명으로 이름 변경



### 	master

​		어디서 master가 되느냐 가장 중요

​		git init : master가 되어보자

​		rm -rf .git : 관리자 권한 삭제

​		git init

​		touch README.md

​		git add .

​		never do that

​		폴더에서 git init 진행

​		리포 안에 피로 만들기

​		git init 입력 전 확인 사항



### 	모니터링 명령어

​		'''

git status	# 현재 상황, 우리의 사진이 어디에 있는지 확인하는 명령어

git log 		#commit 로그, 앨범의 사진을 보는 명령어

git add <filename>		#스테이지로 올려버리는 명령어

git commit -m 'MESSAGE'

​		'''
원격 저장소 (remote app)