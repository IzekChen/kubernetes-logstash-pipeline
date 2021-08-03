### Logstash Pipeline for log collection ###
Consumer different type of logs from Jenkins, Application or others.
The logs are formatted through a Logstash filter.



### Pipeline details

| Pipeline name  | Pipeline port | Pipeline configmap name | Service name | Service Port name | Service Port number | 
| -------------  | ------------- | ------------------------| ------------ | ----------------- | ------------------- |
|  ls-jenkins    |      9980     | logstash-jenkins.conf   | logstash | ls-jenkins | 9980 |
| logstash-alerts  | 9981  | logstash.conf |  logstash | ls-alerts  | 9981  |