# 小小跳跃 (Little Jump)

## 猫猫 · 头号冒险

无依赖的 HTML5 Canvas 平台跳跃 Demo。操纵猫猫的头部与身体：蓄力抛头、切换控制、相碰合体，打开桥梁并收集三颗星星，一起抵达小屋。

## 操作说明

| 按键 | 功能 |
|------|------|
| **A/D 或 ←/→** | 移动当前控制的部分 |
| **空格** | 当前控制的部分落地时，按下立即跳跃 |
| **鼠标移动 / Q/E** | 合体时调整发射角度 |
| **合体时按住鼠标左键，松开** | 在游戏画面内蓄力，1.4 秒达到最大力度，松开后发射头部；切走窗口取消蓄力 |
| **Tab** | 分离后切换控制头部或身体；发射后默认控制头部 |
| **头部与身体相碰** | 自动合体（发射后有 0.45 秒保护期）|
| **R / 右上角重新开始按钮** | 回到检查点 / 完全重开 |

完整玩法与操作说明见 [cat-launch/README.md](cat-launch/README.md)。本 Demo 面向有键盘和鼠标的电脑。

## 在线试玩

[开始游戏](https://elio0110.github.io/LittleJump/)

根目录首页自动进入 `cat-launch/`，也可以[直接打开游戏](https://elio0110.github.io/LittleJump/cat-launch/)。

## 本地运行

用桌面浏览器打开根目录 `index.html` 或 `cat-launch/index.html` 即可，无需安装。保留 `cat-launch/` 中的 HTML、CSS、JavaScript 文件及相对目录结构。

## 技术栈

- HTML5 Canvas
- Vanilla JavaScript
- 无外部依赖

---

*Made with ❤️ by 小小杯月*
