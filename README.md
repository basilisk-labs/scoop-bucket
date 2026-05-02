# Basilisk Labs Scoop Bucket

Scoop manifests for Basilisk Labs tools.

**Topics:** `agentplane` `scoop` `windows` `cli`

## Why use this bucket

AgentPlane is designed to be used in regular developer tooling workflows.
Scoop makes it easy for Windows users to install and keep it up to date with minimal friction.

## Install

```powershell
scoop bucket add basilisk-labs https://github.com/basilisk-labs/scoop-bucket
scoop install agentplane
```

## Verify

```powershell
agentplane --version
agentplane quickstart
```

## Update

```powershell
scoop update agentplane
```

Use `agentplane` immediately after install to initialize conventions for the current repository.

## Notes

- `checkver` and `autoupdate` are configured for release discovery.
- Keep manifest checksum in sync with upstream standalone package artifacts.
