<p align="center"><img src="https://cdn.jsdelivr.net/gh/23784148/upload-images@main/typora/20221003_1664779851.png" /></p>

# 简悦配置库

简悦配置库是简悦官方推出的一套针对新用户的极简配置方案，方便新用户用最快的方式使用简悦的各种高级服务，配置库内置了常用的双链笔记用法，如：Notion、Obsidian、Logseq、Roam Research，同时包含了简悦在阅读模式上的一些常规插件：Live Editor、题图、Safari 阅读模式等。

## 特点

用户仅需要下载对应的配置库，修改里面的 UID 为自己的高级账户 UID，即可实现简悦的各种高级操作。

## 受众

新用户或者不想使用手动配置的用户。

## 包含

- [Obsidian](#obsidian)
- [Notion](#notion)
- [Logseq](#obsidian)
- [剪藏版](#%E5%89%AA%E8%97%8F%E7%89%88)

## Obsidian

简悦跟 Obsidian 具有 [多种的联动方案](https://github.com/Kenshin/simpread/discussions?discussions_q=label%3Aobsidian)，为方便新用户上手，发布了 Obsidian 配置包，内置了一些常见的使用场景并覆盖下面的流程：

- 加入稍后读，自动将本地快照和 Markdown 导入到 Obsidian
- 加入标注时，自动将标注内容导入本地快照和 Obsidian
- 改变稍后读或标注的元数据时，自动将改动的内容保存到本地快照和 Obsidian
- 在 Obsidian 中直接内置好了简悦的标注系统，可直接在 Obsidian 实现标注

不同的使用场景具体包含的内容可以根据下面的链接查看，下面是这几种方案的区别：

|     | 适合受众                   | 同步助手 | 自动导入标注 | 本地快照 | 在 Obsidian 直接标注 | 文档          |
|-----|------------------------|------|--------|------|-----------------|-------------|
| 极速版 | 尝鲜用户                   | 不需要  | ✓      | ✕    | ✕               | [Github](https://github.com/Kenshin/simpread-configs/blob/main/obsidian%40little/Getting%20Started.md) · [语雀](https://www.yuque.com/kenshin/simpread/xkuecp) |
| 基础版 | 轻度使用简悦 +  Obsidian 的用户 | 需要   | ✓      | ✓    | ✕               | [Github](https://github.com/Kenshin/simpread-configs/blob/main/obsidian%40localrestapi/Getting%20Started.md) · [语雀](https://www.yuque.com/kenshin/simpread/cg33gh) |
| 高级版 | 重度使用简悦 + Obsidian 的用户  | 需要   | ✓      | ✓    | ✓               | [Github](https://github.com/Kenshin/simpread-configs/blob/main/obsidian%40sync/Getting%20Started.md) · [语雀](https://www.yuque.com/kenshin/simpread/wq35mh) |


备注：极速版可支持 Markdown 形式的本地快照，其余两种均支持 HTML 和 Markdown 本地快照。

## Notion

简悦跟 Notion 具有 [多种的联动方案](https://github.com/Kenshin/simpread/discussions?discussions_q=label%3Anotion)，为方便新用户上手，发布了 Notion 配置包，内置了一些常见的使用场景并覆盖下面的流程：

- 加入稍后读，自动将本地快照和 Markdown 导入到 Notion
- 加入标注时，自动将标注内容导入本地快照和 Notion
- 改变稍后读或标注的元数据时，自动将改动的内容保存到本地快照和 Notion
- 导入到 Notion 的内容包含：题图、Favicon、标签、原文地址等丰富的元数据信息

不同的使用场景具体包含的内容可以根据下面的链接查看，下面是这几种方案的区别：

|     | 适合受众                 | 同步助手 | Notion 图床 | 自动导入标注 | 本地快照 | 文档          |
|-----|----------------------|------|-----------|--------|------|-------------|
| 极速版 | 尝鲜用户                 | 不需要  | ✓         | ✕      | ✕    | [Github](https://github.com/Kenshin/simpread-configs/blob/main/notion%40base/Getting%20Started.md) · [语雀](https://www.yuque.com/kenshin/simpread/ewaflu) |
| 基础版 | 轻度使用简悦 +  Notion 的用户 | 不需要  | ✓         | ✓      | ✕    | [Github](https://github.com/Kenshin/simpread-configs/blob/main/notion%40enhance/Getting%20Started.md) · [语雀](https://www.yuque.com/kenshin/simpread/odhlf2) |
| 高级版 | 重度使用简悦 + Notion 的用户  | 需要   | ✓         | ✓      | ✓    | [Github](https://github.com/Kenshin/simpread-configs/blob/main/notion%40sync/Getting%20Started.md) · [语雀](https://www.yuque.com/kenshin/simpread/zuptv2) |


## Logseq

简悦跟 Logseq 具有 [多种的联动方案](https://github.com/Kenshin/simpread/discussions?discussions_q=label%3Alogseq)，为方便新用户上手，发布了 Logseq 配置包，内置了一些常见的使用场景并覆盖下面的流程：

- 加入稍后读，自动生成本地快照
- 加入标注时，自动将标注内容导入本地快照和 Logseq
- 改变稍后读或标注的元数据时，自动将改动的内容保存到本地快照和 Logseq
- 在 Logseq 中直接内置好了简悦的标注系统，可直接在 Logseq 实现标注

因为 Logseq 与 Obsidian 在插件 API 的支持度有限，所以并没有轻量级使用方案，根据 Logseq 支持的文件格式，区别为以下两种：

|             | 同步助手 | 自动导入标注 | 本地快照 | 在 Logseq 直接标注 | 支持文件格式 | 文档                                                         |
| ----------- | -------- | ------------ | -------- | ------------------ | ------------ | ------------------------------------------------------------ |
| Org Mode 版 | 需要     | ✓            | ✓        | ✓                  | `.org`       | [Github](https://github.com/Kenshin/simpread-configs/blob/main/logseq%40orgmode/Getting%20Started.md) · [语雀](https://www.yuque.com/kenshin/simpread/mdgp9n) |
| Markdown 版 | 需要     | ✓            | ✓        | ✓                  | `.md`        | [Github](https://github.com/Kenshin/simpread-configs/blob/main/logseq%40md/Getting%20Started.md) · [语雀](https://www.yuque.com/kenshin/simpread/tukkeo) |

# 剪藏版

如果想要把网页的内容完全保存，最好的做法是本地化保存，通过简悦导出到本地的文件更具可读性（通过阅读模式可剔除不必要的内容，仅保留正文）与更小的 size。

简悦众多的导出服务（剪藏功能），所以如果是喜欢将正文收藏到本地的用户，简悦官方为此适配了一组剪藏相关的配置包。

|                | 同步助手 | 本地快照 | 图片永久化方案                    | 支持文件格式 | 文档                                                         |
| -------------- | -------- | -------- | --------------------------------- | ------------ | ------------------------------------------------------------ |
| 离线 HTML 版   | 需要     | ✓        | 将图片以 `base64` 编码保存到 HTML | `.html`      | [Github](https://github.com/Kenshin/simpread-configs/blob/main/snapshot/Getting%20Started.md) · [语雀](https://www.yuque.com/kenshin/simpread/fiyku3) |
| PDF            | 需要     | ✓        | PDF                               | `.pdf`       | [Github](https://github.com/Kenshin/simpread-configs/blob/main/pdf/Getting%20Started.md) · [语雀](https://www.yuque.com/kenshin/simpread/omehxx) |
| md + assets 版 | 需要     | ✓        | 将图片下载到 `./assets` 文件夹    | `.md`        | [Github](https://github.com/Kenshin/simpread-configs/blob/main/assets/Getting%20Started.md) · [语雀](https://www.yuque.com/kenshin/simpread/chyo5a) |

上述方案均没有设置标注的自动化，可以看作完全是为了剪藏服务的配置包。
