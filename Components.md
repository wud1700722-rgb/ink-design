# Ink 组件

## 基础
- 按钮 Button
- 图标按钮 ButtonIcon
- 链接按钮 ButtonLink
- 链接 Link
- 标签 Tag
- 图标 Icon

## 表单
- 输入框 Input
- 多行文本 Textarea
- 选择器 Select
- 复选框 Checkbox
- 单选框 Radio
- 开关 Switch
- 滑块 Slider

## 选择
- 芯片 Chip
- 分段控件 Segmented
- 下拉菜单 Menu

## 反馈
- 徽标 Badge
- 进度条 Progress
- 消息条 Snackbar
- 对话框 Dialog
- 横幅 Banner
- 提示气泡 Tooltip

## 容器
- 卡片 Card
- 折叠面板 Accordion
- 列表 List
- 表格 Table
- 代码块 Code Block

## 导航
- 顶栏 Topbar
- 底部导航 Bottom Nav
- 侧边导航 Side Nav
- 抽屉 Drawer
- 标签页 Tabs
- 面包屑 Breadcrumb

## 字体
- Ink-EN-FIGURE (弃用)
- inkshou “凌”写

## 布局
- 容器 Wrap
- 栅格 Grid


### 按钮 Button

按钮控件是最基础的控件，主要用于执行一些操作，例如发送邮件、分享文档或点赞评论等。

#### 基本用法

```html
<button class="ink-btn ink-btn--primary">主要按钮</button>
```

#### 尺寸

```html
<button class="ink-btn ink-btn--sm">小号</button>
<button class="ink-btn">默认</button>
<button class="ink-btn ink-btn--lg">大号</button>
```

### 图标按钮 ButtonIcon

```html
<button class="ink-btn ink-btn--icon ink-btn--outline" aria-label="设置">
  <svg class="ink-icon"><use href="#i-settings"/></svg>
</button>
```

#### 注意事项

图标按钮必须带 aria-label，否则屏幕阅读器读不出它的用途。

#### 状态

| 状态 | 写法 | 说明 |
|------|------|------|
| 禁用 | `disabled` 属性 | 原生支持，键盘和鼠标都走不到 |
| 加载中 | `.is-loading` 类 | 配合 `.ink-spinner` 使用 |

#### 无障碍

- 图标按钮必须有 `aria-label`
- 主要操作应该排在 Tab 顺序的前面
- 不要用 `div` 假装按钮，用 `<button>`

#### 接口

| 类名 | 说明 |
|------|------|
| `ink-btn` | 基础类，必须 |
| `ink-btn--primary` | 主要变体 |
| `ink-btn--outline` | 次要变体 |
| `ink-btn--soft` | 柔和变体 |
| `ink-btn--ghost` | 文字变体 |
| `ink-btn--danger` | 危险变体 |
| `ink-btn--sm` | 小号 |
| `ink-btn--lg` | 大号 |
| `ink-btn--icon` | 图标按钮（正方形） |

### 链接 Link

文字链接用于页面内或页面间的跳转。和按钮的区别：

| | 链接 | 按钮 |
|--|------|------|
| 语义 | 导航 | 操作 |
| 元素 | `<a>` | `<button>` |
| 视觉 | 文字 | 块 |
| 典型 | 「查看文档」 | 「提交」 |

#### 基本用法

```html
阅读 <a class="ink-link" href="#">快速开始</a>，或查看 <a class="ink-link" href="#">组件总览</a>。
```

#### 变体

| 变体 | 类名 | 用途 |
|------|------|------|
| 默认 | `ink-link` | 正文内链接 |
| 下划线 | `ink-link--underline` | 需要显式强调 |
| 静默 | `ink-link--muted` | 不抢视觉，hover 才亮 |
| 带箭头 | `ink-link--arrow` | 「了解更多 →」 |
| 外链 | `ink-link--external` | 带外链图标 |

#### 无障碍

- 链接文字要有意义，「点击这里」是反例
- 外链应加 `rel="noopener"`（如果用了 `target="_blank"`）
- 不要用 `<a>` 假装按钮——用 `<button>`

### 链接按钮 ButtonLink

当视觉上需要按钮、但行为是导航时，用 `<a>` 加按钮类名：

```html
<a class="ink-btn ink-btn--primary" href="./home.html">开始使用</a>
```

注意：用 `<a>` 而不是 `<button>`，因为行为是跳转。

#### 无障碍

- 链接按钮应保持和按钮相同的键盘行为（Tab 可聚焦，Enter 触发）
- 外链应加 `rel="noopener"`，防止安全风险
- 链接文字应有意义，不要用「点击这里」

#### 支持的原生属性

| 属性 | 用途 |
|------|------|
| `href` | 目标地址 |
| `target` | `_blank` 新标签打开 |
| `rel` | `noopener`、`nofollow` 等 |
| `download` | 提示下载 |

#### 外链示例

```html
<a class="ink-btn ink-btn--outline" href="https://github.com" target="_blank" rel="noopener">
  GitHub
</a>
```

### “凌”写 inkshou
“凌”写，是一款手写装饰字体，常被用于 404 页面。
#### 为何需要这一款手写字体？
此段落需要补充
你可以帮助我们补充这一段落