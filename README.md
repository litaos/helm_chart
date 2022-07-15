# helm-chart

## helm的chart仓库地址为：https://771417573.github.io/helm_chart/

## 本Chart仓库的使用方法

1、添加chart仓库
```
# helm repo add myrepo https://771417573.github.io/helm_chart/
```

2、添加成功
```
# helm repo list
NAME  	URL                                   
myrepo	https://771417573.github.io/helm_chart/
```

3、搜索chart包
```
# helm search repo myrepo
NAME            CHART VERSION   APP VERSION     DESCRIPTION
myrepo/jenkins  4.1.13          2.346.2         Jenkins - Build great things at any scale! The ...
```

4、安装chart包
```
# helm install xxx myrepo/test
```

xxx为relaese名字

