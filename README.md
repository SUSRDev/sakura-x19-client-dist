# SakuraBot X19 Client — 分发中转

本仓库仅用于存放构建产物，供服务器或其它环境通过 **Raw** 链接直链下载。

## 文件说明

| 文件 | 说明 |
|------|------|
| `Client-all.jar` | X19 Service Client（`shadowJar`） |
| `config.yml` | 客户端配置（`server` 等） |

## 直链下载（将 `main` 换为你的默认分支名，一般为 `main`）

把下面 URL 中的 `OWNER` 与 `REPO` 换成本仓库在 GitHub 上的路径。

```
https://raw.githubusercontent.com/OWNER/REPO/main/Client-all.jar
https://raw.githubusercontent.com/OWNER/REPO/main/config.yml
```

示例（curl）：

```bash
curl -fL -o Client-all.jar "https://raw.githubusercontent.com/OWNER/REPO/main/Client-all.jar"
curl -fL -o config.yml "https://raw.githubusercontent.com/OWNER/REPO/main/config.yml"
```

更新文件时：在本仓库替换对应文件并 `git push` 即可；直链地址不变（同一分支、同一路径）。
