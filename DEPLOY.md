部署说明

1. 将此目录全部内容推送到 GitHub 仓库的 main 分支。
2. 在仓库 Settings > Pages 中将构建来源设为 GitHub Actions。
3. 等待 Actions 工作流完成，访问 GitHub Pages 显示的公开网址。
4. 测试：
   - https://<账号>.github.io/<仓库名>/index.html?condition=unlabelled
   - https://<账号>.github.io/<仓库名>/index.html?condition=labelled
5. 如需返回问卷，将编码后的问卷地址加在 `&return=` 参数。

页面不会收集个人信息或阅读行为。`noindex,nofollow` 仅请求搜索引擎不索引，不会阻止公众访问。请保留 index.html 与 media/ 的相对路径结构。
