# 50位当代女性艺术家 · 资料库

> 部署地址：https://[你的域名].vercel.app

## 仓库结构

```
50-female-artists/
├── shared/
│   └── style.css          ← 所有艺术家页面共享的样式
├── artists/
│   ├── 01_marina-abramovic/
│   │   ├── index.html
│   │   ├── 1.jpg          ← 艺术家照片
│   │   ├── 2.jpg          ← 作品图1
│   │   ├── 3.jpg          ← 作品图2
│   │   └── ...            ← 按页面顺序命名
│   ├── 02_yayoi-kusama/
│   │   ├── index.html
│   │   └── 1.jpg ...
│   └── 03_.../
└── README.md
```

## 图片命名规则

每位艺术家文件夹内，图片按页面出现顺序命名：

| 文件名 | 对应位置 |
|--------|---------|
| 1.jpg  | P1 艺术家照片 |
| 2.jpg  | P3 WORK 01 图片 |
| 3.jpg  | P3 WORK 02 图片 |
| 4.jpg  | P3 WORK 03 图片 |
| 5.jpg  | P4 Spotlight Hero图 |
| 6.jpg  | P5 左小图 |
| 7.jpg  | P5 右小图 |
| 8.jpg  | P6 左小图 |
| 9.jpg  | P6 右小图 |

## 每篇URL格式

```
https://[域名]/artists/01_marina-abramovic/
https://[域名]/artists/02_yayoi-kusama/
```

## 飞书嵌入方式

在飞书知识库页面插入「嵌入网页」模块，粘贴上方URL即可。

## 新增艺术家

1. 在 `artists/` 下新建文件夹，命名格式：`03_名字拼音/`
2. 复制任意一篇 `index.html` 作为模板
3. 修改内容，放入图片（命名 1.jpg—9.jpg）
4. push 到 GitHub，Vercel 自动部署
