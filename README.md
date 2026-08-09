# app-policies

各 iOS App 的隐私政策等合规静态页，通过 GitHub Pages 发布。

## 站点结构

```text
app-policies/
├── index.html           # 索引页
├── chuwubao/
│   ├── privacy.md       # 源稿（改政策先改这里）
│   └── privacy.html     # 发布页
└── {other-app}/         # 后续 App 按同样结构添加
    ├── privacy.md
    └── privacy.html
```

## GitHub Pages

1. 仓库 **Settings → Pages**
2. Source：**Deploy from a branch** → 分支 `main` → 文件夹 **`/ (root)`**
3. 保存后访问：`https://castchen.github.io/app-policies/`

## 各 App 隐私政策 URL

| App | App Store 填写的 URL |
|-----|----------------------|
| 储物小精灵 | https://castchen.github.io/app-policies/chuwubao/privacy.html |

## 更新流程

1. 编辑对应 App 目录下的 `privacy.md`
2. 同步修改同目录 `privacy.html`
3. `git commit` 并 `push`，Pages 约 1–3 分钟自动更新
