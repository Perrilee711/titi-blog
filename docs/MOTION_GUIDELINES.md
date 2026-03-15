# MOTION GUIDELINES

## 目标
微动效用于让页面更有呼吸感、更有触感、更有层级，而不是为了炫技。

## 动效原则
- 短
- 轻
- 克制
- 有质感
- 服务于层级和反馈
- 不干扰阅读

## 推荐动效
### Hero
- 右侧视觉锚点可有极轻微 breathing / glow
- 背景可有非常轻的明暗变化
- 动效要慢、幅度小

### Button Hover
- translateY(-2px)
- 轻微阴影变化
- 过渡时长 160ms~220ms

### Card Hover
- 微抬起
- scale 1.01~1.02
- 阴影轻柔扩散
- 不能夸张

### Section Reveal
- opacity + translateY(8px~12px)
- 只做轻量淡入
- 不要拖慢阅读节奏

### Timeline
- 节点进入或 hover 时可轻微高亮
- 节点本身要清晰但不抢戏

## 禁止动效
- 大面积漂浮
- 逐字动画
- 炫技视差
- 自动播放音乐
- 夸张弹跳
- 过长 reveal
- 影响阅读的动效

## 可访问性
- 优先考虑 prefers-reduced-motion
- 动效不是必须信息承载方式
- 即使关闭动效，页面也必须成立
