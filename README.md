# 任务：创建一个个人博客页面

## 目标
创建一个静态的个人博客页面，该页面应该响应式，适应不同的屏幕大小。

## 要求

### 使用组件库
- vue项目用elemet UI，react项目用ant design。
### 页面结构
- 使用HTML5来构建页面结构。
- 页面应该包含以下部分：
  - 头部（Header）
  - 文章列表（Article List）
  - 侧边栏（Sidebar）
  - 页脚（Footer）

### 样式设计
- 使用CSS来设计页面样式，确保样式是响应式的。
- 可以选择使用CSS框架如Bootstrap来加速开发过程。

### 交互功能
- 使用JavaScript实现基本的交互功能。
- 当用户点击侧边栏的一个主题时，文章列表会更新显示相关主题的文章。

### 文章列表
- 至少包含3篇文章的摘要。
- 每篇文章摘要应该包含标题、发布日期、简短描述和一个阅读更多（Read More）的链接。

### 侧边栏
- 包含一个关于作者的简短介绍。
- 包含文章主题的列表。

### 页脚
- 包含版权声明和联系方式。

## 进阶挑战
- 使用JavaScript从一个JSON文件或者API动态加载文章列表。
- 实现一个简单的搜索功能，允许用户通过关键词搜索文章标题和描述。

## 提交要求
- 将代码提交到GitHub，并确保有清晰的README.md文件说明如何运行和测试页面。
- 确保代码清晰并且有适当的注释。

## 表单任务扩展

### 目标
在个人博客页面中添加一个联系表单，允许用户发送消息给博客作者。

### 要求

#### 表单元素
- 包含以下字段：姓名（Name）、电子邮件地址（Email Address）、主题（Subject）和消息内容（Message）。
- 每个字段都应有相应的标签（Label）。
- 提交按钮用于发送表单。

#### 表单样式
- 使用CSS设计表单样式，确保与博客页面风格一致。
- 表单在不同设备上应有良好展示效果。

#### 表单验证
- 使用JavaScript进行前端表单验证。
- 确保所有字段在提交前都已填写。
- 验证电子邮件地址格式正确性。

#### 响应式设计
- 确保表单在手机和平板等移动设备上也能正确显示和使用。

#### 提交反馈
- 用户提交表单后，显示确认消息。

### 进阶挑战
- 实现后端服务接收表单数据，并通过电子邮件发送。
- 使用Ajax技术实现表单的异步提交。

### 提交要求
- 代码和相关文件提交到GitHub仓库。
- 更新README.md文件，说明如何测试表单提交和验证功能。
- 确保代码整洁，有清晰注释。
