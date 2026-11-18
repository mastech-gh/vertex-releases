# Vertex Collector releases

This repository holds the current installers and the signed update files for the **Vertex Collector**, made by MasTech. It contains no source code.

Vertex is pre-release software. It has not yet been run on a customer network, and it is meant for testing by people MasTech has invited.

| File | What it is |
| --- | --- |
| Releases | The Windows installer (`VertexCollectorSetup.exe`) and the Linux package (`.deb`) for the current version |
| `latest.json`, `latest-linux.json` | Signed update files. An installed Collector reads these to offer an update; it only installs one that carries a valid MasTech signature, and only when the operator chooses to |

Windows may show a SmartScreen warning when you run the installer, because the installer is not code-signed yet.
