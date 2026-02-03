# 40421

Reproduction for [Renovate discussion 40421](https://github.com/renovatebot/renovate/discussions/40421)

[Dependency Dashboard](https://github.com/benedfit/renovate-nvm-npm/issues/1)

## Current behavior

Updates to `node` and `npm` are separately created, and `npm` is updated to the latest version published.

### Results

- [`node`](https://github.com/benedfit/renovate-nvm-npm/pull/3): `24.13.0`
- [`npm`](https://github.com/benedfit/renovate-nvm-npm/pull/2): `11.7.0`

## Expected behavior

Restrict the version of `npm` to the version installed by the `nvm` images

### Desired
- `node`: `24.13.0`
- `npm`: `11.6.2`
