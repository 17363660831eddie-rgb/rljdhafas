部署说明
1. 解压 ZIP。
2. 打开 Cloudflare Pages：https://dash.cloudflare.com/
3. 进入 Workers & Pages，选择创建应用 / Pages / Direct Upload（拖放上传）。
4. 上传本 ZIP 或解压后的文件夹，然后点击 Deploy。
5. 部署成功后，平台会生成一个 *.pages.dev 网址，把网址发给朋友即可。

注意：
- 入口文件必须位于根目录并命名为 index.html。
- 原 HTML 引用了 cmb.png、spdb.png、cib.png、ccb.png、icbc.png 五张图片；当前没有这些图片，银行 Logo 可能显示为占位图。若要正常显示，请将图片放在 index.html 同一目录并一起上传。
- 页面目前是静态演示界面；查询、审批等按钮没有连接后台，不会真正查询或办理贷款。
- 页面已加入“演示页面”提示，并替换部分企业/个人示例信息。请继续检查页面中是否还有你不想公开的内容。
