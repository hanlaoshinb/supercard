# 塔罗牌在线占卜网站

这是一个简洁现代的塔罗牌在线占卜网站，使用HTML、TailwindCSS和JavaScript构建。

## 网站结构

网站由以下页面组成：

1. **首页 (index.html)**
   - 网站主页，展示塔罗牌占卜服务介绍
   - 包含"开始占卜"按钮，引导用户进入占卜流程

2. **选择塔罗师页面 (select-master.html)**
   - 展示四位不同风格的塔罗师供用户选择
   - 每位塔罗师都有独特的形象和专长领域
   - 用户可以点击选择喜欢的塔罗师进行占卜

3. **输入问题页面 (reading.html)**
   - 用户选择塔罗师后会被引导至此页面
   - 用户可以输入自己想要占卜的具体问题
   - 提供预设的常见问题类别供用户选择

4. **结果展示页面 (result.html)**
   - 展示塔罗牌占卜的详细结果
   - 显示用户所选的塔罗师和提出的问题
   - 提供详细的塔罗牌解读和建议

## 技术特点

- 使用 **TailwindCSS** 进行响应式设计，兼容移动端和桌面端
- 简洁现代的UI设计，提供良好的用户体验
- 使用JavaScript实现页面间数据传递和动态内容生成
- 模拟API响应，展示塔罗牌占卜结果（实际项目中可对接真实API）

## 使用说明

1. 直接打开 `index.html` 文件即可浏览网站
2. 点击"开始占卜"进入选择塔罗师页面
3. 选择塔罗师后，输入您的问题
4. 查看您的占卜结果

## 自定义

- 可以在TailwindCSS配置中修改颜色主题
- 可以替换图片资源自定义塔罗师形象
- 可以修改JavaScript代码自定义结果生成逻辑

## 文件说明

- `index.html` - 网站首页
- `select-master.html` - 选择塔罗师页面
- `reading.html` - 输入问题页面
- `result.html` - 结果展示页面
- `images/` - 存放网站使用的图片资源 