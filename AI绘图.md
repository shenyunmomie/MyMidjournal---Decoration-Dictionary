[TOC]

# Midjourney

使用方式：无需部署，外网discord即可

使用教程：[知乎](https://zhuanlan.zhihu.com/p/630409910)

Slack中也有，但MJ服务器满载，Claude(ChatGPT)不支持中国地区

购买方式：Discord官方，Slack bot付费，银河录像局拼车

## setting

![image-20240210215545603](https://shenyunmomie.oss-cn-beijing.aliyuncs.com/imags/202402102156525.png)

- RAW Mode：光影，人物表现力，环境光更优秀
- stylize：--s参数，让mj发挥更大想象
- Remix mode：混合模式，方便操作

## prompts

> 可由文本，图片url，表情符号组成

具体说明：

- 选词

词语的选择很重要。在许多情况下，更具体的同义词效果更好。不要尝试“大”，而是尝试“微小”、“巨大”、“巨大”、“巨大”或“巨大”。

- 复数词和集体名词

复数词留下了很多机会。尝试具体数字。“三只猫”比“猫”更具体。集体名词也可以用“flock of Birds”代替“birds”。

- 专注于你想要的

最好描述你想要什么，而不是描述你不想要什么。如果你要求举办一个“没有蛋糕”的派对，你的形象可能会包括一个蛋糕。为了确保最终图像中没有对象，请尝试使用[`--no`参数](https://docs.midjourney.com/multi-prompts)进行高级提示。

- 尽可能简短

- 多样、细节、多方面、多角度

  - **主题：** *人、动物、人物、地点、物体*

  - **媒介：** *照片、绘画、插图、雕塑、涂鸦、挂毯*

  - **环境：** *室内、室外、月球上、水下、城市中*

  - **灯光：** *柔和、环境、阴天、霓虹灯、工作室灯*

  - **颜色：** *充满活力、柔和、明亮、单色、彩色、黑白、柔和*

  - **情绪：** *平静、平静、喧闹、精力充沛*

  - **构图：** *肖像、爆头、特写、鸟瞰*

[官网prompt案例](https://docs.midjourney.com/docs/explore-prompting)

## Varistion变化、Upscalers放大

<img src="https://shenyunmomie.oss-cn-beijing.aliyuncs.com/imags/202402110042804.png" alt="image-20240211004238466" style="zoom:67%;" />

![image-20240211004200070](https://shenyunmomie.oss-cn-beijing.aliyuncs.com/imags/202402110042008.png)

- V：Varistion/Vary，变化
  - High Variation Mode：设置为高变化
  -  Low Variation Mode：设置为低变化
  - Vary (Strong)：再次生成时变化强烈
  -  Vary (Subtle)：再次生成时变化微小
  - Vary (Region)：指定区域变化，再次生成
- U：Upscalers，放大
  - Upscale (2x)：放大两倍像素
  - Upscale (4x)：放大四倍像素

![image-20240210222945730](https://shenyunmomie.oss-cn-beijing.aliyuncs.com/imags/202402102229815.png)

## 命令

- /blend: 混合多张图片，不适用文本
- /describe: 根据上传图片编写描述，4个左右
- /fast: 切换快速模式
- /imagine: 使用提示生成图像
- /setting: 设置
- /shorten: 将长文本prompt缩短
- /show: +job ID，加载历史工作
- /info: 账户信息
- /prefer auto_dm: 每次生图自动获取job ID

## 参数

- ar: Aspect Ratios 纵横比，
- c: 四张图片差异性，0-100
- s: 风格化效果，与关键词关联性，0-1000
- q: 渲染质量设置，0.25、0.5、1(1)
- iw: 上传图片权重，0-2(1)
- no: 负面描述词，--no book,pen
- stop: 渲染停止设置，10-100
- seed: 种子值，？？？
- tile: 无缝拼贴
- r: repeat，重复生图
- niji: 切换niji模式
- video: 记录生成过程

## 版本

- V5.2

该模型可产生更详细、更清晰的结果以及更好的**颜色、对比度和构图**。与早期型号相比，它对**提示的理解**也稍好一些，并且对整个[`--stylize`参数](https://docs.midjourney.com/stylize)范围的响应更加灵敏。

- V5.1

该模型比早期版本具有**更强的默认美感**，使其更易于使用简单的文本提示。它还具有高一致性，擅长准确解释自然语言提示，产生更少的不需要的伪影和边框，提高了图像清晰度，并支持重复模式等高级功能[`--tile`](https://docs.midjourney.com/tile)。

- V5.0

Midjourney V5.0 型号比 V5.1 型号产生更多的摄影世代。该模型生成的图像与提示非常匹配，但可能需要更长的提示才能实现您所需的美感。

- Niji5

Niji 模型是 Midjourney 和[Spellbrush](https://spellbrush.com/)之间的合作，旨在制作动漫和插图风格，并具有更多的动漫、动漫风格和动漫美学知识。它非常适合动态和动作镜头以及以角色为中心的构图。

# stable diffusion

> 开源但需部署



# prompt描述

关键词词典

- git 种类多：**[MidJourney-Styles-and-Keywords-Reference](https://github.com/shenyunmomie/MidJourney-Styles-and-Keywords-Reference)**

- midlibrary 词典 全 5：[midlibrary](https://midlibrary.io/)

- kalos 艺术家风格 4：[kalos,V5.2,artists](https://lib.kalos.art/topic?model=4&topic=0&type=artist)
- 森然网 中文 易使用 全 5：[森然网](https://wbh7.com/)

辅助关键词生成

- B族 中文易用 4：[B族提示词](https://www.bzu.cn/)
- promptFolder 英文 更贴合mj：[promptFolder ](https://promptfolder.com/midjourney-prompt-helper/)

# 装修词典

Interior Design+描述文字

参数原则：

- ar横宽比推荐16:9，否则视觉效果略显拥挤。
- c差异性，推荐500。
- s默认250就可，不宜太高，推荐500以内。
- 上传图片不推荐，mj不仅会提取房间结构特征，还会提取环境特征，类似毛坯房墙壁、自然光等，而且生成出的图片结构上与原图相差不小。推荐用文字细致描述。

描述方向

房间尺寸：5米长 x 4米宽 x 3米高
布局：客厅+餐厅，不需要卧室
风格：现代简约风格，以白色为主色调
材料：使用实木家具、大理石地板和墙面贴面板

视角和灯光效果：使用室内透视视角，白天光照效果
场景描述：客厅内有一张沙发、一张茶几、一组电视柜，餐厅内有一张餐桌、四把椅子、一组橱柜