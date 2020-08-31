# k8s-service-lab
Some yaml files for k8s service and ingress lab.

## service
关于service的部分Demo，包括
- ClusterIP
- NodePort
- External
- Headless

## ingress-nginx-oss
基于NGINX oss版本的ingress controller demo
- 基于host的基本ingress
- 基于uri外加tls的ingress
- cookie会话保持
- 灰度发布
   - 基于http header的灰度发布
   - 基于比例的灰度发布

## ingress-nginx-plus
基于NGINX Plus版本的ingress controller demo
- 跨越多namespace，master&minion
- 监听多个端口
- 4层tls sni负载均衡
- Virtual Server CRD
   - 基本Virtual Server
   - 负责Virtual Server
   - 主动健康检查
   - 基于header的灰度发布
   - if条件判断
- uri rewrite
- 基本ingress
- cookie会话保持
