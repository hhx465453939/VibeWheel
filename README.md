# VibeWheel Pro

面向专业开发者的全栈系统架构师 & AI 指令工程工具集。将自然语言需求转化为**生产级（Production-Ready）**技术规范和 AI 编码指令。

## 核心能力

- **全栈架构设计**：DDD、Clean Architecture、Microservices、Serverless
- **多技术栈支持**：根据任务特性选择最优解（Rust, Go, Python, TypeScript, C++ 等）
- **工程化标准**：类型安全、单元测试、错误处理、性能优化
- **AI 指令工程**：生成高密度 Technical Context，最大化 AI 编程工具推理能力

## 工作流程

### 1. 需求分析与架构设计

1. **下载提示词模板**：
   - [全栈系统架构师 & AI 指令工程师 (Pro Edition)](专业版：全栈系统架构师%20&%20AI%20指令工程师%20(Pro%20Edition).md) - 核心架构师角色
   - [重型技术栈-产品解决方案大师](重型技术栈-产品解决方案大师.md) - 复杂应用场景

2. **使用 AI 生成技术规格**：
   - 在 Claude Code、或者Cherry Studio 中使用提示词模板
   - 描述需求，AI 会生成包含 ADR、系统设计、数据模型的详细技术文档

### 2. 本地开发环境

1. **初始化项目**：
   ```bash
   # 根据技术栈选择对应命令
   npm init -y          # Node.js/TypeScript
   cargo new project    # Rust
   go mod init          # Go
   python -m venv venv # Python
   ```

2. **使用专业 IDE**：
   - **Cursor**：推荐，AI 辅助编程体验最佳
   - **Windsurf**：强大的 AI 代码生成能力
   - **VS Code + GitHub Copilot**：经典组合

3. **导入技术规格**：
   - 将生成的技术文档作为 Context 导入 IDE
   - AI 会根据架构设计自动生成符合规范的代码

### 3. 工程化实践

- **类型安全**：严格类型检查，避免运行时错误
- **单元测试**：使用 Pytest、Jest、Go Test 等
- **错误处理**：Result<T, E> 模式，禁止静默失败
- **代码审查**：生成清晰的逻辑链条，便于人工审计

## 提示词模板

- **全栈架构师**：[专业版：全栈系统架构师 & AI 指令工程师 (Pro Edition).md](专业版：全栈系统架构师%20&%20AI%20指令工程师%20(Pro%20Edition).md)
  - 支持多技术栈选型
  - 生成 ADR（架构决策记录）
  - 详细系统设计和实现约束

- **重型技术栈**：[重型技术栈-产品解决方案大师.md](重型技术栈-产品解决方案大师.md)
  - 复杂应用场景
  - Python/Streamlit、FastAPI 等后端技术
  - 微服务架构支持

## 架构设计原则

- **最优选型**：根据性能、并发、安全需求选择技术栈
- **设计模式**：Repository Pattern、CQRS、MVC 等
- **非功能性需求**：性能、并发、安全、可维护性
- **审计友好**：输出清晰的逻辑链条，便于专家审查

## 实践案例

查看 [完整实践流程](完整实践流程/) 目录了解从需求到生产的完整示例。

## Cursor 规则配置

本项目包含预配置的 Cursor 规则，自动应用架构设计最佳实践：

- **vibe-coding-architect.mdc**：核心架构原则（自动应用）
- **js-first-stack.mdc**：JavaScript/TypeScript 技术栈规范
- **architecture-patterns.mdc**：架构设计模式与最佳实践

规则文件位于 `.cursor/rules/` 目录，Cursor 会自动加载并应用这些规则。

## 推荐工具

- **AI 编程 IDE**：Cursor、Windsurf、Claude Code
- **Web AI**：Claude 3.5 Sonnet、GPT-4o、DeepSeek
- **版本控制**：Git + GitHub/GitLab
- **CI/CD**：GitHub Actions、GitLab CI

## 许可证

详见 [LICENSE](LICENSE) 文件。

