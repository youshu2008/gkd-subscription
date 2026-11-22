# 自用 GKD 规则

个人自用的 GKD 订阅规则（单文件版），仅用于辅助跳过广告、关闭弹窗，不对外分发。

## 订阅地址（在 GKD 内添加）

```
https://raw.githubusercontent.com/youshu2008/gkd-subscription/main/gkd.json5
```

大陆访问不畅时的备用镜像（二选一）：

```
https://fastly.jsdelivr.net/gh/youshu2008/gkd-subscription@main/gkd.json5
```

## 文件说明

| 文件 | 作用 |
|---|---|
| `gkd.json5` | **唯一的订阅文件**，所有规则都写在这里，GKD 直接订阅它 |
| `维护教程.md` | 自己加规则、修规则、更新的完整操作手册 |

## 维护

日常加规则、修规则的步骤见 [`维护教程.md`](./维护教程.md)，全程在浏览器上改网页即可，不需要装 git、不需要 Node。
