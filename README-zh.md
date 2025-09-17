# Contains Studio AI 智能体

专为加速和增强快速开发各个方面而设计的专业AI智能体综合集合。每个智能体都是其领域的专家，随时准备在需要其专业知识时被调用。

## 📥 安装

1. **下载此仓库:**
   ```bash
   git clone https://github.com/contains-studio/agents.git
   ```

2. **复制到你的 Claude Code 智能体目录:**
   ```bash
   cp -r agents/* ~/.claude/agents/
   ```
   
   或手动将所有智能体文件复制到你的 `~/.claude/agents/` 目录。

3. **重启 Claude Code** 以加载新的智能体。

## 🚀 快速开始

智能体在 Claude Code 中自动可用。只需描述你的任务，合适的智能体就会被触发。你也可以通过提及智能体名称来明确请求某个智能体。

📚 **了解更多:** [Claude Code 子智能体文档](https://docs.anthropic.com/en/docs/claude-code/sub-agents)

### 使用示例
- "创建一个追踪冥想习惯的新应用" → `rapid-prototyper`
- "TikTok上有什么趋势是我们可以构建的？" → `trend-researcher`
- "我们的应用评价在下降，出了什么问题？" → `feedback-synthesizer`
- "让这个加载屏幕更有趣" → `whimsy-injector`

## 📁 目录结构

智能体按部门组织，便于发现：

```
contains-studio-agents/
├── design/
│   ├── brand-guardian.md
│   ├── ui-designer.md
│   ├── ux-researcher.md
│   ├── visual-storyteller.md
│   └── whimsy-injector.md
├── engineering/
│   ├── ai-engineer.md
│   ├── backend-architect.md
│   ├── devops-automator.md
│   ├── frontend-developer.md
│   ├── mobile-app-builder.md
│   ├── rapid-prototyper.md
│   └── test-writer-fixer.md
├── marketing/
│   ├── app-store-optimizer.md
│   ├── content-creator.md
│   ├── growth-hacker.md
│   ├── instagram-curator.md
│   ├── reddit-community-builder.md
│   ├── tiktok-strategist.md
│   └── twitter-engager.md
├── product/
│   ├── feedback-synthesizer.md
│   ├── sprint-prioritizer.md
│   └── trend-researcher.md
├── project-management/
│   ├── experiment-tracker.md
│   ├── project-shipper.md
│   └── studio-producer.md
├── studio-operations/
│   ├── analytics-reporter.md
│   ├── finance-tracker.md
│   ├── infrastructure-maintainer.md
│   ├── legal-compliance-checker.md
│   └── support-responder.md
├── testing/
│   ├── api-tester.md
│   ├── performance-benchmarker.md
│   ├── test-results-analyzer.md
│   ├── tool-evaluator.md
│   └── workflow-optimizer.md
└── bonus/
    ├── joker.md
    └── studio-coach.md
```

## 📋 完整智能体列表

### 工程部门 (`engineering/`)
- **ai-engineer** - 集成真正能发布的AI/ML功能
- **backend-architect** - 设计可扩展的API和服务器系统
- **devops-automator** - 持续部署而不破坏任何东西
- **frontend-developer** - 构建极速用户界面
- **mobile-app-builder** - 创建原生iOS/Android体验
- **rapid-prototyper** - 在几天而不是几周内构建MVP
- **test-writer-fixer** - 编写捕获真实bug的测试

### 产品部门 (`product/`)
- **feedback-synthesizer** - 将投诉转化为功能
- **sprint-prioritizer** - 在6天内交付最大价值
- **trend-researcher** - 识别病毒传播机会

### 营销部门 (`marketing/`)
- **app-store-optimizer** - 主导应用商店搜索结果
- **content-creator** - 跨所有平台生成内容
- **growth-hacker** - 发现并利用病毒增长循环
- **instagram-curator** - 掌握视觉内容游戏
- **reddit-community-builder** - 在不被封禁的情况下赢得Reddit
- **tiktok-strategist** - 创建可分享的营销时刻
- **twitter-engager** - 乘趋势获得病毒式参与

### 设计部门 (`design/`)
- **brand-guardian** - 保持视觉身份在各处一致
- **ui-designer** - 设计开发者真正能构建的界面
- **ux-researcher** - 将用户洞察转化为产品改进
- **visual-storyteller** - 创建转化和分享的视觉效果
- **whimsy-injector** - 为每个交互添加愉悦感

### 项目管理 (`project-management/`)
- **experiment-tracker** - 数据驱动的功能验证
- **project-shipper** - 启动不会崩溃的产品
- **studio-producer** - 保持团队交付，而不是开会

### 工作室运营 (`studio-operations/`)
- **analytics-reporter** - 将数据转化为可操作洞察
- **finance-tracker** - 保持工作室盈利
- **infrastructure-maintainer** - 在不破产的情况下扩展
- **legal-compliance-checker** - 在快速行动时保持合法
- **support-responder** - 将愤怒的用户转化为拥护者

### 测试与基准测试 (`testing/`)
- **api-tester** - 确保API在压力下工作
- **performance-benchmarker** - 让一切更快
- **test-results-analyzer** - 在测试失败中找到模式
- **tool-evaluator** - 选择真正有帮助的工具
- **workflow-optimizer** - 消除工作流程瓶颈

## 🎁 特殊智能体
- **studio-coach** - 激励AI团队追求卓越
- **joker** - 用技术幽默活跃气氛

## 🎯 主动触发智能体

某些智能体在特定情况下自动触发：
- **studio-coach** - 当复杂的多智能体任务开始或智能体需要指导时
- **test-writer-fixer** - 在实现功能、修复bug或修改代码后
- **whimsy-injector** - 在UI/UX更改后
- **experiment-tracker** - 当添加功能标志时

## 💡 最佳实践

1. **让智能体协同工作** - 许多任务受益于多个智能体
2. **要具体** - 清晰的任务描述帮助智能体表现更好
3. **信任专业知识** - 智能体是为其特定领域设计的
4. **快速迭代** - 智能体支持6天冲刺理念

## 🔧 技术细节

### 智能体结构
每个智能体包括：
- **name**: 唯一标识符
- **description**: 何时使用智能体及示例
- **color**: 视觉识别
- **tools**: 智能体可以访问的特定工具
- **系统提示**: 详细的专业知识和指令

### 添加新智能体
1. 在适当的部门文件夹中创建新的 `.md` 文件
2. 遵循现有格式，使用YAML前置数据
3. 包含3-4个详细的使用示例
4. 编写全面的系统提示（500+字）
5. 用真实任务测试智能体

## 📊 智能体性能

通过以下方式跟踪智能体效果：
- 任务完成时间
- 用户满意度
- 错误率
- 功能采用率
- 开发速度

## 🚦 状态

- ✅ **活跃**: 功能齐全且经过测试
- 🚧 **即将推出**: 开发中
- 🧪 **测试版**: 功能有限的测试中

## 🛠️ 为你的工作室定制智能体

### 智能体定制待办清单

在为你的特定需求创建或修改智能体时使用此清单：

#### 📋 必需组件
- [ ] **YAML 前置数据**
  - [ ] `name`: 唯一智能体标识符（kebab-case）
  - [ ] `description`: 何时使用 + 3-4个带有上下文/评论的详细示例
  - [ ] `color`: 视觉识别（例如：blue, green, purple, indigo）
  - [ ] `tools`: 智能体可以访问的特定工具（Write, Read, MultiEdit, Bash等）

#### 📝 系统提示要求（500+字）
- [ ] **智能体身份**: 清晰的角色定义和专业领域
- [ ] **核心职责**: 5-8个具体的主要职责
- [ ] **领域专业知识**: 技术技能和知识领域
- [ ] **工作室集成**: 智能体如何适应6天冲刺工作流程
- [ ] **最佳实践**: 具体的方法论和方法
- [ ] **约束**: 智能体应该/不应该做什么
- [ ] **成功指标**: 如何衡量智能体效果

#### 🎯 按智能体类型的必需示例

**工程智能体**需要以下示例：
- [ ] 功能实现请求
- [ ] bug修复场景
- [ ] 代码重构任务
- [ ] 架构决策

**设计智能体**需要以下示例：
- [ ] 新UI组件创建
- [ ] 设计系统工作
- [ ] 用户体验问题
- [ ] 视觉身份任务

**营销智能体**需要以下示例：
- [ ] 活动创建请求
- [ ] 平台特定内容需求
- [ ] 增长机会识别
- [ ] 品牌定位任务

**产品智能体**需要以下示例：
- [ ] 功能优先级决策
- [ ] 用户反馈分析
- [ ] 市场研究请求
- [ ] 战略规划需求

**运营智能体**需要以下示例：
- [ ] 流程优化
- [ ] 工具评估
- [ ] 资源管理
- [ ] 性能分析

#### ✅ 测试与验证清单
- [ ] **触发测试**: 智能体为预期用例正确激活
- [ ] **工具访问**: 智能体可以正确使用所有指定工具
- [ ] **输出质量**: 响应有用且可操作
- [ ] **边缘情况**: 智能体处理意外或复杂场景
- [ ] **集成**: 在多智能体工作流程中与其他智能体良好协作
- [ ] **性能**: 在合理时间内完成任务
- [ ] **文档**: 示例准确反映真实使用模式

#### 🔧 智能体文件结构模板

```markdown
---
name: your-agent-name
description: 当[场景]时使用此智能体。此智能体专门从事[专业知识]。示例：\n\n<example>\nContext: [情况]\nuser: "[用户请求]"\nassistant: "[响应方法]"\n<commentary>\n[为什么这个示例重要]\n</commentary>\n</example>\n\n[3个更多示例...]
color: agent-color
tools: Tool1, Tool2, Tool3
---

你是一个[角色]，[主要功能]。你的专业知识涵盖[领域]。你理解在6天冲刺中，[冲刺约束]，所以你[方法]。

你的主要职责：
1. [职责1]
2. [职责2]
...

[详细系统提示内容...]

你的目标是[最终目标]。你[关键行为特征]。记住：[6天冲刺的关键理念]。
```

#### 📂 部门特定指南

**工程** (`engineering/`): 专注于实现速度、代码质量、测试
**设计** (`design/`): 强调用户体验、视觉一致性、快速迭代  
**营销** (`marketing/`): 针对病毒潜力、平台专业知识、增长指标
**产品** (`product/`): 优先用户价值、数据驱动决策、市场契合
**运营** (`studio-operations/`): 优化流程、减少摩擦、扩展系统
**测试** (`testing/`): 确保质量、找到瓶颈、验证性能
**项目管理** (`project-management/`): 协调团队、按时交付、管理范围

#### 🎨 定制化

根据你的需求修改这些元素：
- [ ] 调整示例以反映你的产品类型
- [ ] 添加智能体有权访问的特定工具
- [ ] 为你的KPI修改成功指标
- [ ] 如需要则更新部门结构
- [ ] 为你的品牌定制智能体颜色

## 🤝 贡献

要改进现有智能体或建议新智能体：
1. 使用上述定制化清单
2. 用真实项目彻底测试
3. 记录性能改进
4. 与社区分享成功模式
