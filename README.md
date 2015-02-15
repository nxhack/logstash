# logstash
## my logsash config

ELK (Elasticsearch + Logstash + Kibana) 面白い。

Logstash は柔軟すぎるぐらい柔軟なので、大抵の操作はできる。

grok pattern は github や web で漁ったのを改変してます。

## 参考にしたサイトとコード

* postfix grok patterns :
 * https://github.com/whyscream/postfix-grok-patterns
 * https://gist.github.com/poolski/9911628
 * https://gist.github.com/jamtur01/4385667
 * https://gist.github.com/randywallace/6983588

* sshd grok patterns :
 * https://github.com/autosportlabs/docker-logstash/blob/master/src/conf/520-mogrify-sshd.conf

* Lightweight log shipper : logstash-forwarder (aka lumberjack)
 * https://github.com/elasticsearch/logstash-forwarder
 * https://www.digitalocean.com/community/tutorial_series/centralized-logging-with-logstash-and-kibana-on-ubuntu-14-04
 * https://www.digitalocean.com/community/tutorials/adding-logstash-filters-to-improve-centralized-logging

* grok filter ruby :
 * https://groups.google.com/forum/#!topic/logstash-users/iEYRv7bCqdM
 * http://stackoverflow.com/questions/20512416/adding-tags-to-logstash-events-based-on-the-md5-of-the-filename

* kibana geoip BetterMap :
 * https://beingasysadmin.wordpress.com/2014/04/07/near-realtime-dashboard-with-kibana-and-elasticsearch/
 * http://dev.maxmind.com/geoip/legacy/geolite/

* grok apache User-Agent :
 * http://untergeek.com/2013/09/11/getting-apache-to-output-json-for-logstash-1-2-x/
