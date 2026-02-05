# TSL Language Support for VS Code

VS Code 的 TSL (Tinysoft Statistical Analysis Language) 语言支持扩展，提供完整的语法高亮、智能代码补全、代码诊断、格式化等功能。

## 功能特性

### 🎯 语言支持
- **文件扩展名**: `.tsl`, `.tsf`
- **语法高亮**: 完整的 TSL 语法高亮支持
- **语义高亮**: 根据代码语义提供精确的着色

### 💡 智能功能

#### 1. 代码补全 (Auto Completion)
- 基于上下文的智能代码补全
- 内置函数、关键字、类型提示
- Unit 系统支持（Uses 语句自动补全）
- 触发字符: `.`, `(`, `,`, `空格`, `[`

#### 2. 悬停提示 (Hover)
- 函数签名和文档提示
- 变量类型信息
- 快速预览定义

#### 3. 跳转到定义 (Go to Definition)
- 函数和过程定义跳转
- 变量声明跳转
- 类成员跳转
- 跨文件导航（支持 Unit 系统）

#### 4. 查找引用 (Find References)
- 查找符号的所有引用位置
- 区分读取和写入引用

#### 5. 重命名 (Rename)
- 安全的符号重命名
- 跨文件重命名支持
- 预览更改功能

### 🔍 代码分析

#### 1. 实时诊断 (Diagnostics)
- 语法错误检测
- 语义错误提示
- 代码问题警告
- 实时错误标记

#### 2. 代码折叠 (Folding)
- 基于语义的代码折叠
- 支持函数、过程、类、Begin-End 块
- 自定义折叠区域

#### 3. 文档符号 (Document Symbols)
- 文件大纲视图
- 快速导航到函数/变量/类
- 符号分类显示

#### 4. 工作区符号 (Workspace Symbols)
- 跨文件符号搜索
- 支持正则表达式搜索
- 快速打开符号定义

### 🎨 代码美化

#### 1. 代码格式化 (Formatting)
- 完整的文档格式化 (`Shift+Alt+F`)
- 选中范围格式化
- 保存时自动格式化（需配置）
- 关键字大小写规范化

#### 2. 内联提示 (Inlay Hints)
- 参数名称提示
- 类型推断提示
- 可配置显示选项

### 📋 代码片段 (Snippets)

提供丰富的代码片段，快速生成常用代码结构：

| 前缀 | 描述 |
|------|------|
| `function` | 函数定义模板 |
| `procedure` | 过程定义模板 |
| `if` | If 语句 |
| `ifelse` | If-Else 语句 |
| `for` | For 循环 |
| `while` | While 循环 |
| `repeat` | Repeat-Until 循环 |
| `case` | Case 语句 |
| `tryexcept` | Try-Except 块 |
| `tryfinally` | Try-Finally 块 |
| `class` | 类定义模板 |
| `select` | SQL Select 语句 |
| `vselect` | SQL VSelect 语句 |
| `array` | 数组声明 |
| `forarray` | 数组遍历循环 |
| `unit` | Unit 模块模板 |
| `property` | 属性声明 |
| `marketdata` | 股票行情数据查询 |
| `infodata` | 财务数据查询 |

## 安装

### 从 VSIX 安装

1. 下载 `vscode-tsl-0.1.0.vsix` 文件
2. 在 VS Code 中打开扩展视图 (`Ctrl+Shift+X`)
3. 点击右上角的 `...` 菜单
4. 选择 **"从 VSIX 安装..."**
5. 选择下载的 `.vsix` 文件

### 从 Marketplace 安装

搜索 "vscode-tsl" 或者 "TSL Language Support" 并安装。



## 反馈与支持

如有问题或建议，请提交到 GitHub Issues：
https://github.com/weigj/vscode-tsl/issues

---

**享受编码！** 🚀
