# service-discovery-dock

基于 Docker Compose 搭建的服务发现环境

# IP地址
内部IP地址从 172.25.35.3 开始

# 服务清单

## Consul (172.21.8.3~172.21.8.5)
| status | service | backend ip | frontend ip | version | 备注 |
|---|---|---|---|---|---|
| [&cross;] | consul | 172.21.8.3 | 172.20.8.3 | latest | | |

## Zookeeper (172.21.8.6~172.21.8.7)
| status | service | backend ip | frontend ip | version | 备注 |
|---|---|---|---|---|---|
| [&cross;] | zookeeper | 172.21.8.3 | 172.20.8.3 | latest | | |

## Nacos (172.21.8.10~172.21.8.20)
| status | service | backend ip | frontend ip | version | 备注 |
|---|---|---|---|---|---|
| [&cross;] | nacos | 172.21.8.10 | 172.20.8.10 | latest | | |

## Etcd (172.21.8.20~172.21.8.21)
| status | service | backend ip | frontend ip | version | 备注 |
|---|---|---|---|---|---|
| [&cross;] | etcd | 172.21.8.20 | 172.20.8.20 | latest | | |


# 使用到的镜像
```json
[

]
```
