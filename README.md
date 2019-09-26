# CVE-2019-10392 RCE with Git Client Plugin 2.8.2 (Authenticated)

![](./newjob.jpg)
![](./configure.jpg)
![](./exploit.jpg)
![](./script.jpg)

## 0x01 docker 启动

`docker run -p 8080:8080 -p 50000:50000 jenkins/jenkins:lts-alpine`


## 0x02 漏洞环境

```
Jenkins 2.176.3
Git Client Plugin 2.8.2 

https://updates.jenkins-ci.org/download/plugins/git-client/
Git Plugin 3.12.0

```

## 参考链接

https://iwantmore.pizza/posts/cve-2019-10392.html

https://devco.re/blog/2019/01/16/hacking-Jenkins-part1-play-with-dynamic-routing/
