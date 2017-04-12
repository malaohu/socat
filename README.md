# socat
参考老外的代码：https://github.com/istepanov/docker-socat
去掉 CMD 部分

启动： docker run -d -p 80:80 istepanov/socat TCP4-LISTEN:80,fork,reuseaddr TCP4:registry:5000
