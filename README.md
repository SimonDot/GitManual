# GitHub Manual
Github manual Kor.
* * *
## 1. 초급 - 기본명령어
### -2. Git 설치 후 최초 설정.
* git config --global user.name "--"
* git config --global user.email "--@--"
* git config --list
> 설정 확인.

### -1. Git 초기화.
* git init

### 0. Github 저장소 연결 및 해제
* git remote add origin https://----
* git remote rm origin

### 1. Github 당겨오기
* git pull origin master
> 당겨오기 전에 변경내용 확인.???????

### 2. Github Index
* git status
* git add .
> 깃허브 저장소 업로드 순서
> 로컬PC -> INDEX -> HEAD -> GitHub

### 3. Github Head
* git commit -m "--"

### 4. Github 올리기
* git push origin master
> 2번 ~ 4번을 진행해야 업로드가 완료된다.
* * *
## 2. 중급
### 1. 깃 당겨오면서 초기화
* git clone https://----

### 2. 브랜치

### 3. 병합
* * *
## 3. 고급
### 리포지터리 생성 시 README.md 생성과 로컬에서 README.md 차이점.
> 리포지터리 생성 시 README.md 생성하게 되면 브랜치는 master가 아닌 main으로 생성이 된다.

> README.md 파일은 마크다운형식으로 작성.
> 마크다운 형식 테스트 링크.

포크, 코드리뷰,
블럭인용문자 사용 후 두줄 띄기 안하면 줄바꿈이 안된다.
