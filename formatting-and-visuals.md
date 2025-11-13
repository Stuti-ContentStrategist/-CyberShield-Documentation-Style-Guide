# 🎨 Formatting & Visuals

## 🧱 Overview

The **Formatting & Visuals** section ensures that CyberShield documentation maintains a consistent, polished, and readable design across all pages.

It defines how to structure headings, emphasize text, use callouts, include visuals, and display code examples.

> 💡 **Tip:** A clear, visually balanced layout helps users locate information faster and improves comprehension.

***

#### 🧩 Headings

Use headings to organize content logically. Each page should begin with a top-level (`#`) heading followed by meaningful subheadings.

| Level | Markdown | Example                         | Usage                     |
| ----- | -------- | ------------------------------- | ------------------------- |
| H1    | `#`      | `# Installing CyberShield`      | Page title (one per page) |
| H2    | `##`     | `## Before You Begin`           | Major sections            |
| H3    | `###`    | `### Step 1: Run the Installer` | Subsections               |
| H4    | `####`   | `#### Example Output`           | Optional — use sparingly  |

> ⚙️ **Note:** Use sentence case for all headings (capitalize only the first word and proper nouns).

***

#### 🔤 Text Formatting

| Element           | Usage                                   | Example                               |
| ----------------- | --------------------------------------- | ------------------------------------- |
| **Bold**          | UI elements, buttons, and emphasis      | “Click **Save Changes**.”             |
| _Italic_          | Terms, filenames, or references         | “Refer to _config.yaml_.”             |
| `Inline code`     | Commands, parameters, or code variables | “Use the `--verbose` flag.”           |
| ~~Strikethrough~~ | Only for deprecated features (rare)     | “~~Legacy FTP export~~ (deprecated).” |

> 💡 **Tip:** Avoid overusing bold or italics — readability is more important than style.

***

#### 🧱 Lists & Structure

Use **numbered lists** for sequential instructions and **bulleted lists** for unordered items.

**Example**

**Numbered List:**

1. Open the **Dashboard**.
2. Click **Policies**.
3. Select **Add Policy**.

**Bulleted List:**

* The Dashboard displays:
  * Alerts
  * Scans
  * Reports

> 🧠 **Info:** Limit list items to 1–2 sentences. Long explanations should become subsections.

***

#### 💬 Callouts

Callouts are a key visual element in CyberShield documentation. Use them to highlight key ideas, warnings, or best practices.

| Type           | Icon | Usage                                  |
| -------------- | ---- | -------------------------------------- |
| 💡 **Tip**     | 💡   | Helpful hints or shortcuts             |
| ⚠️ **Note**    | ⚠️   | Cautionary statements or limitations   |
| 🧠 **Info**    | 🧠   | Background context or explanations     |
| 🧾 **Example** | 🧾   | Real-world use case or sample          |
| 🚫 **Warning** | 🚫   | Security risks or irreversible actions |

**Example**

> 💡 **Tip:** Schedule scans during off-peak hours to reduce system load.\
> ⚠️ **Note:** Once deleted, reports cannot be recovered.

***

#### 🧰 Tables

Use tables for structured data — comparisons, settings, or parameters. Keep 2–4 columns for readability.

| Parameter   | Description                   | Example               |
| ----------- | ----------------------------- | --------------------- |
| `scan_type` | Defines the scan category.    | `network`, `endpoint` |
| `target`    | Specifies the target address. | `192.168.1.0/24`      |
| `profile`   | Defines the scan intensity.   | `quick`, `full`       |

> 💡 **Tip:** Avoid nested tables; they make pages harder to read on mobile.

***

#### 🖼️ Visual Elements

**Screenshots**

* Capture full, clear UI screenshots with consistent resolution.
* Highlight relevant areas using **subtle boxes or arrows** (no clutter).
* Include concise captions below each image.

**Example:**

```
![Dashboard Overview showing Threat Analytics tab](../assets/dashboard-threats.png)
*Figure 1: The Dashboard displays real-time analytics and scan summaries.*
```

**Icons & Emojis**

* Use emojis sparingly — only in headings or callouts.
* Use consistent icons for each content type (e.g., 💡 for tips, ⚙️ for processes).
* Avoid decorative or unrelated emojis.

***

#### 💻 Code Blocks

Use fenced code blocks for commands, configuration files, and JSON examples.

**Example**

```bash
# Start a security scan
POST /api/v1/scan/start
Authorization: Bearer <access_token>
```

```json
{
  "scan_type": "network",
  "target": "192.168.1.0/24",
  "status": "initiated"
}
```

> ⚙️ **Note:** Always specify language type (`bash`, `json`, `yaml`) for syntax highlighting.

***

#### 🔗 Links

| Type               | Usage                                   | Example                                                          |
| ------------------ | --------------------------------------- | ---------------------------------------------------------------- |
| **Internal Links** | Link to another CyberShield page.       | `[Installation Guide](../getting-started/installation-guide.md)` |
| **External Links** | Include descriptive text, not raw URLs. | `[Learn more about GitBook](https://www.gitbook.com)`            |
| **Email Links**    | Use plain, lowercase format.            | `support@cybershield.com`                                        |

> 💡 **Tip:** Avoid “click here.” Use meaningful link text like “Read the Installation Guide.”

Applying these formatting and visual standards helps create documentation that is easy to scan, visually structured, and enjoyable to read.
