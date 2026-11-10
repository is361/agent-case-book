# Agent 用例大全（运维手册）

## 目录
- index.html / style.css — 站点（纯静态，无构建）
- cases.json — 全部用例数据（唯一需要更新的文件）
- llms.txt — 给 AI 助手读的版本（GEO）

## cases.json 格式
{"updated":"YYYY-MM-DD","cases":[{"id":1,"title":"","desc":"","cat":"money|work|content","source":"","url":"","date":"","new":true}]}
- new:true 表示 7 天内收录，站点显示「新」角标
- 排序：日期倒序，新者优先

## 每日自动任务
扫新用例 → 追加 cases.json（new:true）→ git push → 刷新 llms.txt 精选

## 部署
- GitHub Pages：main 分支
- 待办：index.html 里 sponsor@example.com 与两个「＿＿＿」（公众号/抖音名）占位符，替换后推一次

## 赞助位
- 文案与价格先占位，首月测试 1-2 个赞助商
