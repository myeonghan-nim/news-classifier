# News Classifier(Demo.ver)

## 0. 시작하기 전에

- `requirements.txt`의 lib을 설치해주세요.

```bash
$ pip install -r requirements.txt
```

## 1. 파일 설명

- `articles_ko.csv`: classifier의 X를 담당하는 데이터가 들어있습니다.

- `label_ko.csv`: classifier의 y를 담당하는 데이터가 들어있습니다.

  - `True`: 전날 대비 주식 가격 상승 시

  - `False`: 전날 대비 주식 가격 하락 시

  - `NaN`: 전날 대비 주식 가격 변동 없음

- `news_classifier_ko.ipynb`: jupyter notebook 파일로 순서대로 실행해주세요.

- 기타 파일들은 우선 내버려두세요.
