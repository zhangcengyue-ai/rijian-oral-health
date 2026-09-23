# 日健口腔科普网站预览版

纯静态网站，可通过 GitHub Pages 免费公开仓库部署。无安装步骤、无外部字体、无患者资料收集。

## 当前状态
六个栏目、10篇科普短稿、20条FAQ。所有页面带 noindex，避免待核实资料进入搜索。尚未完成医生审核，不能伪造作者或医学审核人。

## 部署
1. 在 GitHub 创建 Public 仓库 `rijian-oral-health`，若已有同名仓库先检查，不覆盖。
2. 将本文件夹内文件上传到 main 分支根目录，index.html 必须在根目录，不要只上传 zip。
3. Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save。
4. 等待部署成功，在 Pages 显示的真实 URL 打开网站（通常 https://你的用户名.github.io/rijian-oral-health/）。
5. 本站链接采用相对路径，支持项目站子路径。

## 正式开放索引前
确认机构名称、地址、电话、接诊时间、医生执业资料；医生审阅文章并确认真实署名；确认网站用途符合托管平台规则。之后移除每个页面的 noindex，添加真实网址 canonical 与 sitemap.xml，并在 robots.txt 添加 Sitemap URL。网站可抓取不意味着必然收录或被 AI 引用。

GitHub Pages 不允许用作经营在线业务、电子商务或主要促成商业交易的免费托管。本站按信息和科普预览设计，若转为商业获客/预约交易网站，应重新评估托管适用性。

不要上传任何患者病历、照片、账号密码或密钥。免费公开仓库内的文件均可被他人查看。
