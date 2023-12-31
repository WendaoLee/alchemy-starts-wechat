# 白夜回归塔-README
白夜极光国服光灵图鉴微信小程序‘**白夜回归塔**’相关仓库。目前未上传源码。

扫码即可访问小程序：
![](./qrcode.jpg)

如果您愿意支持该项目，可以前往爱发电https://afdian.net/a/leewendao 通过自选金额打赏或承包一个月或多个月的服务器开销费用哦🥰🥰🥰

![sponsor](./afdian.jpg)

## 1. 反馈

提交Issue说明相关问题即可。

## 2. 更新日志

#### Version1.0.3.4 2023-11-01 Update

- 修复了因为Kimaris数据源对typo的修改导致的技能先制标签无法正确显示的问题。

#### Version1.0.3.3 2023-10-19 Update

-  光灵详情页面添加表示稀有度的竖条（和主页同步）
-  提高了切换皮肤的按钮组（实际上是文本组，因为微信默认的按钮太难调整了）选中与不选中的颜色区分度
-  添加了光灵技能描述中的个别特性描述文本（如 溅射、强化格子）。
-  修复了【光灵页面】中技能描述文本无法选择的问题。
-  技能个别特性描述文本的颜色可以正常应用了。
-  更改了【觉醒材料】栏的背景配色
-  略微修复了【觉醒材料】栏的排版，使它稍微能够适配小尺寸屏幕。

#### Version1.0.3.1 2023-9-9 Update

这只是一个添加修复补丁的版本。

-  修复清除本地资源疑似不会删除光灵数据目录的问题
-  修复光灵礼物页面卡死无法下滑（在窄的屏幕中）的问题
-  修改【关于】页面的描述
-  针对缺失的数据进行显示的优化（如时装名称缺失）

#### Version1.0.3 2023-8-12 Update

1. Feature Correct

-  修复没有第二属性的三、四星光灵在显示页面的上多余黑框问题。
-  修复光灵详情页面以及其他页面中一些理应支持复制的文字无法复制的问题。
-  修复光灵数据在本地储存存在时无法得到更新的问题。
-  修复光灵武器图片无法点击放大的问题。

2. Feature Add

-  工具箱页面添加【设置】页。设置页内可主动清空本地储存、检查更新。
-  本地资源路径添加配置文件与资源检查文件。

3. Feature Change

-  将【关于】页面合并至工具箱页面。

#### Version1.0.2 2023-7-30 Update

1. Feature Add
   - 跟进 风暴停转之时 版本的光灵数据；补充缺失的丹棠、李天闲数据。
   -  光灵详情页面添加礼物喜好&&觉醒材料栏。
   - 增添工具箱页面
   - 在工具箱页面添加了CG画廊（目前不包括人物剧情立绘）、阿斯特拉故事录。
   - CG、光灵皮肤立绘等目前支持点击放大查看与保存
2. Feature Change
   - 删除了无用的资源文件列表清单以及相应逻辑代码
   - 向本地资源路径中添加了新的资源路径
   - 【重要】目前暂时放弃光灵最大数值选项的显示。原光灵最大数值的显示块将被光灵最大觉醒阶段的max值替换。
     如：上限为觉3的光灵显示觉3max数值；上限只为觉2的三星光灵显示觉2max数据。
   - 迁移CG资源云端存储来源。
3. Feature Correct （是的，这叫特性，不叫Bug）
   - 个别图标资源缺失的问题。

### Version1.0.1 2023-7-22 Update

- 完成了基本功能。目前功能有：
  - 基本的光灵图鉴索引信息。支持根据关键词索引光灵。
  - 支持查看光灵立绘、光灵数值、光灵技能（主动技能、连锁技能、装备技能与巨像工作技能）、光灵档案、光灵装备信息。
- 需要修复的问题：
  - 缺少光灵丹棠、李天闲的数值数据；缺少旧印光灵的装备技能描述。
  - 因为皮肤文件本身的尺寸问题导致会有一些光灵的立绘显示页面过于空旷/拥挤。目前我还没想好如何适配。
  
  