# PowerPoint Report Studio

A Microsoft PowerPoint add-in that turns Excel survey and table data into report slides, filling the presentation's tables, charts and text automatically.

This repository only **hosts the compiled add-in**. GitHub Pages serves it at:

```
https://danield07.github.io/powerpoint-report-studio/
```

It contains no source code, and this is not an open-source project.

## Installing the add-in

The add-in is installed from its **manifest file** (`manifest.xml`), which you get from the author. That file is not included in this repository.

**For a whole organization (recommended):** a Microsoft 365 admin uploads the manifest under
**Microsoft 365 admin center → Settings → Integrated apps → Upload custom apps**
and assigns it to users or groups. The add-in then appears in PowerPoint for those users automatically. This can take up to 24 hours.

**For a single user (testing):** in PowerPoint, go to
**Home → Add-ins → More Add-ins → My Add-ins → Upload My Add-in**
and select the manifest file.

## Updates

Updates are published to this repository and take effect automatically. Users get the latest version the next time they open PowerPoint, and nothing needs to be reinstalled.

## Requirements

- PowerPoint for Microsoft 365 (Windows, Mac or web)
- Internet access to `danield07.github.io`

## License

Copyright (c) 2026. All rights reserved. See [LICENSE.md](LICENSE.md).
Bundled third-party components are covered by their own licenses, listed in the `*.LICENSE.txt` files.

## Contact

For access, support or licensing questions, contact the author.
