# 代码提交规范

## 提交代码前请确保做完的事
- [ ] 1. 代码本地测试成功。
- [ ] 2. 测试环境部署并测试成功。
- [ ] 3. 没有不相关的代码和文件在commit中。
- [ ] 4. 代码中包含 test case 或者 unit test。
- [ ] 5. 如果是新的接口，请提供详细的markdown文档。

## 如何提交你的代码？
1. github 中 Fork 项目到自己的项目下
2. 提交 commit 至自己 Fork 出的github项目
3. 在 github 中发起PR至原项目的非master分支
4. 发起review

## Branch 规范
1. 命名规则：`WIP-{problem_you_sovled}`或者其它。但至少让人知道这个branch解决了什么问题
2. PR 被Owner 进行 merge 后，删除branch

## Commit 规范
1. 一次commit只干一件事！
2. 每完成了一个独立的功能或解决了一个bug再去push！
3. 每次push前请先保证你本地测试已经通过！
4. commit message 使用的语种保持一致！
5. commit message 尽可能**详细**的描述你的commit所解决的事情，即使你只改了一行代码。
6. commit前最好format你的新代码。
7. 如果你的N个commit都是在做同一件事（比如只修复一个bug），提交PR时，本地先 git rebase -i, 可以合并多个提交，修改提交顺序，以及更改 commit message；。

## 最后
如果没有按照以上规范提交你的代码，我们会100%拒绝你的commit。
