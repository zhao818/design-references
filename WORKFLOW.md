# Workflow — 设计参考仓库使用流程

## 什么时候用

- 看到优秀的页面/UI设计想收藏
- 做设计时需要灵感借鉴
- 想分析某个设计的优缺点

## 标准流程

### 新增设计参考

```
① 搜集：看到优秀页面，保存完整 HTML 源文件
② 归档：放入 references/<name>.html
③ 分析：在 notes/ 创建 <name>-analysis.md
   至少分析：色彩系统、布局节奏、交互动效、可借鉴点
④ 索引：更新 references/README.md 清单
⑤ git add → commit → push
```

### 设计时参考

```
① 翻 notes/ 目录，快速定位可借鉴的技巧
② 打开对应 HTML 文件查看源码
③ 提取 CSS 变量/动画/布局模式
```

## 结构

| 目录 | 用途 |
|------|------|
| references/ | 收集的页面源文件（HTML） |
| notes/ | 设计分析笔记 |
| references/README.md | 收集清单索引 |
