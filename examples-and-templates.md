# 💡 Examples & Templates

## 🧱 Overview

This section provides ready-to-use writing templates and content patterns for CyberShield documentation.

Writers and editors can use these examples to maintain a consistent tone, structure, and formatting style across all product areas — including user guides, SDK docs, API references, and knowledge base articles.

> 💡 **Tip:** Use these as blueprints — modify the examples only when a section’s context truly demands it.

***

### 🧩 1. Feature Description Template

Use this format when introducing a new feature, function, or tool in CyberShield documentation.

**Template**

```markdown
### 🧠 [Feature Name]

**Purpose:**  
[One-line purpose statement — what this feature enables the user to do.]

**Description:**  
[Brief explanation of how it works and when to use it. Keep it under 4 lines.]

**Example Use Case:**  
[Provide a practical example showing how the feature fits into a workflow.]
```

**Example**

```markdown
### 🧠 Threat Analytics Dashboard

**Purpose:**  
Displays real-time threat data from all connected agents.

**Description:**  
The Dashboard consolidates alerts, logs, and scan summaries in one view.  
Users can sort alerts by severity, export data, or view detailed reports.

**Example Use Case:**  
An IT administrator reviews high-severity alerts daily to ensure endpoint compliance.
```

***

### 🚀 2. How-To / Procedure Template

Use for installation, configuration, or task-based instructions.

**Template**

```markdown
## [Task Name]

### Before You Begin
[List prerequisites, tools, or permissions.]

### Steps
1. [Action 1 — Start with a verb.]
2. [Action 2 — Keep concise and direct.]
3. [Action 3 — Include visuals or screenshots if relevant.]

### Result
[Describe what the user should see or confirm after completing the steps.]

> 💡 **Tip:** Add links to related topics at the end of the procedure.
```

**Example**

```markdown
## Configure Multi-Factor Authentication (MFA)

### Before You Begin
- Administrative access required.
- MFA must be enabled in the security policy.

### Steps
1. Open the **Dashboard** → **Settings** → **Authentication**.  
2. Select **Enable MFA**.  
3. Choose **Token-based Authentication** and click **Save**.

### Result
CyberShield prompts users for a second verification step during login.

> 💡 **Tip:** To disable MFA temporarily, use the API endpoint `/api/v1/auth/settings`.
```

***

### 🧰 3. API Endpoint Template

Use this structure for API endpoint pages.

**Template**

````markdown
### [Endpoint Name]

| Method | Endpoint |
|--------|-----------|
| [GET/POST/PUT/DELETE] | `/api/v1/...` |

**Description:**  
[One-line summary of what this endpoint does.]

**Request Example:**
```bash
[Code block]
````

**Response Example:**

```json
[Code block]
```

> ⚙️ **Note:** Include parameter tables below the example if applicable.

````

---

## 📋 4. Callout Template  

Keep callouts consistent across the documentation.  

| Type | Markdown Example | Use Case |
|------|------------------|-----------|
| 💡 **Tip** | `> 💡 **Tip:** Schedule scans during off-peak hours.` | Helpful hints |
| ⚠️ **Note** | `> ⚠️ **Note:** Reports are auto-deleted after 30 days.` | Cautionary reminders |
| 🧠 **Info** | `> 🧠 **Info:** The Dashboard aggregates logs every 15 minutes.` | Background details |
| 🚫 **Warning** | `> 🚫 **Warning:** Do not delete active scan reports.` | Security or data risks |

---

## 🖼️ 5. Screenshot Template  

```markdown
![Alt text: Dashboard showing threat summary](../assets/dashboard-summary.png)
*Figure 1: The CyberShield Dashboard displays key security insights.*
````

> ⚙️ **Note:**
>
> * Use meaningful alt text (describe what’s visible).
> * Keep captions concise (max one line).
> * Highlight relevant UI elements using simple shapes or arrows before uploading.

***

### 🧾 6. Table Template

```markdown
| Parameter | Description | Example | Required |
|------------|--------------|----------|-----------|
| `scan_type` | Type of scan. | `network` | ✅ |
| `target` | IP address range. | `192.168.0.0/24` | ✅ |
| `schedule` | Defines scan frequency. | `daily` | ❌ |
```

> 💡 **Tip:** Keep tables short (max 6 rows) and use separate pages or tabs for large data lists.

***

### 🧠 7. Error Example Template

Use to document expected errors or troubleshooting cases.

```json
{
  "status": 401,
  "error": "Unauthorized",
  "message": "Access token expired or invalid."
}
```

> ⚙️ **Note:** Always provide one success and one error example for each API endpoint.

***

### 🧭 8. Page Footer Template

Use a short footer on long technical pages for consistency.

```markdown
---

📘 **Related Topics:**  
- [Developer Reference → Authentication](../developer-reference/authentication.md)  
- [API Reference → Error Codes](../api-reference/error-codes.md)  
- [Knowledge Base → FAQs](../knowledge-base/faqs.md)
```

> 💡 **Tip:** Use related links to improve discoverability and navigation flow.

***

#### ✅ Final Reminder

When creating new documentation pages:

* Start with a clear **objective statement** (“This page explains how to…”).
* Use **consistent heading structure** (H1 → H2 → H3).
* Apply **callouts and visuals** for engagement.
* Link **related resources** at the end of each page.

> 🧠 **Info:** Templates reduce rework — they help multiple contributors produce consistent, high-quality docs with minimal editing effort.

#### 🧭 **End of Guide!**

🎉 Great work — you’ve completed the **CyberShield Documentation Style Guide**!

You now know how to:

* Apply CyberShield’s writing conventions with clarity and consistency
* Use approved formatting patterns, visual rules, and component styles
* Follow technical standards for terminology, versioning, and structure
* Reuse ready-made templates to create feature descriptions, release notes, and other content efficiently

📚 To continue learning, head over to the **CyberShield Contributor Guide** for contribution workflows, review practices, and collaboration standards.
