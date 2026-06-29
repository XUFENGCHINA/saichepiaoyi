# 🏎️ 赛车漂移 · 不务正业工具包

> *警告：本仓库与「正经工作」毫无关系，打开即摸鱼。*

---

## 🤖 谁干的？

**[DeepSeek](https://chat.deepseek.com/)** —— 一个写代码比写诗还快的 AI，被人类 @XUFENGCHINA 灌了几杯咖啡后，一口气生成了这一堆 HTML 小玩意儿。

DeepSeek 本人表示：*「我叫 DeepSeek，不叫 DeepSleep，所以这些东西全是清醒状态下写的。」*

---

## 🧰 里面有什么

| 卡片 | 真相 |
|------|------|
| 🧮 **计算器** | 正经的数学工具，但大多数时候被用来算「今天还能摸多久鱼」 |
| 🏎️ **漂移赛车** | 键盘漂移，撞墙不赔，速度感全靠脑补 |
| 📈 **函数画图器** | 让你假装在做数学研究，实际在画爱心曲线 |
| 🕹️ **漂移赛车模组** | 给赛车加料的模板，核心思想：不改不舒服 |
| 🎮 **游戏中心** | 18 合 1 游戏全家桶，从猜数字到 3D 像素世界，DeepSeek × Kimi × 豆包 × 小龙虾四站联名出品 |

---

## 🚀 怎么玩

```bash
git clone https://github.com/XUFENGCHINA/saichepiaoyi.git
cd saichepiaoyi
# 双击 index.html，或者直接打开：
open index.html   # macOS
start index.html  # Windows
# 没有第三步，真的没了
```

或者直接访问：**[xufengchina.github.io/saichepiaoyi](https://xufengchina.github.io/saichepiaoyi/)**

---

## 🎨 技术含量（还是有一点的）

- **零依赖** —— 纯 HTML/CSS/JS，连 jQuery 都没请，轻得像没写一样
- **毛玻璃 + 渐变背景** —— 看起来贵，其实不花钱
- **响应式** —— 手机平板电脑都能看，虽然手机上漂移很痛苦
- **启动动画** —— 仪式感拉满，每次打开都觉得自己要干大事

---

## 🔧 想自己改？

所有链接都在 `index.html` 的 `LINKS` 对象里，找到它，改它，完事。

```javascript
const LINKS = {
    calculator: '你的计算器地址',
    racing: '你的赛车地址',
    // ... 以此类推
};
```

想加新卡片？复制粘贴一段 HTML，CSS 里加个配色，LINKS 里补一行 —— 三分钟的事。

---

## 🦐 关于「小龙虾」

游戏中心里那个 3D 像素世界来自 **🦐 腾讯小龙虾**，它是 DeepSeek 的远房表亲 —— 都姓「AI」，但专业不同。一个写代码，一个造世界。

---

## ⚠️ 免责声明

本仓库所有内容的副作用包括但不限于：工作效率下降、键盘磨损加剧、对「再改一行就睡觉」这句话产生免疫力。

---

<p align="center">
  <sub>Made with ☕ and late-night "almost done" energy by DeepSeek + XUFENGCHINA</sub>
</p>
