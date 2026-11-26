# Open Artifact signed update rehearsal

Isolated verification of GitHub discovery, ZIP integrity, code-signature rejection, and native macOS restart/install.

These are test fixtures, not production Open Artifact releases. They use a dedicated bundle identifier and profile. Some fixtures intentionally contain an incorrect checksum or a damaged signature; do not install them for daily use. Production releases and GitHub Latest in JimLiu/open-artifact are unchanged.

- Original project: https://github.com/JimLiu/open-artifact
- Test run: 20261125-a1cd84
- Test application: dev.openartifact.desktop.update-drill.r20261125-a1cd84
- Base version: 0.16.1
- Successful target: 0.16.4

A verification report will be added after the native rehearsal completes.

## Verified result

The signed native update rehearsal passed, including real download progress, cancellation, SHA-256 rejection, native signature rejection, unsaved-work cancellation/recovery, restart installation and retained document data. Both test versions use the same Developer ID identity. [Verification details](verification.json).
