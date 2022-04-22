## 官网

[nfs-subdir-external-provisioner官网](https://github.com/kubernetes-sigs/nfs-subdir-external-provisioner)

## 部署方式

```shell
kubectl apply -f nfs-subdir-external-provisioner/
```

## 说明

`nfs-subdir-external-provisioner`相比`nfs-subdir-external-provisioner-official`做了以下改动:
- 更改了名称空间
- 拆分了官方`rbac.yaml`文件
- 更改了`StorageClass`部分配置项


