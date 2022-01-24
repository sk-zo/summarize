# summarize
BART 및 BERTSUM 사용방법입니다.

### BERTSUM
* 다음 명령어를 실행합니다.
  * git clone https://github.com/microsoft/nlp-recipes.git

* ~/nlp-recipes/utils_nlp/models/transformers/extractive_summarization.py 파일을 본 저장소의 파일로 교체합니다.

* ~/nlp-recipes/examples/text_summarization/ 위치에 본 저장소의 bertsum_train.ipynb, create_dataset.ipynb 파일을 추가합니다.

### BART

* ~/lib/python3.7/site-packages/transformers/models/bart/modeling_bart.py 파일을 본 저장소의 파일로 교체합니다.

### 실행 순서

  1. bertsum_train.ipynb: BERTSUM 학습
  2. create_dataset.ipynb: 데이터셋 생성
  3. bart_base.ipynb / bart_ppsd: BART 학습 및 평가

### 코드 수정
* modeling_bart.py에서 method option 검색
