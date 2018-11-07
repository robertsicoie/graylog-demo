Build images and start graylog, MongoDB and Elasticsearch containers
`
$ docker-compose up -d
`
Open graylog in browser: http://localhost:9000

Send test log message
`
$ echo "This is my first log message" | nc localhost 5555
`

Install graylog sidecar: http://docs.graylog.org/en/2.4/pages/collector_sidecar.html#graylog-collector-sidecar


