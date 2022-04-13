# Decison Location of Senior Center on Data Analytics for Age-friendly Busan
고령친화도시 위한 데이터 기반 최적 경로당 입지 선정 


## 개요
국제보건기구 WHO는 [Age-Friendly World](https://extranet.who.int/agefriendlyworld/age-friendly-cities-framework/) 프레임워크 내 8개의 상호연결된 도메인을 제안하였습니다. 도메인은 노인들의 건강과 참여에 대한 경계를 식별 및 언급하는데 도움을 줄 수 있습니다. 우리는 오픈 데이터 기반 로케이션 인텔리젼스 프레임워크를 제안함으로서 고령친화 도시 부산에 관련된 정책의 투명성과 정책품질의 향상을 추구합니다. 고령친화도시 부산의 정책적 방향은 5대 전략과 20대 과제, 110개의 세부사업으로 구성됩니다 [관련링크](http://afc.bswdi.re.kr/Main.do). 우리의 목표는 진행중/실시될 정책에 대하여 오픈 데이터와 함께 분석사례를 만들어 재사용 및 재생산이 가능하면서도 확장가능한 오픈소스 기반 분석 프레임워크와 그에 대한 사례를 개발하는 것입니다.

## 현재단계

현재 프레임워크는 오픈소스 기반 GIS(Geographic Information Service)도구를 이용하여 시니어 센터의 입지 분석 기능을 지원합니다. 
1. 최적화된 입지분석을 위한 데이터 분석 과정 ( 접근성(도보 이동시간), 시니어 센터 이용률, 고령인구 변화 )
2. 부동산 이론을 차용하여 경로당 최적입지 수리적 모형 설정.

## 향후 진행방향
우리의 목표는 상업적 프레임워크를 사용하는 것이 아닌, 오픈소스 기반 분석 프레임워크를 향상 개발하고 이에 대한 분석사례 개발을 목표합니다.
1. 입지분석을 위해 고려해야할 요인을 추가
2. 현재 도로 네트워크의 교차점별로 데이터가 집계되어 있음. 집계데이터에, 통계학 방법/기계학습/딥러닝/그래프 방법론 등을 적용
3. 입지분석을 위해 다양한 시각적인 지도, 차트 구현.
4. 입지분석을 위한 편의시설에 대한 데이터 추가.(무료급식소, 종합병원, 약국)


## 특징

## 기술적 요구사항
- 코드 간결화
- 부동산, 고도, 이동 거리에 따른 시간을 수치화 할 수 있는 방법 
  - ex) 이동 시간(y) = A이동거리(x) + B (A,B : 부동산, 고도)
- 인구 예측 수식 고도화
- 주석 필수

## 국내 참고자료
- 노인복지시설 현황 분석
- 국내외 논문
- [서울시 빅데이터분석 사례](https://github.com/pwjdgus/Data_Analytics_for_Age_friendly_busan/blob/main/%EC%B0%B8%EA%B3%A0%EC%9E%90%EB%A3%8C/%EC%84%9C%EC%9A%B8%EC%8B%9C%20%EB%85%B8%EC%9D%B8%EC%97%AC%EA%B0%80%EB%B3%B5%EC%A7%80%EC%8B%9C%EC%84%A4%20%EC%9E%85%EC%A7%80%20%EB%B6%84%EC%84%9D.pdf)
- [부산 노인복지시설 현황](http://www.busansenior.or.kr/04find/01.php)
- 대한적십자 무료급식소 데이터 [[Link]](https://www.data.go.kr/data/15089276/fileData.do)
- 부산광역시_종합병원 현황 [[Link]](https://www.data.go.kr/data/15083386/fileData.do)
- 부산광역시_행정안전부 약국 [[Link]](https://www.data.go.kr/data/15045036/fileData.do)

- [공시지가, 경사도 고려](https://github.com/pwjdgus/Data_Analytics_for_Age_friendly_busan/blob/main/%EC%B0%B8%EA%B3%A0%EC%9E%90%EB%A3%8C/%EA%B3%B5%EC%8B%9C%EC%A7%80%EA%B0%80%2C%20%EA%B2%BD%EC%82%AC%EB%8F%84%20%EA%B3%A0%EB%A0%A4.pdf)
- [교통사고, 동별 노인인구, 유동인구 고려](https://github.com/pwjdgus/Data_Analytics_for_Age_friendly_busan/blob/main/%EC%B0%B8%EA%B3%A0%EC%9E%90%EB%A3%8C/%EA%B5%90%ED%86%B5%EC%82%AC%EA%B3%A0%2C%20%EB%8F%99%EB%B3%84%20%EB%85%B8%EC%9D%B8%EC%9D%B8%EA%B5%AC%2C%20%EC%9C%A0%EB%8F%99%EC%9D%B8%EA%B5%AC%20%EA%B3%A0%EB%A0%A4.pdf)
- [노인 실태조사](https://github.com/pwjdgus/Data_Analytics_for_Age_friendly_busan/blob/main/%EC%B0%B8%EA%B3%A0%EC%9E%90%EB%A3%8C/2020%EB%85%84%EB%8F%84_%EB%85%B8%EC%9D%B8%EC%8B%A4%ED%83%9C%EC%A1%B0%EC%82%AC_%EB%B3%B4%EA%B3%A0%EC%84%9C.pdf)
- [노인여가생활 동향 분석](https://github.com/pwjdgus/Data_Analytics_for_Age_friendly_busan/blob/main/%EC%B0%B8%EA%B3%A0%EC%9E%90%EB%A3%8C/%EC%A0%95%EB%B3%B4%ED%99%94%EC%97%90%20%EB%94%B0%EB%A5%B8%20%EB%85%B8%EC%9D%B8%EC%9D%B8%EA%B5%AC%20%EC%97%AC%EA%B0%80%EC%83%9D%ED%99%9C%20%EB%8F%99%ED%96%A5.pdf)
- [무료급식소 표준 데이터](https://www.data.go.kr/data/15013107/standard.do)
- [부산광역시_종합병원 현황](https://www.data.go.kr/data/15083386/fileData.do)
- [부산광역시_행정안전부 약국](https://www.data.go.kr/data/15045036/fileData.do)


## 관련 용어

[로케이션 인텔리젼스](https://www.esri.com/en-us/location-intelligence)(LI: Location Intelligence): [지리공간 데이터](https://www.ibm.com/topics/geospatial-data)(geospatial data)와 비지니스 데이터를 결합하여 새로운 인사이트(insight)를 발굴하는 과정을 의미합니다.

시니어 센터/노인복지시설


## 현재 노인복지시설의 문제점

- 도시개발에 중점을 둔 나머지 증가하는 노인인구에 비해 노인복지시설 개발은 늦어지고 있음
- 예전과는 다른 65세 이상 노인들의 수준에 맞지 않는 프로그램
- 노후화된 시설 방치
- 도시개발에 중점을 둔 나머지 증가하는 노인인구에 비해 노인복지시설 개발은 늦어지고 있습니다.
