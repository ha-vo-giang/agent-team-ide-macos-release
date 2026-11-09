# Agent Team IDE — macOS releases

Test builds of Agent Team IDE for macOS (universal: Apple Silicon + Intel). Each release holds the app zip and
`update-manifest.json`, which the update portal reads for macOS clients.

Signed with a local test identity, not notarized. After the first download:

```
xattr -dr com.apple.quarantine "Agent Team IDE.app"
```
