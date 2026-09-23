# Jobbook Web

This repository contains only the static, hosted build of Jobbook. It does not include personal records, IndexedDB data, backup files, or API keys.

Published site: https://SeanLyee.github.io/Jobbook-web/

## 更新日志 / Changelog

[查看完整版本更新日志（v1.0.0–v2.1.0）](CHANGELOG.md)。版本编号已经按 [JobBook 版本编号守则](VERSIONING.md) 校准；内容与网页版「设置 → 版本与更新日志」一致。

Jobbook remains local-first: data is stored in each browser's IndexedDB. To transfer data between devices, export a `.zip` backup on the old device and import it on the new device. Older `.jobbook` backups are still accepted. GitHub Pages does not sync data. Before restoring, the app previews the actual record counts and rejects empty backups.

The hosted build includes free on-device Chinese OCR. Its model files are downloaded on the first screenshot recognition and then cached by the browser. Screenshots remain local; DashScope is optional and only used when explicitly configured. Import/export and the existing library and resume features remain available.

Version 2.0.0 introduced Job Discovery as the user-approved major product generation. Version 2.1.0 expands it with ten sourced company rankings (1,797 memberships / 1,395 deduplicated companies), catalog search, reviewed text and on-device screenshot OCR imports, and a pausable batch-refresh queue. Automatic job reads remain limited to supported official Greenhouse/Lever sources; ordinary company sites stay explicit manual fallbacks. Ranking sources, imported screenshots, jobs, and application tracking remain local and are included in ZIP backups.
