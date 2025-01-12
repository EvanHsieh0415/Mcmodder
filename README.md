# ☆Mcmodder☆

> MC 百科编审辅助工具  
> 原帖地址：[☆Mcmodder☆——MC百科编审辅助工具 － MC 百科](https://bbs.mcmod.cn/forum.php?mod=viewthread&tid=20483)

> [!NOTE]
> Mcmodder 支持 MC 百科 v4 页面和部分 v3 页面，对过旧的页面和非主站页面（社群 / 整合包区 / 找服玩等）暂无支持计划。
> Mcmodder 与 MC 百科官方无任何关联，使用时遇到任何问题都应优先在此贴反映！

## ☆ 更新日志 ☆

【2025-01-12】v1.1.1 紧急更新：修复了2个Bug：
- 插件设置无法正常生效；
- 推荐模组按钮无法点击。

## ☆ 功能列表 ☆

### 通用更新

1. **全面升级的百科主站 / 后台排版界面**；
2. **全面支持夜间模式！**－夜猫子们的福音；
3. 隐身模式：支持随时登出当前用户，且能够随时重新登入。
![](./img/image1.png)

### 个人页更新

1. 主页个人数据新增「平均字节数」和「科龄」（精确到天）数据；
2. 新增主站等级预览功能！可用于一系列经验相关计算；
3. 活跃图表新增对每日编辑字数的统计功能。
   *请注意：字数编辑量需从贡献榜获取，否则一律显示为空白！当打开贡献榜界面并显示某一时间段内的数据时，插件会自动加载并保存选定时间段内每一天中每一名用户的贡献数据；也正因此原因，只有单日贡献排名前 60 的用户能够成功记录到相应的编辑字数。*

### 资料页更新

1. 正文表格默认居于左侧而不再居于中央，更符合用户阅读习惯。超过 10 行的表格将自动折叠；
2. 对于综合父资料页，所有的子资料都将会被压缩，以减少无效空间的占用面积；
3. 可视化合成表现在默认折叠以减小占用空间；
4. 支持快捷跳转至上一个 / 下一个 ID。

### 模组/资料编辑页更新

1. 编辑器宽度适应窗口，高度适应当前正文内容长度；
2. 实时统计正文字节数 / 变动字节数；
3. **自动链接界面升级**：同名资料高亮提示，同属当前所编辑模组（包括前置和拓展模组）的资料直接置顶，搜索结果的前 9 项支持快捷键选择！同时也允许直接添加矿物词典 / 物品标签链接（搜索时加前缀 #）；
4. 自定义模版内容，一键插入 / 替换正文；
5. （BETA!）编辑器新增对 Markdown 的支持，支持正文一键 Markdown 转 HTML（标题自动添加兼容百科的诸如 `[h1=xxx]` 格式）；
6. 小图标 / 大图标编辑，允许上传任意尺寸的静态图像，插件会自动保留硬边缘缩放图像尺寸至 `32px` 和 `128px`（BUFF / DEBUFF 为 `36px` 和 `144px`）！静态的小图标和大图标间同样支持互转；
7. 编辑日志时，允许直接输入而不必在下拉菜单中选择日期；
8. 成功提交审核后，不再强制跳转至待审列表页面。对免审编辑无效；
9. 修复Bug：自动快速保存时，当前打开的菜单会收起。

### 合成表编辑页更新

1. 更加整齐的数据编辑区域！同时支持直接编辑合成表内的物品 ID / 矿物词典 / 物品标签，因此即使百科索引未更新也可以正常添加物品了；
2. 支持**锁定无序合成 / 自动设置 GUI**；
3. 支持删除单一记忆，即便选错物品也再也不必清空记忆啦；
4. 直接显示搜索结果的物品 ID、主要名称、次要名称，一目了然；

### 杂项更新

1. 自动签到，不再错过知识碎片；
2. 百科进度提示不再自动消失；
3. 自动记录主页闪烁标语；
4. 百科愚人节彩蛋在任何时候都能触发；
5. 自动隐藏短评正文中的空白行；
6. 支持轻触来快捷访问楼中楼里出现的链接；
7. 核弹警告：当短评长度超过某一预定值时，弹出核弹警告。同时支持自定义短评折叠最短长度 / 核弹警告触发最短长度；
8. 短评黑名单：自动屏蔽所选定用户发布的短评和回复；
9. 自动显示目标用户留言板，以及模组 / 作者的短评区；
10. 查询任一时间段内的审核列表和历史编辑记录时，自动加载并展开所有内容，并允许筛选；
11. 矿物词典/物品标签页面中，所有物品按所属模组分类；
12. 贡献榜更新：让贡献榜中各用户的昵称、排名、编辑量、编辑占比一目了然！

### 后台更新

1. 管理员的福音！——**自动查询并提醒待审项**：每隔一段时间，插件会自动打开后台并查询当前所有所管理模组区域的待审项。在模组区审核页面中，也提供了一键统计各模组区域待审项数量的快捷功能。打开自己的个人主页时，插件会自动更新模组区域；（出于一些原因，插件无法直接从后台获取数据，只能先打开后台页面）
2. 样式管理：设置资料列表表格的 CSS 样式时，实时显示预览。同时修复了百科原有的无法加载某些带有特殊样式的 CSS 的问题；

### 正文对比

由 KM 查询（https://kmcha.com/ ）提供支持的正文对比功能，现已整合至本插件中。在下列情形中，正文对比将自动执行，并显示新增及删除的正文部分：

- 查看改动对比时；
- 查看他人提交的待审项时；
- 在后台审核任一待审项时。

*注意：正文对比的字节统计量不准确。若正文对比统计量与编辑器上方统计量出现冲突，则以后者为准。*

---

## ☆ 如何安装？ ☆

1. 为你的浏览器安装油猴（安装方法问度娘）；
2. 单击「管理面板」打开已安装脚本列表，轻触这里的 `＋`；![](./img/image2.png)
3. 在本贴下载 `mcmodder.txt`，并将其中的内容全选复制粘贴进这个窗口；
4. `Ctrl＋S` 保存，大功告成！

## ☆ 自定义你的插件 ☆

Mcmodder 的许多功能都是可配置，且默认关闭的！  
你可以在个人主页的「设置」一栏中自由配置这些选项。  
如果安装后你的浏览器页面出现异常色块（虽然那不太可能发生），你需要通过这个设置菜单来禁用文字渐变的特性。

## ☆ 未来更新 ☆

我们正致力于为广大百科用户与编辑者们提供更加舒适的百科使用体验与更加快捷的编辑操作。  
**有更多的建议和新功能需求尽管来提！**我们会重视每一份提出的建议，并**保证及时予以答复**！（由于作者个人原因，最近可能会暂缓更新）  
本插件还非常新，一些功能可能随时会出现 Bug。`Mcmodder` 与 `MC 百科` 官方无任何关联，使用时遇到任何问题都应优先在此贴反映！  
本插件不定期更新！请记得随时回来检查更新。未来插件也会自带检查更新的功能。

---

本人从未接触过系统的 HTML/CSS/JavaScript 相关教程，这是作者本人第一次大胆地尝试并公开插件，各位大佬轻喷 >_<  
感谢 [@ein_Name](https://center.mcmod.cn/728642/), [@114514zhu](https://center.mcmod.cn/446458/), [@QQ酱119280](https://center.mcmod.cn/119280/) 为本插件的开发工作提供的支持！！
