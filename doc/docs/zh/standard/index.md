# 书写规范

:tada: :100:
::: tip
① 接口文档使用Swagger  
② 编写者必须严格遵守项目中tslint编写规则  
③ 编写者必须严格遵循代码命名语义化、提高代码可读性  
④ 编写者编写代码完毕必须经过单元测试，保证代码可用性  
⑤ 编写必须完全使用TypeScript，保证代码严谨性、可维护性  
⑥ 编写者提交代码发生冲突，必须先解决，在推送，严禁使用git push -f origin 分支  
⑦ vue代码请放在vue-ts分支下，react代码请放在react-ts分支下，angular代码请放在angular-ts分支下
:::

::: danger
管理者严禁将代码直接推送或合并到main分支，main分支只用来存放后端代码和文档代码，这样避免了首次拉取代码需要等很长时间，代码整体编写完毕后会合并到main分支
:::