# 本地修改说明（local 分支）

基于上游 eze-is/web-access（导入时 HEAD）。⚠️ 基于较早快照，升级时逐文件复核。

## 修改点
1. 新增 `references/site-patterns/mp.weixin.qq.com.md`：公众号文章抓取攻略
2. 新增 `references/site-patterns/xiaohongshu.com.md`：小红书抓取攻略（swiper-slide 去重、xsec_token 免登录等）
3. SKILL.md / README.md / .claude-plugin/plugin.json / references/cdp-api.md / scripts/cdp-proxy.mjs 有本地调整

## 不入库
`config.env`（本地配置，被 .gitignore 排除，绝不推送）
