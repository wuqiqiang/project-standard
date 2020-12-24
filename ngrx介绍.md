# 简介
官方地址: https://ngrx.io/docs

![avatar](https://ngrx.io/generated/images/guide/store/state-management-lifecycle.png)

# 辅助命令
## Action
```
ng g @ngrx/schematics:action login/actions/login-page
```
## Store
```
ng g @ngrx/schematics:store login/login -m login.module.ts
```
## Reducer
```
ng g @ngrx/schematics:reducer login/reducers/login-page
```
## Effect
```
ng g @ngrx/schematics:effect login/effects/login -m login/login.module.ts
```