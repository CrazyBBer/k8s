# k8s
repository fo k8s

## Helm (basic using Default ServiceAccout ：default)
helm init --tiller-image registry.cn-hangzhou.aliyuncs.com/acs/tiller:v2.9.1

### RBAC

helm init --tiller-image registry.cn-hangzhou.aliyuncs.com/acs/tiller:v2.9.1 --service-account tiller --upgrade
