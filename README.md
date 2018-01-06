## Anaconda

- **Install**
   - [본 링크를 클릭 후, 자신의 OS와 같은 'Python 3.6 version'을 다운로드받으 후 설치하자](https://www.anaconda.com/download/#macos)

- **Run**
    - Windows일 경우, `Windows 키`를 클릭 후, **Anaconda Navigator**를 검색하여 실행하자.
    - MacOS일 경우, `command + space`를 입력 후, **Anaconda Navigator**를 검색하여 실행하자.
    - [실행 후, `Environments`를 클릭하자.](https://www.dropbox.com/s/e3xukgvgl1cvn1t/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202018-01-05%2020.07.59.png?dl=0)

- **Create your own python**
    - ['Create' 버튼을 클릭한다.](https://www.dropbox.com/s/jaostbbzroq08tf/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202018-01-05%2020.13.12.png?dl=0)
    - ['about_python' 입력 —> 3.6 클릭 —> 'Create'버튼 클릭](https://www.dropbox.com/s/rhhxjrxucnx7qop/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202018-01-05%2020.15.05.png?dl=0)

## Jupyter

- **Install**
  - [본 링크 스크린샷에 표기된 화살표 순서로 Jupyter를 설치하자](https://www.dropbox.com/s/frnrfi9d29z305s/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202018-01-05%2020.31.17.png?dl=0)
- **Run**
  - ['Open with Jupyter Notebook'을 클릭하자](https://www.dropbox.com/s/rhwjf58cvf6vd4l/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202018-01-06%2012.03.00.png?dl=0)
  - [폴더를 만들어보자](https://www.dropbox.com/s/mz6h18cwuxwbvai/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202018-01-06%2012.08.07.png?dl=0)
  - [방금 만든 폴더를 체크한 후, 화면 상단에 있는 'rename'을 누르자](https://www.dropbox.com/s/ew03muoyfr4k1at/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202018-01-06%2012.09.27.png?dl=0)
  - ['about_python'이라고 이름짓자](https://www.dropbox.com/s/34g9e0r7wh2aos0/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202018-01-06%2012.10.46.png?dl=0)
  - ['about_python' 폴더로 들어간 후, JupyterNoteBook 파일을 만들자](https://www.dropbox.com/s/wci5jsw8k5h3lxp/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202018-01-06%2012.12.15.png?dl=0)



## Github

- **Setting**
  - 먼저, [GitHub.com](https://github.com/)에 가입한다. 다른 소셜 네트워크에 가입하는 것처럼 간단하다. 로컬 컴퓨터에서 작업하려면 깃을 설치해야 한다. 

  - [필요에 따라](http://git-scm.com/downloads) 윈도우, 맥, 리눅스 용 깃을 설치하라.

  - 이제 커맨드 라인으로 넘어갈 시점이다. 윈도우에선 방금 설치한 Git Bash 앱으로, OS X에선 터미널로 시작한다. 

  - 깃에 자신을 소개할 차례이다. 다음 코드를 타이핑한다.

  - ```
    git config --global user.name "Your Name Here"
    ```

  - 물론, “Your Name Here”의 인용부호 안에 자신의 이름을 넣어야 한다.

  - 다음엔, 당신의 이메일을 말해준다. 조금 전에 GitHub.com을 가입할 때 사용한 이메일이어야 한다. 다음과 같이 한다.[(참조자료)](https://www.dropbox.com/s/4khsbqjhgtxeprz/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202018-01-06%2012.21.44.png?dl=0)

  - ```
    git config --global user.email "your_email@youremail.com"
    ```

    ​


- **온라인 저장소 만들기**
  - 이제 프로젝트가 거주할 장소를 만들 시점이다. 
  - 깃과 깃허브는 당신의 프로젝트와 그 화일들, 깃이 저장한 화일들의 모든 버전에 접근할 수 있는 디지털 디렉토리나 저장공간을 저장소(repository 줄여서 repo)라고 한다.
  - GitHub.com으로 돌아가서 사용자명 다음에 있는 작은 책 아이콘을 클릭한다. 혹은, 모든 아이콘이 다 똑같아 보인다면 [new repository page](https://github.com/new)로 간다. 
  - [저장소에 짧고 기억할만한 이름을 준다. 재미삼아 public으로 해본다.](https://www.dropbox.com/s/viwjuacexd9ibgp/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202018-01-06%2012.59.15.png?dl=0)
    - 위의 스크린샷에서, “Initialize this repository with a README.” 앞의 체크박스는 신경쓰지 않는다. Readme 화일은 보통 프로젝트에 관해 설명하는 텍스트 화일이다. 여기선 연습삼아 로컬에서 자신의 Readme 화일을 만들 것이다
    - 위의 스크린샷에서 녹색의 “Create Repository” 버튼을 클릭한다. 이제 프로젝트가 거주할 온라인 공간을 가진 것이다.


### Install

### Run

### Basic



## Docker

### Install

### Run

### Basic

