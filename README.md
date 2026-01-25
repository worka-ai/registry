# Worka Registry

This repository is the canonical registry metadata store for Worka packs.

Structure:
```
registry/
  index.yaml
  categories/
    <category>.yaml
  packs/
    <tenant>/
      <name>/
        pack.yaml
        versions/
          <version>.yaml
```

This repo contains metadata only. Pack artifacts are hosted externally (e.g. GitHub Releases) and referenced by URL and digest in version records.
