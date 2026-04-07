# B-Roll空镜使用指南

> 版本：1.0 | 日期：2026-04-07

---

## 什么是B-Roll？

B-Roll是插入主镜头之间的**情绪空镜头**，用于：
- 打破视觉单调
- 强化情绪表达
- 转场过渡
- 交代环境氛围

---

## B-Roll核心优势

| 优势 | 说明 |
|------|------|
| AI极度友好 | 不需要露脸，纯物体/风景，崩坏概率≈0 |
| 打破单调 | 长视频如果只有3个固定机位，观众会视觉疲劳 |
| 情绪强化 | 烟灰缸、时钟、雨滴 → 强化压抑感 |
| 时间压缩 | 2秒空镜 = 暗示时间流逝 |

---

## B-Roll类型对照表

### 情绪类型分类

| 情绪 | B-Roll示例 | 适用场景 |
|------|-----------|---------|
| **压抑破败** | 烟灰缸里燃尽的烟头 | 痛点期 |
| **压抑焦虑** | 时钟指向凌晨3点 | 痛点期 |
| **压抑孤独** | 被雨水打湿的窗户 | 痛点期 |
| **压抑失败** | 散落的文件/揉皱的纸 | 痛点期 |
| **转机希望** | 阳光透过窗帘洒入 | 转折点 |
| **转机惊喜** | 一杯咖啡热气袅袅 | 转折点 |
| **希望新生** | 窗外绿树/玻璃幕墙 | 情绪释放 |
| **归属温暖** | 握手/举杯致敬 | 品牌落版 |
| **信任建立** | 玻璃门上的logo | 品牌落版 |

---

## 60-90秒版B-Roll时间轴示例

### 《凌晨3点》完整时间轴

| 时间 | 主场景 | B-Roll插入 | B-Roll类型 | 时长 |
|------|--------|------------|------------|------|
| 0-3s | 车内（开场） | 无 | - | 3s |
| 3-5s | 车内 | **插入：烟灰缸空镜** | 压抑破败 | 2s |
| 5-8s | 车内 | 无 | - | 3s |
| 8-10s | 车内 | **插入：时钟特写（凌晨3点）** | 压抑焦虑 | 2s |
| 10-15s | 车内→情绪最低 | 无 | - | 5s |
| 15-18s | 转场 | **黑场+字幕过渡** | 转场 | 3s |
| 18-22s | 办公室 | **插入：阳光洒入桌面** | 转机希望 | 4s |
| 22-28s | 办公室 | 无 | - | 6s |
| 28-32s | 办公室 | **插入：咖啡热气** | 转机惊喜 | 4s |
| 32-40s | 办公室→情绪释放 | 无 | - | 8s |
| 40-45s | 品牌落版 | **插入：握手/背影+logo** | 归属温暖 | 5s |

**统计：**
- 主场景：2个（车内、办公室）✅ ≤3
- B-Roll插入：4次
- B-Roll总时长：15秒
- 有效打跑视觉单调，同时不破坏AI安全底线

---

## B-Roll生成提示词模板

### 情绪空镜-A：压抑破败

```english
【B-Roll-A1：烟灰缸空镜】
Close-up shot of an ashtray with burnt-out cigarette butts
The ashtray is slightly overflowing
Slight ash trail on the edge
Warm tungsten lighting, dim atmosphere
Cinematic, shallow depth of field
No text, no people, no motion blur

Negative: distorted, blurry, overexposed, text, fingers
```

```english
【B-Roll-A2：时钟特写】
Extreme close-up of a wall clock showing 3:00 AM
The second hand is still ticking
Dim blue light from a phone screen illuminating the clock face
Anxiety atmosphere
Cinematic, sharp focus on clock face

Negative: distorted, blurry, overexposed, text, hands
```

```english
【B-Roll-A3：湿窗户雨滴】
Close-up of raindrops sliding down a glass window
City lights blurred in the background
Cold blue-grey tones
Slight motion blur on the droplets
No people visible, interior shot

Negative: distorted, blurry, overexposed, text, faces
```

### 情绪空镜-B：转机希望

```english
【B-Roll-B1：阳光洒入】
Medium shot of sunlight streaming through curtains onto a desk
Dust particles visible in the light beams
Warm golden tones
Cozy, hopeful atmosphere
The light slowly shifts

Negative: distorted, blurry, overexposed, people
```

```english
【B-Roll-B2：咖啡热气】
Close-up of a cup of coffee on a desk
Steam wisps rising from the cup
Warm ambient lighting
Cozy atmosphere
The steam slowly curls upward

Negative: distorted, blurry, overexposed, hands, people
```

### 情绪空镜-C：归属温暖

```english
【B-Roll-C1：握手特写】
Close-up of two hands clinking coffee cups together
Warm afternoon light
Both people slightly out of frame
Only hands and cups visible
Friendly, warm atmosphere

Negative: distorted, blurry, overexposed, faces, text
```

```english
【B-Roll-C2：背影走向】
Shot of a person walking towards glass doors with company branding
Back view, professional attire
Natural daylight
The doors have subtle logo visible
Confident, forward-looking atmosphere

Negative: distorted, blurry, overexposed, faces, text
```

---

## B-Roll使用黄金法则

### 法则1：不超过主场景数
```
主场景：≤3个
B-Roll：不计入主场景数量

所以：3个主场景 + 任意B-Roll = 合规
```

### 法则2：每10秒最多1次B-Roll
```
60秒视频：约6次B-Roll
90秒视频：约9次B-Roll
每次B-Roll：2-3秒
```

### 法则3：B-Roll要"无用但有意义"
```
B-Roll不能推动剧情
B-Roll要强化情绪
B-Roll要暗示时间/空间变化
```

### 法则4：AI友好优先
```
✅ 纯物体/风景（烟灰缸、时钟、咖啡）
✅ 固定镜头或缓慢移动
❌ 不要人物正脸
❌ 不要复杂运镜
❌ 不要动态液体（洒落的咖啡）
```

---

## B-Roll快速查询表

| 时长 | 建议B-Roll次数 | 总时长 | 每10秒 |
|------|---------------|--------|--------|
| 15秒 | 0-1次 | 2秒 | 1.3次 |
| 45秒 | 2-3次 | 6-9秒 | 0.6次 |
| 60秒 | 4-5次 | 10-15秒 | 0.7次 |
| 90秒 | 6-8次 | 15-24秒 | 0.8次 |
