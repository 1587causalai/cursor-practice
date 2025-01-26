# CursorRules 文件使用指南

`.cursorrules` 文件是一个用于优化 Cursor AI 编码体验的重要工具。通过在项目的根目录中创建此文件，开发者可以为 AI 提供具体的编码指导和项目要求，从而提高代码生成的准确性和一致性。

## 基础配置

### 创建文件

1. **文件位置**：在你的项目根目录下创建一个名为 `.cursorrules` 的文件。
   
2. **文件内容**：在文件中添加你的自定义规则和指令。以下是一个基本模板：

```plaintext
你是一位精通 TypeScript、Node.js、Next.js、React 的开发者。

代码风格和结构：
- 编写简洁且技术性的 TypeScript 代码，提供准确的示例。
- 使用函数式和声明式编程模式，避免使用类。
- 优先考虑迭代和模块化，避免代码重复。

命名约定：
- 目录使用小写字母和短横线（例如：components/auth-wizard）。
- 优先使用命名导出。

TypeScript 使用：
- 所有代码均使用 TypeScript；优先使用接口而非类型。
```

## 最佳实践

### 编写规则的建议

- **明确具体**：确保规则清晰且具体，例如"使用两个空格进行缩进"比"使用适当缩进"更有效。
- **自然语言书写**：尽量用简单的自然语言描述规则，以便 AI 更好地理解。
- **优先列出重要规则**：将最重要的规则放在前面，这样它们对 AI 行为的影响最大。
- **逐步迭代与完善**：随着使用过程中的反馈，不断更新和调整规则，以提高 AI 的帮助效果。

### 规则示例

以下是一些常见的 `.cursorrules` 文件示例，适用于不同的技术栈：

#### Java Spring Boot 示例

```plaintext
你是一位经验丰富的 Java 开发者，遵循 SOLID 原则和 DRY 原则。

技术栈：
- 框架：Java Spring Boot 3，Maven，Java 17
- 依赖：Spring Web, Spring Data JPA, Thymeleaf, Lombok, PostgreSQL 驱动
```

#### SwiftUI 示例

```plaintext
你是一位熟悉 SwiftUI 的开发者，始终使用 async/await 来处理异步操作。

代码风格：
- 避免回调地狱，优先使用现代 Swift API。
```

## 总结

利用 `.cursorrules` 文件，你可以显著提升 Cursor AI 在编码过程中的表现，使其更好地适应你的项目需求和编码风格。无论是简单的脚本还是复杂的应用程序，合理配置 `.cursorrules` 文件都能为你的开发体验带来积极变化。
