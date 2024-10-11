# 第4节：5.X前端项目启动

作者：你的泪丶烫伤我的脸
<br/>QQ：12345678
<br/>WX：12345678

>沉淀、分享、成长，让自己和他人都能有所收获！😄

## 一、准备工作
- 必须安装基础建设: nodejs npm
  - `nodejs` >= 18.18
  - `npm` >= 8.X (7.X确认有问题)

# 二、前端运行

```bash
# 克隆项目
git clone https://gitee.com/JavaLionLi/plus-ui.git

# 安装依赖
npm install --registry=https://registry.npmmirror.com

# 启动服务
npm run dev

# 推荐使用yarn或pnpm包管理工具
# 构建测试环境 yarn build:stage
# 构建生产环境 yarn build:prod
# 前端访问地址 http://localhost:80
```