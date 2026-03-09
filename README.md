# sing-box 自动构建

这个仓库用于给 [`reF1nd/sing-box`](https://github.com/reF1nd/sing-box) 自动构建两个 Linux 版本并发布。

## 当前功能

- 定时同步上游 `reF1nd-testing-next`
- 自动构建两个版本：
  - `linux/amd64`
  - `linux/amd64v3`
- 自动发布 GitHub Release

## 分支说明

- `master`
  只保留 GitHub Actions 工作流。
- `reF1nd-testing-next`
  用于保存同步后的源码结果。

## 触发方式

- 每小时自动运行一次
- 也可以手动触发
