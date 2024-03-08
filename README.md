# starbucks_web_crawler
스타벅스 웹사이트의 매장 정보를 크롤링하고 json으로 저장하는 파이썬 코드

### 크롤러
1. crawler_v1_ : accurate but slow
2. crawler_v2_ : less accurate but very fast

### 크롤링 방식
* 스타벅스 페이지는 동적 페이지라서 selenium을 이용하여 각 시/도/구를 순회하며 데이터 추출
* crawler_1_은 시도 > 

### 데이터 형식
```
...
        {
            "지점면": "역삼아레나빌딩  ",
            "주소": "서울특별시 강남구 언주로 425 (역삼동)",
            "시군구": "서울특별시",
            "시도": "강남구",
            "타입": "G"
        },
...
```
