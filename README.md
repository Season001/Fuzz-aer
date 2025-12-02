# Fuzz-aer

![image](https://github.com/Season001/Fuzz-aer/blob/main/images/logo.jpg)

## 简介

Fuzz-aer 是一款基于 Burp Suite 扩展的智能模糊测试辅助工具。它集成了 AI 配置、字典管理和 JS 分析等功能，旨在帮助安全研究人员和渗透测试人员更高效地进行接口模糊测试和漏洞挖掘。

## 功能特性

*   **AI 配置**：
    *   灵活配置多种 AI 服务（如 OpenAI、自定义接口），通过智能提示词驱动测试流程，让模糊测试更具针对性与深度。
*   **JS 分析配置**：
    *   基于 AI 深度解析 JavaScript 代码，自动识别潜在的 API 接口、敏感参数和隐藏路径，大幅提升前端资产发现效率。支持自定义分析提示词与实时测试验证。
*   **字典管理**：
    *   内置多场景基础字典与主流框架指纹库，支持用户灵活扩展与自定义。结合分析结果，可快速生成针对性测试字典，提升漏洞挖掘覆盖率。

## 安装

1.  **下载 JAR 包**：
    *   从项目的 [Releases](https://github.com/your-repo/fuzz-aer/releases) 页面下载最新版本的 `fuzz-aer-1.0.jar` 文件。
2.  **导入 Burp Suite**：
    *   打开 Burp Suite。
    *   进入 `Extensions` -> `Installed` 选项卡。
    *   点击 `Add` 按钮。
    *   在弹出的对话框中，将 `Extension type` 设置为 `Java`。
    *   点击 `Select file...` 按钮，选择你下载的 `fuzz-aer-1.0-SNAPSHOT-shaded.jar` 文件。
    *   点击 `Next` 完成导入。

## 使用说明

### 1. 主界面

安装成功后，Burp Suite 中会出现一个新的 `Fuzz-aer` 选项卡。

![image](https://github.com/Season001/Fuzz-aer/blob/main/images/%E4%B8%BB%E7%95%8C%E9%9D%A2.png)

### 2. AI 配置

点击左侧导航栏的 `AI 配置`。

![image](https://github.com/Season001/Fuzz-aer/blob/main/images/AI%E9%80%9A%E7%94%A8%E9%85%8D%E7%BD%AE.png)

*    `AI 配置` 页面中 `普通提示词` 选项卡的内容，包括提示词的说明和编辑区域。

![image](https://github.com/Season001/Fuzz-aer/blob/main/images/AI-JS%20%E5%88%86%E6%9E%90%E9%85%8D%E7%BD%AE.png)

*    `AI 配置` 页面中的 `JS 分析配置` 选项卡下的 `JS 分析提示词` 子页面，包括提示词的说明和编辑区域。

![image](https://github.com/Season001/Fuzz-aer/blob/main/images/AI%E9%85%8D%E7%BD%AE-js%E5%88%86%E6%9E%90.png)

*   `AI 配置` 页面中 `JS 分析配置` 选项卡下的 `JS 分析测试` 子页面，包括 `JS 分析` 输入框、`结果将显示在这里` 输出框和 `执行分析` 按钮。

### 3. 字典管理

点击左侧导航栏的 `字典管理`。

![image](https://github.com/Season001/Fuzz-aer/blob/main/images/%E5%9F%BA%E7%A1%80%E5%AD%97%E5%85%B8.png)

*   显示 `字典管理` 页面中 `基础字典` 选项卡的内容，包括 `类型` 选择区域和 `字典内容` 编辑区域。

![image](https://github.com/Season001/Fuzz-aer/blob/main/images/%E6%A1%86%E6%9E%B6%E6%8C%87%E7%BA%B9.png)

*  `字典管理` 页面中 `框架指纹` 选项卡的内容，包括 `字典内容` 编辑区域。

  ### 注意事项

* 使用 AI 功能前需正确配置 API 信息。

*   字典文件支持导入/导出，建议定期更新以覆盖最新漏洞特征。



#### 如果对你有帮助，请给个 ⭐ 支持一下！
