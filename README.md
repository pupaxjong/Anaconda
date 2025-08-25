# Anaconda
- [아나콘다 설치하기](https://www.anaconda.com/)

## Windows
Anconda PowerSheel Prompt
Anaconda Prompt

## Commands
- conda env list : conda 에 설치된 env list 를 보기
- conda create -n [env_name] : env 설치
- conda env remove -n [env_name] : env 삭제

- conda activate -n [env_name] : env 활성화 하기
- conda deactivate -n [env_name]  : env 비활성화 하기. 이전 Activate 된 env 로 변경됨.

- conda list : 현재 활성화된 env 에 설치된 패키지 리스트를 보기
- conda search [channel::package]  : 패키지 검색
- conda install channel::package==version : 특정 버전 패키지 설치. ==version 제거하면 마지막 버전 설치.

- 클론 생성 : conda create -n [env_name] --clone  env [existing_env]
- 이름 변경 : conda rename -n [old_name] [new_name]
- export : conda export > [env_file.yml]   : .yml 확장자.
- import : conda env create --file [env_file.yml]        -> Terminal / Anaconda Prompt 가 name.yml 의 경로에 있어야 함.

### Anaconda Update
- conda update -n base conda
- conda update --all
- python -m pip install --upgrade pip
