# Jobbook Web

This repository contains only the static, hosted build of Jobbook. It does not include personal records, IndexedDB data, backup files, or API keys.

Published site: https://SeanLyee.github.io/Jobbook-web/

## 更新日志 / Changelog

[查看完整版本更新日志（v1.0.0–v2.6.1）](CHANGELOG.md)。内容与网页版「设置 → 版本与更新日志」一致；后续发布时由应用中的同一份版本记录生成。

Jobbook remains local-first: data is stored in each browser's IndexedDB. To transfer data between devices, export a `.zip` backup on the old device and import it on the new device. Older `.jobbook` backups are still accepted. GitHub Pages does not sync data. Before restoring, the app previews the actual record counts and rejects empty backups.

The hosted build omits the large on-device OCR model. Import/export and the existing library and resume features remain available.
