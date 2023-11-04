# cms

## 描述
vue3 基于vuecli eslint，vscode + prettier，commitizen，husky，lint-staged的代码格式化规范，和git、代码提交规范的模板。

## 环境
Vue CLI v5.0.8
node  v18.17.0
10以上版本就行，在某些情况下，新的 peerDependencies 规则可能导致一些包无法安装，因此使用 --legacy-peer-deps 可以暂时绕过这些问题。

## 使用
提交使用git cz,然后根据引导提交，Yneh，e是edit，h是help。

自动的eslint修复

## 其他
1. [约定式提交规范](https://www.conventionalcommits.org/zh-hans/v1.0.0/)
2. [commitizen](https://github.com/commitizen/cz-cli)：git 提交规范化工具
3. [commitlint](https://github.com/conventional-changelog/commitlint)：用于检查提交信息
4. `pre-commit`： `git hooks` 钩子
5. [lint-staged](https://github.com/okonet/lint-staged)：只检查本次修改更新的代码，并在出现错误的时候，自动修复并且推送
6. 每次在本地 `commit` 之前，校验你提交的内容是否符合你本地配置的 `eslint`规则(这个见文档 [ESLint](https://panjiachen.github.io/vue-element-admin-site/zh/guide/advanced/eslint.html) )