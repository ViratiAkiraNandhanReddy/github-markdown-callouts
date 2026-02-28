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
> ```
> #!/bin/bash
> echo "Clearing local cache..."
> rm -rf node_modules/.cache
> npm run build:dll
> echo "Done! ⚡"
> ```
```

---

## 💬 3. Important Examples (`[!IMPORTANT]`)

### Basic Important
**Rendered:**
> [!IMPORTANT]
> Node.js version 18.0.0 or higher is strictly required to run this application.

**Code:**
```markdown
> [!IMPORTANT]
> Node.js version 18.0.0 or higher is strictly required to run this application.
```

### Very Complex: Important with Embedded Diagrams and JSON
*Demonstrating how to embed reference images and configuration structures inside a critical alert.*

**Rendered:**
> [!IMPORTANT]
> **OAuth2 Authentication Flow Changes**
> 
> The authentication architecture has been updated. All client applications must now intercept the token exchange as shown in the diagram below:
> 
> 
> 
> You must update your `config.json` to include the new `pkce` parameters:
> 
> ```json
> {
>   "auth": {
>     "clientId": "YOUR_CLIENT_ID",
>     "flow": "authorization_code",
>     "enablePkce": true
>   }
> }
> ```

**Code:**
```markdown
> [!IMPORTANT]
> **OAuth2 Authentication Flow Changes**
> 
> The authentication architecture has been updated. All client applications must now intercept the token exchange as shown in the diagram below:
> 
> 
> 
> You must update your `config.json` to include the new `pkce` parameters:
> 
> ```
> {
>   "auth": {
>     "clientId": "YOUR_CLIENT_ID",
>     "flow": "authorization_code",
>     "enablePkce": true
>   }
> }
> ```
```

---

## ⚠️ 4. Warning Examples (`[!WARNING]`)

### Basic Warning
**Rendered:**
> [!WARNING]
> The `getUserData()` method is deprecated and will be removed in version 3.0.

**Code:**
```markdown
> [!WARNING]
> The `getUserData()` method is deprecated and will be removed in version 3.0.
```

### Very Complex: Warning with Diff Blocks and Context
*Demonstrating how to use markdown diffs inside a warning to show users exactly what code they need to remove/add.*

**Rendered:**
> [!WARNING]
> **Breaking Change in v4 Router API**
> 
> The `<Switch>` component has been entirely removed from `react-router-dom` v6. If you attempt to use it, your application will crash on load. 
> 
> You **must** migrate to `<Routes>` immediately:
> 
> ```diff
>  import { BrowserRouter as Router, Route } from "react-router-dom";
> -import { Switch } from "react-router-dom";
> +import { Routes } from "react-router-dom";
> 
>  function App() {
>    return (
>      <Router>
> -      <Switch>
> +      <Routes>
>          <Route path="/" element={<Home />} />
> -      </Switch>
> +      </Routes>
>      </Router>
>    );
>  }
> ```

**Code:**
```markdown
> [!WARNING]
> **Breaking Change in v4 Router API**
> 
> The `<Switch>` component has been entirely removed from `react-router-dom` v6. If you attempt to use it, your application will crash on load. 
> 
> You **must** migrate to `<Routes>` immediately:
> 
> ```
>  import { BrowserRouter as Router, Route } from "react-router-dom";
> -import { Switch } from "react-router-dom";
> +import { Routes } from "react-router-dom";
> 
>  function App() {
>    return (
>      <Router>
> -      <Switch>
> +      <Routes>
>          <Route path="/" element={<Home />} />
> -      </Switch>
> +      </Routes>
>      </Router>
>    );
>  }
> ```
```

---

## 🛑 5. Caution Examples (`[!CAUTION]`)

### Basic Caution
**Rendered:**
> [!CAUTION]
> Never commit your `.env` file. This will expose your credentials to the public.

**Code:**
```markdown
> [!CAUTION]
> Never commit your `.env` file. This will expose your credentials to the public.
```

### Very Complex: Caution with Destructive Commands, Nested Lists, and Bold Emphasis
*Demonstrating how to properly warn users about catastrophic system actions using structured hierarchy.*

**Rendered:**
> [!CAUTION]
> **IRREVERSIBLE DATA DESTRUCTION**
> 
> Executing the script below will completely format the mounted volume and destroy all production records. There is **no undo** for this action.
> 
> If you proceed, the following will occur:
> 1. All active sessions will be abruptly terminated.
> 2. The `pg_data` directory will be unmounted and wiped.
> 3. S3 bucket backups older than 30 days will be purged.
> 
> ```sql
> -- ONLY RUN THIS IF YOU INTEND TO WIPE THE CLUSTER
> DROP DATABASE production_db WITH (FORCE);
> DROP ROLE admin_service_account;
> ```
> 
> *Ensure you have written authorization from the CTO before executing these commands.*

**Code:**
```markdown
> [!CAUTION]
> **IRREVERSIBLE DATA DESTRUCTION**
> 
> Executing the script below will completely format the mounted volume and destroy all production records. There is **no undo** for this action.
> 
> If you proceed, the following will occur:
> 1. All active sessions will be abruptly terminated.
> 2. The `pg_data` directory will be unmounted and wiped.
> 3. S3 bucket backups older than 30 days will be purged.
> 
> ```
> -- ONLY RUN THIS IF YOU INTEND TO WIPE THE CLUSTER
> DROP DATABASE production_db WITH (FORCE);
> DROP ROLE admin_service_account;
> ```
> 
> *Ensure you have written authorization from the CTO before executing these commands.*
```
