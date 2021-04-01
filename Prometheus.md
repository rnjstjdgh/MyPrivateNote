# 모니터링이란? , 모니터링의 필요성

    * 특정 소프트웨어를 운영하게 되면 장애가 발생할 가능성은 항상 존재함

    * 시스템의 상태를 명확하게 파악하기 어렵다면 장애를 미리 방지할 수 없을 뿐 아니라 장해가 발생했을 때에 원인을 찾는 것도 어려울 것임

    * 모니터링 서버를 잘 구축해 두면 시스템의 상태를 명확히 인지할 수 있을 것이고 이를 바탕으로 여러 직관을 얻을 수 있고 이를 통해 장애에 대한 예측, 대응이 가능할 것임

    * 따라서 모니터링이 필요함

    * ex> 특정 서버의 부하가 특정 시간에 높아지는 것을 인지하여 그 시간에만 리소스 확장
    * ex> network traffic이 일정 시간동안 일정 비율로 꾸준히 높아지게 되면 경고 알람 전송

    * 모니터링을 위한 오픈소스 중 Prometheus를 살펴볼 것임



# 목차
    0.  대략적인 설명(아키텍처)

    1.  Exporter Example

        1. node_exporter            => linux HW metric
        2. WMI exporter             => window metric
        3. spring boot actuator     => spring boot metric
        4. 그밖에 exporter

    2.  Pushgateway(x)

    3.  Prometheus
        
        1.  Service Discovery  
        2.  PromQL

    4.  alert
    
        1. prometheus 내부에 정의된 rule
        2. alertmanager
    
    5. Grafana


# 본론
0.  대략적인 설명(아키텍처)
![image](https://user-images.githubusercontent.com/41561652/113249662-09461800-92fa-11eb-8877-de69771aec08.png)



1.  Exporter Example

    1. node_exporter            => linux HW metric
    2. WMI exporter             => window metric
    3. spring boot actuator     => spring boot metric
    4. 그밖에 exporter

2.  Pushgateway(x)

3.  Prometheus
        
    1.  Service Discovery  
    2.  PromQL

4.  alert
    
    1. prometheus 내부에 정의된 rule
    2. alertmanager
    
5. Grafana


# Demo 



# Reference

* https://prometheus.io/docs/introduction/overview/
* https://grafana.com/
