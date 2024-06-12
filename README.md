# Grafana Dashboard Template
- Grafana Dashboard 구성은 이제 그만..  

## 디렉토리 구조
``` text
├── README.md
└── prometheus
    └── spring-boot-actuator
        ├── cache.json               @see https://grafana.com/grafana/dashboards/21303-cache/
        ├── hikaricp-jdbc.json       @see https://grafana.com/grafana/dashboards/21064-jvm-micrometer/
        └── jvm.json                 @see https://grafana.com/grafana/dashboards/20729-spring-boot-jdbc-hikaricp/
```
- 우측 url은 2가지 경우 중 하나를 의미한다.
  - 제공된 template을 기반으로 수정한 경우
  - 직접 구성해 공유한 경우