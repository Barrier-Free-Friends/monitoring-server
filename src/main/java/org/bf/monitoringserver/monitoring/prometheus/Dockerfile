FROM prom/prometheus:latest

COPY prometheus.yml /etc/prometheus/prometheus.yml

# 실행 시 설정 파일 적용
CMD [ "--config.file=/etc/prometheus/prometheus.yml" ]