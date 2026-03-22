# Claude 使用经验记录

> 记录与 Claude AI 协作过程中学到的经验、教训和技巧

## 使用说明

- 此文件由 Claude 自动更新
- 记录每次交互中学到的知识和犯过的错误
- 帮助优化人机协作效率

---

## 经验记录

### 2026-03-22

#### 1. Skill 包安装位置
- **路径**: `C:\Users\尹兴\.claude\skills`
- **包含的 skills**:
  - algorithmic-art, api-design, brand-guidelines
  - canvas-design, doc-coauthoring, docx
  - frontend-design, image-to-pdf, internal-comms
  - mcp-builder, pdf, planning-with-files
  - pptx, prompt-generator, skill-creator
  - slack-gif-creator, superpowers, theme-factory
  - web-artifacts-builder, webapp-testing, xlsx

#### 2. 常见错误
- **Unknown skill**: 输入非有效的 skill 名称时会报此错误
  - 例如输入 "BTW" 会被当作 skill 名称，但它只是 "By the way" 的缩写

#### 3. GitHub CLI 安装
- Windows 安装: `winget install GitHub.cli`
- 安装后需要运行 `gh auth login` 登录
- 默认安装路径: `C:\Program Files\GitHub CLI\gh.exe`

---

*持续更新中...*
