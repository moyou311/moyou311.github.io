# Subscriptions

## 正式入口

- `main-10m.yaml`
- 线上地址：
  - `https://moyou0929.me/subscriptions/main-10m.yaml`
- 当前内容：
  - `DE-XHTTP-IP`
  - `DE-XHTTP-DOMAIN`

## 测试入口

- `main-10m-test.yaml`
- 线上地址：
  - `https://moyou0929.me/subscriptions/main-10m-test.yaml`
- 用途：
  - 服务器切换前验证
  - 客户端兼容性验证

## 历史参考

- `us-manual.yaml`
  - 历史参考文件
  - 不作为当前正式入口

## 说明

- 如果正式方案发生变化，优先更新 `main-10m.yaml`
- 如果只是做临时验证，优先更新 `main-10m-test.yaml`
- 如果 GitHub Pages 短时仍返回旧内容，先检查：
  - GitHub 仓库主分支是否已更新
  - `raw.githubusercontent.com` 是否已返回新文件
  - Pages/CDN 缓存是否尚未刷新
