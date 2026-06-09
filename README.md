# BUGCC — Boston University Global China Connection

社团官网静态站点。

## 站点结构

```
index.html          首页（Hero · 关于 · 加入我们）
departments.html    部门总览
dept/               部门详情页（主席团 / 事务部 / 融资部 / 市场部）
events.html         活动总览
event/              活动详情页（新生见面会 / Workshop / Mentorship / Cultural）
styles.css          统一样式
assets/             图片资源
```

## 本地预览

```bash
# 任选一种
python3 -m http.server 8000
# 或
npx serve
```

打开 http://localhost:8000

## 设计规范

- 主色：暗红 `#A6182A` / `#7B0F1F` + 米黄 `#FBF4DD`
- 字体：衬线（标题）+ 无衬线（正文）+ 英文等宽
- 导航悬浮下拉（`.nav__sub-menu`）：详见 `styles.css` 注释
- 全站不使用 emoji 装饰
