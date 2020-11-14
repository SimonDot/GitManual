# GitHub Manual
Github manual Kor.
* * *
## 1. 초급 - 기본명령어
* 연결하고싶은 폴더 우클릭 후 git bash 실행하여 명령어 작성.

### -2. Git 설치 후 최초 설정.
최초 설치 후 1회 실행하면 된다.

>* git config --global user.name "--"
>	* user.name 설정
>* git config --global user.email "--@--"
>	* user.email 설정
>* git config --list
>	* 설정 확인.

### -1. Git 초기화.
폴더 지정 후 1회 실행하면 된다.

>* git init
>	* 폴더 내부에 git 파일이 생성 됨.

### 0. Github 저장소 연결 및 해제
폴더 지정 후 1회 실행하면 된다.

>* git remote add origin https://----
>	* 저장소 연결
>* git remote rm origin
>	* 저장소 링크 잘못 연결시 삭제.

### 1. Github 당겨오기
올리기 전에 당겨오기 부터 해야한다.
>* git pull origin master
>	*현재 작성한 내용이 최신버전일때 당겨오면 덮어씌어지므로 주의.?????? 오늘은 괜츈네

### 2. Github 올리기
깃허브 저장소 업로드 순서

로컬PC -> INDEX -> HEAD -> GitHub
>* git status
>	* 파일 상태 확인.
>* git add .
>	* 변경된 모든 파일 INDEX로 업로드.
>* git commit -m "--"
>	* 커밋을 하게되면 HEAD로 업로드.
>* git push origin master
>	* GitHub 업로드 완료.

* * *
## 2. 중급
### 1. 깃 당겨오면서 초기화
>* git clone https://----
>	* 다운로드 후 git init 과 동일하다.

### 2. 브랜치

### 3. 병합

* * *
## 3. 고급
### 리포지터리 생성 시 README.md 생성과 로컬에서 README.md 차이점.
> 리포지터리 생성 시 README.md 생성하게 되면 브랜치는 master가 아닌 main으로 생성이 된다.

> README.md 파일은 마크다운형식으로 작성.
> 마크다운 형식 테스트 링크.

포크, 코드리뷰, >>이부분도 안되고있음
블럭인용문자 사용 후 두줄 띄기 안하면 줄바꿈이 안된다.
