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

![螢幕快照 2017-06-27 16.45.19](../螢幕快照 2017-06-27 16.45.19.png)

![螢幕快照 2017-06-27 16.47.32](../螢幕快照 2017-06-27 16.47.32.png)