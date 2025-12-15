# CFP 考试学习代码库

🎉 **我在 2025 年 11 月 10 日通过了 CFP 考试！** 🎉

这是我的个人学习代码库，帮助我在第二次尝试时通过了注册理财规划师 (CFP) 考试。在 2024 年 11 月失败后，我使用 AI 驱动的引导式学习与 Claude Code 重建了我的学习方法 - 这改变了一切。

**感谢 AI 和 Claude Code**，我从失败的尝试到**82% 的掌握率**（73 个主题中的 60 个），通过 23 次专注的学习会话，最终通过了考试。

**让我们在 LinkedIn 上联系**：[linkedin.com/in/chenran818](https://linkedin.com/in/chenran818)

---

**最终考试统计**：
- **考试日期**：2025 年 11 月 10 日 ✅ 通过
- **最终进度**：82%（掌握 73 个 CFP 主题中的 60 个）
- **学习会话**：23 次会话（2025 年 10 月 11 日 - 11 月 7 日）
- **学习材料**：1,088 页（2024 Dalton Review 幻灯片）

## 工作原理

此代码库使用 Claude Code 作为交互式 CFP 考试导师，它：
- 使用苏格拉底式方法进行教学（首先询问你知道什么）
- 提供简洁（约 200 字）的解释
- 通过后续问题验证你的理解
- 根据你的回答调整教学风格
- **跟踪每次学习会话以个性化你的学习体验**

## 代码库结构

```
/sessions/                    # 记录了 23 次每日学习会话
  /2025-10-11/               # 每个学习日一个文件夹
  /2025-10-17/               # 从 10 月 11 日到 11 月 7 日的会话
  /2025-11-07/
  SESSION-TEMPLATE.md        # 记录会话的模板

/progress/                    # 考试准备的单一真实来源
  cfp-study-tracker.md       # 综合跟踪器，包含：
                             # - 所有 73 个 CFP 主题的映射
                             # - 掌握的主题（60/73）
                             # - 识别的知识缺口
                             # - 剩余天数的学习计划

/2024 Slides/                 # 完整的 2024 Dalton Review 材料
  2024 TDR Estate slides.pdf
  2024 TDR Fundamentals slides.pdf
  2024 TDR Insurance slides.pdf
  2024 TDR Investments slides.pdf
  2024 TDR Retirement slides.pdf
  2024 TDR Tax slides.pdf

CLAUDE.md                     # AI 导师说明（苏格拉底式方法）
README.md                     # 本文件
```

## 使用方法

### 每日学习会话

1. 在此代码库中打开 Claude Code
2. 自然地询问 CFP 主题问题 - 就像与导师交谈一样
3. 回答 Claude 提出的理解检查问题
4. 每次会话后，Claude 会自动记录：
   - 你学到了什么
   - 你遇到困难的地方
   - 你掌握的内容
   - 下一步要复习什么

### 复习会话

当你想复习时，只需询问 Claude：
- "让我们复习我遇到困难的主题"
- "我今天应该关注什么？"
- "测试我的薄弱领域"
- "显示我的进度"

Claude 会阅读你的会话历史，并根据你过去的表现创建个性化复习。

### 跟踪你的进度

在 `/progress/cfp-study-tracker.md` 查看你的综合学习跟踪器，了解：
- 整体考试准备情况（目前 82%）
- 哪些领域已完成（4 个主要领域 ✅）
- 剩余的知识缺口
- 考试日的优先学习计划

## 学习理念

**引导式学习方法：**
- 对话式且不带评判
- 在你现有知识基础上构建
- 在继续之前检查理解
- 适应你的学习风格
- 专注于深入理解，而不仅仅是记忆

## 学习材料

**2024 Dalton Review 幻灯片**（总共 1,088 页）：
- 遗产规划（200 页）
- 基础知识（90 页）
- 保险（188 页）
- 投资（188 页）
- 退休（182 页）
- 税务（150 页）

所有材料都已彻底映射到 73 个 CFP 考试主题。

## 免费学习资源

除了 Dalton Review 材料外，以下是一些优秀的**免费资源**，可以补充你的 CFP 考试准备：

**播客和音频：**
- [Open Exam Prep Podcast](https://open.spotify.com/show/55EmWfdtPaK641q4Rk3mI1) - Spotify 上的免费 CFP 考试准备播客
- [Financial Planning Essentials Playlist](https://open.spotify.com/playlist/6GUIZvnpaiOiYmXkanqwZ8) - Spotify 上的学习音乐播放列表

**视频内容：**
- [Open Exam Prep YouTube](https://www.youtube.com/@Open-exam-prep) - 涵盖 CFP 考试主题的免费视频内容

**网站：**
- [open-exam-prep.com](https://open-exam-prep.com/) - 额外的免费资源和学习材料

这些免费资源非常适合在通勤、锻炼或休息时间进行被动学习。

## 主要功能

**个性化学习**：
- 23 次记录的学习会话，附详细笔记
- 苏格拉底式教学方法（在你已知基础上构建）
- 根据你的回答进行适应性解释
- 针对你薄弱领域的练习题

**综合跟踪**：
- 每次会话自动记录
- 识别和跟踪知识缺口
- 掌握的主题及置信度
- 根据考试权重衡量进度

**基于证据的方法**：
- 所有答案均通过权威来源验证（IRS.gov、CFP 委员会）
- 技术问题不猜测
- 为复杂规则提供引用
- 专注于理解"为什么"而不仅仅是"什么"

## 如何将此代码库用于你自己的 CFP 考试准备

想使用这个 AI 驱动的学习系统进行你自己的 CFP 考试准备吗？很简单：

1. **克隆此代码库**：
   ```bash
   git clone https://github.com/chenran818/CFP-Study.git
   cd CFP-Study
   ```

2. **清除我的学习历史**（重新开始）：
   ```bash
   rm -rf progress/ sessions/
   ```

3. **运行 Claude Code**：
   ```bash
   claude-code
   ```

4. **就这样！** 开始询问 CFP 问题，Claude 将：
   - 使用苏格拉底式方法教你
   - 自动创建新的 `progress/` 和 `sessions/` 文件夹
   - 像为我一样跟踪你的学习历程
   - 适应你的学习风格

`CLAUDE.md` 文件包含 Claude 应该如何辅导你的所有说明。`2024 Slides/` 文件夹包含所有已映射到 CFP 主题的学习材料。**它神奇地工作！**

## 开始使用

只需与 Claude Code 开始对话并询问你的第一个 CFP 问题。Claude 将从那里引导你，同时自动跟踪你的进度。

---

## 关于作者

在 2024 年 11 月 CFP 考试失败后，我知道我需要不同的方法。传统的学习方法对我无效。使用 Claude Code 作为我的 AI 学习伙伴改变了我的准备 - 苏格拉底式教学方法、个性化反馈和系统化的进度跟踪使复杂的财务规划概念终于理解了。

如果你正在准备 CFP 考试或任何专业认证，我希望这个代码库能激励你在学习之旅中利用 AI 工具。

**与我联系**：[linkedin.com/in/chenran818](https://linkedin.com/in/chenran818)

