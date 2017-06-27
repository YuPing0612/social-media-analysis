# 2017/07/05 情資分析

### Lab1

We use `ELK`(**E**lasticsearch, **L**ogstash, **K**ibana) to collect tweets on Twitter about information security issues.



> download  [elasticsearch](https://www.elastic.co/downloads/elasticsearch),[logstash](https://www.elastic.co/downloads/logstash),[kibana](https://www.elastic.co/downloads/kibana)



> setting logstash config（twitter keys: https://apps.twitter.com/）

    input{
    	twitter {
    		consumer_key => "xxx"
    		consumer_secret => "xxx"
    		oauth_token => "xxx"
    		oauth_token_secret => "xxx"
    		keywords => ["keyword"]
    		full_tweet => true
    	}
    }
    output{
    	elasticsearch{
    		index => "your index name"
    	}
    }


> run Elasticsearch, Logstash ,Kibana

<img width="1280" alt="2017-06-27 16 45 19" src="https://user-images.githubusercontent.com/19222283/27580426-1a1f9dc8-5b5d-11e7-8926-01abbe2139a1.png">

<img width="1280" alt="2017-06-27 16 47 32" src="https://user-images.githubusercontent.com/19222283/27580428-1e1de790-5b5d-11e7-9df3-bd7d8cc49bf6.png">
