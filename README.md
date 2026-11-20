# kb-figma-to-html

将 Figma 移动端设计稿实现为可验收的 HTML 演示，覆盖 mdpi 逻辑尺寸、比例适配、3× 位图、压缩、原稿 SVG、字体挂载与浏览器验证。

执行规则见 [SKILL.md](SKILL.md)。需要能访问设计文件的 Figma 工具和本地浏览器验证能力。字体、设计图片和账号授权由具体项目提供。

## 安装到 Codex

仓库公开，组员可直接查看、下载和克隆。需要 Git 执行下方命令；直接读取和拉取公开仓库无需维护者邀请。

Windows PowerShell，在目标目录尚不存在时执行：

```powershell
git clone https://github.com/fanxuanyi999/kb-figma-to-html.git "$env:USERPROFILE/.codex/skills/kb-figma-to-html"
```

macOS / Linux：

```sh
git clone https://github.com/fanxuanyi999/kb-figma-to-html.git ~/.codex/skills/kb-figma-to-html
```

使用自定义 CODEX_HOME 时，将目标目录替换为该目录下的 skills/kb-figma-to-html。如果已有手动安装版，先保留旧文件，再将仓库克隆到目标位置。安装后新开 Codex 会话，确认能选择技能。

## 使用

在 Codex 中调用：

```text
用 $kb-figma-to-html 将这个 Figma 节点实现为 HTML。
Figma 地址……，本地输出目录……，先提供本地版本验收。
```

## 拉取更新

Windows PowerShell：

```powershell
git -C "$env:USERPROFILE/.codex/skills/kb-figma-to-html" pull --ff-only
```

macOS / Linux：

```sh
git -C ~/.codex/skills/kb-figma-to-html pull --ff-only
```

拉取前保留自己改动的规则。出现本地修改或分支分歧时，先查看差异再合并。更新后新开会话使用最新版。

维护者更新规则时同步提交到本仓库，再通知组员拉取。也可以让自己的 Codex 检查本仓库并更新已安装的技能，保留个人改动。提交历史可用于查看每次规则变更。组员读取、下载和拉取更新无需仓库写入权限。
