# 灵犀按键自定义

当初就是冲着 OPPO K15 Pro+ 的造型买的，到手最喜欢侧面那颗「灵犀」按键，结果发现它能干的事太少，于是自己写了个 App。

基于 [SlimeNull/OppoCustomSideButtonFunctions](https://github.com/SlimeNull/OppoCustomSideButtonFunctions) 二次开发，感谢原作者铺路！

![preview](https://raw.githubusercontent.com/a1204507929/LingXiSideKey/main/images/preview.png)

## 功能

- 单击 / 双击 / 长按三个手势均可自定义动作，按下即振动（单击一下、双击两下、长按持续）
- 打开任意应用（自选）、灯效开关、打开游戏助手、切换散热风扇（原厂通道，切换有流体云胶囊）
- 按应用配置：可为指定应用单独设置按键功能（优先于全局），如相机前台一键拍照
- 首页显示 Root 与框架激活状态，可一键跳转修复 / 软重启
- 高级设置：作用域检查与一键申请、配置 JSON 导入 / 导出
- 游戏内自动放行原厂灵犀行为

## 安装

1. 安装 APK，在 Vector / LSPosed 中启用本模块，勾选 **Android 系统框架（android）** 作用域
2. 重启系统框架（软重启即可）
3. 打开应用配置动作即可，设置自动保存

## 更新记录

- **v1.1.0** 修复 Root 状态误报未激活（改扫 ksud 守护进程）；作用域检查区分未安装项，不再误报
- v1.0.9 包名迁移至 `io.github.a1204507929.lingxikey`
- v1.0.8 首页环境状态卡片、JSON 配置导入导出、作用域检查交互优化

## 相关

- 源码：<https://github.com/a1204507929/LingXiSideKey>
- 原项目：<https://github.com/SlimeNull/OppoCustomSideButtonFunctions>
