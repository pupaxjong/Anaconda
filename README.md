# Anaconda
- [아나콘다 설치하기](https://www.anaconda.com/)

## Windows
Anconda PowerSheel Prompt
Anaconda Prompt

## Commands
- 현재 활성화된 env 에 설치된 패키지 리스트를 보기 : conda list
- conda 에 설치된 env list 를 보기 : conda env list
- env 설치 : conda create -n name
- env 삭제 : conda env remove -n name
- env 활성화 하기 : conda activate -n name
- env 비활성화 하기 : conda deactivate -n name  -> 이전 Activate 된 env 로 변경됨.
- 클론 생성 : conda create -n name --clone 원본 env
- 이름 변경 : conda rename -n nam" new_name
- export : conda export > name.yml   : .yml 확장자.
- import : conda env create --file name.yml        -> Terminal / Anaconda Prompt 가 name.yml 의 경로에 있어야 함.

### Anaconda Update
- conda update -n base conda
- conda update --all
- python -m pip install --upgrade pip
