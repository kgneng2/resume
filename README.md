# 🙆🏻‍♂️ Who?
## 강준영 Junyoung Kang
- _Data platform Engineer_ , _Backend Server Engineer_, _Data pipeline Engineer_
- 실시간처리가 그저 좋은 Engineer

## 🖥 Career
- LINE 광고 파견 (2017.07 ~ 2018.05)
- NAVER 입사 (2015.12 -ing) 

## ⌨️ github
- https://github.com/kgneng2/

## 📖 blog
- http://kgneng2.github.io/blokg

## 💻 Stack
## Framework
- spring : boot, web, service , spring-yarn 
- kafka : kafka 이용 및 stream, connector 활용 
- spark sql, streaming 개발
- Elasticsearch 이용(ELK) 및 plugin 개발 운영
- CDH, Hadoop eco system 활용 (Yarn, Hbase, Spark, HDFS 등)
- mongodb 이용 및 운영
- Redis 이용 및 운영
- druid 운영
    - druid streaming , cluster 운영
      - tranquility 
      - kafka indexing 운영 및 적용
- airflow 이용한 batch 작업 진행 
- zeppelin 운영 및 활용 (데이터 검증 및 디버깅)

## Language
- Kotlin, Java (JVM)
- Scala 
- Python


-----

# 프로젝트
## Send (2016.03 ~ )
- sms, email, 사내 메신저, NaverTalkTalk 사내/사외 알림 발송 및 이력 제공 서비스 (네이버 검색광고 및 플레이스 대상)
  - 웹서버 운영 및 개발
  - API 제공 및 UI 페이지 제공 
  - 로그 및 이력 제공
- Spring boot, mustache, elasticsearch, streamset, kafka  
- elasticsearch 로그 저장 및 디버깅, mysql을 이용하여 서비스 로그 제공

## Dunkerque (2016.10 ~ 2017.05)
- Elasticsearch 기반 key-value storage
- elastic search plugin 
- bulk, multi get, 등 기능 개발 

## message-batch 개발 (2017.02 ~ )
- Oracle db 읽고 수신 여부 확인 후 문자, 이메일 발송
- spring boot  + spring actuator 적용
- Mybatis -> JDBC template + groovy 적용 

## HbaseMapper Annotation Library 개발 (2016.12 ~ 2017.03)
- Java POJO 모델에 Annotation 기반으로, Hbase 데이터와 POJO 모델간에 serialize, deserialize 개발 및 활용

## LINE AD data pipeline 
- schema-registry 운영
- neon api 연동 batch 개발 -> airflow 이용
- spark batch 는 cluster mode일때는 비동기 처리여서 바로 확인이 안되기 때문에 LivySparkOperator를 이용함
    - https://github.com/rssanders3/airflow-spark-operator-plugin
- report batch 개발 
- druid 운영 
- spring streaming 
- spark batch report  + airflow 작업 진행
    - performance report + conversion report 
    - Cluster mode 할 때 jar를 매번 옮기는데, 옮기지 않게 하기 위해서, hdfs에 업로드해서 처리함
- Elastic search Logstash Kibana : 주로 담당. Aurora platform 에 log stash 진행

## tachikoma
- 광고주의 Landing Page나 Content Network Page들의 분석을 위한 웹크롤링 시스템
- api server 개발 
    - 소재 스크린샷 제공 api 운영
- dump spark batch 
- collector 개발 (spring-yarn)
    - kafka -> hbase


## Dwis (Do what i script)
- 광고 API 
- JVM 기반 JavaScript Engine 기반 batch service
    - Script CRUD API server 개발
    - Script Batch scheduler 개발 
- ~네이버용 구글 Ads script라 생각하면 편함~
- Kotlin + spring boot  , mongo db, Kafka ,elastic search, kibana, js engine nashorn 이용. => graalvm

## Shopping log pipeline 개선
 - Streamset  기반 처리에서 kafka stream + kafka connector 로 전환 
    - lag, process 상태 개선 
    - 로그 및 
- Aitems 반응형 추천 데이터 제공 (kafka stream 이용)
- kubernetes 적용 시도

## SRE
- Bmon-bot 개발 진행 kotlin + command line
- CDH monitoring Golang + Prometheus 진행 
- Spark streaming + kafka + streamiest + ES 검색광고 클릭 로그 및 매출 집계 개발  ( go + scala)


---------

