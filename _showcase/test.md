---
group: Featured       # 分组名称（必须与模板中的 group.name 匹配）
show: true            # 设为 true 才会显示
width: 2              # 卡片宽度（1-4，数字越大卡片越宽）
date: 2023-10-15      # 日期（影响排序）
class: my-custom-card # 可选自定义 CSS 类
---

<!-- 这里写你的内容 -->
<h2 class="card-title">我的项目标题</h2>
<p>这里是项目描述文字，支持<strong>HTML标签</strong>和Markdown语法。</p>

<!-- 插入图片（推荐相对路径） -->
<img src="/assets/images/protrait.jpg" 
     alt="项目示意图" 
     class="img-fluid rounded">

<!-- 添加按钮 -->
<a href="/projects/my-project" class="btn btn-primary mt-2">
  查看详情
</a>