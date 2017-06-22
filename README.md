# logstash
## my logsash config

ELK (Elasticsearch + Logstash + Kibana) is fun!

Logstash is super flexible, most operations can be.

## memo

Start separately Java process, shipper indexer.
(divided into two by copying the startup script that is distributed in the package version)

## reference

 postfix grok patterns :
 * https://github.com/whyscream/postfix-grok-patterns
 * https://gist.github.com/poolski/9911628
 * https://gist.github.com/jamtur01/4385667
 * https://gist.github.com/randywallace/6983588

 sshd grok patterns :
 * https://github.com/autosportlabs/docker-logstash/blob/master/src/conf/520-mogrify-sshd.conf

 Lightweight log shipper : logstash-forwarder (aka lumberjack)
 * https://github.com/elasticsearch/logstash-forwarder
 * https://www.digitalocean.com/community/tutorial_series/centralized-logging-with-logstash-and-kibana-on-ubuntu-14-04
 * https://www.digitalocean.com/community/tutorials/adding-logstash-filters-to-improve-centralized-logging

 grok filter ruby :
 * https://groups.google.com/forum/#!topic/logstash-users/iEYRv7bCqdM
 * http://stackoverflow.com/questions/20512416/adding-tags-to-logstash-events-based-on-the-md5-of-the-filename

 kibana geoip BetterMap :
 * https://beingasysadmin.wordpress.com/2014/04/07/near-realtime-dashboard-with-kibana-and-elasticsearch/
 * http://dev.maxmind.com/geoip/legacy/geolite/

 grok apache User-Agent :
 * http://untergeek.com/2013/09/11/getting-apache-to-output-json-for-logstash-1-2-x/
 * https://github.com/ua-parser/uap-core/blob/master/regexes.yaml

 Integrating DataDog
 * http://ifdattic.com/integrating-datadog-and-logstash-on-aws-ec2/

 zimbra mailbox.log & zimbra.log (amavis)
 * http://blog.itlinux.cl/blog/2015/05/25/buscando-mensajes-de-correo-con-kibana/
 * https://github.com/ITLinuxCL/zimbra_logstash
 * http://antisp.in/2014/04/01/useful-logstash-grok-patterns/
 * https://github.com/Autobase/Zimbra/blob/4bf3dc250c68a38e38286bdd972c8d5469d40e34/ZimbraCommon/src/java/com/zimbra/common/util/ZimbraLog.java
 * https://wiki.zimbra.com/wiki/Centralized_Logs_-_Elasticsearch,_Logstash_and_Kibana
 * https://blog.zimbra.com/2007/05/mailboxlog-the-king-of-zimbra-log-files/
 * https://www.zimbra.com/docs/os/5.0.19/administration_guide/9_Monitoring.11.1.html
