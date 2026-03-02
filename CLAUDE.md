# CLAUDE.md — Repository Guide for AI Assistants

## Repository Overview

**expert-train** is a research and documentation knowledge base supporting the strategic development of an e-commerce AI tools product. It contains no application code — all content consists of PDF reports and spreadsheet data, written in Chinese.

The repository appears to serve as training and reference material for building an AI assistant or expert system targeting the e-commerce sector (the name "expert-train" reflects this purpose).

---

## Repository Structure

```
expert-train/
├── 产品功能清单.pdf                           # Product feature list
├── 电商 AI 工具行业趋势分析摘要.pdf             # Industry trend analysis
├── 目标市场定位与竞品分析报告.pdf               # Market & competitive analysis
├── 电商平台发展痛点及可实现核心落地场景.pdf       # Pain points & use cases
├── 阿里AI技术栈与电商规则调研笔记.pdf            # Alibaba AI tech stack research
└── 二十类别商品数据.xlsx                       # Product category reference data
```

> Note: `产品需求文档.pdf` (Product Requirements Document) was removed in the most recent commit (2026-02-28).

---

## Document Inventory

| File | Type | Purpose |
|------|------|---------|
| 产品功能清单.pdf | PDF | Detailed feature list for the planned AI product |
| 电商 AI 工具行业趋势分析摘要.pdf | PDF | Summary of industry trends for AI tools in e-commerce |
| 目标市场定位与竞品分析报告.pdf | PDF | Target market segmentation and competitive landscape analysis |
| 电商平台发展痛点及可实现核心落地场景.pdf | PDF | E-commerce pain points and concrete AI implementation scenarios |
| 阿里AI技术栈与电商规则调研笔记.pdf | PDF | Research notes on Alibaba's AI stack, APIs, and platform rules |
| 二十类别商品数据.xlsx | XLSX | Reference product data spanning 20 merchandise categories |

---

## Project Context

This knowledge base covers an e-commerce AI tooling initiative focused on:

1. **Market intelligence** — Competitive analysis and market positioning for an AI tool targeting Chinese e-commerce platforms (Alibaba/Taobao/Tmall ecosystem and adjacent platforms).
2. **Product definition** — Feature requirements and prioritized capability lists for the AI product.
3. **Technical grounding** — Research into Alibaba's AI infrastructure, e-commerce platform APIs, and business rules.
4. **Business case** — Identification of merchant/operator pain points and which scenarios are most viable for AI-driven automation or assistance.
5. **Data assets** — Structured product category data usable for training, demos, or domain grounding.

---

## Working with This Repository

### Reading documents
Since all files are PDFs and XLSX, use Claude's file reading capability or standard document viewers. Documents are in **Simplified Chinese**.

### Adding new documents
- Follow the existing Chinese-language naming convention for filenames
- Place all files at the repository root (no subdirectory structure currently exists)
- Commit with a clear message describing the document, e.g.:
  ```
  Add 用户调研访谈记录.pdf — user interview notes from March 2026
  ```

### Updating existing documents
- Replace the file and commit with a message explaining what changed
- Do not rename existing files unless the scope/topic has fundamentally changed, as filenames serve as the primary index

### No build, test, or CI processes
There are no scripts, package managers, linters, or CI/CD pipelines. No commands need to be run for any workflow.

---

## Conventions for AI Assistants

- **Language**: All document content is in Chinese. When summarizing or referencing documents, preserve key Chinese terms alongside any English translation to avoid ambiguity.
- **No code changes**: There is no source code to modify. Tasks will involve reading, summarizing, extracting insights, or organizing document content.
- **Document authority**: The PDFs are the primary source of truth for product and market decisions. Do not contradict or override them without flagging the discrepancy.
- **Spreadsheet data** (`二十类别商品数据.xlsx`): Treat as reference data for product category scope. Use when grounding responses about which merchandise categories are in scope.
- **Deleted document**: The product requirements document (`产品需求文档.pdf`) was deleted on 2026-02-28. If tasks reference PRD content, note that the document is no longer tracked and check whether the content has been incorporated into the remaining `产品功能清单.pdf`.

---

## Git Metadata

| Property | Value |
|----------|-------|
| Repository | liuzhitao790-beep/expert-train |
| Default branch | master |
| First commit | 2026-02-13 |
| Last commit | 2026-02-28 |
| Total commits | 8 |
