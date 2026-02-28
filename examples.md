# GitHub Markdown Callouts: The Ultimate Example Library

This document serves as a copy-paste reference guide for GitHub Markdown Callouts (Alerts). Each section demonstrates the rendered output alongside the raw Markdown code required to produce it.

---

## 📘 1. Note Examples (`[!NOTE]`)

### Basic Note
**Rendered:**
> [!NOTE]
> The default branch for this repository was recently changed from `master` to `main`.

**Code:**
```markdown
> [!NOTE]
> The default branch for this repository was recently changed from `master` to `main`.
```

### Very Complex: Note with Math, Tables, and Formatting
*Demonstrating how to include structural data and LaTeX math equations inside a note.*

**Rendered:**
> [!NOTE]
> **Performance Benchmarks for v2.4**
> 
> When calculating the time complexity of the new sorting algorithm, we use the following formula for the upper bound:
> 
> $$O(n \log n)$$
> 
> Here is how the new engine compares to the legacy system across different payload sizes:
> 
> | Payload Size | Legacy Engine | New Engine (v2.4) | Delta       |
> | :----------- | :------------ | :---------------- | :---------- |
> | 10 MB        | 450ms         | 120ms             | 🚀 **-73%** |
> | 50 MB        | 2100ms        | 580ms             | 🚀 **-72%** |
> | 100 MB       | 4500ms        | 1100ms            | 🚀 **-75%** |
> 
> For a deeper dive into the math, see our [Algorithmic Breakdown](#).

**Code:**
```markdown
> [!NOTE]
> **Performance Benchmarks for v2.4**
> 
> When calculating the time complexity of the new sorting algorithm, we use the following formula for the upper bound:
> 
> $$O(n \log n)$$
> 
> Here is how the new engine compares to the legacy system across different payload sizes:
> 
> | Payload Size    | Legacy Engine | New Engine (v2.4) | Delta       |
> | :-------------- | :------------ | :-----------------| :---------- |
> | 10 MB           | 450ms         | 120ms             | 🚀 **-73%** |
> | 50 MB           | 2100ms        | 580ms             | 🚀 **-72%** |
> | 100 MB          | 4500ms        | 1100ms            | 🚀 **-75%** |
> 
> For a deeper dive into the math, see our [Algorithmic Breakdown](#).
```

---

## 💡 2. Tip Examples (`[!TIP]`)

### Basic Tip
**Rendered:**
> [!TIP]
> Press `Cmd + K` (Mac) or `Ctrl + K` (Windows) to open the command palette.

**Code:**
```markdown
> [!TIP]
> Press `Cmd + K` (Mac) or `Ctrl + K` (Windows) to open the command palette.
```

### Very Complex: Tip with Interactive Task Lists and Code Blocks
*Demonstrating how to embed actionable checklists and multi-line scripts.*

**Rendered:**
> [!TIP]
> **Optimizing your Local Environment**
> 
> To get the best performance out of the development server, complete the following checklist:
> - [x] Install the latest Docker Desktop
> - [ ] Enable VirtioFS in Docker settings
> - [ ] Run the optimization script below:
> 
> ```bash
> #!/bin/bash
> echo "Clearing local cache..."
> rm -rf node_modules/.cache
> npm run build:dll
> echo "Done! ⚡"
> ```

**Code:**
```markdown
> [!TIP]
> **Optimizing your Local Environment**
> 
> To get the best performance out of the development server, complete the following checklist:
> - [x] Install the latest Docker Desktop
> - [ ] Enable VirtioFS in Docker settings
> - [ ] Run the optimization script below:
> 
> ```bash
> #!/bin/bash
> echo "Clearing local cache..."
> rm -rf node_modules/.cache
> npm run build:dll
> echo "Done! ⚡"
> ```
```

---
