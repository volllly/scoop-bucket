# Volly's Scoop Bucket

[![Tests](https://github.com/volllly/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/volllly/scoop-bucket/actions/workflows/ci.yml) [![Excavator](https://github.com/volllly/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/volllly/scoop-bucket/actions/workflows/excavator.yml)

Template bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

## How do I install these manifests?

After manifests have been committed and pushed, run the following:

```pwsh
scoop bucket add volllly https://github.com/volllly/scoop-bucket
scoop install volllly/<manifestname>
```
