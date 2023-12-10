# 🗺️ Python Folium을 사용해서, 대한민국 법정동 경계선 시각화해보기

### 1️⃣ 소개
- Python folium을 사용해 대한민국 법정동 경계선을 시각화한 경험을 공유하는 글을 작성했습니다. 글에서 소개한 코드와 파일을 제공합니다.
  * 글 소개 : [Python Folium을 사용해서, 대한민국 법정동 경계선 시각화해보기](https://velog.io/@h-go-getter/Python-Folium%EC%9D%84-%EC%82%AC%EC%9A%A9%ED%95%B4%EC%84%9C-%EB%8C%80%ED%95%9C%EB%AF%BC%EA%B5%AD-%EB%B2%95%EC%A0%95%EB%8F%99-%EA%B2%BD%EA%B3%84%EC%84%A0-%EC%8B%9C%EA%B0%81%ED%99%94%ED%95%B4%EB%B3%B4%EA%B8%B0)
- `2.2. 법정동 경계선 시각화` 코드 실행 시 아래와 같이 시각화 해볼 수 있습니다.
![image](https://github.com/hoinnovation/Korea-area-map/assets/45919197/62536b29-c26a-4fa9-bb86-050b5be3602e) 



### 2️⃣ 디렉토리 설명
### 데이터 공유 
* GeoJson파일은 지오서비스에서 제공하는 대한민국의 행정구역에 대한 시도, 시군구, 읍면동(법정동), 에 대한 공간 데이터 [링크](http://www.gisdeveloper.co.kr/?p=2332)를 활용했습니다.
* (2023.12.10) 기준 가장 최신 데이터인 (2023년 7월 업데이트)를 활용했습니다.
  * [시군구 GeoJson파일 구글드라이브 공유](https://drive.google.com/file/d/1LeVTTpCUlPszLPQ_IUE60SNDdrdfTQ7l/view?usp=drive_link)
  * [읍면동 GeoJson파일 구글드라이브 공유](https://drive.google.com/file/d/11m7LrATcquLYVQKNJcYHOEAxB2dmGE33/view?usp=drive_link)

## 디렉토리 설명
```html
├── code
│	├── 2.1. Folium 소개
│	└── 2.2. 법정동 경계선 시각화
└── README.md
```

### 3️⃣ 참고 자료
* [Folium 시작하기](https://python-visualization.github.io/folium/latest/index.html) 
* [Folium github](https://github.com/python-visualization/folium)
* [Folium을 이용한 데이타 시각화](https://blog.naver.com/PostView.nhn?blogId=kcchang61&logNo=221350672356)
* [서울경제,박윤선의 부동산 TMI](https://www.sedaily.com/NewsView/1Z1IV774D6)
