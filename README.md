### 安装nacos

```
## 安装
docker run --restart=always --env MODE=standalone --name nacos -d -p 8848:8848 nacos/nacos-server

## 查看日志
docker logs nacos
```

### 测试注册中心

启动类上添加 `@EnableDiscoveryClient`

![](https://i.loli.net/2021/02/19/TB8qvFrOR4jop6n.png)

### 测试配置中心
![](https://i.loli.net/2021/02/19/9nHPe1r5ajKEiGs.png)

![](https://i.loli.net/2021/02/19/b2LGISZJCq1dzkR.png)

![](https://i.loli.net/2021/02/19/XLbBmzUDoIv17Z3.png)

![](https://i.loli.net/2021/02/19/KRM9AP6OLFf4ZXa.png)

![](https://i.loli.net/2021/02/19/ytRHbiFIXoAPp9n.png)

![](https://i.loli.net/2021/02/19/32VZaMCsjhKvo18.png)

![](https://i.loli.net/2021/02/19/27BGK6DuCmZ1jA3.png)