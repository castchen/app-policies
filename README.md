# app-policies



各 iOS App 的隐私政策、技术支持等合规静态页，通过 GitHub Pages 发布。



**目录命名**：使用 App **对外名称的拼音**（小写、无空格），例如「储物小精灵」→ `chuwuxiaojingling`。



## 站点结构



```text

app-policies/

├── index.html              # 索引页（列出各 App）

├── chuwuxiaojingling/      # 储物小精灵

│   ├── privacy.md

│   ├── privacy.html

│   └── support.html

├── babylog/                # 喂奶与纸尿裤 / Feed & Diaper

│   ├── privacy.md

│   ├── privacy.html

│   └── support.html

└── {app-pinyin}/           # 后续 App：同样含 privacy + support

    ├── privacy.md

    ├── privacy.html

    └── support.html

```



## GitHub Pages



1. 仓库 **Settings → Pages**

2. Source：**Deploy from a branch** → 分支 `main` → 文件夹 **`/ (root)`**

3. 保存后访问：`https://castchen.github.io/app-policies/`



## 各 App URL（App Store Connect）



| App（对外名称） | 隐私政策 URL | 技术支持 URL |

|----------------|--------------|--------------|

| 储物小精灵 | https://castchen.github.io/app-policies/chuwuxiaojingling/privacy.html | https://castchen.github.io/app-policies/chuwuxiaojingling/support.html |

| 喂奶与纸尿裤 / Feed & Diaper | https://castchen.github.io/app-policies/babylog/privacy.html | https://castchen.github.io/app-policies/babylog/support.html |



## 更新流程



1. 编辑对应 App 目录下的 `privacy.md` / `support.html`

2. 隐私政策改动时同步 `privacy.html`

3. `git commit` 并 `push`，Pages 约 1–3 分钟自动更新

