FROM docker.elastic.co/logstash/logstash-oss:6.3.0
ADD ./httpd_logs /var/log/httpd
ADD ./conf.d /usr/share/logstash/config
CMD chmod -R 755 /usr/share/logstash/config