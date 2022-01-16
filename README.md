# summarize
BART 및 BERTSUM 사용방법입니다.

### BERTSUM
* 다음 명령어를 실행합니다.
  * git clone https://github.com/microsoft/nlp-recipes.git

* ~/nlp-recipes/utils_nlp/models/transformers/extractive_summarization.py 파일을 본 저장소의 파일로 교체합니다.

* ~/nlp-recipes/examples/text_summarization 위치에 본 저장소의 bertsum_train.ipynb, create_dataset.ipynb 파일을 추가합니다.

### BART

* ~/lib/python3.7/site-packages/transformers/models/bart/modeling_bart.py 파일을 본 저장소의 파일로 교체합니다.

### 파일 설명

  * bertsum_train.ipynb: BERTSUM 학습
  * create_dataset.ipynb: 학습 데이터 생성
  * bart_train.ipynb: BART 학습
  * bart_test.ipynb: BART 테스트

#### 자세한 설명은 파일의 주석을 참고해주시면 감사하겠습니다.
