# github
## windows에서 자격증명 확인 / github관련 자격증명 삭제
## gihhub 회원가입
## github 사이트에서 Repository 생성
  * Repository 주소 복사
  * 
## git 다운로드/설치
  * user.name / user.email 등록
    + git config --global user.name="dlsrb12123"
    + git config --global user.email="dlsrb12123@naver.com"
  * git config --list : 등록된 항목 확인
    
## github 토큰 신청/발급
* github.com 화면 우측 상단 아이콘 클릭 > Settings > 왼쪽 메뉴 하단 Developer settings > Personal access tokens >
* Tokens(classic) > Generate new token > Generate new token(classic) >
* Note:간단 설명 입력 > Generate token

## 로컬 Repository에 원격 리파지토리 복사
* 원격 저장소에 등록된 프로젝트를 최초로 로컬 저장소에 복제한다
* git init
* git clone(https://github.com/ingyu1/123.git)
* git config --list <-- origin 이라는 이름으로 원격 저장소의 주소가 등록된 것을 확인

최초로 저장된 내용 

 
확인 

확인

## 로컬 저장소의 내용변경 및 원격 저장소에 병합(push)하기
* 로컬 저장소에 있는 파일에 수정작업을 변경하고 저장한다
* git add . : 현재 디렉토리(프로젝트 루트)에서 staging 작업 실행(파일을 모은다)
* git status : 현재 상태 확인
* git commit -m "변경 내역에 기록할 메세지"
* git status
* git push -u origin main : origin은 원격 저장소의 주소에 대한 별칭으로 로컬에 설정된 상태임, main : 원격 저장소 브랜치 이름
* 위에 명령은 -u(--set-upstream) 설정, 인증을 위한 웹브라우저가 실행됨
* 웹브라우저 하단의 초록버튼을 누르고 화면이 전환되면 브라우저를 닫는다
* git 명령을 실행하던 콘솔창을 닫고 다시 실행한다
* git status 명령으로 git의 현재 작업 상태 확인
* 파일의 변경 상태가 표시되지 않으면 대상 파일을 열고 다시 변경하고 저장한다
* git add . : 변경된 로컬 저장소의 내용을 staging
* git status : 변경된 파일이 git에 의해 표시되는 지 확인
* git commit -m "변경내역에 기록할 메세지"
* git status : 위에서 commit 된 정보가 확인되는 지
* git push origin main : 최종적으로 로컬프로젝트를 원격 저장소(origin)의 main 브랜치에 병합한다
* github.com에 접속하여 해당 파일의 내용이 변경되었는 지 확인한다

>>>>>>> 668007eaafbf2788ce6bb92ee11b7e9f9a11f758
