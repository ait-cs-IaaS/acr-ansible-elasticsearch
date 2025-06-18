# Ansible Role: elasticsearch

This role installs and configures [elasticsearch](https://www.elastic.co/de/what-is/elasticsearch)

## Defaults

```yaml
# ELK vars
elastic_stack_version: 9.0.0
elastic_initial_password: Mozart.R0cks!

## xpack security settings
elasticsearch_xpack_ssl_ca: /path/to/local/ca.crt
elasticsearch_xpack_ssl_cert: /path/to/local/elasticsearch.crt
elasticsearch_xpack_ssl_key: /path/to/local/elasticsearch.key
elasticsearch_xpack_http_ssl_ca: /path/to/local/ca.crt
elasticsearch_xpack_http_ssl_cert: /path/to/local/elasticsearch.crt
elasticsearch_xpack_http_ssl_key: /path/to/local/elasticsearch.key

elasticsearch_users: []
elasticsearch_system_users: []
elasticsearch_roles: {}
```

