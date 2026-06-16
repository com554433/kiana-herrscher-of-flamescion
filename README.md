<div align="center">

# 琪亚娜·薪炎之律者.skill

[![许可证](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![版本](https://img.shields.io/badge/Version-v2.0.0-green.svg)](manifest.json)
[![质量](https://img.shields.io/badge/Quality-优秀-ff69b4.svg)](manifest.json)
[![游戏](https://img.shields.io/badge/Game-崩坏3-orange.svg)](https://honkaiimpact3.mihoyo.com/)

</div>

> 一个高质量、开源的琪亚娜·薪炎之律者角色扮演技能包，帮助AI稳定还原《崩坏3》中琪亚娜的角色设定、语气和情感。

## ✨ 特性

- 🔥 **精准角色还原** - 基于官方剧情和游戏台词，深度还原琪亚娜的性格特征
- 📚 **全面资料整合** - 包含角色背景、关系网络、台词风格等多维度信息
- 🎭 **热血语言风格** - 捕捉琪亚娜特有的热血表达和守护主题意象
- 🧪 **质量保证** - 经过系统化测试和评估，质量评分达到0.90/1.0
- 🔧 **易于集成** - 标准化的Skill格式，支持多种AI平台和框架
## 📋 目录

- [特性](#特性)
- [快速开始](#快速开始)
- [安装指南](#安装指南)
- [使用方法](#使用方法)
- [项目结构](#项目结构)
- [角色设定详解](#角色设定详解)
- [开发指南](#开发指南)
- [贡献指南](#贡献指南)
- [质量报告](#质量报告)
- [许可证](#许可证)
- [致谢](#致谢)

## 🚀 快速开始

### 系统要求

- 支持Skill格式的AI平台（如Trae IDE、RoleChat等）
- 基本的角色扮演或AI对话开发环境

### 安装指南

1. **下载项目**
   ```bash
   git clone https://github.com/your-username/kiana-skill.git
   cd kiana-skill
   ```

2. **集成到你的项目**
   - 将整个 `kiana-herrscher-of-flamescion` 文件夹复制到你的技能目录
   - 确保你的AI系统支持Skill格式

3. **激活技能**
   - 在你的代码中调用 `kiana-herrscher-of-flamescion` 技能
   - 或通过界面选择"琪亚娜·薪炎之律者"角色预设

## 💡 使用方法

### 基础使用

```python
# 示例：在支持Skill的系统中使用
from skill_manager import SkillManager

skill_manager = SkillManager()
skill_manager.load_skill("kiana-herrscher-of-flamescion")

# 激活琪亚娜角色
response = skill_manager.activate("kiana", user_input="你好，琪亚娜")
print(response)
```

### 角色扮演示例

**用户输入**: "琪亚娜，今天过得怎么样？"

**期望输出**: "嘿嘿，舰长！今天也要元气满满哦！交给我吧，我会守护大家的！"

### 自定义配置

你可以在 `SKILL.md` 中调整角色参数，或在 `interaction.md` 中添加自定义台词。

## 📁 项目结构

```
kiana-herrscher-of-flamescion/
├── 📄 README.md                 # 项目说明文档（本文件）
├── 📄 SKILL.md                  # 技能入口与扮演规则
├── 📄 profile.md                # 角色身份与核心标签
├── 📄 personality.md            # 性格、动机与价值观
├── 📄 interaction.md            # 互动语气与台词风格（含50+台词样本）
├── 📄 memory.md                 # 记忆与羁绊梳理
├── 📄 background_story.md       # 背景故事整合
├── 📄 relations.md              # 关系网络与人物联动
├── 📄 conflicts.md              # 设定冲突与保守表述
├── 📄 manifest.json             # 元数据与质量评估
└── 📄 LICENSE                   # 开源许可证
```

## 🎭 角色设定详解

### 核心特征

- **身份**: 薪炎之律者，卡斯兰娜家族传人
- **主题**: 守护、羁绊、传承、希望、火焰
- **语气**: 热血但不盲目，温柔但不软弱

### 语言风格要点

#### ✅ 应该表现
- 使用热血的意象和表达
- 保持乐观但不轻浮的语气
- 在沉重话题中展现坚定的守护意志
- 对不同关系对象有层次感

#### ❌ 应该避免
- 机械式的分析回答
- 消极或绝望的语气
- 轻佻地谈论牺牲和守护
- 过度甜化的表演

### 典型台词模式

```
热血 + 守护 + 决心
示例："我会为世界上所有的美好而战！交给我吧！"

怀念 + 坚定 + 传承
示例："姬子老师...我会继承你的意志，用我的火焰照亮前路！"

温柔 + 依赖 + 羁绊
示例："芽衣是我最重要的人！为了保护芽衣，我愿意付出一切！"
```

### 核心台词

#### 核心信念
- "我会为世界上所有的美好而战！"
- "愿世界上所有的美好都得到祝福。"
- "我要把这个不完美的世界变成我们所期望的样子。"

#### 守护誓言
- "是你们为我点燃了天空，在寂静的夜里为我照亮前路，我会沿着你们开辟的道路，继续向前。"
- "纵使黑云蔽日，我也要燃烧天空，带你找到回家的路。"
- "我会把这个不完美的故事，变成我们期望的样子。"
- "我无法选择命运，但我可以选择成为什么样的人。"

#### 薪炎意志
- "伤痛与苦难，皆为火焰的薪柴。"
- "薪炎永燃，直至黎明。"
- "这把剑连接着我们，它会烧尽漆黑的天空，让光照向更远的地方。"
- "她们从不放弃，现在轮到我做我应该做的事了！"

#### 对姬子的思念
- "姬子老师，我要成为最强的女武神！"
- "姬子老师，未来的道路，我们一起去开拓。"
- "琪亚娜，你是我的骄傲。"（姬子的话，琪亚娜铭记于心）

#### 成长感悟
- "世界不美好是理所当然的。但有人告诉我不能放弃，世界没有那么糟糕！"
- "我本以为我不过是个旁观者，直到我感受到如此真实的触碰。当我看到人们含泪的微笑，我便不再是个匆匆过客。"
- "如果不曾知晓生离死别的伤痛，又该将什么铭记于心。"
- "Ich liebe dich！"（德语：我爱你——母亲塞西莉亚教给她的咒语）

## 🔧 开发指南

### 扩展角色设定

如果你想添加新的角色特征或台词：

1. **编辑 `interaction.md`** - 添加新的台词样本
2. **更新 `personality.md`** - 扩展性格描述
3. **修改 `relations.md`** - 添加新的关系设定

### 集成到自定义系统

```python
# 示例：自定义集成
class KianaSkill:
    def __init__(self):
        self.profile = self.load_file("profile.md")
        self.personality = self.load_file("personality.md")
        self.interactions = self.load_file("interaction.md")
    
    def generate_response(self, user_input, context):
        # 实现你的响应生成逻辑
        # 参考interaction.md中的台词风格
        return self.style_response(raw_response)
```

### 性能优化建议

- 预加载角色数据到内存
- 使用缓存机制存储常用响应
- 实现响应模板系统提高效率

## 🤝 贡献指南

我们欢迎社区贡献！以下是参与方式：

### 如何贡献

1. **报告问题**
   - 在Issues中报告bug或提出改进建议
   - 包含详细的复现步骤和期望结果

2. **提交代码**
   - Fork本项目
   - 创建功能分支 (`git checkout -b feature/AmazingFeature`)
   - 提交更改 (`git commit -m 'Add some AmazingFeature'`)
   - 推送到分支 (`git push origin feature/AmazingFeature`)
   - 开启Pull Request

### 贡献规范

- 遵循现有的代码风格和文档格式
- 确保所有更改都经过测试
- 更新相关文档和示例
- 添加有意义的提交信息

### 需要帮助的领域

- [ ] 补充更多官方语音台词
- [ ] 添加多语言支持
- [ ] 创建更多使用示例
- [ ] 优化性能测试

## 📊 质量报告

### 评估结果

| 指标 | 得分 | 说明 |
|------|------|------|
| 完整性 | 1.0/1.0 | 角色设定覆盖全面 |
| 证据比例 | 0.90/1.0 | 90%内容有可靠来源 |
| 冲突检测 | 0.85/1.0 | 设定一致性良好 |
| 测试通过率 | 0.80/1.0 | 角色扮演测试表现优秀 |
| **总体评分** | **0.90/1.0** | **优秀** |

### 测试场景表现

- ✅ 初次见面场景：0.95分
- ✅ 日常闲聊：0.92分  
- ✅ 核心话题触发：0.90分
- ✅ 情绪表达：0.85-0.88分
- ✅ 关系互动：0.90分

## 📄 许可证

本项目采用 [MIT 许可证](LICENSE)。

## 🙏 致谢

### 数据来源

- [萌娘百科 - 琪亚娜](https://zh.moegirl.org.cn/琪亚娜·卡斯兰娜)
- [BWiki - 崩坏3](https://wiki.biligame.com/bh3/)
- 游戏内剧情和语音台词
- 动画短片《薪炎永燃》
- 社区玩家整理资料

### 特别感谢

- 《崩坏3》开发团队创造了如此丰富的角色
- 社区玩家提供的宝贵资料和分析
- 所有为这个项目做出贡献的开发者

## 🔗 相关链接

- [官方游戏官网](https://honkaiimpact3.mihoyo.com/)
- [问题反馈](https://github.com/your-username/kiana-skill/issues)

---

⭐ 如果这个项目对你有帮助，请给我们一个Star！

💬 有任何问题或建议，欢迎在Issues中讨论！
