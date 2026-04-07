# AI短视频创作大师·参考文档索引

> 版本：4.0 | 日期：2026-04-07

---

## 文档结构

```
references/
├── INDEX.md                        # 本索引
├── core-screenwriting-framework.md   # 工业级影视编剧核心法则
├── b2b-conversion-case-study.md   # B2B高转化实战案例
├── b-roll-guide.md                # B-Roll空镜使用指南
├── emergency-protocol-v2.md      # 急救触发协议v2.0
│
├── industry-cases/                 # 行业案例库（6个案例）
│   ├── 00_INDEX.md               # 案例索引
│   ├── park-incubator.md        # 产业园/孵化器
│   ├── legal-services.md         # 法律服务
│   ├── tax-planning.md          # 财税筹划
│   ├── corporate-training.md     # 企业培训
│   ├── it-outsourcing.md        # IT外包
│   └── catering-chain.md         # 餐饮连锁
│
├── model-adapters/               # 模型适配器（9个模型）
│   ├── 00_INDEX.md              # 适配器索引
│   ├── image-models.md          # 图片模型（MJ/DALL-E/即梦/通义）
│   ├── video-models.md          # 视频模型（可灵/海螺/Runway/Pika）
│   └── lip-sync.md              # 对口型模型
│
└── variable-templates/           # 变量池模板库（13个模板）
    ├── 00_INDEX.md              # 模板索引
    ├── park-incubator.md        # 产业园模板×3
    ├── legal-services.md         # 法律服务模板×2
    ├── tax-planning.md          # 财税筹划模板×2
    ├── corporate-training.md      # 企业培训模板×2
    ├── it-outsourcing.md        # IT外包模板×2
    └── catering-chain.md         # 餐饮连锁模板×2
```

---

## 快速调用指南

### 场景1：开始新的B2B企服项目

1. 读取 `variable-templates/00_INDEX.md` → 选择行业模板
2. 读取 `variable-templates/[行业].md` → 获取变量池预设
3. 读取 `SKILL.md` Phase 1 → 开始需求侦察

### 场景2：参考案例创作

1. 读取 `industry-cases/00_INDEX.md` → 选择行业案例
2. 读取 `industry-cases/[行业].md` → 参考完整剧本
3. 按模板替换角色名+品牌名

### 场景3：AI生成失败急救

**方式1：自然语言（推荐）**
用户说"这个镜头生成失败了" → 系统自动识别 → 触发对应急救

**方式2：代码触发**
输入 `报错8.1` → 显示8.1节完整内容

详细规则见 `emergency-protocol-v2.md`

### 场景4：选择AI模型

1. 读取 `model-adapters/00_INDEX.md` → 选择模型类型
2. 读取 `model-adapters/[类型].md` → 获取详细适配指南

### 场景5：B-Roll使用

读取 `b-roll-guide.md` → 获取：
- B-Roll类型分类
- 完整时间轴示例
- 生成提示词模板

---

## 整合来源

| 来源 | 内容 |
|------|------|
| 分镜头执行方法论 | AI实操技巧（场景≤3个、8维度提示词） |
| 工业级AI视频制作SOP | 流程优先级（剧情>图片>视频） |
| 好莱坞影视编剧法则 | 文学功底（潜台词，双轨节奏） |
| B2B企服行业血泪复盘 | 血泪案例 |
| 行业案例库 | 6个完整行业案例 |
| 模型适配器 | 9个模型的详细指南 |
| 变量池模板库 | 13个行业预设模板 |
| B-Roll使用指南 | 空镜使用完整指南 |
| 急救协议v2.0 | 自然语言+代码双触发 |

---

*整合者：奕龙虾（太子）*
*版本：4.0*
*适配平台：Coze / Dify / GPTs / Claude 等*
