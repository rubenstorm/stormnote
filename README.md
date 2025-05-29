# ⚡ StormNote

**StormNote** is a modern, colorful, and responsive [Hugo](https://gohugo.io/) shortcode that makes it easy to add beautifully styled notification boxes to your static website. From alerts and warnings to friendly tips and success messages — StormNote keeps your content clear, clean, and engaging.

Created with ❤️ by [Ruben Storm](https://github.com/rubenstorm)

---

![StormNote Banner](/rubenstorm/stormnote/refs/heads/main/static/images/stormnote-banner.png) <!-- Replace with your actual image path -->

---

## 🎯 Features

- 🎨 Flat & colorful alert box styles
- 🌓 Dark mode support out of the box
- ✍️ Fully markdown-compatible
- ⚡ Easy to customize title and type
- 🧩 Plug-and-play shortcode file — no extra CSS needed

---

## 🚀 Getting Started

### 📥 Installation

Copy the shortcode file into your Hugo site:

```bash
mkdir -p layouts/shortcodes
curl -o layouts/shortcodes/stormnote.html https://raw.githubusercontent.com/rubenstorm/stormnote/main/layouts/shortcodes/stormnote.html
````

---

### 💡 Usage

**Info Box:**
```markdown
{{< stormnote type="info" sntitle="Did you know?" >}}
You can add markdown inside this notification box. **Bold**, _italic_, [links](#), and more!
{{< /stormnote >}}
```

**Warning Box:**
```markdown
{{< stormnote type="warning" sntitle="Heads up!" >}}
This action may have consequences. Always double-check your steps!
{{< /stormnote >}}
```

**Success Box:**
```markdown
{{< stormnote type="success" >}}
Great job! You've successfully implemented **StormNote**.
{{< /stormnote >}}
```

---

### ⚙️ Parameters

| Name      | Type     | Default | Description                                                   |
| --------- | -------- | ------- | ------------------------------------------------------------- |
| `type`    | `string` | `info`  | Type of box: `info`, `success`, `warning`, `error`, or `note` |
| `sntitle` | `string` | `Info`  | Custom title of the alert box                                 |

---

## 📚 Available Types

| Type      | Emoji | Color Theme          | Ideal For                              |
| --------- | ----- | -------------------- | -------------------------------------- |
| `info`    | 💡    | Sky Blue / Teal      | Tips, notices, helpful context         |
| `success` | ✅     | Mint Green / Emerald | Confirmations, completions, checkmarks |
| `warning` | ⚠️    | Amber / Gold         | Caution, potential issues, reminders   |
| `error`   | ❌     | Red / Burgundy       | Errors, failures, blockers             |
| `note`    | 📝    | Lavender / Purple    | Annotations, reminders, footnotes      |

Each type adapts automatically to dark mode and includes a unique icon to help users visually scan your content quickly.

---

## 📄 License

**MIT License** © [Ruben Storm](https://github.com/rubenstorm)

You are free to use, copy, modify, and distribute this software under the terms of the MIT license.

---

## ⚡ Support This Project — Zap Me!

If **StormNote** saved you time or brought joy to your site, consider zapping me a little ⚡ love!

👉 **[Zap via Coinos](https://coinos.io/rubenstorm)**
Or scan this QR code with your Lightning wallet:

[Coinos Zap profile](https://coinos.io/rubenstorm)

![Scan to Zap](/rubenstorm/stormnote/refs/heads/main/static/images/rubenstorm@coinos.io-qr.gif)

Thanks for supporting open-source! 🖤

