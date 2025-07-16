# acr-sync-template
同步docker镜像
1. 在 Settings → Secrets and variables → Actions 中新建：
   ACR_REGISTRY=registry.cn-hangzhou.aliyuncs.com
   ACR_USERNAME=你的阿里云AK
   ACR_PASSWORD=你的阿里云SK
2. 修改 images.txt → Commit，Actions 即开始同步。
