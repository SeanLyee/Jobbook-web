# Jobbook Web

This repository contains only the static, hosted build of Jobbook. It does not include personal records, IndexedDB data, backup files, or API keys.

Published site: https://SeanLyee.github.io/Jobbook-web/

Jobbook remains local-first: data is stored in each browser's IndexedDB. To transfer data between devices, export a `.jobbook` backup on the old device and import it on the new device. GitHub Pages does not sync data.

The hosted build omits the large on-device OCR model. Import/export and the existing library and resume features remain available.
