# LogTime

> **Time is linear. Perception is not.**

LogTime 是一个以**非线性节奏呈现时间**的计时器。

真实时间始终匀速流逝，而 LogTime 通过数学模型改变时间的视觉呈现。

## 时间模型

LogTime 提供三种时间模型：

### Linear

$$
P_L(x)=x
$$

线性呈现，视觉进度与真实时间同步。

### Model A · 启程

$$
P_A(x)=\frac{\ln(1+2x)}{\ln3}
$$

先快后慢。

### Model B · 抵达

$$
P_B(x)=x^2
$$

先慢后快。

三种模型描述的是同一段真实时间，只是采用不同的视觉节奏。

## 视觉

* **Ring** — 圆环
* **Grid** — 方格（20 × 10）

两种视觉形式均支持三种时间模型。

## 功能

* 自定义任务名称与时长
* 支持秒、分钟、小时、天、周
* 暂停 / 继续 / 重新开始
* Ring / Grid 视觉模式
* Linear / 启程 / 抵达时间模型
* 实际时间进度显示 / 隐藏
* 任务状态本地保存
* 刷新页面后恢复任务
* 生成当前状态图片
* 响应式移动端与桌面端界面

## 在线体验

[LogTime](https://yalways17.github.io/logtime/)

## 技术

HTML · CSS · Vanilla JavaScript · Canvas API · CSS Grid · localStorage · html2canvas

---

**LogTime · v1.0 · 2026**
