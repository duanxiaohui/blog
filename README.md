# 任务：创建一个简单的用户管理页面

## 目标
创建一个简单的中后台管理页面，用于显示用户列表和提交新用户信息。

## 功能要求

### 用户列表展示
- 创建一个用户列表页面，展示用户的基本信息，如用户名、邮箱、注册日期等。
- 提供一个查询功能，允许通过用户名或邮箱对用户列表进行搜索。

### 新增用户表单
- 创建一个表单页面，用于提交新用户的信息。
- 表单至少包含以下字段：用户名（必填）、密码（必填）、邮箱（必填）、手机号（选填）。

### 表单验证与提交
- 实现表单验证，确保用户名、密码和邮箱字段在提交前都已正确填写。
- 提交按钮用于将表单数据发送到服务器。

### 响应式布局
- 页面布局应该响应式，适应不同的屏幕尺寸，包括桌面、平板和手机。

## 技术栈建议

- **HTML/CSS**：用于构建页面结构和样式。
- **JavaScript**：用于实现页面的交互逻辑。
- **框架**：可以使用如React、Vue前端框架来简化开发。
- **组件库**：Vue使用elment ui，react使用ant design。

## 进阶挑战

- 使用Ajax技术实现无需刷新页面的用户列表查询和表单提交。
- 实现表单提交后的成功提示和错误处理逻辑。
- 使用前端路由管理页面跳转（如果使用了前端框架）。

## 提交要求

- 将代码提交到GitHub仓库，并确保有清晰的README.md文件说明如何运行和测试页面。
- 确保代码整洁，并且有适当的注释。
