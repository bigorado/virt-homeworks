# Домашнее задание к занятию "4. Оркестрация группой Docker контейнеров на примере Docker Compose"

## Задача 1

<p align="center">
  <img width="1200" height="600" src="/root/virt-homeworks/image/1.JPG">
</p>

## Задача 2

<p align="center">
  <img width="1200" height="600" src="/root/virt-homeworks/image/2.JPG">
</p>

<p align="center">
  <img width="1200" height="600" src="/root/virt-homeworks/image/22.JPG">
</p>


## Задача 3
[centos@node01 ~]$ sudo docker ps
CONTAINER ID   IMAGE                              COMMAND                  CREATED              STATUS                        PORTS                                                                              NAMES
e682453a24e6   gcr.io/cadvisor/cadvisor:v0.47.0   "/usr/bin/cadvisor -…"   About a minute ago   Up About a minute (healthy)   8080/tcp                                                                           cadvisor
c8ac886ef4d8   grafana/grafana:7.4.2              "/run.sh"                About a minute ago   Up About a minute             3000/tcp                                                                           grafana
30b0fffc4a02   prom/pushgateway:v1.2.0            "/bin/pushgateway"       About a minute ago   Up About a minute             9091/tcp                                                                           pushgateway
fd9b75a20b46   stefanprodan/caddy                 "/sbin/tini -- caddy…"   About a minute ago   Up About a minute             0.0.0.0:3000->3000/tcp, 0.0.0.0:9090-9091->9090-9091/tcp, 0.0.0.0:9093->9093/tcp   caddy
0ddb7d21915b   prom/prometheus:v2.17.1            "/bin/prometheus --c…"   About a minute ago   Up About a minute             9090/tcp                                                                           prometheus
f149da772157   prom/alertmanager:v0.20.0          "/bin/alertmanager -…"   About a minute ago   Up About a minute             9093/tcp                                                                           alertmanager
dc43bd500d86   prom/node-exporter:v0.18.1         "/bin/node_exporter …"   About a minute ago   Up About a minute             9100/tcp                                                                           nodeexporter

<p align="center">
  <img width="1200" height="600" src="/root/virt-homeworks/image/3.JPG">
</p>


## Задача 4
<p align="center">
  <img width="1200" height="600" src="/root/virt-homeworks/image/4.JPG">
</p>

