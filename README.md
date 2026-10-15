# 逐光记 · GitHub Pages 固定链接

一条永久不变的网址，以后每次更新只需重新上传 `index.html`，刷新页面即是新版。

---

## 一次性设置（约 5 分钟）

1. 打开 <https://github.com>，注册 / 登录（免费）。
2. 右上角 **+** → **New repository**。
   - **Repository name** 填：`zhuguangji`
   - 必须选 **Public**（私有仓库的 Pages 需要付费计划）
   - 其余保持默认，点 **Create repository**
3. 进仓库后点 **Add file** → **Upload files**。
4. 把本文件夹里的 **`index.html`** 拖进上传区（就这一个文件）。
5. 点页面底部 **Commit changes**。
6. 点仓库顶部 **Settings** → 左侧菜单 **Pages**。
   - **Source** 选 **Deploy from a branch**
   - **Branch** 选 `main`，文件夹选 `/ (root)`
   - 点 **Save**
7. 等约 1 分钟，刷新该页面，顶部会出现：

   > Your site is live at `https://你的用户名.github.io/zhuguangji/`

   **这就是你的固定网址，一辈子不会变。**

8. 手机浏览器打开它 → 分享 →「添加到主屏幕」，图标永久有效。

---

## 以后每次更新（约 30 秒）

1. 打开 <https://github.com/你的用户名/zhuguangji>
2. 点 `index.html` → 右上角铅笔图标（Edit）→ 全选删除 → 粘贴新内容 → **Commit changes**
   （或者：**Add file** → **Upload files** → 拖新文件覆盖同名文件）
3. 等 30 秒，刷新页面即是新版。

**怎么确认更新成功了？** 看页面最底部那行小字：

> 逐光记 · 版本 `v2026.10.15-3` · 每科单独成图

每次我更新后会告诉你新的版本号，对得上就说明线上已是最新。

---

## 注意

- **数据存在浏览器本地**，不随网址走。GitHub 只托管这一个 HTML 文件，
  你的成绩记录在你手机的浏览器里。换设备 / 清浏览器数据会丢，
  请定期在「我的 → 导出 JSON」备份。
- 想要电脑和手机数据一致：在电脑上导出 JSON，手机上导入。
- 若 GitHub 在国内访问慢，可换 **Cloudflare Pages**（同样免费固定域名），
  步骤相近，告诉我我写一份。
