# KG-ML-Study

### 사전 준비하기
- homebrew 설치
  - https://brew.sh/index_ko.html
  
- Python 설치 
~~~  
  1. 버전 확인 : python -V
  2. 2버전 설치 or 미설치 시 3버전 설치가 필요함
    brew install python3
  3. python3 alias 설정
    vi ~/.bash_profile 
    a버튼 입력 후 INSERT 상태 변경. 최상단에 아래 명령어 한줄 추가 alias python=“python3" 
    esc 버튼 입력 -> : 입력 -> wq 입력 -> 엔터
    source ~/.bash_profile
  4. version 확인 (python -V 명령어)
~~~

- Anaconda / Jupyter notebook 설치 (아래 페이지 이동 후 설치)
  - http://jupyter.readthedocs.io/en/latest/install.html
  - https://www.anaconda.com/download/
  - 버전 확인 : conda -V
  - 버전이 확인되면 정상 설치되었음.
  - 실행방법 (아래 2가지 방법)
  -- Anaconda 실행 후 Jupyter notebook 실행
  -- 터미널에서 jupyter notebook 입력

### GitHub 연동하기
- git clone (원격 저장소 -> 로컬 저장소로 복사)
  - 로컬 저장 위치로 이동 git clone https://github.com/james-jjj/KG-ML-Study.git
- 초기 설정 진행 (교재 진행에 필요한 필수 모듈 설치)
  - pip install -r requirements.txt
- 본인 폴더 생성 및 테스트 코드 작성
  - KG-ML-Study/james/HelloWorld.ipynb 참고
- git 업로드 (본인의 브랜치에 업로드)
  - git 브랜치생성
    - git checkout -b {브랜치 이름}
  - add
    - git add *
  - commit
    - git commit -m "커밋 내용을 입력"
  - push
    - git push origin {브랜치이름}
    - 저장소 찾지 못할 경우 : git remote add origin https://github.com/james-jjj/KG-ML-Study.git
    - 최초 1회 github ID / password 입력
- github.com/james-jjj/KG-ML-Study 접속 후 정상 커밋 확인
---

#### 참고1. TensorFlow Machine Learning Cookbook
- https://github.com/nfmcclure/tensorflow_cookbook
- http://acornpub.co.kr/book/tensor-machine-learning-cook

#### 참고2. git - 간편 안내서
- https://rogerdudler.github.io/git-guide/index.ko.html

#### 참고3. Simplicity and power in a beautiful Git GUI
- https://www.sourcetreeapp.com/

