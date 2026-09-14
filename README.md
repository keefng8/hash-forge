# Hash Forge

SHA-256, SHA-1 and MD5 for text or a whole file, with a compare box that tells you plainly whether two hashes match. Runs on the file in place - nothing is uploaded.

A feature for [Mavis AI](https://www.mavis-ai.com) — a desktop voice assistant.

```
You: "open hash forge"
```

Mavis opens it and stands its own panels down so they are not in your way. Say *"show the interface"* to bring them back.

## Install

From the Mavis Appstore — find **Hash Forge** and click Install.

Or install it directly:

```python
from utils.feature_install import install_from_github
install_from_github("https://github.com/keefng8/hash-forge")
```

## What you can say

- *"open hash forge"*
- *"check this file's hash"*
- *"verify a download"*
- *"sha256 of a file"*

These are not matched word for word. Mavis gives them to its language model as examples of intent, so close variations work too.

## How it works

MD5 is included because publishers still print MD5 checksums and a tool that cannot check the hash in front of you is not much use - but it tells you plainly that MD5 and SHA-1 are broken for security purposes and only prove a download was not corrupted.

## Requirements

None. A single HTML file — it runs in your browser, offline, and nothing leaves your machine.

## Building your own

See [Building features for Mavis](https://github.com/keefng8/mavis-feature-docs) — a feature is just a GitHub repository with a `mavis.json`.

## License

MIT — see [LICENSE](LICENSE).
