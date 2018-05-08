# kubernetes-dashboard

##dashboard

>https://www.kubernetes.org.cn/3834.html

>https://www.kubernetes.org.cn/3808.html

###获取 token
**kubectl get secret -n kube-system |grep dashboard-admin|awk '{print "kubectl describe secret -n kube-system "$1" "}' |bash

