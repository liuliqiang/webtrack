# webtrack
Many offline important web page for me


- Docker
    - Documents
        - [Docker cheat sheet](https://liuliqiang.github.io/webtrack/docker/docker-cheat-sheet-v2.pdf)
- [MicroServices]()
    - [Istio]()
        - [Dive in Deep]()
            - [Istio Sidecar 注入过程解密](https://liuliqiang.github.io/webtrack/microservices/isito/dive-in-deep/istio.io/zh/blog/2019/data-plane-setup/index.html)
- [CNCF]()
    - [Prometheus]()
        - [从头编写一款时间序列数据库](https://liuliqiang.github.io/webtrack/cncf/prometheus/devopstarter.info/translate-writing-a-time-series-database-from-scratch/index.html)

# Dump 网页方法 [Wget tips](https://admin.liuliqiang.info/laumonkey/posts/122b9300)

## 下载整个页面
wget -l 1 -p -np -k http://www.baidu.com

## 下载整站
wget -c -r -nd -np -k -L -p http://www.baidu.com
