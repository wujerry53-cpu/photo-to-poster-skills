# GitHub 发布步骤

## 1. 新建仓库

推荐仓库名：

`photo-to-poster-skills`

Description：

`Open-source AI prompts & skills for turning everyday photos into editorial design posters.`

建议：
- Public
- 不需要勾选 GitHub 自动创建 README
- License 可以不选，因为本包已经包含 MIT LICENSE

## 2. 上传文件

创建仓库后：

`Add file` → `Upload files`

将本压缩包解压后的 `photo-to-poster-skills` 文件夹中的所有内容拖入上传区域。

注意：
不要把最外层整个文件夹拖进去导致仓库里再次出现一层 `photo-to-poster-skills/`。
仓库首页应该直接看到：

```text
README.md
LICENSE
prompts/
skills/
examples/
```

## 3. Commit

Commit message 可以填写：

`Initial release: photo poster prompts and skills`

然后点击 Commit changes。

## 4. 小红书怎么写

不建议在正文里塞完整长 Prompt。

可以写：

> 完整 Prompt + Skill 已经开源到 GitHub。
> GitHub 搜索：photo-to-poster-skills

如果你的 GitHub 用户名已确定，也可以直接告诉用户：

> GitHub 搜索：你的用户名 / photo-to-poster-skills

这样比放无法点击的超长 URL 更适合小红书正文。

## 5. 后续更新

以后只需要更新：
- `prompts/`：用户直接复制的 Prompt
- `skills/`：Agent Skill
- `examples/`：Before / After 案例

小红书原笔记无需重新发布。
