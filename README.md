# opencode-config

⭐ **If you found this useful, please give it a star!** / ⭐ **اگر این پروژه برایتان مفید بود، لطفاً ستاره بدهید!**

---

## English

### What is this?

**opencode-config** is a synchronized snapshot of the opencode AI assistant configuration: skills, plugins, and MCP server definitions. It lets you reproduce the same opencode setup across multiple machines.

### Why it exists

Setting up opencode with the right skills, plugins, and MCP servers takes time. By keeping the configuration in a git repository, you can clone it on any machine and get the same environment instantly. It also serves as a backup and a way to share a proven configuration.

### Contents

- `opencode-settings.jsonc` — main opencode settings (providers, MCP, plugins, disabled providers).
- Skills, plugins, and MCP definitions synced from `~/.config/opencode/`.

### Note on secrets

API keys in the settings file have been replaced with `YOUR_*_API_KEY` placeholders. Fill them in with your own keys before use.

---

## فارسی

### این چیست؟

**opencode-config** یک نسخهٔ همگام‌سازی‌شده از پیکربندی دستیار هوش مصنوعی opencode است: مهارت‌ها، پلاگین‌ها و تعریف‌های سرور MCP. به شما امکان می‌دهد همان محیط opencode را روی ماشین‌های مختلف بازتولید کنید.

### چرا به وجود آمد؟

راه‌اندازی opencode با مهارت‌ها، پلاگین‌ها و سرورهای MCP مناسب زمان‌بر است. با نگه‌داری پیکربندی در یک ریپازیتوری گیت، می‌توانید آن را روی هر ماشین clone کنید و همان محیط را فوراً داشته باشید. همچنین به‌عنوان پشتیبان و روشی برای اشتراک‌گذاری یک پیکربندی آزموده‌شده عمل می‌کند.

### محتویات

- `opencode-settings.jsonc` — تنظیمات اصلی opencode (providerها، MCP، پلاگین‌ها، providerهای غیرفعال).
- مهارت‌ها، پلاگین‌ها و تعریف‌های MCP همگام‌سازی‌شده از `~/.config/opencode/`.

### نکته دربارهٔ اسرار

کلیدهای API در فایل تنظیمات با placeholder های `YOUR_*_API_KEY` جایگزین شده‌اند. قبل از استفاده، آن‌ها را با کلیدهای خود پر کنید.