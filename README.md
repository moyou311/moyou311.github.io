# moyou311.github.io

这个仓库当前主要用于 GitHub Pages 发布订阅文件，不再承担完整运维工作区的职责。

## 当前正式订阅

- 正式订阅地址：
  - `https://moyou0929.me/subscriptions/main-10m.yaml`
- 当前正式方案：
  - `DE-XHTTP-IP`
  - `DE-XHTTP-DOMAIN`
- 当前正式主线：
  - `443/TLS + XHTTP`

## 当前测试订阅

- 测试订阅地址：
  - `https://moyou0929.me/subscriptions/main-10m-test.yaml`
- 用途：
  - 冒烟测试
  - 切换前验证
  - 不直接作为客户长期日常入口

## 仓库结构

- `CNAME`
  - GitHub Pages 自定义域名
- `subscriptions/main-10m.yaml`
  - 当前正式订阅
- `subscriptions/main-10m-test.yaml`
  - 当前测试订阅
- `subscriptions/us-manual.yaml`
  - 历史参考文件，不是当前正式入口

## 维护原则

- 正式发布优先只改 `subscriptions/main-10m.yaml`
- 测试验证改 `subscriptions/main-10m-test.yaml`
- 不把历史排障文件重新当成正式入口
- 订阅变更后优先核对：
  - Git 仓库文件
  - `raw.githubusercontent.com`
  - GitHub Pages 地址缓存是否已刷新
