# task

## 과제방에 repo 주소로 업로드

1. task repository 포크로 본인 repository에 복사
2. 내려 받기해서 해당 README.md 문서 수정
3. 오늘까지 배운 git 내용 마크다운 형식으로 __잘__ 정리
  _markdown-cheetseat 참고_
4. 본인 repository에 업로드
5. 로컬 저장소 내용도 캡쳐해서 함께 업로드

이 아래로 내용 작성
-
# Git # 

## Git의 기본적인 설정

Git을 사용할 폴더를 생성한뒤 **Git Bash Here** 을 클릭하여 Git Bash 클라이언트를 키거나 

Git Bash 클라이언트에서 CLI 명령어를 사용하여 해당 폴더로 이동한다

**git init**를 입력하면 .git 폴더가 생성되며 git main 저장소가 생성된다.

**git config --global user.name "ID"**

**git config --global user.email "EMAIL@EMAIL.COM"** 을 

github 계정과 동일하게 설정해준다

## Git의 주요 명령어 ##

**git config --list** = 정보 확인

**git add README.md** = 특정 파일 추가 

**git add .** = 모든 파일 추가

**git commit -m "설명"** = 설명란에 쓴 내용과함께 커밋(저장)함

**git commit -am "설명"** = 한번이상 커밋한 이후에 사용가능 하며 add + commit을 한꺼번에 처리해줌

**git status** = 현재 상태 확인

### log ###

**git log** = 모든 커밋 기록 확인

#### log 뒤에 입력하는 명령어 ####

**--oneline** = 한줄씩 요약된 커밋 기록 확인

**--graph** = 그래프가 추가된 커밋 기록 확인

**--all** = 그동안 생성된 브랜치까지 확인하여 기록 확인

### Branch ###

**git branch abc** = abc 라는 이름의 브랜치 생성

**git switch abc2** = abc2 라는 이름의 브랜치로 이동

**git merge abc** = 현재 브랜치에서 abc 브랜치와 합침

**git branch -a** = 브랜치 리스트 확인


## GitHub와 연동시 사용하는 명령어 ##


### push(업로드) ###

**git push -u origin main** = main 브런치에 push 하는 경우

**git push origin 브런치이름** = 다른 브런치에 push 하는 경우 

### pull(다운로드) ###

**git pull (origin main)** = main 브런치에서 pull 하는 경우

**git pull origin 브런치이름** = 다른 브런치에서 pull 하는 경우

### github에서 내 로컬 저장소로 복사하기 ###

**git clone https://~** = 내 로컬 저장소에 폴더가 없는경우 폴더를 생성후 복사

**git clone https://~ .** = 내 로컬 조장소에 이미 폴더가 있는 경우 그 폴더에 복사





