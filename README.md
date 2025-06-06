# 文本库jenkins流水线工程
## 简介
- packages为工程模块
  - common 通用模块
  - distributeMultiText2Branches 系统文本分发至各分支的模块，可引用common模块，不可以引用其它模块

## 使用方式
- 初次使用：yarn install
- 编译工程：yarn build
- 发布工程：yarn deploy
- test测试：yarn test