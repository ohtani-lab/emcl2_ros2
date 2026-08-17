# Upstream information

Upstream repository:
https://github.com/CIT-Autonomous-Robot-Lab/emcl2_ros2

Upstream branch:
`main`

Upstream commit used as the BPS base:
`3eacea2dc70d9d29eb0d501d01eb5df001814776`

Fork repository:
https://github.com/ohtani-lab/emcl2_ros2

The tag `bps-base-v1` points to the upstream commit above. BPS-specific
changes can be inspected with:

```bash
git diff bps-base-v1..HEAD
git log --oneline bps-base-v1..HEAD
```

BPS changes:

- Include `<cstdint>` explicitly in the headers and source that use fixed-width
  integer types.
