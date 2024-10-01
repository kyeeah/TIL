# Git이란?
- 대표적인 분산형 버전 관리 시스템
- 원격 저장소와 별개로, 개발자 각각의 로컬 컴퓨터에 복제본 소스 코드를 저장 할 수 있음
- 네트워크나 인터넷이 연결되어 있지 않은 상태에서도 로컬 컴퓨터의 소스 코드만으로 버전 관리 가능
- 작업 후, 인터넷 연결되었을때 동기화하면 된다


<br>


## Git 설치 (macOS 환경)
```
brew install git
```
Homebrew가 설치되어 있다는 가정 하에, git을 설치한다.

Download URL : https://git-scm.com/downloads

<br>

## Git 연동
1. vscode에서 좌측 세번째 메뉴인 '소스제어'를 연다
2. 상단바에서 업로드할 폴더를 지정한다
3. 'github에 게시' 버튼을 클릭한다

<br>

## Git 커밋하기
1. Commit 버튼을 클릭한다.
2. (초기설정) 하단의 터미널에 접속하여 아래 명령어를 입력한다
<br>

    ```
    git config user.name (github 이름)
    git config user.email (github 이메일)
    ```
3. 