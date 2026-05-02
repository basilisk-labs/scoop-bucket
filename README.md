# Basilisk Labs Scoop Bucket

Scoop manifests for Basilisk Labs tools.

**Topics:** `agentplane` `scoop` `windows` `cli`

## AgentPlane

Add the bucket and install AgentPlane:

```powershell
scoop bucket add basilisk-labs https://github.com/basilisk-labs/scoop-bucket
scoop install agentplane
```

This bucket is generated from AgentPlane release distribution metadata.

## Discovery chips

- `agentplane`
- `cli`
- `standalone`
- `windows`

## Update and verification

To refresh with a new release (when checksum updates):

```powershell
scoop update agentplane
```

To verify installation:

```powershell
agentplane --version
agentplane quickstart
```

## Notes

- `checkver` and `autoupdate` are configured for release discovery.
- Keep manifest hash synchronized with the published standalone archive checksum.
