# 第三方组件

工具栏使用 Microsoft [Codicons](https://github.com/microsoft/vscode-codicons) 原始 SVG 图标（CC BY 4.0）；未修改图形路径，许可保留于 `media/codicons/LICENSE`。

编辑器基于本目录中的 [Vditor 4.0.1](https://github.com/Vanessa219/vditor)，采用 MIT 许可。原作者声明随安装包保留于 `media/vditor/LICENSE`。

本扩展直接构建本地源码，适配了外部脚本加载、JSON5 图表配置解析、Mermaid 严格渲染、差异库导入、代码复制事件和 Graphviz 的 Webview 渲染路径，并修复了 SMILES 渲染节点及脚本标识冲突。公式、图表、图标及语法高亮组件来自 Vditor 自带资源；其原始许可声明保留在随包资源中。

文档生成使用 docx（MIT）；浏览器调用使用 playwright-core（Apache-2.0）；HTML 处理使用 linkedom（ISC）；差异处理使用 diff-match-patch（Apache-2.0）；图表配置解析使用 JSON5（MIT）。依赖版本记录于 `package-lock.json`。
