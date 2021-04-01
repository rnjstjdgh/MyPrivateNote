# 모니터링이란? , 모니터링의 필요성

    * 특정 소프트웨어를 운영하게 되면 장애가 발생할 가능성은 항상 존재함

    * 시스템의 상태를 명확하게 파악하기 어렵다면 장애를 미리 방지할 수 없을 뿐 아니라 장해가 발생했을 때에 원인을 찾는 것도 어려울 것임

    * 모니터링 서버를 잘 구축해 두면 시스템의 상태를 명확히 인지할 수 있을 것이고 이를 바탕으로 여러 직관과 장애에 대한 예측, 대응이 가능할 것임

    * 따라서 모니터링이 필요함

    * 모니터링을 위한 오픈소스 중 Prometheus를 살펴볼 것임

# Prometheus

    0.  대략적인 설명

    1.  Exporter Example

        1. node_exporter            => linux
        2. WMI exporter             => window
        3. spring boot actuator     => spring boot

    2.  Pushgateway(x)

    3.  Prometheus
        
        1.  Service Discovery  
        2.  PromQL

    4.  alert
    
        1. prometheus 내부에 정의된 rule
        2. alertmanager
    
    5. Grafana



# Demo 