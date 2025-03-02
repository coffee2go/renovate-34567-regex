# renovate-34567
Reproduction for renovate [discussion 34567](https://github.com/renovatebot/renovate/discussions/34567)

## Current behavior

Renovate fails to update the values file

## Expected behavior

Renovate updates the tag and digest to a newer `nginx` version, e.g.

```yaml
image:
  name: nginx
  tag: 1.27.4
  digest: sha256:28edb1806e63847a8d6f77a7c312045e1bd91d5e3c944c8a0012f0b14c830c44
```

