# Kira Product Monster Skills

专业的产品经理 AI 技能集,帮助你高效完成产品文档撰写和管理工作。

## 📦 包含的技能

### 1. 2red-product-monster-prd
**顶级结构化 PRD 撰写工具**

- ✅ 严格的序号层级体系(1/1-1/1-1-1)
- ✅ 完整的微交互状态机描述
- ✅ 异常边界和容错处理
- ✅ 纯中文表达,无英文术语
- ✅ 强制 MECE 原则

**使用场景**:
- 撰写新功能的 PRD
- 扩写现有 PRD 的某个模块
- 评审和优化 PRD 质量

### 2. 2red-product-monster-featurelist
**结构化功能清单提炼工具**

- ✅ MECE 拆解功能模块
- ✅ 多维表格属性映射
- ✅ 软硬件依赖分析
- ✅ 用户故事表述

**使用场景**:
- 产品立项时梳理功能清单
- 版本规划时整理需求列表
- 跨部门沟通功能范围

### 3. 2red-product-whitepaper
**产品白皮书维护工具**

- ✅ PRD 增量变更自动合并
- ✅ 按功能模块逻辑组织
- ✅ 保留原文描述
- ✅ 版本号自动管理
- ✅ 安全的删除确认机制

**使用场景**:
- 基于 PRD 生成产品白皮书初版
- 将新版本 PRD 合并到现有白皮书
- 维护产品全量功能文档

## 🚀 如何使用

### 支持的 AI 工具

这些技能基于 **AgentSkills** 标准,支持所有兼容该标准的 AI 工具:

- ✅ **OpenClaw** (推荐)
- ✅ **Antigravity**
- ✅ **Codex**
- ✅ 其他支持 AgentSkills 的工具

### 安装方法

#### 方法一: OpenClaw (推荐)

1. 克隆本仓库到本地:
```bash
git clone https://github.com/Kira2red/Kira-product-monster-skills.git
cd Kira-product-monster-skills
```

2. 将 skills 目录链接到 OpenClaw:
```bash
ln -s $(pwd)/skills ~/.openclaw/skills/
```

3. 在对话中使用:
```
@2red-product-monster-prd 帮我写一个用户登录模块的 PRD
```

#### 方法二: Antigravity

将 `skills/` 目录下的所有文件夹复制到:
```
~/.gemini/antigravity/skills/skills/
```

然后在聊天中使用 `@技能名` 调用。

#### 方法三: 其他工具

参考你使用的 AI 工具的 skills 安装文档,将本仓库的 `skills/` 目录放到对应位置。

## 📖 使用示例

### 撰写 PRD
```
@2red-product-monster-prd 
写一个充电预约功能的 PRD,需要包含:
- 用户可以设置充电时间段
- 支持充至停止时间或充至上限两种模式
- 低电量时自动充电不受预约限制
```

### 生成功能清单
```
@2red-product-monster-featurelist
基于这个 PRD 生成功能清单,用于版本规划
```

### 维护产品白皮书
```
@2red-product-whitepaper
将这个 PRD 合并到充电模块产品白皮书中
```

## 🔗 相关链接

- GitHub 仓库: https://github.com/Kira2red/Kira-product-monster-skills
- AgentSkills 标准: https://github.com/openclaw/openclaw
- OpenClaw 官网: https://openclaw.ai

## 📝 贡献

欢迎提交 Issue 和 Pull Request!

## 📄 License

MIT License
