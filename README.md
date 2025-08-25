


          
我需要查看dist目录的内容，以及项目的其他相关文件，来创建一个合适的README文件。
        
            
toolName: view_files
            
status: success
          
            
filePath: /Users/seasonxia/Documents/Coding/tdireidvalidator/index.html
          
我需要查看App.jsx文件来了解应用的主要功能。
        
            
toolName: view_files
            
status: success
          
            
filePath: /Users/seasonxia/Documents/Coding/tdireidvalidator/src/App.jsx
          
我需要查看main.go文件来了解后端功能，以及package.json来了解项目依赖。
        
            
toolName: view_files
            
status: success
          
            
filePath: /Users/seasonxia/Documents/Coding/tdireidvalidator/main.go
/Users/seasonxia/Documents/Coding/tdireidvalidator/package.json
          
我需要查看deploy-static.sh文件来了解部署过程。
        
            
toolName: view_files
            
status: success
          
            
filePath: /Users/seasonxia/Documents/Coding/tdireidvalidator/deploy-static.sh
          
我需要查看README.md文件，看看是否已经存在，以及查看dist/index.html来了解构建后的应用。
        
            
toolName: view_files
            
status: success
          
            
filePath: /Users/seasonxia/Documents/Coding/tdireidvalidator/README.md
/Users/seasonxia/Documents/Coding/tdireidvalidator/dist/index.html
          
# TDI ReID Validator

一个用于验证和分析行人重识别(Re-Identification)结果的前端工具。

## 项目概述

TDI ReID Validator 是一个基于 React 和 Vite 构建的单页应用程序，专为分析和验证行人重识别(ReID)系统的结果而设计。该工具提供了直观的用户界面，帮助用户查看、组织和验证身份匹配的准确性。

## 主要功能

- **视觉化分析**：按 UUID 分组显示所有捕获的图像
- **身份管理**：添加、重命名和链接身份
- **准确性计算**：计算假阳性和假阴性指标
- **交互式标记**：用于验证和纠正识别结果
- **数据导入/导出**：支持保存和恢复分析进度
- **隐私保护**：完全在浏览器本地运行，无数据上传
- **暗/亮主题切换**：支持不同的显示模式

## 技术栈

- **前端框架**：React 18
- **UI 组件**：Material UI (MUI)
- **构建工具**：Vite
- **国际化**：i18next
- **其他库**：UUID 生成

## 安装与运行

### 开发环境

1. 克隆仓库
2. 安装依赖：
   ```bash
   npm install
   ```
3. 启动开发服务器：
   ```bash
   npm run dev
   ```

### 构建生产版本

```bash
 npm run build
```

构建后的文件将位于 `dist` 目录中，可以部署到任何静态文件服务器。

### 部署

项目包含一个自动部署脚本 `deploy-static.sh`，可以将构建后的应用部署到指定的 GitHub 仓库：

```bash
npm run deploy-static
```

## 使用方法

1. 打开应用后，点击"选择文件夹"按钮或拖放文件夹到指定区域
2. 应用将扫描文件夹结构并加载图像数据
3. 使用界面工具分析和验证 ReID 结果
4. 可以导出分析进度以便后续继续工作

## 隐私说明

本应用完全在浏览器中运行，所有文件夹和图像处理均在本地计算机上完成。不会将任何数据上传到服务器。

## 许可证

[MIT](LICENSE)

        
