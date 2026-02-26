# GitHub Markdown Callouts

> [!TIP]
> This repository is your ultimate reference for GitHub Markdown Callouts. It includes examples, best practices, anti-patterns, and practical tips for making your README, Issues, Pull Requests, and Docs look professional.

---

## Table of Contents

1. [Introduction](#introduction)  
2. [What Are GitHub Markdown Callouts?](#what-are-github-markdown-callouts)  
3. [Supported Callout Types](#supported-callout-types)  
4. [Syntax & Rules](#syntax--rules)  
5. [Examples](#examples)  
    - [Note](#note)  
    - [Tip](#tip)  
    - [Important](#important)  
    - [Warning](#warning)  
    - [Caution](#caution)  
6. [Best Practices](#best-practices)  
7. [Anti-Patterns / Common Mistakes](#anti-patterns--common-mistakes)  
8. [Callouts in GitHub Context](#callouts-in-github-context)  
9. [SEO & Readability Benefits](#seo--readability-benefits)  
10. [Repo Usage Example](#repo-usage-example)  
11. [Conclusion](#conclusion)  

---

## Introduction

GitHub Markdown Callouts are **visual blocks** that highlight important information in documentation. They help make READMEs, issues, PRs, and wikis **more readable, scannable, and professional**.  

This guide covers **all aspects**: from syntax to examples, best practices, anti-patterns, and practical recommendations.

---

## What Are GitHub Markdown Callouts?

Callouts are **special blockquotes with a keyword** like `NOTE`, `TIP`, or `WARNING` at the start. GitHub renders them in a visually distinct style, improving the readability of your documentation.

```
> [!NOTE]
> This is a simple callout block.
```

Key points:  
- Must start with `>` for blockquote  
- Keyword must be **uppercase**  
- Keyword must appear on the **first line**  

---

## Supported Callout Types

| Callout Type | Syntax Keyword | Typical Use Case |
|--------------|----------------|----------------|
| Note         | `[!NOTE]`      | Additional info, clarifications |
| Tip          | `[!TIP]`       | Recommendations, shortcuts |
| Important    | `[!IMPORTANT]` | Critical information for workflow |
| Warning      | `[!WARNING]`   | Potentially harmful actions |
| Caution      | `[!CAUTION]`   | Experimental or risky features |

> [!TIP]
> You can combine callouts with headings for longer sections for better structure.

---

## Syntax & Rules

1. Start **every callout** with `>`  
2. Keyword **must be first line**  
3. Keyword **must be uppercase**  
4. Only **one callout type per blockquote**  
5. No empty lines between the keyword and content

✅ Correct:
```
> [!TIP]
> Always commit with meaningful messages.
```

❌ Incorrect:
```
> Always commit with meaningful messages.
> [!TIP]
```

---

## Examples

### Note

> [!NOTE]
> This is a note callout. Use it for additional information or clarifications.

### Tip

> [!TIP]
> Run tests before pushing changes to avoid CI failures.

### Important

> [!IMPORTANT]
> Ensure you have Python 3.10+ installed before running the script.

### Warning

> [!WARNING]
> Deleting the main branch is irreversible. Proceed with caution.

### Caution

> [!CAUTION]
> This feature is experimental and may break in future releases.

---
